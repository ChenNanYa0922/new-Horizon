---
layout: default
title: "Horizon Summary: 2026-07-21 (ZH)"
date: 2026-07-21
lang: zh
---

> 从 43 条内容中筛选出 12 条重要资讯。

---

1. [黑客清空罗马尼亚土地登记数据库](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 9.0/10
2. [Ben Thompson 提议美国立法将 AI 数据训练视为合理使用](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 9.0/10
3. [Fastjson 1.x 曝无 gadget 高危 RCE 漏洞，无补丁](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10
4. [智谱建成国产芯片 1GW 数据中心](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10
5. [Jane Street 开源增量计算库 Incremental](https://github.com/janestreet/incremental) ⭐️ 8.0/10
6. [中国开放权重 AI 战略正在取得进展](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10
7. [软件中的完美不是过度工程](https://var0.xyz/posts/perfection-is-not-over-engineering.html) ⭐️ 8.0/10
8. [Jellyfin 创始人 Andrew 卸任项目领导职务](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10
9. [SSAO 批评：角落不该那样](https://nothings.org/gamedev/ssao/) ⭐️ 8.0/10
10. [Coincidex：无需重放缓冲区的持续学习框架](https://www.reddit.com/r/MachineLearning/comments/1v1rmbb/exploring_continual_learning_without_replay/) ⭐️ 8.0/10
11. [用类 PyTorch 框架训练通用 LLM Harness](https://www.reddit.com/r/MachineLearning/comments/1v1qbl7/training_a_harness_for_modelagnostic_and/) ⭐️ 8.0/10
12. [Cloudflare 推出集成 Zero Trust 的内部 DNS 服务](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [黑客清空罗马尼亚土地登记数据库](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 9.0/10

一名黑客清空了罗马尼亚整个土地登记数据库，迫使国家地籍与土地登记局\(ANCPI\)从头重建网络，并将应用程序迁移至政府云。 这一事件威胁到数百万罗马尼亚人的土地所有权证明，若无备份可能引发法律和经济混乱。它突显了关键国家基础设施易受网络攻击的脆弱性以及离线备份的重要性。 官员声称拥有离线备份，并正在迁移至政府云，预计 7 月 22 日前完成。黑客被确认为来自阿尔及利亚的 Zakaria Mahdjoub，阿尔及利亚与罗马尼亚有引渡条约。

hackernews · speckx · 7月20日 13:28 · [社区讨论](https://news.ycombinator.com/item?id=48978605)

**背景**: 土地登记数据库是记录财产所有权的关键国家系统，用于法律交易、税收和土地管理。离线备份——与主系统分开存储的副本——对于在灾难性故障或网络攻击后恢复数据至关重要。云迁移是指将应用程序和数据迁移到政府管理的集中式数据中心。

**社区讨论**: 评论指出该机构拥有离线备份，避免了长期混乱。一些罗马尼亚用户将事件归咎于政府 IT 合同中的腐败，而安全公司 KELA 公开了黑客的身份为来自阿尔及利亚的 Zakaria Mahdjoub。

**标签**: `#cybersecurity`, `#critical infrastructure`, `#data breach`, `#Romania`, `#land registry`

---

<a id="item-2"></a>
## [Ben Thompson 提议美国立法将 AI 数据训练视为合理使用](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 9.0/10

知名科技分析师 Ben Thompson 提议美国通过一项法律，明确将 AI 模型训练的数据收集视为合理使用，并禁止服务条款中禁止模型蒸馏的规定。此外，阿里巴巴发布了 Qwen 3.8 Max，一个拥有 2.4 万亿参数、开放权重的模型，推翻了之前不发布上一版本的决定。 该提案针对的是 AI 实验室使用未经许可的数据训练模型却禁止他人蒸馏其模型的不一致行为，并可能帮助美国的开放模型更好地与中国同行竞争。Qwen 3.8 Max 以开放权重形式发布，标志着中国 AI 向更开放的方向转变，可能受到政策方向的影响。 Qwen 3.8 Max 拥有 2.4 万亿参数，几乎与 2.8 万亿参数的 Kimi K3 相当。Ben Thompson 认为，阿里巴巴改弦更张、以开放权重发布该模型，可能受到习近平最近鼓励开源与合作的讲话影响。

rss · Simon Willison · 7月20日 17:09

**背景**: 模型蒸馏是一种通过查询较大‘教师’模型 API、让较小‘学生’模型学习并有效转移知识的技术。许多 AI 公司在服务条款中禁止蒸馏，但自身却使用从网络抓取的未经明确许可的数据进行训练，这种做法在当前版权法下可能不明确合法。合理使用是一种法律原则，允许在无需许可的情况下有限使用受版权保护的材料；明确将训练数据收集视为合理使用将保护 AI 公司免受诉讼。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://www.datacamp.com/blog/distillation-llm">LLM Distillation Explained: Applications, Implementation &amp; More</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#distillation`, `#fair use`, `#Chinese AI`, `#open models`

---

<a id="item-3"></a>
## [Fastjson 1.x 曝无 gadget 高危 RCE 漏洞，无补丁](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10

一个影响 Fastjson 1.2.68 至 1.2.83 版本的远程代码执行漏洞被披露，该漏洞无需 gadget 或 autoType 支持即可利用。由于该库已于 2024 年 10 月停止维护，官方将不会发布安全补丁。 该漏洞非常关键，因为 Fastjson 在 Java 应用中广泛用于 JSON 解析，且漏洞能在 JDK 8、17、21 上无需特殊条件即可利用。受影响用户必须紧急迁移到 Fastjson2 或启用 SafeMode，以防潜在的远程代码执行攻击。 该漏洞不需要 autoType 支持或 classpath gadgets，因此比以往的 Fastjson 漏洞更危险。唯一的缓解措施是升级到 Fastjson2 或启用 SafeMode，SafeMode 自 1.2.68 版本起可用，它会完全禁用 autoType。

telegram · zaihuapd · 7月20日 14:32

**背景**: Fastjson 是阿里巴巴开发的 Java 流行 JSON 解析库，以高性能著称，但也历史上容易出现反序列化漏洞。AutoType 支持启用后允许在反序列化时恢复类型信息，若未严格限制则可能被利用。SafeMode 是 1.2.68 版本引入的安全功能，可完全禁用 AutoType，但需要用户手动启用。此次披露的漏洞绕过了以往的限制，甚至无需 AutoType 即可利用，因此尤为严重。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nsfocusglobal.com/fastjson-1-2-62-and-earlier-remote-code-execution-vulnerability-threat-alert/">Fastjson 1.2.62 and Earlier Remote Code Execution Vulnerability ...</a></li>
<li><a href="https://github.com/alibaba/fastjson/wiki/fastjson_safemode_en">fastjson _ safemode _en · alibaba/ fastjson Wiki · GitHub</a></li>

</ul>
</details>

**标签**: `#security`, `#vulnerability`, `#Fastjson`, `#RCE`, `#Java`

---

<a id="item-4"></a>
## [智谱建成国产芯片 1GW 数据中心](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10

智谱（原名智谱 AI）已完成一座全部采用国产 AI 芯片的 1 吉瓦数据中心建设，并已开始部分运营。该设施将用于训练其 GLM 大语言模型。 这标志着中国 AI 基础设施自主化的重要里程碑，展示了在不依赖受限的英伟达芯片的情况下建设大规模 AI 训练设施的能力。这减少了对国外技术的依赖，推动了中国的技术自主目标。 该数据中心功率为 1 吉瓦，相当于同时为约 75 万户家庭供电。智谱运营着多个各拥有超万枚芯片的计算集群，该设施是中国 AI 实验室建造的最大规模设施之一。

telegram · zaihuapd · 7月20日 15:43

**背景**: 由于美国出口限制，中国 AI 实验室在获取英伟达 H100 等高端 GPU 方面面临困难。智谱（原名智谱 AI）是中国领先的 AI 公司，以其开源 GLM 模型系列著称，该系列于 2025 年 7 月以 MIT 许可证发布。这座完全采用国产芯片的数据中心是北京推动芯片自主的关键一步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai">Z. AI Completes Giant Data Center With Chinese Chips to... - Bloomberg</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z. ai - Wikipedia</a></li>
<li><a href="https://news.aibase.com/news/29736">Zhipu AI Launches 1GW Domestic AI Computing Center and...</a></li>

</ul>
</details>

**标签**: `#AI`, `#data center`, `#domestic chips`, `#self-sufficiency`, `#infrastructure`

---

<a id="item-5"></a>
## [Jane Street 开源增量计算库 Incremental](https://github.com/janestreet/incremental) ⭐️ 8.0/10

Jane Street 开源了 Incremental 库，该库实现了增量计算，只重新计算依赖已变更数据的输出，从而提高效率。 该库将高性能增量计算带给更广泛的用户，可用于响应式 UI、构建系统和数据处理管道。 Incremental 使用 OCaml 编写，汲取了数十年的函数式编程研究成果；其概念类似于 Vue 和 SolidJS 等 JavaScript 框架中的响应式信号。

hackernews · handfuloflight · 7月21日 03:50 · [社区讨论](https://news.ycombinator.com/item?id=48987822)

**背景**: 增量计算是一种技术，当输入只有小部分变化时，仅更新相关的输出，避免完全重新计算。这种方法用于构建系统（如 Make）和电子表格重新计算。Jane Street 的 Incremental 库为 OCaml 提供了通用的增量计算机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Incremental_computation">Incremental computation</a></li>
<li><a href="https://angular.dev/essentials/signals">Reactivity with signals • Angular</a></li>

</ul>
</details>

**社区讨论**: 评论者指出了该库与现代 JS 框架中响应式信号的相似性，并讨论了 Differential Dataflow 和 DBSP 等相关系统。有人回忆了金融领域的历史应用，如高盛在金融工具定价中的做法。

**标签**: `#incremental-computation`, `#functional-programming`, `#reactive-programming`, `#jane-street`

---

<a id="item-6"></a>
## [中国开放权重 AI 战略正在取得进展](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10

一篇备受讨论的文章指出，中国的开放权重 AI 模型正在超越美国的专有模型，并声称大多数初创公司都在采用中国模型。 这种转变可能重塑全球 AI 格局，使开放生态系统优于封闭的专有系统，并可能加速中国的创新。 文章引用了 80%的初创公司使用中国模型的说法，但一些评论者质疑这一统计数据，指出他们自己使用的是美国模型。

hackernews · benwerd · 7月20日 14:21 · [社区讨论](https://news.ycombinator.com/item?id=48979269)

**背景**: 开放权重 AI 模型将其训练参数公开，任何人都可以下载并运行。这与 OpenAI 的 GPT-4 等专有模型形成对比，后者只能通过 API 访问。关于开放与封闭 AI 生态系统的争论涉及透明度、创新速度和可控性之间的权衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://center-forward.org/basic/emerging-ai-open-vs-closed-source/">Emerging AI: Open vs Closed Source - Center Forward</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不同的看法：一些人同意开放模型在历史上胜出的观点，举了 Linux 等例子；其他人则对文章的说法持怀疑态度，指出企业更看重数据留存和现有供应商关系。一位评论者指出文章与 Palantir CEO 的言论相似，质疑其客观性。

**标签**: `#AI`, `#open-source`, `#China`, `#LLMs`, `#technology strategy`

---

<a id="item-7"></a>
## [软件中的完美不是过度工程](https://var0.xyz/posts/perfection-is-not-over-engineering.html) ⭐️ 8.0/10

var0.xyz 的一篇文章论证，软件工程中的完美主义不应与过度工程混为一谈，强调解决正确问题并抵制有害的产品思维的重要性。 这挑战了软件开发中常见的反完美主义论调，鼓励工程师在不担心被贴上过度工程标签的情况下为自己的工作感到自豪；该文章引发了广泛的社区讨论。 文章强调，真正的过度工程是解决错误的问题，而不是追求完美，并警告说，当产品思维忽视质量和用户需求时，它可能变得有害。

hackernews · var0xyz · 7月20日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48979120)

**背景**: 在软件开发中，过度工程经常受到批评，YAGNI（“你不需要它”）等原则鼓励避免不必要的复杂性。然而，文章区分了过度工程和仔细、深思熟虑的设计，后者考虑了所有约束条件，并认为当完美主义专注于正确的问题时，它并不是过度工程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Overengineering">Overengineering - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Technical_debt">Technical debt</a></li>
<li><a href="https://medium.com/agileinsider/what-is-the-product-mindset-af06e01adf70">What is the Product Mindset?. Learning to navigate an uncertain world | by Chris Butler | Agile Insider | Medium</a></li>

</ul>
</details>

**社区讨论**: 评论者大多同意文章的观点，有些人指出需求往往是隐性的，并且过度工程可能源于针对不存在的约束进行优化。还讨论了产品思维的有害性以及工程师理解用户需求的重要性。

**标签**: `#software engineering`, `#technical debt`, `#product mindset`, `#code quality`, `#engineering culture`

---

<a id="item-8"></a>
## [Jellyfin 创始人 Andrew 卸任项目领导职务](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10

Jellyfin 创始人 Andrew（cube00）宣布退出该项目，理由是无法继续承受角色要求，面临严重倦怠和健康风险。 Andrew 的离职凸显了开源项目的可持续性挑战以及维护者倦怠这一普遍问题，尤其是在 Plex 涨价促使更多用户转向 Jellyfin 等免费替代品的背景下。此事引发了对项目治理和未来发展的质疑。 Plex 最近将终身 Plex Pass 价格提高至 750 美元，促使用户寻求自托管替代方案。Andrew 在离职声明中强调 FLOSS 确实可行且有需求，但也承认维护者面临严重倦怠。

hackernews · swat535 · 7月20日 23:15 · [社区讨论](https://news.ycombinator.com/item?id=48986091)

**背景**: Jellyfin 是一款自由开源媒体服务器软件，2018 年从 Emby 分叉而来，作为 Plex 等专有解决方案的替代品。它允许用户自行托管媒体库，无需订阅费即可在多种设备上串流。该项目由志愿者维护，领导层变动可能影响其稳定性和未来方向。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://github.com/jellyfin/jellyfin">GitHub - jellyfin/jellyfin: The Free Software Media System - Server Backend &amp; API · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍积极，许多用户感谢 Andrew 和贡献者的工作，并称赞 Jellyfin 是 Plex 的出色替代方案。一些用户提到 Plex 涨价促使他们探索开源选项。多条评论还指出了开源生态系统中维护者倦怠这一普遍问题。

**标签**: `#jellyfin`, `#plex`, `#open-source`, `#media-server`, `#leadership`

---

<a id="item-9"></a>
## [SSAO 批评：角落不该那样](https://nothings.org/gamedev/ssao/) ⭐️ 8.0/10

2012 年文章《角不该那样》的作者指出，屏幕空间环境光遮蔽（SSAO）会在角落产生不真实的变暗效果，这与真实世界中的环境光遮蔽现象不符。 该批评在游戏开发领域引发了长期讨论：在使用 SSAO 等实时渲染技术时，究竟应优先追求完美真实感还是视觉吸引力，这影响了开发者如何权衡性能与视觉质量。 SSAO 由 Crytek 于 2007 年在《孤岛危机》中引入，因其低成本而广泛使用，但文章指出其均匀环境光照的假设会导致角落阴影错误，尤其在具有强方向光的场景中。

hackernews · firephox · 7月20日 15:07 · [社区讨论](https://news.ycombinator.com/item?id=48979931)

**背景**: 环境光遮蔽（AO）是一种着色技术，用于近似计算环境光到达某点的程度，使角落和缝隙等区域变暗。屏幕空间环境光遮蔽（SSAO）是一种实时近似方法，利用深度缓冲区计算遮蔽，以精度换取性能。自 2000 年代末以来，SSAO 一直是游戏中的常用技术，但其局限性催生了 HBAO 和 FidelityFX CACAO 等新方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Screen_space_ambient_occlusion">Screen space ambient occlusion - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ambient_occlusion">Ambient occlusion - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论中观点不一：有人同意真实感并非总是目标，适量使用 SSAO 仍能获得不错效果；也有人批评其不真实的外观，并提到 CACAO 等改进方法。共识是 SSAO 在当时是一种实用的折中方案，但现代解决方案更优。

**标签**: `#game development`, `#rendering`, `#ambient occlusion`, `#SSAO`, `#computer graphics`

---

<a id="item-10"></a>
## [Coincidex：无需重放缓冲区的持续学习框架](https://www.reddit.com/r/MachineLearning/comments/1v1rmbb/exploring_continual_learning_without_replay/) ⭐️ 8.0/10

作者推出了 Coincidex，一个开源框架，通过动态任务相似性路由实现持续学习，无需依赖重放缓冲区或手动调整的任务掩码。 该方法解决了重放缓冲区的内存和隐私关键限制，为资源受限或隐私敏感环境中的序列任务学习提供了轻量级替代方案。 Coincidex 作为一个单层替换，在线计算任务相似性矩阵以路由数据；它在干净的任务边界上表现良好，但在高度混乱、长尾且分布偏移大的任务序列中则难以维持稳定性。

reddit · r/MachineLearning · /u/theawkwardbong · 7月20日 17:13

**背景**: 持续学习的目标是从连续的任务流中学习而不遗忘先前知识，这一挑战称为灾难性遗忘。传统的解决方案如重放缓冲区存储过去的数据以强化学习，但这会带来内存开销和隐私问题。任务相似性路由是一种根据学习到的相似性度量动态将输入引导至合适模型组件的技术，可能绕过存储样本的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@dhruvansh26/early-results-for-task-based-model-routing-using-sae-features-b3a839285bde">Early Results for Task -Based Model Routing using SAE... | Medium</a></li>

</ul>
</details>

**标签**: `#continual learning`, `#catastrophic forgetting`, `#task-similarity routing`, `#replay buffer`, `#open-source`

---

<a id="item-11"></a>
## [用类 PyTorch 框架训练通用 LLM Harness](https://www.reddit.com/r/MachineLearning/comments/1v1qbl7/training_a_harness_for_modelagnostic_and/) ⭐️ 8.0/10

该项目提出一个类 PyTorch 的训练框架，用于训练一个通用‘Harness’（工具层），该 Harness 一旦训练完成，可以在不修改 LLM 本身的情况下，提升任何大型语言模型在不同任务环境中的能力。作者在 Terminal-Bench 2.0 和 SWE-Bench 任务上展示了结果，表明训练后的 Harness 能够迁移到未见过的任务环境中。 这种方法可以显著降低将 LLM 适配到新任务和环境的成本和精力，因为一个训练好的 Harness 可以跨多个模型和任务工作。这与从以模型为中心的再训练转向可重用基础设施的趋势一致。 该框架使用‘StrictPareto\(\)’准则和‘GreedyMonotonic\(\)’优化器，通过智能体驱动的自我改进循环来评估和改善 Harness 的行为。Harness 使用冻结的任务 LLM 进行训练，然后可以通过兼容 OpenAI 的 API 替换为任何其他 LLM。

reddit · r/MachineLearning · /u/Megadragon9 · 7月20日 16:26

**背景**: 智能体 Harness 是位于 LLM 及其环境之间的软件层，用于管理工具调用、记忆和规划，而无需修改模型权重。传统方法需要为每个新任务微调 LLM，既昂贵又不可移植。该项目转而训练 Harness 本身使其成为模型和任务无关的，借鉴了强化学习和 Pareto 优化的思想。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/workofart/harness-training">GitHub - workofart/harness-training: Train a harness to improve its...</a></li>
<li><a href="https://parallel.ai/articles/what-is-an-agent-harness">What is an agent harness in the context of large-language models? | Parallel Web Systems | Infrastructure for intelligence on the web</a></li>

</ul>
</details>

**标签**: `#LLM`, `#training framework`, `#model-agnostic`, `#harness training`, `#PyTorch`

---

<a id="item-12"></a>
## [Cloudflare 推出集成 Zero Trust 的内部 DNS 服务](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10

Cloudflare 宣布其内部 DNS 服务全面上线，该服务为企业私有网络提供权威和递归 DNS 解析，并与公共 DNS 和 Zero Trust 策略统一在单一全球网络上。 这通过消除独立公共和私有 DNS 系统之间的数据漂移简化了分割 DNS 管理，并将 Zero Trust 安全策略扩展到 DNS 解析层，从而有利于企业网络安全和运营。 现有 Cloudflare Gateway 客户无需额外付费即可启用该服务。该服务支持通过 API、Terraform 和 Cloudflare WAN 进行配置，并允许管理员设置解析器策略，以确定不同用户和设备可以访问哪些内部 DNS 视图。

telegram · zaihuapd · 7月21日 03:49

**背景**: 传统的分割 DNS 根据请求源地址提供不同的 DNS 响应，通常需要单独的服务器或复杂配置。Cloudflare 的内部 DNS 将其与 Zero Trust 网络访问和安全 Web 网关产品集成到单一平台中，从而降低运营开销并缩小安全缺口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Split-horizon_DNS">Split-horizon DNS</a></li>

</ul>
</details>

**标签**: `#Cloudflare`, `#DNS`, `#Zero Trust`, `#Enterprise Networking`, `#Network Security`

---