---
layout: default
title: "Horizon Summary: 2026-07-21 (ZH)"
date: 2026-07-21
lang: zh
---

> 从 42 条内容中筛选出 14 条重要资讯。

---

1. [Jane Street 的增量计算库](https://github.com/janestreet/incremental) ⭐️ 8.0/10
2. [Kimi Work：本地 AI 代理克隆 Claude/Codex](https://www.kimi.com/products/kimi-work) ⭐️ 8.0/10
3. [AI 在反例生成上超越人类数学家](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 8.0/10
4. [Cursor 自建 VCS 管理代理集群，比较模型经济](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10
5. [中国开放权重 AI 模型是否正战胜美国专有模型？](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10
6. [Jellyfin 创始人 Andrew 因倦怠离职](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10
7. [Claude Tag 处理了 65% 的 PR，Anthropic 团队透露](https://simonwillison.net/2026/Jul/21/cat-and-thariq/#atom-everything) ⭐️ 8.0/10
8. [AI 编码代理大幅降低逆向工程成本](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10
9. [美国立法提案：AI 训练数据合理使用与蒸馏合法化](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10
10. [Fastjson 1.x 存在无 gadget 高危 RCE 漏洞](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 8.0/10
11. [智谱建成全国产芯片 AI 数据中心](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 8.0/10
12. [谷歌开发 Frozen v2 AI 芯片，将 Gemini 硬编码到硬件](https://www.quiverquant.com/news/Google+Reportedly+Developing+%E2%80%98Frozen+v2%E2%80%99+AI+Chip+to+Boost+Gemini+Efficiency) ⭐️ 8.0/10
13. [Cloudflare 推出内部 DNS 服务，面向私有网络](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10
14. [台积电 2027 年起芯片涨价 5%至 10%](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Jane Street 的增量计算库](https://github.com/janestreet/incremental) ⭐️ 8.0/10

Jane Street 发布了 Incremental 库，用于在 OCaml 中进行增量计算，仅更新依赖于已变化输入的计算部分。 这种方法对于交易系统和用户界面等应用至关重要，部分重计算可节省时间和资源，并与响应式编程和构建系统的广泛趋势相关联。 该库构建了一个计算依赖图，并使用变更传播算法来最小化重计算，类似于 JavaScript signals 和差分数据流系统中的机制。

hackernews · handfuloflight · 7月21日 03:50 · [社区讨论](https://news.ycombinator.com/item?id=48987822)

**背景**: 增量计算是一种技术，当数据发生变化时，仅重新计算依赖于该数据的输出，而不是重新计算所有内容。这常用于电子表格和构建系统。Incremental 库在 OCaml 中实现，OCaml 是 Jane Street 用于量化金融应用的函数式编程语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Incremental_computation">Incremental computing - Wikipedia</a></li>
<li><a href="https://github.com/janestreet/incremental">GitHub - janestreet / incremental : A library for incremental ...</a></li>
<li><a href="https://blog.janestreet.com/introducing-incremental/">Jane Street Blog - Introducing Incremental</a></li>

</ul>
</details>

**社区讨论**: 评论者将该库与 JavaScript signals（已提交 TC39 提案）及 Vue、SolidJS 等框架联系起来，并指出其与构建系统和差分数据流的相似性。一位评论者提到高盛几十年前曾在工具定价中使用类似方法。

**标签**: `#incremental computation`, `#reactive programming`, `#dataflow`, `#functional programming`, `#Jane Street`

---

<a id="item-2"></a>
## [Kimi Work：本地 AI 代理克隆 Claude/Codex](https://www.kimi.com/products/kimi-work) ⭐️ 8.0/10

Kimi Work 是一款在 Mac 和 Windows 上本地运行的桌面 AI 代理，支持挂载本地文件夹、通过 WebBridge 自主浏览网页以及后台执行 Python 代码。它高度复制了 Anthropic 的 Claude/Codex 产品的功能和界面，但价格大幅降低。 Kimi Work 的激进定价和本地优先策略可能颠覆 AI 代理市场，使强大的自动化对注重成本的用户和关注数据隐私的企业更加可及。但其公然抄袭现有工具的做法引发了关于知识产权和公平竞争的讨论。 该代理可同时运行多达 300 个并行代理，并包含一个安全机制，要求在修改文件或运行代码前获得用户明确许可。批评者指出，Kimi 的隐私声明可能具有误导性，它声称用户拥有绝对控制权，但实际上可能将数据发送到云端模型。

hackernews · ms7892 · 7月20日 17:13 · [社区讨论](https://news.ycombinator.com/item?id=48981703)

**背景**: 像 Claude/Codex 这样的 AI 代理利用大型语言模型在用户计算机上自动化复杂工作流程，例如编码、网络研究和数据分析。本地优先的代理在设备上处理数据以增强隐私、减少延迟并降低云计算成本。Kimi Work 作为低成本替代品进入这一领域，但被指控在无明显创新下抄袭了 Codex 的设计和行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kimi.com/products/kimi-work">Kimi Work: Next-Gen Desktop AI Agent for Knowledge Workers</a></li>
<li><a href="https://www.kimi.com/resources/kimi-work-introduction">Kimi Work: The Local AI Agent for Your Desktop</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：一些人称赞其低价格和本地隐私优势，称即使抄袭也是‘胜出的产品’。另一些人批评其‘无耻地’1:1 复制 Codex 以及误导性的隐私政策。人们还因缺乏 Linux 客户端而感到失望，并对长时间运行任务的状态持久性表示好奇。

**标签**: `#AI agents`, `#local-first`, `#privacy`, `#codex clone`, `#workflow automation`

---

<a id="item-3"></a>
## [AI 在反例生成上超越人类数学家](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 8.0/10

一篇博文讨论了 AI 系统日益生成数学猜想反例的现象，这可以快速证伪错误猜想，为数学家节省时间。 这一进展可能显著加速数学研究，让数学家专注于有价值的猜想，而非在错误方向上浪费时间。 博文强调了 AI 在自动推理和反例生成方面日益增强的能力，并给出了具体例子，这对数学和 AI 领域高度相关，但尚未构成范式转变。

hackernews · artninja1988 · 7月20日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=48983382)

**背景**: 数学猜想是尚未被证明但被认为正确的陈述。反例是能证伪猜想的实例，常促使理论完善。AI 系统如今利用机器学习和自动推理高效地发现此类反例。

**社区讨论**: 社区评论总体积极，用户指出 AI 生成的反例能节省时间并有助于数学完善。一则评论分享了一位数学家因错误推论而影响职业生涯的轶事，暗示 AI 本可避免此类问题。另一用户强调了反例在拉卡托斯《证明与反驳》传统中的重要性。

**标签**: `#mathematics`, `#AI`, `#counterexamples`, `#automated reasoning`, `#machine learning`

---

<a id="item-4"></a>
## [Cursor 自建 VCS 管理代理集群，比较模型经济](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10

Cursor 宣布从头构建了一个新的版本控制系统（VCS），以管理每秒产生多达 1000 次提交的代理集群，并在从文档构建 Rust 版 SQLite 的基准任务中比较了多种 AI 模型的成本效率。 这突破了 AI 代理协作的边界，凸显了超越 Git 的基础设施需求。同时，它提供了实用的成本对比，可能影响 AI 辅助软件开发中的模型选择。 新 VCS 每秒处理 1000 次提交，而之前是每小时 1000 次。在基准测试中，Opus + Composer 的表现与完整的 Fable 系统相当，但成本仅为后者的 1/19，代码量也少一半。

hackernews · jlaneve · 7月20日 18:06 · [社区讨论](https://news.ycombinator.com/item?id=48982535)

**背景**: 代理集群指多个 AI 代理同时处理代码，产生大量变更。传统 Git 难以应对高提交量和锁竞争。Cursor 的自定义 VCS 专为此类高吞吐场景设计，能实现更好的协调和冲突解决。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cursor.com/blog/agent-swarm-model-economics">Agent swarms and the new model economics · Cursor</a></li>
<li><a href="https://www.startuphub.ai/ai-news/technology/2026/ai-agent-swarms-rethink-model-economics">AI Agent Swarms Rethink Model Economics | StartupHub.ai</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：有人质疑基准测试的现实相关性，也有人对成本效率和 VCS 创新感到兴奋。一位评论者指出 Opus + Composer 以极低成本取得了可比结果，引发了关于模型经济学的兴趣。

**标签**: `#agent swarms`, `#AI coding`, `#version control`, `#cost efficiency`, `#software engineering`

---

<a id="item-5"></a>
## [中国开放权重 AI 模型是否正战胜美国专有模型？](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10

一篇博客文章认为，中国的开放权重 AI 模型在采用率和可访问性上正超越美国的专有模型，这在 Hacker News 上引发了争论。 这场争论凸显了一个关键的地缘政治和技术趋势：开放权重模型可能通过更广泛的访问和创新来重塑全球 AI 竞争格局。 文章声称 80%的初创公司使用中国模型，但社区评论者质疑这一数字。Llama（Meta）仍是重要的开放权重模型，但企业往往优先考虑数据保留而非开放性。

hackernews · benwerd · 7月20日 14:21 · [社区讨论](https://news.ycombinator.com/item?id=48979269)

**背景**: 开放权重模型公开发布训练后的参数，允许任何人下载、运行和修改，这与专有模型不同。例如 Llama、Mistral 和 DeepSeek Coder。这场争论反映了历史上开放或低成本解决方案最终主导市场的模式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@aruna.kolluru/exploring-the-world-of-open-source-and-open-weights-ai-aa09707b69fc">Exploring the World of Open Source and Open Weights AI | Medium</a></li>
<li><a href="https://aicoderhq.com/glossary/open-weights-model">Open - Weights Model : Definition &amp; Explanation | AI Coder HQ</a></li>
<li><a href="https://www.ai21.com/glossary/open-weights-model/">What is an Open - Weights Model ? | AI 21</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了怀疑：有人指出许多初创公司仍依赖 Claude 和 Codex 等美国模型，另有人质疑 80%的说法是否可靠。部分人同意当硬件成本下降时开放权重可能胜出，但知识产权侵权问题也被提及。

**标签**: `#AI`, `#open-source`, `#China`, `#deep learning`, `#Hacker News`

---

<a id="item-6"></a>
## [Jellyfin 创始人 Andrew 因倦怠离职](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10

开源媒体服务器项目 Jellyfin 的创始人 Andrew 因严重倦怠宣布离开团队。此次交接似乎平稳，项目将在现有维护者带领下继续运行。 此次领导层变动突显了开源软件中维护者倦怠的持续挑战，尤其是像 Jellyfin 这样作为 Plex 等专有服务免费替代品的广泛使用项目。社区超过 260 条评论的热烈反应凸显了该项目的重要性和用户的情感投入。 Andrew 将严重倦怠和无法满足角色要求作为离职原因。多位社区成员指出这并非孤立事件，并提及 Filebrowser 等其他开源项目中的类似倦怠案例。

hackernews · swat535 · 7月20日 23:15 · [社区讨论](https://news.ycombinator.com/item?id=48986091)

**背景**: Jellyfin 是一款免费的开源媒体服务器软件，允许用户将自己的媒体库流式传输到任何设备。它于 2018 年从 Emby 分支出来，现已发展成为 Plex 等专有解决方案的流行替代品。该项目由志愿者维护，维护者倦怠是开源社区中已知的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://github.com/jellyfin/jellyfin">GitHub - jellyfin/jellyfin: The Free Software Media System - Server Backend &amp; API · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区评论者表达了对 Andrew 贡献的感激和对他的倦怠的同情，同时也反思了开源可持续性的更广泛问题。一些人指出最近 Plex 终身通行证涨价至 750 美元是用户考虑 Jellyfin 的驱动因素。

**标签**: `#open-source`, `#media-server`, `#jellyfin`, `#burnout`, `#project-leadership`

---

<a id="item-7"></a>
## [Claude Tag 处理了 65% 的 PR，Anthropic 团队透露](https://simonwillison.net/2026/Jul/21/cat-and-thariq/#atom-everything) ⭐️ 8.0/10

在 AI Engineer World&\#x27;s Fair 的炉边谈话中，Anthropic 的 Claude Code 团队透露，Claude Tag 目前处理了其产品工程 65% 的拉取请求，并且功能在公开发布前会基于内部用户留存率进行验证。 这提供了罕见的视角，展示领先 AI 实验室如何在自己的生产环境中使用其工具，为开发者生产力提供基准，并为编码代理和协作 AI 集成的最佳实践提供洞见。 Claude Code 的功能首先向 Anthropic 员工推送，只有展示出用户留存率才会发布；系统提示词最近减少了 80%，因为对于像 Fable 5 这样的新模型，添加示例已不再是最佳实践。

rss · Simon Willison · 7月21日 12:54

**背景**: Claude Tag 是一个协作式 Slack 集成，允许团队用 @Claude 标记任务，然后它会将任务分解并逐步执行。Claude Code 是一个代理式编码助手，可以自主导航代码库并实现功能。Anthropic 的内部文化称为“蚁食”（ant fooding），强调在外部发布前通过自己使用产品来验证变更。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://support.claude.com/en/articles/15594475-what-is-claude-tag">What is Claude Tag ? | Claude Help Center</a></li>
<li><a href="https://www.anthropic.com/news/introducing-claude-tag">Claude Tag is a new way for teams to work with Claude .</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**标签**: `#Claude Code`, `#Anthropic`, `#AI engineering`, `#developer productivity`, `#tool design`

---

<a id="item-8"></a>
## [AI 编码代理大幅降低逆向工程成本](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10

Simon Willison 观察到，AI 编码代理大幅降低了逆向工程家用设备所需的工作量和成本，使自动化项目更加可行。 这一转变降低了维护的心理障碍，因为代码成本低廉意味着如果 API 发生变化，重写或丢弃代码不再那么令人痛苦，从而鼓励更多爱好者和专业人士进行自动化。 在编码代理出现之前，逆向工程需要大量精力，并且要承担维护不稳定 API 的责任；代理降低了试错成本，使许多项目的投资回报率为正。

rss · Simon Willison · 7月20日 19:24

**背景**: 编码代理是基于 AI 的工具，能够根据自然语言提示生成、调试和修改代码，极大地加速了软件开发。逆向工程家用设备涉及分析无文档记录的协议以创建自定义集成，传统上耗时且脆弱。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Hybrid_Mac_mini_and_RTX_4090_setup_for_local_AI_coding_agents">Hybrid Mac mini and RTX 4090 setup for local AI coding agents</a></li>
<li><a href="https://hackaday.com/2020/01/21/reverse-engineering-yokis-home-automation-devices/">Reverse Engineering Yokis Home Automation Devices | Hackaday</a></li>

</ul>
</details>

**标签**: `#reverse-engineering`, `#coding agents`, `#automation`, `#AI-assisted coding`, `#software development`

---

<a id="item-9"></a>
## [美国立法提案：AI 训练数据合理使用与蒸馏合法化](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10

知名科技分析师本·汤普森提议美国立法，明确将训练数据收集视为合理使用，并禁止禁止模型蒸馏的服务条款，以帮助美国的开放权重模型与中国模型竞争。 该提议揭示了 AI 开发中的一个关键矛盾——实验室在未授权数据上训练模型，却阻止他人蒸馏其模型——并可能重塑版权政策和开放模型的全球竞争格局。 文章还提到阿里巴巴发布了 Qwen 3.8 Max，一个 2.4 万亿参数的开放权重模型，本·汤普森认为这可能是受习近平鼓励开源合作的讲话影响。

rss · Simon Willison · 7月20日 17:09

**背景**: 知识蒸馏是一种技术，较小的学生模型通过查询较大教师模型的 API 来学习。目前，许多 AI 公司的服务条款禁止此类蒸馏。同时，使用受版权保护的数据进行训练的法律地位仍有争议，一些人认为这属于合理使用。开放权重模型（如 Meta 和阿里巴巴的模型）提供训练好的参数，但不提供完整的训练过程，这与开源 AI 不同。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation</a></li>
<li><a href="https://creativecommons.org/2023/02/17/fair-use-training-generative-ai/">Fair Use : Training Generative AI - Creative Commons</a></li>
<li><a href="https://www.linkedin.com/pulse/frontier-ai-models-closed-vs-open-weight-source-varadaraj-pandurangan-yrdue">Frontier AI Models: Closed vs Open Weight vs Open Source</a></li>

</ul>
</details>

**标签**: `#AI`, `#open models`, `#copyright`, `#policy`, `#distillation`

---

<a id="item-10"></a>
## [Fastjson 1.x 存在无 gadget 高危 RCE 漏洞](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 8.0/10

安全研究员 Kirill Firsov 披露了 Fastjson 1.2.68 至 1.2.83 版本存在高危远程代码执行漏洞，无需开启 autoType 或依赖 classpath gadget 即可利用。 该漏洞影响 Java 生态中广泛使用的 JSON 库，且 Fastjson 1.x 已停止维护，官方不会提供补丁，用户必须紧急迁移到 Fastjson2 或启用 SafeMode。 该漏洞在 JDK 8、17、21 上均可利用，唯一缓解措施是升级到 Fastjson2，或在 JVM 参数或配置文件中设置 SafeMode。

telegram · zaihuapd · 7月20日 14:32

**背景**: Fastjson 是阿里巴巴开发的 Java 高性能 JSON 序列化/反序列化库。其 autoType 功能开启后允许多态类型反序列化，但曾引发多个漏洞。传统的 RCE 利用需要 gadget 链——即 classpath 上的类可组合执行任意代码。此新漏洞绕过 autoType 和 gadget 需求，更加危险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://topic.alibabacloud.com/a/com-alibaba-fastjson-jsonexception-autotype-is-not-support-_1_27_32615398.html">Com. alibaba. fastjson . JSONException: autoType is not support</a></li>
<li><a href="https://stackoverflow.com/questions/11490844/whats-the-gadget-vulnerability">security - What&#x27;s the &quot; gadget vulnerability &quot;? - Stack Overflow</a></li>
<li><a href="https://github.com/alibaba/fastjson2/blob/main/docs/autotype_en.md">fastjson 2/docs/autotype_en.md at main · alibaba/ fastjson 2 · GitHub</a></li>

</ul>
</details>

**社区讨论**: 该披露在安全社区引发紧急讨论，许多人强调必须尽快迁移出 Fastjson 1.x。

**标签**: `#fastjson`, `#security`, `#rce`, `#vulnerability`, `#java`

---

<a id="item-11"></a>
## [智谱建成全国产芯片 AI 数据中心](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 8.0/10

智谱 AI 已完成一座全部采用国产芯片、功率达 1 吉瓦的数据中心建设，并已部分投入运营，用于支持其旗舰 GLM 平台。 这一里程碑表明中国在建设自给自足的 AI 基础设施方面取得进展，尽管面临美国出口限制，可能减少对 NVIDIA 等外国 GPU 在大规模 AI 训练中的依赖。 该数据中心功率达 1 吉瓦，足以供应约 75 万户家庭，是中国 AI 实验室建造的最大规模设施之一，拥有多个各含超万枚芯片的计算集群。

telegram · zaihuapd · 7月20日 15:43

**背景**: 智谱 AI（现国际品牌名 Z.ai）是清华大学孵化的中国 AI 公司，以开发开源 GLM 系列大语言模型而闻名。由于美国出口管制，中国 AI 企业面临压力，需要开发和部署国产 AI 芯片（如华为昇腾）作为先进 NVIDIA GPU 的替代品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zhipu_AI">Zhipu AI</a></li>
<li><a href="https://pandaily.com/china-chips-supporting-domestic-models-waic-jul2026">2026: China Chips Underpin Domestic AI Models at WAIC... - Pandaily</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#domestic chips`, `#Chinese AI`, `#data center`, `#Zhipu`

---

<a id="item-12"></a>
## [谷歌开发 Frozen v2 AI 芯片，将 Gemini 硬编码到硬件](https://www.quiverquant.com/news/Google+Reportedly+Developing+%E2%80%98Frozen+v2%E2%80%99+AI+Chip+to+Boost+Gemini+Efficiency) ⭐️ 8.0/10

据报道，谷歌正在开发一款代号为“Frozen v2”的服务器芯片，将 Gemini AI 模型的部分能力直接写入硬件，目标是在推理效率上比当前 TPU 提升 6 到 10 倍，计划于 2028 年部署。 如果成功，Frozen v2 将大幅降低 Gemini 的推理成本和功耗，缓解内部算力短缺，并使谷歌在超高效 AI 硬件领域占据领先地位，但硬编码设计会限制模型的灵活性。 该芯片将 Gemini 的神经网络架构直接烧录到电路中，减少了数据移动和计算开销。它旨在补充而非取代谷歌的 TPU，是缓解内部算力短缺（已限制云服务供给）的更大战略的一部分。

telegram · zaihuapd · 7月21日 01:01

**背景**: 当前的 AI 芯片（如 TPU）将模型保存在内存中并来回传输数据，这消耗功耗和时间。将模型元素硬编码到硅片中会将硬件锁定到特定模型架构，牺牲灵活性以换取效率。谷歌的 Frozen v2 针对推理工作负载（模型固定且速度至关重要）而设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qz.com/google-gemini-chip-frozen-tpu-efficiency-072026">Google developing Gemini-specific chip called Frozen v 2</a></li>
<li><a href="https://logicity.in/en/blog/google-s-frozen-v2-chip-embeds-gemini-in-hardware-for-6-10x-gains">Google&#x27;s Frozen v 2 chip embeds Gemini in hardware for... | Logicity</a></li>
<li><a href="https://thenextweb.com/news/google-frozen-chip-gemini-silicon">Google Frozen chip : Gemini baked into the silicon</a></li>

</ul>
</details>

**标签**: `#AI chips`, `#Google`, `#Gemini`, `#hardware acceleration`, `#inference efficiency`

---

<a id="item-13"></a>
## [Cloudflare 推出内部 DNS 服务，面向私有网络](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10

Cloudflare 于 2026 年 7 月 20 日宣布内部 DNS 服务正式全面上线，为企业私有网络提供权威与递归 DNS 解析，并与 Zero Trust 和 Gateway 深度集成。 该服务将公共与私有 DNS 整合至单一平台，简化了 split-horizon DNS 管理，并将 Zero Trust 策略延伸至 DNS 层，从而降低了企业网络管理员的配置复杂度和数据漂移问题。 该服务通过「DNS 视图」控制不同用户和设备可访问的内部域名，支持通过 API、Terraform 和 Cloudflare WAN 部署。已使用 Cloudflare Gateway 的客户无需额外付费即可启用。

telegram · zaihuapd · 7月21日 03:49

**背景**: Split-horizon DNS（也称为 split-view DNS）允许 DNS 服务器根据查询来源返回不同响应，常用于区分内部和外部 DNS 解析。传统实现需要独立服务器或软件配置，容易导致数据不一致。Cloudflare 的内部 DNS 利用其全球网络统一这些视图，简化了企业网络管理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Split-horizon_DNS">Split-horizon DNS</a></li>

</ul>
</details>

**标签**: `#Cloudflare`, `#DNS`, `#Zero Trust`, `#企业网络`, `#私有DNS`

---

<a id="item-14"></a>
## [台积电 2027 年起芯片涨价 5%至 10%](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

台积电已与客户达成协议，将从 2027 年初起将芯片制造价格上调 5%至 10%，涵盖 7 纳米以下先进制程及 12 纳米以上成熟制程。对于超出原始预测的高性能计算芯片订单，还将额外加收 10%至 15%的溢价。 此次涨价表明半导体制造成本因海外工厂扩张和先进节点开发而持续攀升，可能推高整个科技行业的芯片价格。台积电的定价策略将影响苹果、英伟达和 AMD 等主要客户，并可能重塑供应链格局。 基础涨价适用于从 7 纳米到 12 纳米及以上的所有制程，对于超出预测量的高性能计算订单还要在基础涨幅上加收最高 15%的溢价。台积电董事长表示定价是战略性的，不会像存储芯片行业那样突然大幅涨价。

telegram · zaihuapd · 7月21日 09:28

**背景**: 台积电是全球最大的专业半导体代工厂，为苹果、英伟达和 AMD 等公司制造芯片。7 纳米、5 纳米等工艺节点指的是晶体管尺寸，更小的节点提供更好的性能和能效。台积电计划在 2025-2027 年间量产 2 纳米芯片，并在美国、日本和欧洲扩建海外工厂，这大幅增加了成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/tsmc-forecasts-2-trillion-market-opportunity-2nm-technology-jha-kc0hc">TSMC Forecasts $2 Trillion Market Opportunity for 2 nm Technology</a></li>
<li><a href="https://grokipedia.com/page/2_nm_process">2 nm process</a></li>

</ul>
</details>

**标签**: `#TSMC`, `#semiconductor`, `#chip pricing`, `#supply chain`

---