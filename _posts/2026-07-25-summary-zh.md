---
layout: default
title: "Horizon Summary: 2026-07-25 (ZH)"
date: 2026-07-25
lang: zh
---

> 从 92 条内容中筛选出 15 条重要资讯。

---

1. [开放权重 AI 的 Kubernetes 时刻](#item-1) ⭐️ 9.0/10
2. [Anthropic 发布 Claude Opus 5，价格仅为 Fable 5 的一半](#item-2) ⭐️ 9.0/10
3. [SK 集团与英伟达达成超 5000 亿美元 AI 合作](#item-3) ⭐️ 9.0/10
4. [Anthropic 向 SK 海力士请求芯片供应以自造 AI 硬件](#item-4) ⭐️ 9.0/10
5. [三星与博通签署 2000 亿美元芯片代工协议，采用 2nm 及以下工艺](#item-5) ⭐️ 9.0/10
6. [Ruff v0.16.0 将默认规则扩展至 413 条](#item-6) ⭐️ 8.0/10
7. [AMD 能否打破 NVIDIA 的 CUDA 护城河？策略分析](#item-7) ⭐️ 8.0/10
8. [中国对携程处以 7.7 亿美元罚款，因滥用市场支配地位](#item-8) ⭐️ 8.0/10
9. [多所大学因准确性问题限制 AI 检测工具](#item-9) ⭐️ 8.0/10
10. [OpenAI 与 Anthropic 游说限制开源 AI](#item-10) ⭐️ 8.0/10
11. [宇树科技 2025 年交付 5500 台人形机器人，拟上海 IPO](#item-11) ⭐️ 8.0/10
12. [Fluidstack 以 75 亿美元估值完成 8.3 亿美元 A 轮融资](#item-12) ⭐️ 8.0/10
13. [Android 可能限制设备端 ADB，引发开发者争议](#item-13) ⭐️ 7.0/10
14. [AI“大力出奇迹”时代还能持续多久？](#item-14) ⭐️ 7.0/10
15. [GitHub Issues 通过缓存和预取实现大幅提速](#item-15) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [开放权重 AI 的 Kubernetes 时刻](https://tobi.knaup.me/2026-07-25-open-weight-ai-is-having-its-kubernetes-moment/) ⭐️ 9.0/10

一篇文章认为，开放权重 AI 模型正成为 AI 领域无处不在的基础设施层，类似于 Kubernetes 在云计算中的角色。这一转变预计将对监管、市场动态和地缘政治产生深远影响。 开放权重模型可以减少供应商锁定并降低成本，使初创公司和研究人员能够建立在共同基线之上。这种 AI 基础设施的民主化可能会刺激创新并改变竞争格局，正如 Kubernetes 对云原生应用所做的那样。 文章将 Kubernetes 对容器编排的标准化与开放权重模型标准化 AI 部署的潜力直接类比。文章指出，美国实验室需要以宽松许可证发布前沿级别的开放权重模型，以便初创公司在此基础上进行创新。

hackernews · tknaup · 7月25日 14:49 · [社区讨论](https://news.ycombinator.com/item?id=49048034)

**背景**: 开放权重 AI 模型是指其训练参数（权重）公开可用的模型，允许用户下载、运行和修改它们。Kubernetes 是一个用于自动化部署、扩展和管理容器化应用程序的开源系统，已成为云基础设施的行业标准。该类比表明，开放权重模型可能同样成为 AI 应用程序的默认基础。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://allthings.how/what-is-an-open-weight-ai-model-and-how-to-use-one/">What is an Open Weight AI Model and How to Use One</a></li>

</ul>
</details>

**社区讨论**: 评论者强调了按来源禁止中国 AI 模型的难度，因为权重只是数字，并讨论了 AI 定价（代币经济学）的不稳定性，而开放权重模型可能稳定这一现象。其他人指出 OpenAI 已发布了一些开放权重模型，但呼吁更频繁地更新，有些人设想了一种真正协作的开放模型，类似于 Linux。

**标签**: `#open-weight AI`, `#AI infrastructure`, `#AI regulation`, `#open source AI`, `#AI economics`

---

<a id="item-2"></a>
## [Anthropic 发布 Claude Opus 5，价格仅为 Fable 5 的一半](https://simonwillison.net/2026/Jul/24/introducing-claude-opus-5/#atom-everything) ⭐️ 9.0/10

Anthropic 宣布推出新的旗舰大语言模型 Claude Opus 5，该模型在 Artificial Analysis 排行榜上领先，性能接近 Claude Fable 5，但价格仅为后者的一半。 此次发布以更低的价格提供顶尖能力，使前沿 AI 更易于获取，可能加速企业和研究领域的采用，同时保持强大的安全特性。 Claude Opus 5 定价与 Opus 4.8 相同，并提供快速模式（价格翻倍）；它展示了主动行为，能自主构建计算机视觉管线来完成任务。该模型在漏洞检测方面有所改进，但刻意未接受利用漏洞的训练。

rss · Simon Willison · 7月24日 23:48

**背景**: Claude 是 Anthropic 开发的一系列大语言模型，通常以三种规模发布：Haiku、Sonnet 和 Opus（能力最强）。2026 年，Anthropic 推出了更强大的 Mythos 和 Fable 模型，其中 Claude Fable 5 是面向公众的前沿模型。Claude Opus 5 作为更经济的选择，保持了接近前沿的水平。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/leaderboards/models">LLM Leaderboard - Comparison of AI models from OpenAI, Anthropic...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Opus">Claude Opus</a></li>
<li><a href="https://openrouter.ai/anthropic/claude-opus-5">Claude Opus 5 - API Pricing &amp; Benchmarks | OpenRouter</a></li>

</ul>
</details>

**社区讨论**: 有评论称赞 Anthropic 在提炼 Fable 方面的能力；Boris Cherny 则根据系统卡中的评估指出，Opus 5 是目前最难被提示注入的模型。整体情绪积极，对其主动能力和安全改进感到兴奋。

**标签**: `#AI`, `#Anthropic`, `#Claude Opus 5`, `#Large Language Models`, `#Machine Learning`

---

<a id="item-3"></a>
## [SK 集团与英伟达达成超 5000 亿美元 AI 合作](https://36kr.com/newsflashes/3910690882507907?f=rss) ⭐️ 9.0/10

SK 集团与英伟达宣布了一项价值超过 5000 亿美元的战略合作，计划共同建设 AI 工厂并联合开发下一代高带宽内存（HBM）。SK 电信将基于英伟达的 Vera Rubin DSX 参考设计建设一座 2 吉瓦的 AI 工厂，同时 SK 海力士将与英伟达合作开发先进的 HBM 内存解决方案。 此次合作是 AI 基础设施领域最大规模的投资之一，确保了用于训练大型语言模型和支持代理 AI 及物理 AI 等新兴 AI 工作负载的关键 HBM 内存的长期供应。这加深了 SK 海力士与英伟达之间的相互依赖关系，将影响全球半导体供应链和 AI 计算格局。 该协议包括一份意向书，以正式确定在 AI 工厂建设和 AI 内存供应方面的合作。SK 电信的 2 吉瓦 AI 工厂将利用英伟达 Vera Rubin DSX 参考设计，该设计通过 NVIDIA Omniverse DSX 的数字孪生技术为共建 AI 基础设施提供了蓝图。

rss · 36氪 · 7月25日 06:40

**背景**: 高带宽内存（HBM）是一种 3D 堆叠内存技术，提供高带宽和低功耗，对于英伟达 GPU 等 AI 加速器至关重要。AI 工厂是为 AI 工作负载专门优化的数据中心，通常采用英伟达 Vera Rubin DSX 等参考设计，该设计包含数字孪生仿真，以实现高效的设计和运营。代理 AI 是指能够自主规划和执行任务的 AI 系统，而物理 AI 则涉及将 AI 嵌入硬件中与真实世界交互，两者都需要巨大的计算能力和内存带宽。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-releases-vera-rubin-dsx-ai-factory-reference-design-and-omniverse-dsx-digital-twin-blueprint-with-broad-industry-support">NVIDIA Releases Vera Rubin DSX AI Factory Reference Design ...</a></li>
<li><a href="https://semiengineering.com/high-bandwidth-memory-hbm-everything-you-need-to-know/">High Bandwidth Memory (HBM): Everything You Need To Know</a></li>

</ul>
</details>

**标签**: `#NVIDIA`, `#AI基础设施`, `#HBM`, `#SK海力士`, `#战略合作`

---

<a id="item-4"></a>
## [Anthropic 向 SK 海力士请求芯片供应以自造 AI 硬件](https://www.techmeme.com/260725/p12#a260725p12) ⭐️ 9.0/10

SK 集团会长崔泰源宣布，AI 开发商 Anthropic 已向 SK 海力士请求芯片供应，以制造自己的半导体，这标志着 AI 公司向垂直整合迈出了重要一步。 此举表明领先的 AI 开发商不再满足于仅依赖外部芯片供应商，可能颠覆半导体供应链并加剧 AI 硬件领域的竞争。 该请求已提交给全球最大内存芯片制造商之一 SK 海力士，但芯片类型或时间表等细节尚未披露。

rss · Techmeme · 7月25日 13:50

**背景**: Anthropic 是一家著名的人工智能研发公司，以创建 Claude 系列大型语言模型而闻名。传统上，像 Anthropic 这样的 AI 公司依赖 NVIDIA 或 AMD 等芯片制造商提供硬件，但设计定制芯片可以在性能和成本方面为其特定算法提供优势。

**标签**: `#AI hardware`, `#Anthropic`, `#semiconductor`, `#vertical integration`, `#SK Hynix`

---

<a id="item-5"></a>
## [三星与博通签署 2000 亿美元芯片代工协议，采用 2nm 及以下工艺](https://www.techmeme.com/260725/p9#a260725p9) ⭐️ 9.0/10

三星电子宣布与博通达成价值超过 2000 亿美元的合同，将在 2030 年前使用其 2nm 及以下工艺技术为博通制造芯片。 这一里程碑式的协议巩固了三星在先进半导体代工市场的地位，并确保了 AI 基础设施关键芯片的长期供应，可能重塑全球芯片制造竞争格局。 该合同聚焦于三星的 2nm 及以下工艺节点，代表了目前处于开发中的最先进半导体制造技术。博通的产品主要面向 AI 基础设施和网络设备。

rss · Techmeme · 7月25日 09:45

**背景**: 2nm 工艺是继 3nm 之后的下一代半导体制造节点，可实现更高的晶体管密度和能效。该技术仍处于早期阶段，三星和台积电正竞相实现商业化。三星赢得此合同表明其代工能力取得重大进展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/2_nm_process">2 nm process - Wikipedia</a></li>
<li><a href="https://avecas.in/advanced-process-nodes-2nm-and-beyond/">Advanced Process Nodes (2nm and Beyond): The Future of Chip Manufacturing - Avecas</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#AI hardware`, `#Samsung`, `#Broadcom`, `#2nm process`

---

<a id="item-6"></a>
## [Ruff v0.16.0 将默认规则扩展至 413 条](https://simonwillison.net/2026/Jul/25/ruff/#atom-everything) ⭐️ 8.0/10

Astral 于 2026 年 7 月 23 日发布了 Ruff v0.16.0，将默认 linting 规则从 59 条增加到 413 条，这可能会破坏现有的 CI 工作流。新的默认规则能够捕获之前需要手动启用的严重问题，如语法错误和运行时错误。 这一变化大幅提高了 Python 代码质量基线，无需任何配置即可自动捕获更多错误。在 CI 中使用未固定版本 Ruff 的开发者可能会遇到意外失败，但该更新鼓励更好的编码实践，并契合 Astral 被 OpenAI 收购后 AI 辅助修复代码的方向。 Ruff 现在默认启用 413 条规则（v0.1.0 时仅为 59 条），而可用规则总数从 708 条增至 968 条。可通过 \`uvx ruff@latest check . --fix --unsafe-fixes\` 应用升级，在一个项目中自动修复了 1618 个错误中的 1538 个。

rss · Simon Willison · 7月25日 22:44

**背景**: Ruff 是一个用 Rust 编写的极快 Python 代码检查器和格式化工具，旨在作为 Flake8、isort 和 Black 等工具的即插即用替代品。它由 Astral 开发（该公司近期被 OpenAI 收购），因其速度和全面的规则集而迅速被采用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.astral.sh/ruff/linter/">The Ruff Linter | Ruff - Astral</a></li>
<li><a href="https://pypi.org/project/ruff/">ruff · PyPI</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and ... ruff · PyPI Ruff - Astral Ruff: Complete Guide to Python&#x27;s Fastest Linter | pydevtools GitHub - sartcod/ruff: An extremely fast Python linter and ... Ruff: A Modern Python Linter for Error-Free and Maintainable ...</a></li>

</ul>
</details>

**标签**: `#Python`, `#linting`, `#Ruff`, `#software development`, `#CI`

---

<a id="item-7"></a>
## [AMD 能否打破 NVIDIA 的 CUDA 护城河？策略分析](https://newsletter.semianalysis.com/p/can-amd-break-the-cuda-moat-amd-advancing) ⭐️ 8.0/10

Semianalysis 发表了对 AMD 挑战 NVIDIA CUDA 霸主地位的深度分析，重点介绍了代理内核生成（Agentic Kernel Generation）、软件质量改进以及为 OpenAI 提供高达 105% 股权回扣折扣等激进财务激励策略，同时详细说明了不稳定的内部集群和 Helios MI455X 生产爬坡等挑战。 打破 CUDA 护城河对于 AMD 在 AI 硬件领域获得有意义的市场份额至关重要；如果 AMD 的软件生态系统和集群可靠性能够与 NVIDIA 匹敌，可能会重塑 AI 基础设施格局，减少对单一供应商的依赖。 AMD 的代理内核生成方法利用 AI 自动编写优化内核，可能减少手动 CUDA 编程的需求。Helios MI455X 系统配备 72 个 GPU、31TB HBM4 内存和近 2,900 PFLOPS FP4 性能，但其 Infinity Fabric 互连带宽（896 GB/s）落后于 NVIDIA 的 NVLink 6（3.6 TB/s）。

rss · SemiAnalysis · 7月25日 00:33

**背景**: NVIDIA 的 CUDA 平台因其成熟的软件生态系统和开发者锁定效应而在 AI 计算领域占据主导地位。AMD 一直试图用其 ROCm 软件栈与之抗衡，但历史上存在软件错误和生态系统碎片化问题。代理内核生成是一种新技术，通过 AI 模型自动编写和优化 GPU 内核，可能降低 AMD 硬件采用的门槛。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newsletter.semianalysis.com/p/can-amd-break-the-cuda-moat-amd-advancing">Can AMD break the CUDA Moat? AMD Advancing AI 2026</a></li>
<li><a href="https://www.servethehome.com/amds-epyc-venice-instinct-mi455x-helios-hardware-on-display-for-first-time-at-ces-2026/">AMD’s EPYC Venice, Instinct MI 455 X , &amp; Helios ... - ServeTheHome</a></li>
<li><a href="https://arxiv.org/pdf/2512.23236">KernelEvolve: Scaling Agentic Kernel Coding for Heterogeneous AI...</a></li>

</ul>
</details>

**标签**: `#AMD`, `#CUDA`, `#AI`, `#GPU`, `#semiconductor`

---

<a id="item-8"></a>
## [中国对携程处以 7.7 亿美元罚款，因滥用市场支配地位](https://www.techmeme.com/260725/p16#a260725p16) ⭐️ 8.0/10

中国市场监管机构对携程集团（Trip.com Group）处以总计 52 亿元人民币（约合 7.7 亿美元）的罚款并没收违法所得，原因是其在国内在线酒店预订市场滥用市场支配地位。 这一重大罚款突显了中国对大型科技平台加强反垄断执法力度，标志着对数字经济中垄断行为的持续监管打击。 罚款及没收违法所得共计 52 亿元人民币，监管机构指出携程在在线酒店预订领域滥用市场支配地位。据路透社报道，该行动于 2026 年 7 月 25 日公布。

rss · Techmeme · 7月25日 20:35

**背景**: 携程集团是中国最大的在线旅行社，在酒店预订市场占据主导地位。中国反垄断监管机构此前已对阿里巴巴和腾讯等科技巨头采取行动，近年对科技巨头的垄断行为执法力度持续加强。滥用市场支配地位的行为包括签订独家协议和不公平定价等。

**标签**: `#antitrust`, `#regulation`, `#China`, `#travel`, `#tech`

---

<a id="item-9"></a>
## [多所大学因准确性问题限制 AI 检测工具](https://www.techmeme.com/260725/p15#a260725p15) ⭐️ 8.0/10

包括耶鲁大学、约翰霍普金斯大学和滑铁卢大学在内的多所主要大学，因担心 AI 检测工具的准确性而限制或停用这些工具，并开始重新评估学术诚信政策。 这一转变凸显了 AI 检测工具的现实不可靠性及其对学生的影响，迫使教育机构重新思考如何检测 AI 生成内容并设计评估方式。 据《金融时报》报道，部分机构正在改革评估方法，减少对监控的依赖。像 GPTZero 这样的 AI 检测工具已被证实会产生误报，尤其是对非英语母语者。

rss · Techmeme · 7月25日 18:05

**背景**: AI 检测工具通过分析文本中 AI 生成的典型模式（如 token 级别的可预测性）来工作。但它们并非 100%准确，可能会将人类撰写的文本误判为 AI 生成，从而在学术环境中引发公平性和可靠性的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://merlin-staging.vercel.app/blogs/artificial-intelligence/ai-text-detectors-explained">AI Text Detectors Explained: How They Work &amp; Accuracy</a></li>
<li><a href="https://www.compilatio.net/en/blog/are-ai-detectors-accurate">How accurate are AI detectors ? Explanation, strengths and boundaries</a></li>

</ul>
</details>

**标签**: `#AI detectors`, `#education`, `#academic integrity`, `#AI ethics`, `#policy`

---

<a id="item-10"></a>
## [OpenAI 与 Anthropic 游说限制开源 AI](https://www.techmeme.com/260725/p13#a260725p13) ⭐️ 8.0/10

据纽约时报引用的消息来源，OpenAI 和 Anthropic 正私下游说华盛顿监管机构限制开源 AI 模型，尽管萨姆·奥尔特曼等领导人公开表示支持开源 AI。 这暴露了主要 AI 公司在公开立场与私下行动之间的重大矛盾，可能影响未来的 AI 监管并威胁开源生态系统。 游说行动特别针对限制来自中国的开源 AI 模型，使 Anthropic 和 OpenAI 与科技行业的其他大部分公司对立。

rss · Techmeme · 7月25日 14:45

**背景**: 开源 AI 模型公开供人使用和修改，而闭源模型是专有的。关于开源模型（尤其是来自外国实体的模型）是否构成安全风险或抑制创新，一直存在争论。

**标签**: `#AI`, `#open-source`, `#regulation`, `#lobbying`, `#OpenAI`

---

<a id="item-11"></a>
## [宇树科技 2025 年交付 5500 台人形机器人，拟上海 IPO](https://www.techmeme.com/260725/p10#a260725p10) ⭐️ 8.0/10

总部位于杭州的宇树科技在 2025 年交付了 5500 台人形机器人，占据全球市场份额超过 25%，并正准备在上海证券交易所进行首次公开募股（IPO）。 这标志着人形机器人商业化的重要里程碑，展示了宇树科技的市场主导地位及其重塑机器人和人工智能行业的潜力。即将进行的 IPO 表明投资者信心强劲，可能加速人形机器人在各领域的应用。 据《时代》杂志报道，该公司在 2025 年交付了 5500 台人形机器人，占全球市场份额超过 25%。由王兴兴创办的宇树科技正筹备在上海上市。

rss · Techmeme · 7月25日 10:40

**背景**: 宇树科技是一家专注于人形和四足机器人的中国机器人公司。人形机器人旨在模仿人类形态和运动，常用于研究、工业任务和消费应用。宇树科技的产品与波士顿动力和特斯拉等公司的产品竞争。其巨大的市场份额和 IPO 计划表明人形机器人产业日益成熟。

**标签**: `#robotics`, `#humanoid robots`, `#Unitree`, `#China`, `#IPO`

---

<a id="item-12"></a>
## [Fluidstack 以 75 亿美元估值完成 8.3 亿美元 A 轮融资](https://www.techmeme.com/260725/p2#a260725p2) ⭐️ 8.0/10

与 Anthropic 合作的 AI 数据中心建设商 Fluidstack 宣布，在 1 月份完成了由 Situational Awareness 领投的 8.3 亿美元 A 轮融资，估值达 75 亿美元。 这笔巨额融资凸显了对专业 AI 基础设施的旺盛需求，像 Fluidstack 这样的 Neocloud 提供商通过提供 GPU 优化能力挑战传统超大规模云服务商，并验证了基础设施初创公司与领先 AI 实验室之间不断增长的合作伙伴生态系统。 这轮 8.3 亿美元的 A 轮融资由 Leopold Aschenbrenner 创立的专注于 AI 投资的风险投资公司 Situational Awareness 领投，以 75 亿美元估值完成，反映了投资者对 Neocloud 模式的信心。

rss · Techmeme · 7月25日 05:15

**背景**: Neocloud 是一种新型云服务提供商，专门为 AI 工作负载提供 GPU 计算资源，通常比 AWS 或 Azure 等传统超大规模云服务商提供更快的访问速度和更低的成本。Fluidstack 专门建设和运营针对 AI 训练与推理优化的数据中心，与领先的 AI 安全与研究公司 Anthropic 的合作使其成为前沿 AI 开发的关键基础设施供应商。Situational Awareness 是一家总部位于旧金山的投资顾问公司，认为 AI 将是未来十年全球市场回报的主要驱动力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.thundercompute.com/blog/neoclouds-the-new-gpu-clouds-changing-ai-infrastructure">What is a Neocloud ? The Rise of GPU-only... | Thunder Compute</a></li>
<li><a href="https://situationalawarenesslp.com/about">About - Situational Awareness</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#funding`, `#neocloud`, `#Anthropic`, `#data centers`

---

<a id="item-13"></a>
## [Android 可能限制设备端 ADB，引发开发者争议](https://kitsumed.github.io/blog/posts/android-may-soon-restrict-on-device-adb/) ⭐️ 7.0/10

谷歌正考虑对 Android 进行一项更改，限制设备端 Android 调试桥（ADB）功能，只允许通过授权的 USB 或无线连接使用，并可能移除通过回环地址连接到本地 ADB 守护进程的能力。 这一变化可能严重影响依赖设备端 ADB 的开发者及高级用户，他们常使用此类工具（如 Shizuku）进行自动化或无需电脑的调试，同时也引发了对谷歌掌控生态系统的担忧。 拟议的限制针对的是 ADB 守护进程绑定到回环地址（127.0.0.1）的行为，该行为使得设备端 ADB 成为可能；虽然存在 UiAutomation API 等替代方案，但需要无障碍权限和用户同意。

hackernews · shscs911 · 7月25日 06:57 · [社区讨论](https://news.ycombinator.com/item?id=49045159)

**背景**: ADB（Android 调试桥）是一个命令行工具，允许开发者从电脑安装应用、运行 shell 命令并调试 Android 设备。设备端 ADB 是一种技术，让 ADB 客户端直接在手机上运行，通过回环地址连接到本地守护进程，催生了像 Shizuku 这样的应用生态系统，无需 root 即可提供高级权限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://kitsumed.github.io/blog/posts/android-may-soon-restrict-on-device-adb/">Android May Soon Restrict On - Device ADB , Affecting... | Kitsumed Blog</a></li>
<li><a href="https://en.wikipedia.org/wiki/Android_Debug_Bridge">Android Debug Bridge - Wikipedia</a></li>
<li><a href="https://provenbrief.com/story/google-s-plan-to-restrict-on-device-adb-could-kill-shizuku-and-an-entire-ecosyst">Google May Restrict Android ADB , Killing Shizuku Ecosystem</a></li>

</ul>
</details>

**社区讨论**: 社区评论意见不一：部分用户质疑安全收益，指出攻击路径需要开启开发者选项和远程 ADB，影响极小；另一些用户则认为这是谷歌加强控制，未来可能限制开发者自由。

**标签**: `#android`, `#adb`, `#security`, `#developer-tools`

---

<a id="item-14"></a>
## [AI“大力出奇迹”时代还能持续多久？](https://www.huxiu.com/article/4878177.html?f=rss) ⭐️ 7.0/10

这篇来自虎嗅的文章分析了 AI 领域缩放假说的可持续性，质疑“大力出奇迹”的时代是否正接近极限。 随着 GPT-4 等 AI 模型需要巨大的计算资源，AI 进步的未来可能取决于寻找更高效的算法，而不仅仅是扩大模型规模。 文章提到了缩放假说以及 AI 社区近期关于潜在局限性的讨论，包括成本上升和能源消耗问题。

rss · 虎嗅 · 7月25日 18:39

**背景**: AI 中的缩放假说认为，仅仅增加神经网络的规模和训练数据量就能带来可预测的性能提升。这一观点源自大型语言模型中观察到的经验缩放定律。然而，关于收益递减和环境成本的担忧引发了关于这种“大力出奇迹”的方法能持续多久的讨论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gwern.net/scaling-hypothesis">The Scaling Hypothesis · Gwern.net</a></li>
<li><a href="https://en.wikipedia.org/wiki/Neural_scaling_law">Neural scaling law - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2001.08361">[2001.08361] Scaling Laws for Neural Language Models</a></li>

</ul>
</details>

**标签**: `#AI`, `#scaling`, `#deep learning`, `#research`, `#future`

---

<a id="item-15"></a>
## [GitHub Issues 通过缓存和预取实现大幅提速](https://www.infoq.cn/article/yDgq3fh4YxZM93u21Kr5?utm_source=rss&amp;utm_medium=article) ⭐️ 7.0/10

GitHub 重新设计了 Issues 页面，通过缓存和预取技术，使页面加载速度提高了数倍。 这一改进显著缩短了依赖 GitHub Issues 的开发者和项目经理的等待时间，提升了工作效率和用户体验。 此次优化很可能包括客户端缓存常用数据以及预获取相关资源，从而减少了服务器往返和渲染延迟。

rss · InfoQ 中文 · 7月25日 09:00

**背景**: GitHub Issues 是开发者常用的工具，用于在仓库中追踪 bug、功能请求和任务。传统上，加载 Issues 页面涉及多次网络请求和大量数据处理，导致性能较慢。缓存将数据本地存储以便更快访问，而预取则提前加载可能需要的资源。

**标签**: `#GitHub`, `#performance`, `#caching`, `#prefetching`, `#web development`

---