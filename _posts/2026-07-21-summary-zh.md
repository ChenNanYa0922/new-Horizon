---
layout: default
title: "Horizon Summary: 2026-07-21 (ZH)"
date: 2026-07-21
lang: zh
---

> 从 44 条内容中筛选出 14 条重要资讯。

---

1. [AI 在寻找反例上超越人类数学家](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 9.0/10
2. [Fastjson 1.x 曝无 gadget 高危 RCE 漏洞](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10
3. [智谱建成 1 吉瓦全国产芯片数据中心](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10
4. [Qwen-Image-3.0：高细节、长上下文图像生成](https://qwen.ai/blog?id=qwen-image-3.0) ⭐️ 8.0/10
5. [Jane Street 发布增量计算库 Incremental](https://github.com/janestreet/incremental) ⭐️ 8.0/10
6. [代理集群以每秒 1000 次提交构建 SQLite](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10
7. [中国开放权重 AI 策略正在获胜](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10
8. [Jellyfin 创始人 Andrew 因倦怠离职](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10
9. [黑客清除罗马尼亚土地登记数据库](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 8.0/10
10. [AI 编码代理使逆向工程变得廉价](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10
11. [Ben Thompson 提议美国 AI 训练数据合理使用法案](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10
12. [欧盟或为免签向美交出生物识别数据](https://edri.org/our-work/the-eu-is-about-to-sell-our-most-sensitive-data-to-the-us-for-visa-free-travel/) ⭐️ 8.0/10
13. [欧盟对阿里 Express 罚款 5.5 亿欧元因假冒商品](https://thebalkanchronicle.com/en/business/eu-fines-aliexpress-550-million-counterfeit-goods-2026/) ⭐️ 8.0/10
14. [台积电 2027 年起芯片涨价 5%至 10%](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [AI 在寻找反例上超越人类数学家](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 9.0/10

AI 系统已开始比人类数学家更快地发现数学猜想的反例，这标志着 AI 辅助数学的一个里程碑。 这一转变可能节省研究人员在错误猜想上浪费数年的精力，并改变数学实践，使 AI 成为发现中的创造性伙伴。 该 AI 使用自动定理证明和机器学习来探索巨大的解空间，但尚未能完全取代人类的直觉和创造性推理。

hackernews · artninja1988 · 7月20日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=48983382)

**背景**: 自动定理证明（ATP）是计算机科学的一个子领域，使用程序自动证明数学定理。反例在数学中至关重要，因为它们可以反驳猜想并帮助完善定义，正如 Imre Lakatos 的名著《证明与反驳》中所讨论的。AI 的最新进展使得系统能够主动生成反例，从而增强人类研究。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving</a></li>
<li><a href="https://www.linkedin.com/pulse/ai-challenges-foundational-conjecture-pure-mathematics-odwec">AI Challenges a Foundational Conjecture in Pure Mathematics ...</a></li>
<li><a href="https://haltmal.com/ai-literacy-responsible-use/human-mathematicians-are-being-outcounterexampled/">Human Mathematicians Are Being Outcounterexampled - Halt Mal</a></li>

</ul>
</details>

**社区讨论**: 社区普遍认为这是一项积极发展，指出它防止了精力浪费，并突出了反例的重要性。一些评论者分享了轶事，如张益唐因一个错误推论而职业生涯受阻，这凸显了 AI 早期发现错误的价值。

**标签**: `#AI`, `#mathematics`, `#automated theorem proving`, `#counterexamples`, `#machine learning`

---

<a id="item-2"></a>
## [Fastjson 1.x 曝无 gadget 高危 RCE 漏洞](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10

安全研究员 Kirill Firsov 披露了 Fastjson 1.x 版本 1.2.68 至 1.2.83 存在高危远程代码执行漏洞，该漏洞无需开启 autoType 也无需依赖任何 classpath gadget，且可在 JDK 8、17、21 上利用。 此漏洞极为严重，因为 Fastjson 1.x 在 Java 应用中广泛使用（尤其在中国），且由于该项目已于 2024 年 10 月停止维护，官方不会发布安全补丁。用户必须升级到 Fastjson2 或启用 SafeMode 来降低风险。 该漏洞影响 Fastjson 1.2.68 至 1.2.83 版本，且不依赖任何已知的 gadget 链，因此能绕过常规防御，更加危险。研究员提出的唯一官方缓解措施是迁移到 Fastjson2 或启用 SafeMode（完全禁用 autoType）。

telegram · zaihuapd · 7月20日 14:32

**背景**: Fastjson 是阿里巴巴开发的 Java 常用 JSON 库。在 Java 反序列化中，&\#x27;gadget 链&\#x27; 是一系列类，反序列化时可执行任意代码。之前的 Fastjson 漏洞通常需要 classpath 中存在特定 gadget。SafeMode 自 Fastjson 1.2.68 引入，完全禁用 autoType 以防止反序列化攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://unicorn-dev.medium.com/gadget-chains-in-java-how-unsafe-deserialization-leads-to-rce-88b17409c7aa">Gadget chains in Java : how unsafe deserialization leads to... | Medium</a></li>
<li><a href="https://github.com/alibaba/fastjson/wiki/fastjson_safemode">fastjson_safemode · alibaba/fastjson Wiki</a></li>

</ul>
</details>

**标签**: `#fastjson`, `#rce`, `#vulnerability`, `#security`, `#java`

---

<a id="item-3"></a>
## [智谱建成 1 吉瓦全国产芯片数据中心](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10

智谱 AI 已完成一座功率达 1 吉瓦的全国产芯片数据中心建设，并已部分投入运营，用于训练其 GLM 大语言模型。 这标志着中国在半导体自给自足方面取得重大里程碑，证明国产芯片能够支撑大规模 AI 训练基础设施。 该数据中心功率达 1 吉瓦，足以同时为约 75 万户家庭供电。智谱已建成或运营多个各拥有超万枚芯片的计算集群。

telegram · zaihuapd · 7月20日 15:43

**背景**: 智谱 AI 是一家总部位于北京的公司，开发了 GLM 系列开源大语言模型。由于出口限制，中国 AI 公司无法购买英伟达最新 GPU，正加速采用国产替代芯片。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z. ai - Wikipedia</a></li>
<li><a href="https://pandaily.com/china-domestic-ai-compute-revolution-tipping-point-jul2026">China &#x27;s Domestic AI Compute Revolution Reaches... - Pandaily</a></li>
<li><a href="https://wccftech.com/chinas-domestic-chip-shipments-to-surge-to-5-million-unites-this-year-says-report/">China &#x27;s Domestic Chip Shipments To Surge To 5 Million Unites This...</a></li>

</ul>
</details>

**标签**: `#AI`, `#data center`, `#domestic chips`, `#Zhipu`, `#infrastructure`

---

<a id="item-4"></a>
## [Qwen-Image-3.0：高细节、长上下文图像生成](https://qwen.ai/blog?id=qwen-image-3.0) ⭐️ 8.0/10

Qwen-Image-3.0 是一款新的图像生成模型，支持最长 4.5k token 输入，可生成九宫格信息图、报纸和多层界面等高密度内容。它在小字（10 px）、公式和微观纹理等细节精度上有所提升，并支持 12 种语言和 100 多种艺术风格。 此次发布将图像生成从纯美学转向实用，使其在创建教育材料、UI 原型和多语言内容等实际任务中更有用。它解决了以往模型在处理长而复杂的提示和细节方面的关键限制。 该模型单次可生成高达 4.5k token 的内容，包括多面板布局和文本密集的设计。它还支持联网生成，基于真实世界信息生成更真实的图像。

hackernews · ilreb · 7月21日 08:44 · [社区讨论](https://news.ycombinator.com/item?id=48989701)

**背景**: Qwen 是阿里云开发的大型语言和多模态模型系列。以往的图像生成模型在处理长文本段落和跨多张图像的一致性方面常常存在困难。Qwen-Image-3.0 在这些模型基础上增强了细节处理和上下文能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>
<li><a href="https://qwen.ai/">Qwen Studio</a></li>
<li><a href="https://huggingface.co/Qwen">Qwen (Qwen)</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：有些人对将此类模型用于在线购物或房地产表示怀疑，指出 AI 倾向于美化产品。还有人指出了技术问题，如主图中的阿拉伯文字错误以及移动端 UI 显示 bug。此外，meta 关键词中包含大量 NSFW 参考，引起了关注。

**标签**: `#AI`, `#image generation`, `#Qwen`, `#multimodal`, `#Qwen-Image`

---

<a id="item-5"></a>
## [Jane Street 发布增量计算库 Incremental](https://github.com/janestreet/incremental) ⭐️ 8.0/10

Jane Street 开源了增量计算库 Incremental，它能在输入变化时仅重新计算计算图中受影响的部分。 增量计算是响应式系统中高效更新的基础技术，而像 Incremental 这样的库可以提升从 UI 框架到金融模型等应用的性能。 该库使用 OCaml 编写，实现了基于有向无环图（DAG）的增量计算模型。它自动追踪依赖关系，仅更新必要的计算，类似于 JavaScript UI 框架中的信号和 Differential Dataflow 等系统。

hackernews · handfuloflight · 7月21日 03:50 · [社区讨论](https://news.ycombinator.com/item?id=48987822)

**背景**: 增量计算是一种避免完全重新计算的技术，只更新受变更影响的输出，常用于电子表格和构建系统。Jane Street 是一家量化交易公司，是 OCaml 的主要用户，他们构建了许多内部库并偶尔开源。Incremental 库为响应式程序中的状态更新提供了一种规范的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Incremental_computation">Incremental computation</a></li>
<li><a href="https://github.com/TimelyDataflow/differential-dataflow">GitHub - TimelyDataflow/differential-dataflow: An implementation of differential dataflow using timely dataflow on Rust. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区讨论将该库与 JavaScript 信号（Vue、SolidJS）、构建系统和 Differential Dataflow 进行了比较。评论者注意到该库与 Clojure 中的 Javelin 等早期系统的相似性，并提到在高盛的历史实现。总体情绪积极，用户赞赏其设计良好的实现方式。

**标签**: `#incremental computation`, `#reactive programming`, `#Jane Street`, `#libraries`, `#dataflow`

---

<a id="item-6"></a>
## [代理集群以每秒 1000 次提交构建 SQLite](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10

Cursor 展示了一个 AI 代理集群使用自建的版本控制系统，仅凭 SQLite 的文档从头用 Rust 构建了它，峰值达到了每秒 1000 次提交。 这项实验推动了自主 AI 编程的边界，表明大规模代理协调可以应对复杂工程任务，但也引发疑问：成功源自模型记忆还是真正的推理。 自定义版本控制系统从头构建以处理高达每秒 1000 次提交的高吞吐量，同时作为协调层，使冲突可见，从而实现更复杂的代理协调机制。

hackernews · jlaneve · 7月20日 18:06 · [社区讨论](https://news.ycombinator.com/item?id=48982535)

**背景**: 大语言模型（如 GPT-4）可以记忆训练数据或对新颖问题进行推理。代理集群涉及多个由 LLM 驱动的代理协作完成一项任务，这带来了协调和版本控制的挑战。版本控制系统跟踪变更并支持协作，但传统的 VCS（如 Git）并非为代理集群的高提交速率而设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cursor.com/blog/agent-swarm-model-economics">Agent swarms and the new model economics · Cursor</a></li>
<li><a href="https://techxplore.com/news/2025-11-ai-brain-reveals-memory.html">Mapping AI&#x27;s brain reveals memory and reasoning are not located in the same place</a></li>
<li><a href="https://medium.com/@sahysahy/how-i-built-version-control-for-ai-agents-1f6b69abc860">How I Built Version-Control For AI Agents | by Shay Livni | Medium</a></li>

</ul>
</details>

**社区讨论**: 评论者对代理集群的未来潜力表示兴奋，但也提出了关键疑虑：SQLite 源代码可能出现在训练数据中，Rust 重写版（Turso 的）也可能被记忆，因此怀疑集群是否展示了真正的新颖推理而非记忆。

**标签**: `#agent swarms`, `#AI coding`, `#LLM capabilities`, `#software engineering`, `#version control`

---

<a id="item-7"></a>
## [中国开放权重 AI 策略正在获胜](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10

一篇文章认为，中国的开放权重 AI 模型（如 Qwen 和 DeepSeek）正在超越美国的专有模型，并引用了 80%的创业公司使用中国模型的数据，以及历史上开放或低端解决方案击败专有方案的先例。 这挑战了美国在 AI 领域的主导地位，并表明开放策略可能比专有策略更有效，可能重塑全球 AI 格局并影响国家 AI 战略。 文章将当前情况与过去的科技市场转变（如个人电脑 vs. 大型机、Linux vs. UNIX）进行类比，并指出开放权重模型允许定制但并非完全开源。社区评论对 80%创业公司的数据表示怀疑，并质疑类似 Llama 的开放权重模型对 Meta 的成功程度。

hackernews · benwerd · 7月20日 14:21 · [社区讨论](https://news.ycombinator.com/item?id=48979269)

**背景**: 开放权重 AI 模型公开其训练好的参数，使用户能够微调和部署，但训练代码和数据可能不完全开放。这与完全开源模型（提供代码和数据的完整访问权）以及专有模型（不开放）形成对比。主要的开放权重模型包括 Llama、Qwen 和 DeepSeek。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@aruna.kolluru/exploring-the-world-of-open-source-and-open-weights-ai-aa09707b69fc">Exploring the World of Open Source and Open Weights AI | Medium</a></li>
<li><a href="https://llm-stats.com/">AI Leaderboard 2026: Compare &amp; Rank 300+ Top AI Models by...</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：一些人同意一旦硬件成本下降，开放权重将获胜；而另一些人则对 80%创业公司的说法表示怀疑，并认为企业更看重数据隐私而非开放性。还有人对 Llama 的成功是否直接惠及 Meta 表示怀疑，并担心文章可能反映了 Palantir CEO 的偏见观点。

**标签**: `#AI`, `#open-source`, `#China`, `#geopolitics`, `#large language models`

---

<a id="item-8"></a>
## [Jellyfin 创始人 Andrew 因倦怠离职](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10

开源媒体服务器 Jellyfin 的创始人 Andrew 因严重倦怠宣布退出项目领导层，强调了可持续的 FLOSS 维护需求。 此事凸显了开源社区中持续存在的倦怠问题，维护者常常承担繁重无薪工作。它强调了可持续实践和社区支持对项目长期健康的重要性。 Andrew 将心理健康风险和无法履行职责作为原因，但表示项目将在新领导下继续推进。过渡看起来和平，没有分叉或冲突的报告。

hackernews · swat535 · 7月20日 23:15 · [社区讨论](https://news.ycombinator.com/item?id=48986091)

**背景**: Jellyfin 是一款免费开源媒体服务器，允许用户管理和流式传输个人媒体收藏，是 Plex、Emby 等专有解决方案的替代品。FLOSS 指自由/开源软件，这种模式依赖志愿贡献，但常面临可持续性挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://en.wikipedia.org/wiki/Free_and_open-source_software">Free and open-source software - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 Andrew 的贡献表示感谢，并对他的倦怠表示同情。用户分享了使用 Jellyfin 的积极体验，一些人强调了 FLOSS 维护者倦怠的普遍问题，并列举了其他项目中的类似离职情况。

**标签**: `#open-source`, `#Jellyfin`, `#burnout`, `#FLOSS`, `#community`

---

<a id="item-9"></a>
## [黑客清除罗马尼亚土地登记数据库](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 8.0/10

一名黑客成功清除了罗马尼亚整个土地登记数据库，导致全国房地产交易瘫痪、产权登记暂停。官方目前正在从离线备份中恢复数据，并将系统迁移至政府云。 此次针对关键国家基础设施的攻击威胁到产权和房地产市场，可能造成长期社会混乱。这凸显了政府系统面对勒索软件的脆弱性，以及离线备份和安全云迁移的重要性。 被识别为阿尔及利亚人 Zakaria Mahdjoub 的黑客据称在勒索失败后删除了数据库。罗马尼亚特别电信服务局（STS）正协调将系统迁移至政府云，预计 7 月 22 日完成。

hackernews · speckx · 7月20日 13:28 · [社区讨论](https://news.ycombinator.com/item?id=48978605)

**背景**: 罗马尼亚土地登记局（ANCPI）维护着官方产权、边界和负担记录，对法律交易和抵押登记至关重要。数据库被清除可能引发所有权证明的混乱，但离线备份似乎得以保存。该事件与之前韩国政府数据中心火灾导致 900TB 数据无外部备份而被毁的情况类似。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybernews.com/security/hacker-deletes-romanian-land-registry-database/">Hacker deletes country’s entire land registry database ... | Cybernews</a></li>
<li><a href="https://romanianlawoffice.com/land-registry-romania.htm">Romanian Land Registry , Land Book in Romania , Register Title in...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，离线备份的存在可能避免了重大社会危机，但有人将此次入侵归因于政府在 IT 合同中的腐败。黑客的身份被曝光以及罗马尼亚与阿尔及利亚之间存在引渡条约也引发了讨论，引发了关于可能追诉的疑问。

**标签**: `#cybersecurity`, `#critical infrastructure`, `#data breach`, `#hacking`, `#Romania`

---

<a id="item-10"></a>
## [AI 编码代理使逆向工程变得廉价](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10

编码代理大幅降低了逆向工程和自动化家用设备的成本与精力，为爱好者和开发者降低了入门门槛。 这一转变改变了逆向工程的投入产出比计算，使小型项目变得可行，并减轻了未来可能维护的心理负担。 关键变化在于，即使逆向工程得到的 API 失效，使用代理重写代码的低成本也使得从头开始变得可以接受。

rss · Simon Willison · 7月20日 19:24

**背景**: 编码代理是基于 AI 的编程辅助工具，通常通过自然语言描述生成脚本。逆向工程家用设备通常涉及截获和解码通信协议以编程控制它们，以往这既耗时又脆弱。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/components-of-a-coding-agent">Components of A Coding Agent - by Sebastian Raschka, PhD</a></li>
<li><a href="https://packages.ecosyste.ms/registries/npmjs.org/packages/agents-reverse-engineer">agents - reverse - engineer | npmjs.org | Ecosyste.ms: Packages</a></li>

</ul>
</details>

**标签**: `#reverse-engineering`, `#AI agents`, `#home automation`, `#software economics`

---

<a id="item-11"></a>
## [Ben Thompson 提议美国 AI 训练数据合理使用法案](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10

Ben Thompson 提议美国立法，明确训练数据为合理使用并禁止禁止蒸馏的条款，以帮助美国开源模型与中国模型竞争。此外，阿里巴巴开源了 2.4T 参数的 Qwen 3.8 Max 模型。 这一提议直接针对实验室一面禁止蒸馏、一面使用未授权数据训练的矛盾，可能为美国开源模型创造公平竞争环境。同时，中国开源 Qwen 3.8 Max 表明政策向开源协作转变。 该法案至少适用于美国公司，并使禁止蒸馏的条款无法执行。蒸馏在技术上难以阻止。Qwen 3.8 Max 拥有 2.4 万亿参数，接近 Kimi K3 的 2.8T。习近平近期讲话鼓励开源与共享。

rss · Simon Willison · 7月20日 17:09

**背景**: 合理使用是一种法律原则，允许未经许可有限使用受版权保护的材料；其在 AI 训练数据上的应用目前在法庭上存在争议。模型蒸馏是一种技术，让小模型从大模型的输出中学习。开放权重模型发布训练后的参数，但不提供完整的训练代码或数据，限制了透明度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@creed_1732/5-powerful-ways-ai-model-distillation-is-revolutionizing-affordable-machine-learning-and-why-its-c239cc039b63">5 Powerful Ways AI Model Distillation Is Revolutionizing... | Medium</a></li>
<li><a href="https://www.jdsupra.com/legalnews/the-art-and-legality-of-imitation-4462776/">The Art (and Legality) of Imitation: Navigating the Murky Waters of Fair ...</a></li>
<li><a href="https://www.linkedin.com/pulse/frontier-ai-models-closed-vs-open-weight-source-varadaraj-pandurangan-yrdue">Frontier AI Models: Closed vs Open Weight vs Open Source</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#distillation`, `#open source`, `#copyright`, `#fair use`

---

<a id="item-12"></a>
## [欧盟或为免签向美交出生物识别数据](https://edri.org/our-work/the-eu-is-about-to-sell-our-most-sensitive-data-to-the-us-for-visa-free-travel/) ⭐️ 8.0/10

欧盟委员会正与特朗普政府谈判一项“增强边境安全伙伴关系”（EBSP）框架协议，允许美国访问欧盟生物识别数据库，以换取维持欧盟公民的免签待遇。泄露的草案显示，欧盟几乎全盘接受了美方对敏感个人数据的无限制访问要求。 该协议可能为大规模监控和隐私侵犯树立危险先例，因为生物识别数据极其敏感且不可替换。若获批准，将影响数亿欧盟公民，并削弱欧洲的数据保护标准。 EBSP 框架涉及自动交换旅客个人数据用于筛查和身份验证，包括生物特征和基于政治观点的“风险指标”。EDRi 警告称，该安排可能导致数据被系统性传输至美国，从而威胁言论自由和人权。

telegram · zaihuapd · 7月20日 15:08

**背景**: “增强边境安全伙伴关系”（EBSP）是欧盟与美国拟议的协议，旨在加强边境安全合作。生物识别数据包括指纹、面部图像和虹膜扫描——这些信息无法像密码那样更改。目前，美国要求免签旅行伙伴满足特定安全条件，而该协议将把数据共享范围扩大到现有的旅客订座记录（PNR）方案之外。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ic.work/article/eu-us-visa-waiver-biometric-data-access-talks">欧盟赴美免签谈判，正把生物识别数据库推上桌面 - ic.work</a></li>

</ul>
</details>

**标签**: `#privacy`, `#biometric data`, `#EU-US relations`, `#digital rights`, `#data sharing`

---

<a id="item-13"></a>
## [欧盟对阿里 Express 罚款 5.5 亿欧元因假冒商品](https://thebalkanchronicle.com/en/business/eu-fines-aliexpress-550-million-counterfeit-goods-2026/) ⭐️ 8.0/10

欧盟委员会于 2025 年 7 月 20 日根据《数字服务法案》（DSA）对 AliExpress 处以 5.5 亿欧元罚款，原因是其未能阻止假冒和非法商品在平台上流通。 这是 DSA 针对大型电商平台的首次重大执法，为平台在假冒商品方面的责任树立了先例，可能影响在线市场在欧盟的运营方式。 调查发现，不安全玩具和危险化妆品在被标记后仍上架数周。AliExpress 称罚款“不成比例”，并须在 2026 年 10 月 20 日前提交整改方案。

telegram · zaihuapd · 7月21日 01:44

**背景**: 《数字服务法案》（DSA）是欧盟于 2022 年生效的法规，对在线平台的内容审核和透明度施加严格义务。像 AliExpress 这样的超大型在线平台（VLOP）面临最高标准，包括采取主动措施打击非法和假冒商品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_Services_Act">Digital Services Act</a></li>

</ul>
</details>

**标签**: `#e-commerce`, `#regulation`, `#EU`, `#counterfeit goods`, `#Digital Services Act`

---

<a id="item-14"></a>
## [台积电 2027 年起芯片涨价 5%至 10%](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

台积电已与客户达成协议，从 2027 年初起将芯片制造服务价格上调 5%至 10%，涵盖 7 纳米以下先进制程及 12 纳米以上成熟制程。超出原始预测的高性能计算芯片订单还将额外加收 10%至 15%的溢价。 此次涨价反映了材料、设备和海外新厂建设成本持续攀升，标志着台积电定价策略的战略性转变，将影响苹果、英伟达、AMD 等主要科技客户，并可能波及全球半导体供应链及终端设备价格。 台积电首席财务官表示，海外晶圆厂扩张及 2 纳米量产将继续对利润率构成压力。董事长魏哲家强调定价是战略性的，不会像存储芯片行业那样突然大幅涨价，并称要让客户也能生存。

telegram · zaihuapd · 7月21日 09:28

**背景**: 先进半导体制程（如 7 纳米、5 纳米、3 纳米、2 纳米）为 AI、移动设备和高性能计算等应用提供更高性能和密度。成熟制程（如 12 纳米、28 纳米、45 纳米）用于汽车、物联网和其他对成本敏感的领域，可接受性能上的权衡。台积电是全球最大的专业半导体代工厂，为众多领先科技公司生产芯片。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.eejournal.com/article/are-we-ready-for-the-2nm-process-node/">Are We Ready for the 2 nm Process Node ? – EEJournal</a></li>
<li><a href="https://anysilicon.com/semiconductor-technology-node-history-roadmap/">Semiconductor Technology Node History and Roadmap - AnySilicon</a></li>
<li><a href="https://semiengineering.com/legacy-process-nodes-are-critical-to-many-industries/">Legacy Process Nodes Are Critical To Many Industries</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#TSMC`, `#chip pricing`, `#supply chain`, `#manufacturing costs`

---