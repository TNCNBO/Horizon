---
layout: default
title: "Horizon Summary: 2026-06-26 (ZH)"
date: 2026-06-26
lang: zh
---

> 从 114 条内容中筛选出 16 条重要资讯。

---

1. [首次完整读出赫库兰尼姆卷轴](#item-1) ⭐️ 9.0/10
2. [IBM 宣称实现首个亚 1 纳米逻辑技术](#item-2) ⭐️ 8.0/10
3. [Zig 修订 bitCast 语义并改进 LLVM 后端。](#item-3) ⭐️ 8.0/10
4. [JetSpec 加速无损 LLM 推理。](#item-4) ⭐️ 8.0/10
5. [NVIDIA 发布双塔扩散语言模型。](#item-5) ⭐️ 8.0/10
6. [年龄验证正在威胁网络隐私。](#item-6) ⭐️ 7.0/10
7. [Apple 或将跳过高端 M6，转向面向 AI 的 M7 Mac。](#item-7) ⭐️ 7.0/10
8. [Un-0 探索基于振荡器的图像生成。](#item-8) ⭐️ 7.0/10
9. [Bank Python 的历史再受关注。](#item-9) ⭐️ 7.0/10
10. [Apple 上调 MacBook 和 iPad 价格](#item-10) ⭐️ 7.0/10
11. [Google AI 概览责任争议](#item-11) ⭐️ 7.0/10
12. [GitHub Copilot 推出桌面应用](#item-12) ⭐️ 7.0/10
13. [PostgreSQL 19 Beta 增加图查询。](#item-13) ⭐️ 7.0/10
14. [美光显示 AI 存储需求正在爆发。](#item-14) ⭐️ 6.0/10
15. [Anthropic 的 Claude 付费份额上升。](#item-15) ⭐️ 6.0/10
16. [无界动力融资超 2 亿美元。](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [首次完整读出赫库兰尼姆卷轴](https://scrollprize.org/firstscroll) ⭐️ 9.0/10

研究人员首次完整读出了一卷赫库兰尼姆卷轴，使用了计算成像、分割、虚拟展开和机器学习辅助墨迹检测等技术。该项目还通过 Vesuvius Challenge 发布了预印本和代码。 这对考古学、数字人文学和计算机视觉都是重大进展，因为它证明了已经炭化、无法物理展开的古代文本可以通过非破坏性方式恢复。如果这种方法能够扩大应用，它可能解读更多来自赫库兰尼姆及类似文化遗产收藏的文本。 这项工作涉及 PHerc. 1667，它是一卷更大卷轴受损后留下的内芯，外层曾在早期物理展开尝试中被破坏。其流程依赖高分辨率 CT 类成像、精细的层面分割、虚拟压平，以及对原始扫描中不易看见的墨迹进行学习式检测。

hackernews · Hacker News 热门 · 6月25日 15:48 · [社区讨论](https://news.ycombinator.com/item?id=48675179)

**背景**: 赫库兰尼姆纸草卷是在赫库兰尼姆的纸草别墅中发现的古代卷轴，赫库兰尼姆是一座被维苏威火山喷发掩埋的罗马城镇。这些卷轴被炭化并压缩，因而得以保存，但也使物理展开极具破坏性。虚拟展开使用体积扫描来数字化重建卷起的层面，再通过计算方式将其压平，以便检测和阅读文字。Vesuvius Challenge 发布了数据集和工具，鼓励团队解决这些成像和机器学习难题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://scrollprize.org/unwrapping">Virtual Unwrapping | Vesuvius Challenge</a></li>
<li><a href="https://registry.opendata.aws/vesuvius-challenge-herculaneum-scrolls/">Vesuvius Challenge - CT Scans of Herculaneum Papyri</a></li>
<li><a href="https://scrollprize.org/data">The Data | Vesuvius Challenge - scrollprize.org</a></li>

</ul>
</details>

**社区讨论**: 社区讨论非常热烈，许多评论者感叹能够恢复两千多年前写下的思想所带来的历史震撼。一些评论关注实际影响，包括赫库兰尼姆可能仍有更多卷轴尚未出土；同时，一位 Vesuvius Challenge 团队成员参与讨论，回答有关分割、展开和墨迹检测的技术问题。也有人对早期试图手工展开卷轴造成破坏表示担忧。

**标签**: `#computer-vision`, `#machine-learning`, `#digital-humanities`, `#archaeology`, `#cultural-heritage`

---

<a id="item-2"></a>
## [IBM 宣称实现首个亚 1 纳米逻辑技术](https://newsroom.ibm.com/2026-06-25-ibm-debuts-worlds-first-sub-1-nanometer-chip-technology) ⭐️ 8.0/10

IBM 于 2026 年 6 月 25 日宣布，其开发出所谓全球首个亚 1 纳米逻辑芯片技术，并称其为 0.7 纳米或 7 埃节点。相关报道称，IBM 的 NanoStack 方案目标是在一颗芯片上容纳接近 1000 亿个晶体管，密度约为其 2021 年 2 纳米技术宣称值的两倍。 如果该技术最终被证明具有实用性，它将表明在物理和制造约束日益增强的情况下，晶体管缩放仍可能进入埃级时代。这可能影响未来需要更高计算密度和更好能效的 AI、服务器和移动芯片。 “0.7 纳米”这一名称不应被理解为晶体管结构的实际物理尺寸就是 0.7 纳米；现代制程节点名称更多是代际和密度指标，而不是直接尺寸测量。该公告本身也不意味着短期内会进入大规模量产，尤其是 IBM 已不再是领先的大规模晶圆代工运营商。

hackernews · Hacker News 热门 · 6月25日 15:33 · [社区讨论](https://news.ycombinator.com/item?id=48674967)

**背景**: 在较早的半导体世代中，90 纳米等制程名称与晶体管栅长等物理尺寸关系更直接。随着时间推移，这些名称已经与精确特征尺寸脱钩，如今通常用来表示一个具有预期密度、性能和功耗改进的技术世代。“埃级时代”指的是芯片缩放进入纳米命名范围以下的阶段，其中 1 埃等于 0.1 纳米，而进展越来越依赖新的器件结构、材料和集成方式，而不只是简单缩小尺寸。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.networkworld.com/article/4189510/ibm-unveils-sub-1-nanometer-chip-with-nearly-100-billion-transistors.html">IBM unveils sub - 1 nanometer chip with nearly 100 billion transistors</a></li>
<li><a href="https://www.synopsys.com/blogs/chip-design/angstrom-scale-chip-design.html">Angstrom-Scale Chip Design Explained | Synopsys Blog</a></li>
<li><a href="https://uplatz.com/blog/the-angstrom-era-navigating-process-node-evolution-from-5nm-to-3nm-and-the-confrontation-with-fundamental-physical-limits/">The Angstrom Era: Navigating Process Node Evolution... | Uplatz Blog</a></li>

</ul>
</details>

**社区讨论**: Hacker News 讨论整体上对 IBM 的表述持怀疑态度，多位评论者强调“0.7 纳米”是节点名称，而不是实际特征尺寸。另一些人质疑 IBM 的可信度和量产相关性，同时也有人提供了一篇较长的技术深度解析，供读者进一步了解该技术宣称。

**标签**: `#semiconductors`, `#chip-manufacturing`, `#transistor-scaling`, `#IBM`, `#hardware`

---

<a id="item-3"></a>
## [Zig 修订 bitCast 语义并改进 LLVM 后端。](https://ziglang.org/devlog/2026/#2026-06-25) ⭐️ 8.0/10

Zig 在 2026 年 6 月 25 日的开发日志中介绍了新的跨目标一致的 @bitCast 语义，以及对 LLVM 后端的相关改进。该变化源自已接受的 #19755 提案，使某些转换（例如从 [2]u8 转为 u16）在不同目标平台上表现一致，而不再依赖机器的大小端。 这对系统程序员很重要，因为 @bitCast 常用于底层数据表示处理，而这类代码很容易在跨平台时出错。更精确定义的语义和 LLVM 后端改进也表明 Zig 编译器在面向高性能、可移植软件方面继续走向成熟。 在新模型下，@bitCast 按逻辑位表示来定义，而不是按本机内存字节顺序来定义；对于从 [2]u8 转为 u16 的转换，第一个数组元素在所有目标平台上都会成为最低的 8 位。讨论的焦点是，把这种行为称为“与大小端无关”是否直观，尤其是在数组、向量、紧凑结构体和任意位宽整数场景中。

hackernews · kouosi · 6月25日 14:19 · [社区讨论](https://news.ycombinator.com/item?id=48673825)

**背景**: @bitCast 是 Zig 中把一个值重新解释为另一个相同位大小类型的操作，因此它的精确定义对二进制格式和底层代码很重要。大小端是多字节数值在内存中排列顺序的约定，旧行为可能在大端和小端目标上产生不同结果。LLVM 是许多语言用来为不同架构生成优化机器码的编译器和工具链基础设施，因此后端改进会影响代码生成质量和可移植性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ziglang.org/devlog/2026/?from_theconsensus=1">Devlog ⚡ Zig Programming Language - ziglang.org</a></li>
<li><a href="https://github.com/ziglang/zig/issues/19755">Proposal: initial `@bitCast` semantics (packed + vector + array ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/LLVM">LLVM - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体上很积极且技术性很强。一些评论者欢迎这一变化，认为它有助于处理位紧凑的二进制头并减少手动位操作；另一些人则认为这种“逻辑”顺序实际上偏向小端直觉，可能会让初学者困惑。还有不少读者称赞开发日志的深入程度，并讨论任意位宽整数是否值得承担相应的人体工学和概念复杂度。

**标签**: `#Zig`, `#compilers`, `#systems-programming`, `#LLVM`, `#endianness`

---

<a id="item-4"></a>
## [JetSpec 加速无损 LLM 推理。](https://www.reddit.com/r/LocalLLaMA/comments/1ufntl5/research_jetspec_speculative_decoding_with/) ⭐️ 8.0/10

Hao AI Lab 推出了 JetSpec，这是一种使用因果并行树草稿的投机解码方法，可在一次前向过程中生成候选令牌树。该项目声称在 MATH-500 上实现最高 9.64 倍端到端加速，在开放式聊天中实现 4.58 倍加速，并通过 CUDA Graph 和内核优化在单张 B200 GPU 上达到约每秒 1000 个令牌。 如果这些结果得到验证，JetSpec 可能在不改变模型输出的情况下显著降低 LLM 生成延迟，这对本地推理、交互式聊天和生产服务成本都很重要。它还针对投机解码中的一个关键瓶颈：让草稿既生成成本低，又具有足够高的质量以被目标模型接受。 JetSpec 将自身与自回归草稿头和块扩散风格草稿头进行对比：前者的成本会随树深增加，后者独立评分的分支可能变得相互不一致。据称，它的草稿头会基于冻结目标模型的融合隐藏特征进行条件生成，并在一次前向过程中保持因果性地生成一棵树，但这些突出加速数据仍属于项目方声明，需要独立验证。

reddit · r/LocalLLaMA · /u/No_Yogurtcloset_7050 · 6月25日 21:55

**背景**: 投机解码是一种用于 LLM 的推理时优化方法，它通过草稿机制预测多个后续令牌，然后由主模型进行验证。当验证接受这些草稿令牌时，生成过程就可以一次前进多个令牌，同时保持与普通解码相同的输出分布。CUDA Graph 是一种 GPU 执行优化，可在解码等可预测推理阶段减少重复启动开销。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bentoml.com/llm/inference-optimization/speculative-decoding">Speculative decoding | LLM Inference Handbook</a></li>
<li><a href="https://arxiv.org/pdf/2606.18394">JetSpec : Breaking the Scaling Ceiling of Speculative Decoding with...</a></li>
<li><a href="https://docs.vllm.ai/en/latest/design/cuda_graphs/">CUDA Graphs - vLLM Documentation</a></li>

</ul>
</details>

**标签**: `#LLM inference`, `#speculative decoding`, `#CUDA optimization`, `#machine learning systems`, `#performance`

---

<a id="item-5"></a>
## [NVIDIA 发布双塔扩散语言模型。](https://www.reddit.com/r/LocalLLaMA/comments/1uf4azy/nvidia_has_released/) ⭐️ 8.0/10

NVIDIA 发布了 Nemotron-TwoTower-30B-A3B-Base-BF16，这是一个基于 NVIDIA-Nemotron-3-Nano-30B-A3B-Base-BF16 骨干模型构建的分块自回归扩散语言模型。该模型使用冻结的自回归上下文塔和扩散去噪塔，并行填充标记块，而不是严格逐个生成标记。 这次发布很重要，因为 NVIDIA 声称默认的掩码扩散配置保留了自回归基线综合基准质量的 98.7%，同时实现了 2.42 倍的实际生成吞吐量。如果这种方法能够推广，它可能会影响未来的大语言模型推理系统，使其从完全顺序解码转向部分并行生成。 根据模型信息，上下文塔处理干净提示和此前已提交的标记，生成逐层 KV 缓存和最终的 Mamba-2 状态，而去噪塔执行分块掩码扩散。Hugging Face 页面还注明预训练数据截止日期为 2025 年 6 月 25 日，代码库元数据提到双向块内注意力、分块扫描 Mamba 和 fp64 路由器等工程细节。

reddit · r/LocalLLaMA · /u/nikhilprasanth · 6月25日 08:34

**背景**: 大多数 GPT 风格的语言模型都是自回归模型，也就是按顺序逐个生成标记，每个新标记都依赖此前的上下文。掩码扩散语言模型则学习通过迭代去噪恢复被遮蔽或破坏的文本，因此可能允许多个标记并行预测。双塔设计把上下文处理和去噪分开，使模型能够复用自回归上下文信息，同时探索更快的块级生成方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/nvidia/Nemotron-TwoTower-30B-A3B-Base-BF16">nvidia/Nemotron-TwoTower-30B-A3B-Base-BF16 · Hugging Face</a></li>
<li><a href="https://huggingface.co/nvidia/Nemotron-TwoTower-30B-A3B-Base-BF16/tree/main">nvidia/Nemotron-TwoTower-30B-A3B-Base-BF16 at main</a></li>
<li><a href="https://www.emergentmind.com/topics/masked-diffusion-language-models-dlms">Masked Diffusion Language Models</a></li>

</ul>
</details>

**标签**: `#LLM`, `#NVIDIA`, `#diffusion-models`, `#inference-optimization`, `#model-release`

---

<a id="item-6"></a>
## [年龄验证正在威胁网络隐私。](https://expression.fire.org/p/the-papers-please-era-of-the-internet) ⭐️ 7.0/10

FIRE 的文章认为，不断扩大的线上年龄验证和身份检查要求，可能把网络推向一种“请出示证件”的模式，让用户为了访问普通服务而反复证明自己的身份或年龄。 令人担忧的是，强制身份检查可能削弱匿名性，压制敏感表达，并制造新的数据泄露、胁迫、勒索或身份盗窃风险。这个问题影响的不只是成人内容网站，也可能波及受年龄保障法律约束的社交平台、应用商店、论坛和其他日常线上空间。 技术人士提出了匿名凭证和零知识证明等保护隐私的方法，它们可以证明用户超过某个年龄门槛，而不披露出生日期或持久身份。可是，搜索结果和讨论也强调了限制：这类系统仍依赖签发方、钱包、威胁模型、实现方式，以及政府或平台是否会要求超过必要范围的身份数据。

hackernews · Hacker News 热门 · 6月25日 21:44 · [社区讨论](https://news.ycombinator.com/item?id=48679608)

**背景**: 年龄验证是一种政策和技术流程，用来检查用户是否达到法律或平台规定的年龄门槛，例如是否已满 18 岁。传统做法通常包括上传政府证件、使用信用卡，或依赖第三方身份提供者，这些方式都可能暴露敏感个人信息。保护隐私的年龄验证试图把需要证明的事实，例如“已满 18 岁”，同用户的完整身份分离开来。零知识证明和匿名凭证是可以支持这种分离的密码学技术，但它们本身并不能解决治理、监控、数据留存或胁迫风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cs.columbia.edu/~smb/papers/age-verify.pdf">Privacy-Preserving Age Verification—and Its Limitations Steven M. Bellovin *</a></li>
<li><a href="https://www.newamerica.org/insights/exploring-privacy-preserving-age-verification/">Exploring Privacy-Preserving Age Verification: A Close Look at Zero-Knowledge Proofs</a></li>
<li><a href="https://www.eff.org/deeplinks/2025/07/zero-knowledge-proofs-alone-are-not-digital-id-solution-protecting-user-privacy">Zero Knowledge Proofs Alone Are Not a Digital ID Solution to Protecting User Privacy | Electronic Frontier Foundation</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论整体上认同隐私担忧，但在解决方案和说服方式上存在分歧。一些评论者认为匿名凭证可以让年龄检查不那么侵入性，另一些人则强调，即使是守法用户也会面临勒索、胁迫、敲诈和身份盗窃等具体风险。还有人反复指出，隐私倡导者可能需要给出更清晰、更具体的伤害案例，才能说服那些把年龄验证视为小代价的选民。

**标签**: `#privacy`, `#digital-identity`, `#age-verification`, `#internet-policy`, `#security`

---

<a id="item-7"></a>
## [Apple 或将跳过高端 M6，转向面向 AI 的 M7 Mac。](https://www.bloomberg.com/news/articles/2026-06-25/apple-to-skip-high-end-m6-mac-chips-to-launch-m7-pro-m7-max-m7-ultra-instead?embedded-checkout=true) ⭐️ 7.0/10

Bloomberg 报道称，Apple 计划取消面向高端 Mac 的 M6 Pro 和 M6 Max 芯片，改为推出面向 AI 的 M7 系列，包括 M7 Pro、M7 Max 和 M7 Ultra。首批 M7 Mac 据称目标是在 2027 年推出，而入门级 M6 芯片可能仍会更早发布。 如果报道属实，这一路线图表明 Apple 正在把端侧 AI 和本地推理性能置于常规年度 Pro 与 Max 升级之上。对于关注内存带宽、统一内存容量和高能效 AI 加速的 Mac 开发者、创意专业人士和本地 LLM 用户来说，这可能很重要。 这仍是一则未经官方确认的产品路线图传闻，而且 Bloomberg 的报道据称没有说明代工伙伴或制造工艺节点。社区讨论中特别提到，基础版 M7 的目标内存带宽据称为 240 GB/s，并推测更高端版本如果拥有更高带宽和更大内存，将对本地 LLM 推理尤其有意义。

hackernews · Hacker News 热门 · 6月25日 17:38 · [社区讨论](https://news.ycombinator.com/item?id=48676795)

**背景**: Apple Silicon 是 Apple 自研的 Mac 芯片家族，其中 Pro、Max 和 Ultra 版本通常比基础版提供更多 CPU 与 GPU 核心、更高内存带宽以及更大的统一内存配置。统一内存让 CPU、GPU 和 AI 相关加速器访问同一个内存池，这对大型模型很有用，因为模型权重可能占用数十到数百 GB 的内存。本地 LLM 推理是指在个人电脑上直接运行语言模型，而不是把提示发送到云端 API，它用本地硬件限制换取更少的云端依赖。AI 加速器通常也称为 NPU 或神经引擎，是为更高效加速机器学习工作负载而设计的专用处理器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.macrumors.com/2026/06/25/2027-macs-m7-chips/">2027 Macs to Get AI-Focused M 7 Chips as Apple Skips... - MacRumors</a></li>
<li><a href="https://apxml.com/posts/best-local-llm-apple-silicon-mac">The Best Local LLMs To Run On Every Mac (Apple Silicon)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Neural_processing_unit">Neural processing unit - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论整体偏分析性，许多评论者认为，由于 Apple 不是主要的超大规模云服务商，它有动力让个人电脑强到足以运行本地 LLM。其他人则讨论了内存带宽、内存容量、台式机功耗预算，以及如果消费者需求回到通用计算和大内存，重押 AI 是否存在风险。还有评论者提到另一则关于可能采用 Intel 18A 制造的报道，但也强调 Bloomberg 没有提到代工细节。

**标签**: `#apple-silicon`, `#ai-hardware`, `#local-llms`, `#semiconductors`, `#mac`

---

<a id="item-8"></a>
## [Un-0 探索基于振荡器的图像生成。](https://unconv.ai/blog/introducing-un-0-generating-images-with-coupled-oscillators/) ⭐️ 7.0/10

Unconv.ai 推出了 Un-0，这是一种实验性图像生成方法，使用耦合振荡器动力学，而不是传统的扩散模型或基于 Transformer 的神经模型。该项目展示了一个模拟性质的概念验证，并将其定位为受模拟计算启发的生成式 AI 方向。 这项工作值得关注，因为当前大多数图像生成进展都集中在大型数字神经网络上，而 Un-0 探索的是一种截然不同的计算基础。如果这类系统能够在硬件中高效实现，它们可能指向另一类 AI 加速器，但这种实际影响目前仍未得到证明。 目前这种方法似乎是在传统硬件上模拟运行，因此其潜在优势很可能需要未来的电子或模拟硬件实现才能体现。评论者指出了几个重要限制，包括可能的 n² 连接规模增长、64×64 的演示分辨率，以及它是否真的比神经网络基线更节能仍缺乏答案。

hackernews · Hacker News 热门 · 6月25日 20:50 · [社区讨论](https://news.ycombinator.com/item?id=48679007)

**背景**: 耦合振荡器是指多个单独振荡过程相互影响的系统，常见现象包括同步和正常模式等集体行为。这类动力学长期存在于物理研究中，也曾出现在早期图像处理研究里，例如用振荡器网络进行图像分割。模拟计算是利用物理过程本身来执行计算，而传统数字计算机通常用离散比特来表示数值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48679007">Un - 0 : Generating Images with Coupled Oscillators | Hacker News</a></li>
<li><a href="https://scholar.harvard.edu/files/schwartz/files/lecture3-coupled-oscillators.pdf">Lecture3- Coupled - Oscillators .pdf</a></li>
<li><a href="https://www.researchgate.net/publication/262263612_Image_Segmentation_Using_Frequency_Locking_of_Coupled_Oscillators">(PDF) Image Segmentation Using Frequency Locking of Coupled ...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 讨论整体上对这种新颖思路感到好奇且较为正面，不少评论者认为它相比主流 AI 模型很有新意。与此同时，许多人也提出了可行性担忧，包括硬件实现、n² 连接规模、输出分辨率偏低，以及缺少具体能效对比。

**标签**: `#analog-computing`, `#image-generation`, `#oscillators`, `#AI-research`, `#hardware`

---

<a id="item-9"></a>
## [Bank Python 的历史再受关注。](https://calpaterson.com/bank-python.html) ⭐️ 7.0/10

Cal Paterson 于 2021 年撰写的一篇文章再次受到讨论，内容是大型投行内部基于 Python 的专有平台口述史。文章解释了这些银行为何开发出不寻常的内部生态系统，而不是采用今天 Python 世界中常见的现成工具。 这段历史的重要性在于，它展示了金融基础设施如何长期保留那些在现代打包、数据和部署工具出现之前作出的设计决策。对于维护遗留平台、内部开发者平台或受监管金融系统的工程师来说，这很有参考价值，因为在这些环境中，可靠性和组织约束往往比新技术更重要。 文章和讨论提到，这类银行专用 Python 生态通常包含全局 Python 对象存储、金融工具依赖管理、全行级任务运行系统以及自定义表格库等组件。评论者还把这些系统与 Goldman Sachs 的 SecDB 和 Slang 联系起来，并提到后来以 Python 为中心的平台，例如 JPMorgan 的 Alpha 或 Athena，以及 Merrill 的 Quartz。

hackernews · Hacker News 热门 · 6月25日 20:14 · [社区讨论](https://news.ycombinator.com/item?id=48678645)

**背景**: Python 在金融行业被广泛使用，因为它表达能力强、易于集成，并且适合分析和脚本编写。大型投行的一些核心定价、交易、风险和分析系统围绕 Python 或类似 Python 的环境构建，而且很多是在今天成熟的开源基础设施出现之前就已经形成的。据报道，JPMorgan 的 Athena 是一个规模很大的基于 Python 的交易平台，用于定价、交易、风险管理、分析、数据科学和机器学习。Goldman Sachs 的 SecDB 被描述为一个风险管理系统，并常被视为全行级金融建模平台的重要先驱。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tldr.tech/webdev/2025-06-24">Git’s coolest feature, skip exit interviews, Bank Python</a></li>
<li><a href="https://www.techrepublic.com/article/jpmorgans-athena-has-35-million-lines-of-python-code-and-wont-be-updated-to-python-3-in-time/">JPMorgan 's Athena has 35 million lines of Python ... - TechRepublic</a></li>
<li><a href="http://secdb.com/">SecDb : Goldman Sach 's Risk Management System</a></li>

</ul>
</details>

**社区讨论**: 讨论整体上以赞赏为主，评论者认为这篇文章清楚解释了这些系统的演化方式。多位评论者补充了关于 SecDB、Slang、Alpha、Quartz 以及类似平台的一手或历史背景，同时也有人强调，许多看似奇怪的选择在现代现成工具尚不存在时其实是合理的。还有人好奇这些银行是否已经采用 uv 等新工具，也有人遗憾这些底层基础设施很可能不会开源。

**标签**: `#python`, `#software-history`, `#finance-technology`, `#internal-platforms`, `#legacy-systems`

---

<a id="item-10"></a>
## [Apple 上调 MacBook 和 iPad 价格](https://www.reuters.com/world/asia-pacific/apple-raises-prices-macbooks-ipads-memory-costs-skyrocket-2026-06-25/) ⭐️ 7.0/10

据报道，Apple 在 2026 年 6 月 25 日对多款 MacBook、iPad、iMac 和 Mac Studio 机型上调了价格。例如，13 英寸 MacBook Air 从 1,099 美元涨至 1,299 美元，M3 Ultra Mac Studio 从 3,999 美元涨至 5,299 美元。 这一变化很重要，因为 Apple 的定价往往会影响整个个人电脑和平板市场的预期。如果内存成本是主要原因，其他硬件厂商也可能面临涨价压力，尤其是在 AI 基础设施需求与消费硬件争夺内存供应的情况下。 据称，不同产品的涨幅差异很大，一些入门设备上涨约 100 到 200 美元，而高端 Mac Studio 配置的涨幅超过 1,000 美元。报道给出的原因是内存成本大幅上升，但现有信息并未披露 Apple 的零部件采购合同或利润率，因此无法在这里独立核实具体成本转嫁比例。

hackernews · virgildotcodes · 6月25日 13:02 · [社区讨论](https://news.ycombinator.com/item?id=48672732)

**背景**: DRAM 和 NAND 闪存是电脑、平板、SSD 以及许多电子设备使用的核心存储技术。它们的价格具有周期性，因为供应取决于半导体制造产能和厂商生产计划，而当云计算和 AI 基础设施等大型买家增加订单时，需求可能迅速变化。DRAMeXchange 等市场追踪机构会监测 DRAM、NAND 闪存、SSD 和相关模组的现货与合约价格。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dramexchange.com/">DRAMeXchange - World leading DRAM and NAND Flash market...</a></li>
<li><a href="https://www.linkedin.com/pulse/massive-dram-shortage-until-2027-expect-84-price-ocr9c">Massive DRAM Shortage Until 2027: Expect an 84% Price Surge</a></li>

</ul>
</details>

**社区讨论**: 讨论整体上带有挫败和担忧情绪，多位评论者将涨价归因于 AI 公司和内存需求挤压了消费硬件买家。也有人补充历史视角，认为尽管这次涨价令人痛苦，但计算设备相比几十年前仍然便宜得多。还有评论者认为，Apple 的动作可能预示整个行业将出现更广泛的涨价。

**标签**: `#apple`, `#hardware`, `#supply-chain`, `#memory`, `#consumer-tech`

---

<a id="item-11"></a>
## [Google AI 概览责任争议](https://simonwillison.net/2026/Jun/25/ai-and-liability/#atom-everything) ⭐️ 7.0/10

Bruce Schneier 认为，部署 AI 系统的组织应当对其输出承担法律责任，并引用了德国近期一项裁决：Google 需为 AI 概览中的虚假内容负责。Simon Willison 转引并强调了 Schneier 的观点，即 AI 代理应被视为部署它们的公司的代理。 如果法院将 AI 生成的摘要视为公司的自身表述，那么在搜索、客服、法律、医疗或代理式工作流中使用生成式 AI 的企业，可能会面临更强的输出核验压力。这个问题是 AI 治理的核心之一，因为它决定了企业能否把幻觉输出带来的风险转嫁给用户和第三方。 这一论点把 AI 生成摘要与人类作者产出的内容进行类比：如果公司会因人工撰写摘要中的错误承担责任，那么它不应仅仅因为文本来自 AI 就免除责任。该文章没有对德国案件作详细法律分析，但将这项裁决描述为反对把 AI 错误视为“无责任自动化”的先例。

rss · Simon Willison · 6月25日 22:28

**背景**: Google AI 概览是 Google 搜索中的一项功能，它使用 AI 生成搜索结果摘要，并提供带有进一步阅读链接的信息快照。这类系统可以帮助用户快速获得答案，但也因不准确以及可能减少原始网站流量而受到批评。在 AI 政策讨论中，“幻觉”通常指生成内容看起来可信，但实际上是错误或缺乏依据的情况。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Google_AI_Overviews">Google AI Overviews</a></li>
<li><a href="https://search.google/ways-to-search/ai-overviews/">Google AI Overviews - Search anything, effortlessly</a></li>

</ul>
</details>

**标签**: `#AI liability`, `#AI governance`, `#legal policy`, `#Google`, `#AI overviews`

---

<a id="item-12"></a>
## [GitHub Copilot 推出桌面应用](https://www.infoq.cn/article/GaAsWkrJQW2NFf06kgyG?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

GitHub 推出了面向 Agent 驱动开发工作流的 Copilot 桌面应用。根据 GitHub 的产品页面，该应用面向付费 GitHub Copilot 计划用户开放，并支持 macOS、Windows 和 Linux。 这让 Copilot 拥有了专门的桌面工作区，而不再主要依赖编辑器或网页集成，开发者可能更容易跨代码库、议题和任务管理 AI 辅助编码会话。这也反映了开发者工具从单次代码补全转向 Agent 式工作流的趋势，即让 AI 更主动地规划、修改并协调开发工作。 GitHub 将 Copilot 应用描述为原生构建在 GitHub 之上的 Agent 驱动开发桌面体验，并提供用于代码库、编码会话、议题和 AI 辅助工作流的统一工作区。目前公开信息没有提供深入的实现细节、性能基准，也没有说明并行 Agent 如何调度或隔离。

rss · InfoQ 中文 · 6月25日 19:06

**背景**: GitHub Copilot 是一种 AI 编码助手，可以利用自然语言提示和代码上下文帮助开发者编写、解释和修改代码。Agent 驱动开发不只是自动补全代码，而是让 AI 系统承担更大的任务，例如探索代码库、提出修改、调试或协调多条工作线。并行 Agent 工作流意味着多个 AI Agent 或会话可以同时处理不同任务，这可能加快开发速度，但也会增加代码审查、冲突解决和安全变更管理的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/features/ai/github-app">GitHub Copilot app · GitHub</a></li>
<li><a href="https://github.com/features/copilot">GitHub Copilot · Your AI pair programmer · GitHub</a></li>
<li><a href="https://openai.com/codex/">Codex | AI Coding Partner from OpenAI | OpenAI</a></li>

</ul>
</details>

**标签**: `#GitHub Copilot`, `#AI coding assistants`, `#developer tools`, `#agent workflows`

---

<a id="item-13"></a>
## [PostgreSQL 19 Beta 增加图查询。](https://www.infoq.cn/article/HOFzjxIov0SxEpmZccYT?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

据报道，PostgreSQL 19 Beta 引入了 SQL 图查询能力和支持并发的表重新打包功能。该报道强调了这个版本的两个方向：通过 SQL/PGQ 进行图遍历，以及以更低中断方式执行表维护。 图查询可能让 PostgreSQL 更适合处理关系、路径和网络类工作负载，而不必立即把数据迁移到专门的图数据库。并发表重新打包也可能改善运维维护流程，降低回收膨胀表空间时对写入操作的阻塞影响。 当前新闻条目没有提供语法示例、性能基准、发布说明或实现细节，因此这些 PostgreSQL 19 Beta 功能的确切范围和稳定性仍需在上游文档发布后确认。PostgreSQL 现有的 REINDEX CONCURRENTLY 已经可以在重建索引时减少锁影响，但并发表重新打包针对的是表膨胀，而不只是索引膨胀。

rss · InfoQ 中文 · 6月25日 11:03

**背景**: SQL/PGQ 是 SQL:2023 引入的属性图查询语言，用于在 SQL 内表达图模式和图遍历。PostgreSQL 过去已经可以用普通表表示类似图的数据，但专门的图查询语法可以让多跳关系查询更容易编写和理解。表膨胀在 PostgreSQL 中很常见，因为 MVCC 会保留旧行版本直到清理；重新打包会重写表存储，以回收空间并改善数据布局。传统的整表重写可能带来明显中断，因此并发方式对需要持续读写的生产系统很重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cybertec-postgresql.com/en/handling-graphs-with-sql-pgq-in-postgresql/">Handling graphs with SQL / PGQ in PostgreSQL | CYBERTEC...</a></li>
<li><a href="https://postgresqlhtx.com/postgresql-table-bloat-management-vacuum-full-pg_repack-and-the-coming-repack-concurrently/">PostgreSQL Table Bloat Management: VACUUM FULL, pg_repack...</a></li>
<li><a href="https://www.postgresql.org/docs/current/sql-reindex.html">PostgreSQL : Documentation: 18: REINDEX</a></li>

</ul>
</details>

**标签**: `#PostgreSQL`, `#Database`, `#SQL`, `#GraphQuery`, `#Release`

---

<a id="item-14"></a>
## [美光显示 AI 存储需求正在爆发。](https://36kr.com/p/3868523068298499?f=rss) ⭐️ 6.0/10

文章称，美光在 6 月 24 日发布了异常强劲的 2026 财年第三季度财报，收入达到 415 亿美元，环比增长 74%，同比增长 346%。公司还披露了 16 份战略客户协议，即 SCA，并称即使按价格下限计算，剩余合同期内的签约价值也可达到 1000 亿美元。 美光的业绩被文章视为 AI 基础设施需求仍在强劲拉动存储芯片供应的证据，而不只是拉动 GPU 需求。文章认为，这轮 AI 硬件景气正在把资金从黄金等防御性资产吸引到半导体和算力相关股票中。 根据文章，这些 SCA 包含 220 亿美元现金保证金和金融承诺，有助于提高美光未来需求的可见度。需要注意的是，文章对黄金的比较主要是市场资金层面的分析：其认为利率走高和通胀预期升温仍是压制金价的核心因素，而 AI 板块吸金是额外拖累。

rss · 36氪 · 6月25日 11:49

**背景**: 美光是一家主要的存储芯片厂商，而 AI 服务器需要大量高性能存储来配合加速器运行，并支撑模型训练或推理负载。战略客户协议是一类长期供货安排，通常可以锁定产能、定价框架、保证金或采购承诺。搜索结果称，美光近期的 SCA 涉及不可取消的长期合同和客户预付款，也提到其与 Anthropic 围绕 AI 存储需求达成长期供应安排的报道。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wallstreetcn.com/articles/3775569">美 光 长 协 的含金量：客户先押220...</a></li>
<li><a href="https://wallstreetcn.com/articles/3775212">报道： 美 光 与Anthropic达成 协 议 ，锁定内存 长 期 供 应 协 议</a></li>
<li><a href="https://www.tmtpost.com/8036844.html">Edge AI Daily 早报（6月23日）-钛媒体官方网站</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#AI infrastructure`, `#Micron`, `#financial markets`, `#memory chips`

---

<a id="item-15"></a>
## [Anthropic 的 Claude 付费份额上升。](https://36kr.com/newsflashes/3869577931740417?f=rss) ⭐️ 6.0/10

一份报告称，Anthropic 的 Claude 正在与 OpenAI 的竞争中快速提升付费用户市场份额，Indagari 的信用卡交易数据显示，Claude 的付费用户和收入逐月增长。报告称，自 2026 年 1 月以来，该细分市场收入增长约 75%，DataCamp 也表示 Claude 已成为其平台搜索量最高的词条。 这些数据表明，消费者为 AI 助手付费的意愿可能正在从 OpenAI 的 ChatGPT 生态扩散到其他产品。如果这一趋势持续，Anthropic 的增长势头可能会加剧 AI 订阅市场在价格、产品和模型质量上的竞争。 据称，Indagari 的数据集覆盖 2800 万美国消费者的数千亿笔匿名信用卡交易，并按周追踪 2025 年至 2026 年 5 月 10 日的数据。该消息没有提供原始报告、绝对收入数字、订阅档位拆分，也没有 Anthropic 或 OpenAI 的官方确认，因此这些数字更适合作为第三方市场信号，而非公司官方指标。

rss · 36氪 · 6月26日 05:38

**背景**: Claude 是 Anthropic 开发的一系列大型语言模型和 AI 助手。Anthropic 将 Claude 定位为面向工作场景、强调安全性、准确性和安全保障的新一代助手。在消费级 AI 市场中，付费订阅是一个重要指标，因为它不仅反映用户兴趣，也反映用户是否愿意为更高使用额度、更强模型或高级功能付费。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/">Claude</a></li>
<li><a href="https://docs.anthropic.com/en/docs/about-claude/models/all-models">All models overview - Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model ) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#Anthropic`, `#OpenAI`, `#market share`, `#Claude`

---

<a id="item-16"></a>
## [无界动力融资超 2 亿美元。](https://36kr.com/newsflashes/3869493315900680?f=rss) ⭐️ 6.0/10

6 月 26 日，中国通用具身智能机器人公司无界动力宣布完成超 2 亿美元天使轮融资。参与方包括京东关联基金、C 资本、弘毅投资、盛宇投资、丰源投资，以及老股东线性资本、红杉中国、华业天成、雅瑞资本等。 超 2 亿美元的天使轮融资规模很大，显示出资本市场对中国具身智能和通用机器人的强烈兴趣。这笔资金可能帮助无界动力扩大研发、基础设施建设和交付能力，而行业正试图把 AI 模型能力与实体机器人结合起来。 公司称融资将用于具身通用大脑研发、技术基础设施建设以及全球规模化交付。公告未披露估值、产品指标、技术架构、客户进展或明确的科研里程碑。

rss · 36氪 · 6月26日 04:12

**背景**: 具身智能是指通过机器人等实体与物理世界互动的 AI 系统，而不只是处理文本、图像或其他数字输入。在机器人领域，“通用机器人大脑”通常指能够感知环境、规划动作并控制机器人完成多种任务的软件和模型。中国近年来把具身智能视为推动机器人产业升级的重要方向，这也解释了资本和产业资源为何集中关注这一赛道。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://merics.org/de/report/embodied-ai-chinas-ambitious-path-transform-its-robotics-industry">Embodied AI: China's ambitious path to transform its robotics industry</a></li>

</ul>
</details>

**标签**: `#robotics`, `#embodied-ai`, `#startup-funding`, `#china-tech`, `#venture-capital`

---