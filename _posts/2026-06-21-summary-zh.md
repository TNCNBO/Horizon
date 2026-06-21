---
layout: default
title: "Horizon Summary: 2026-06-21 (ZH)"
date: 2026-06-21
lang: zh
---

> 从 60 条内容中筛选出 5 条重要资讯。

---

1. [Loupe 揭示 iOS 应用可见数据。](#item-1) ⭐️ 7.0/10
2. [Linux 网络中的 epoll 与 io_uring 取舍](#item-2) ⭐️ 7.0/10
3. [缓慢呼吸可能改变奖赏与冒险行为](#item-3) ⭐️ 7.0/10
4. [SMPTE 免费开放其标准库。](#item-4) ⭐️ 7.0/10
5. [微信开始小范围测试“小微”AI 助手](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Loupe 揭示 iOS 应用可见数据。](https://github.com/mysk-research/loupe) ⭐️ 7.0/10

Mysk Research 发布了 Loupe，这是一款开源的 iOS 和 iPadOS 应用，用来演示原生应用可以通过公开 iOS API 读取哪些设备和系统信息。该应用会展示来自这些 API 的真实数值，突出一些可能不需要用户明确授权却具有隐私意义的数据。 Loupe 让普通用户和开发者能够直观看到 iOS 的设备指纹识别暴露面，从而挑战“敏感访问总会由权限弹窗控制”的常见认知。它可能影响隐私审计、应用商店政策讨论，以及用户对移动平台上“无需权限”访问范围的理解。 根据项目说明，Loupe 读取的是公开 iOS API 返回的真实数值，而不是利用私有 API 或漏洞。社区讨论中特别关注了设备设置或抹掉日期、卷创建日期、剪贴板变更计数以及已安装应用探测等令人意外或担忧的例子。

hackernews · Cider9986 · 6月20日 12:08 · [社区讨论](https://news.ycombinator.com/item?id=48608645)

**背景**: iOS 应用通常运行在沙盒中，摄像头、麦克风或位置等许多敏感资源的访问会受到面向用户的权限弹窗控制。不过，应用也可以调用公开系统 API，在不触发这些弹窗的情况下获取设备、系统或运行环境信息。这些信息可能参与设备指纹识别，也就是把多个细微信号组合起来识别或跟踪一台设备。Loupe 的定位是让用户动手了解这些暴露面，而不是一个恶意软件扫描器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/mysk-research/loupe">GitHub - mysk-research/loupe: A privacy-focused iOS app that raises ...</a></li>
<li><a href="https://discuss.privacyguides.net/t/permission-not-required-the-open-source-app-that-makes-the-invisible-visible-loupe-review/38640">The Open Source App that Makes the Invisible Visible (Loupe Review ...</a></li>

</ul>
</details>

**社区讨论**: 评论者总体上认可这款工具，认为像 Loupe 这样的可视化认知工具有助于让隐藏的数据访问变得易于理解。多名用户特别指出 iPhone 设置或抹掉日期、卷创建日期、剪贴板变更计数以及已安装应用探测等数据过于精细，且用户很难自行缓解。也有人认为 iOS 在某些方面仍好于 Android，但整体讨论的基调是担心隐私标签和权限弹窗并没有充分说明这些访问能力。

**标签**: `#iOS`, `#privacy`, `#mobile-security`, `#permissions`, `#open-source`

---

<a id="item-2"></a>
## [Linux 网络中的 epoll 与 io_uring 取舍](https://sibexi.co/posts/epoll-vs-io_uring/) ⭐️ 7.0/10

一篇新的技术文章比较了 epoll 和 io_uring 在构建高性能 Linux 网络服务时的差异，重点不是发布新版本，而是分析实际架构和性能取舍。文章讨论了 io_uring 可能带来收益的场景、epoll 仍然有竞争力的地方，以及为什么很难超越 nginx 或 HAProxy 这类成熟服务器。 这个比较很重要，因为 Linux 网络服务器的性能往往取决于 I/O 架构、系统调用开销、CPU 调度和内存移动方式。对于需要在传统事件循环和 io_uring 之间做选择的工程师来说，文章强调了较新的内核接口并不会自动带来更好的真实网络吞吐量。 epoll 用于监视大量文件描述符是否就绪，而 io_uring 通过用户空间与内核空间共享的环形缓冲区提交异步 I/O 请求并接收完成事件。一个关键限制是，io_uring 对文件 I/O 的提升更明确，但公开资料也指出，它在网络 I/O 上的收益可能较为有限，因为 Linux 网络栈已经拥有成熟的非阻塞接口。

hackernews · Sibexico · 6月20日 23:07 · [社区讨论](https://news.ycombinator.com/item?id=48613872)

**背景**: epoll 是 Linux 的 I/O 事件通知机制，程序可以用它等待大量文件描述符上的活动，例如套接字，而不必为每个连接分配一个线程。它常用于事件驱动的网络服务器，因为在连接数量很大时，它比更早的轮询方式更容易扩展。io_uring 是较新的 Linux 专用异步 I/O 接口，其核心是用户空间和内核空间之间共享的环形缓冲区。程序不只是等待就绪事件，而是提交操作并稍后读取完成事件，这在某些工作负载中可以减少系统调用开销。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://linux.die.net/man/7/epoll">epoll(7): I/O event notification facility - Linux man page</a></li>
<li><a href="https://man7.org/linux/man-pages/man7/io_uring.7.html">io_uring(7) - Linux manual page</a></li>
<li><a href="https://developers.redhat.com/articles/2023/04/12/why-you-should-use-iouring-network-io">Why you should use io_uring for network I/O | Red Hat Developer</a></li>

</ul>
</details>

**社区讨论**: 讨论整体偏技术，许多人把这篇文章视为有用的探索，而不是最终性能结论。评论者提出了 CPU 绑定、类似 SO_INCOMING 的套接字放置、共享缓冲区、内存对齐分配器、mmap、kTLS、eBPF/XDP 等底层优化方向，同时也指出 io_uring 仍缺少某些能力，例如通过它使用 sendfile。也有评论用调侃方式概括了更大的问题：Linux 上等待套接字的方式已经很多。

**标签**: `#linux`, `#io_uring`, `#epoll`, `#networking`, `#performance`

---

<a id="item-3"></a>
## [缓慢呼吸可能改变奖赏与冒险行为](https://www.cell.com/neuron/fulltext/S0896-6273(26)00339-9) ⭐️ 7.0/10

一项发表在 Neuron 的研究报告称，缓慢呼吸，尤其是延长呼气的呼吸模式，会调节大脑活动，并增强奖赏反应性和冒险行为。该发现把一种简单的呼吸模式与自主神经调节、神经功能和决策变化联系起来。 这一结果值得关注，因为缓慢呼吸常被用于镇静、焦虑管理和表现准备，但这项研究表明它也可能改变奖赏和风险处理。对于焦虑、惊恐障碍和抑郁等临床场景，这可能具有意义，因为这些问题常涉及自主神经模式和异常的奖赏处理。 研究报告的效果似乎尤其与延长呼气有关，而延长呼气通常与更强的心脏副交感调节相关。一个重要限制是，冒险行为增加并不一定有益；当恐惧不合理或妨碍有益行动时可能有帮助，但在需要谨慎的场景中也可能带来风险。

hackernews · croes · 6月20日 22:22 · [社区讨论](https://news.ycombinator.com/item?id=48613555)

**背景**: 呼吸不只是气体交换过程；已有研究显示，呼吸节律可以带动大脑振荡，并影响与情绪和认知有关区域的神经活动。自主神经系统调节非自主的身体功能，而副交感激活通常与心率减慢和较平静的生理状态相关。奖赏反应性指个体或大脑系统对潜在奖赏或已获得奖赏的反应强度，它与动机、愉悦感以及一些精神症状有关。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.frontiersin.org/journals/neural-circuits/articles/10.3389/fncir.2021.761812/full">Frontiers | Respiration-Driven Brain Oscillations in Emotional Cognition</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC6037091/">The relaxation effect of prolonged expiratory breathing - PMC</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7969456/">Differentiating Stages of Reward Responsiveness: Neurophysiological Measures and Associations with Facets of the Behavioral Activation System - PMC</a></li>

</ul>
</details>

**社区讨论**: 评论者总体上对副交感激活与更高冒险倾向之间看似反直觉的联系感到好奇。有些人把缓慢呼吸理解为一种自下而上的调节方式，可帮助公开演讲或应对不合理恐惧；也有人提醒，降低恐惧并不总是好事，因为恐惧有时具有保护作用。还有讨论关注人们是否能长期训练默认呼吸模式，以及可穿戴设备能否足够精确地监测呼吸。

**标签**: `#neuroscience`, `#respiration`, `#mental-health`, `#behavioral-science`, `#risk-taking`

---

<a id="item-4"></a>
## [SMPTE 免费开放其标准库。](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 7.0/10

SMPTE 已向全球媒体技术社区免费开放其完整标准目录。此次免费开放的资料包括已发布的 SMPTE 标准、推荐实践、工程指南和注册披露文件。 免费获取降低了在广播、影院、流媒体和媒体制作系统中实现核心规范的成本。这可能改善互操作性，因为厂商、开源项目和独立开发者更容易基于同一套技术参考进行开发。 该公告被描述为 SMPTE 标准制定和发布流程现代化的一部分，其中包括基于 GitHub 的工作流、问题跟踪、结构化 HTML 写作以及集成发布流水线。此次变化影响的是文档获取方式，而不是标准本身的技术内容。

hackernews · zdw · 6月20日 17:01 · [社区讨论](https://news.ycombinator.com/item?id=48610827)

**背景**: SMPTE，即电影与电视工程师协会，是一个在媒体技术领域获得国际认可的标准组织。它的规范覆盖广播、电影制作、数字影院、音频录制、信息技术和医学影像等领域。标准组织会定义共同的技术规则，使来自不同机构的设备、软件和工作流能够可靠地互操作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tvtechnology.com/standards/smpte-makes-its-standards-freely-accessible-to-the-global-media-technology-community">SMPTE Makes Its Standards Freely Accessible to the Global Media ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Society_of_Motion_Picture_and_Television_Engineers">Society of Motion Picture and Television Engineers - Wikipedia</a></li>
<li><a href="https://www.smpte.org/standards/overview">Standards Overview | Society of Motion Picture & Television ...</a></li>

</ul>
</details>

**社区讨论**: 评论者总体持积极态度，认为标准默认就应该免费开放，并将 SMPTE 的做法与 IETF 长期采用的开放获取模式进行比较。也有人提到，当标准被法律强制采用时，免费获取具有法律和公民权利层面的必要性；另一些人则强调，这对过去需要购买特定 SMPTE PDF 的开发者有实际帮助。

**标签**: `#standards`, `#media-technology`, `#open-access`, `#interoperability`, `#broadcast`

---

<a id="item-5"></a>
## [微信开始小范围测试“小微”AI 助手](https://36kr.com/newsflashes/3862458180359424?f=rss) ⭐️ 7.0/10

微信已开始小范围灰度测试原生 AI 助手“小微”，部分用户在微信主界面左上角看到了一个小眼睛样式的入口图标。根据腾讯客服介绍，“小微”支持通过文字或语音对话操作微信原生功能、调起小程序，并完成发送消息、查询朋友圈、预约服务等任务。 由于微信是超大规模的社交与服务平台，内置 AI 助手可能把智能体式任务执行带入日常通讯、生活服务和小程序流程中。如果后续大范围开放，“小微”可能成为中国消费互联网生态中 AI Agent 的重要入口。 目前该功能仅被描述为小范围内测或灰度测试，因此可用范围、支持账号、模型能力、隐私控制和失败处理边界尚不明确。已披露的示例表明，“小微”不只是聊天机器人，而是连接微信原生功能和小程序调用的操作型助手。

rss · 36氪 · 6月21日 05:03

**背景**: 灰度测试是一种常见的软件发布方式，通常先把新功能开放给少量用户，再逐步扩大范围，以便在全面上线前发现问题并收集反馈。AI Agent 通常指能够代表用户执行任务的系统，它不只是生成文本，还会理解目标、规划步骤，并调用工具或应用功能完成操作。在这次微信“小微”的场景中，微信原生功能和小程序似乎就是它可以通过语音或文字指令调用的工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.aliyun.com/article/710854">灰度测试是什么及其实现方法与核心价值-开发者社区-阿里云</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-agents">什么是AI agent (AI 智能体)？</a></li>

</ul>
</details>

**标签**: `#AI助手`, `#微信`, `#腾讯`, `#Agent`, `#产品发布`

---