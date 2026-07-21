---
layout: default
title: "Horizon Summary: 2026-07-21 (EN)"
date: 2026-07-21
lang: en
---

> From 42 items, 14 important content pieces were selected

---

1. [Jane Street&\#x27;s Incremental Library for Efficient Recomputations](https://github.com/janestreet/incremental) ⭐️ 8.0/10
2. [Kimi Work: Local AI Agent Clone of Claude/Codex](https://www.kimi.com/products/kimi-work) ⭐️ 8.0/10
3. [AI Outcounterexamples Human Mathematicians](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 8.0/10
4. [Cursor builds custom VCS for agent swarms, compares model economics](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10
5. [China&\#x27;s open-weights AI models winning over US proprietary ones?](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10
6. [Jellyfin founder Andrew steps down due to burnout](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10
7. [Claude Tag handles 65% of PRs, Anthropic team reveals](https://simonwillison.net/2026/Jul/21/cat-and-thariq/#atom-everything) ⭐️ 8.0/10
8. [AI coding agents slash reverse-engineering costs](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10
9. [Ben Thompson Proposes US Law on AI Training and Distillation](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10
10. [Critical RCE in Fastjson 1.x without Gadgets](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 8.0/10
11. [Zhipu Completes All-Domestic Chip AI Data Center](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 8.0/10
12. [Google Develops Frozen v2 AI Chip with Gemini Hardcoded](https://www.quiverquant.com/news/Google+Reportedly+Developing+%E2%80%98Frozen+v2%E2%80%99+AI+Chip+to+Boost+Gemini+Efficiency) ⭐️ 8.0/10
13. [Cloudflare Launches Internal DNS Service for Private Networks](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10
14. [TSMC to Raise Chip Prices by 5-10% from 2027](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Jane Street&\#x27;s Incremental Library for Efficient Recomputations](https://github.com/janestreet/incremental) ⭐️ 8.0/10

Jane Street has released Incremental, a library for incremental computations in OCaml, which efficiently updates only the parts of a computation that depend on changed inputs. This approach is crucial for applications like trading systems and UIs, where partial recomputation saves time and resources, and it connects to broader trends in reactive programming and build systems. The library builds a dependency graph of computations and uses a change-propagation algorithm to minimize recomputation, similar to mechanisms in JavaScript signals and differential dataflow systems.

hackernews · handfuloflight · Jul 21, 03:50 · [Discussion](https://news.ycombinator.com/item?id=48987822)

**Background**: Incremental computation is a technique that, when a piece of data changes, only recomputes outputs depending on that data, rather than recalculating everything. This is commonly used in spreadsheets and build systems. The Incremental library implements this in OCaml, a functional programming language used by Jane Street for quantitative finance applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Incremental_computation">Incremental computing - Wikipedia</a></li>
<li><a href="https://github.com/janestreet/incremental">GitHub - janestreet / incremental : A library for incremental ...</a></li>
<li><a href="https://blog.janestreet.com/introducing-incremental/">Jane Street Blog - Introducing Incremental</a></li>

</ul>
</details>

**Discussion**: Commenters linked the library to JavaScript signals \(proposed for TC39\) and frameworks like Vue and SolidJS, and noted similarities with build systems and differential dataflow. One commenter mentioned Goldman Sachs used a similar approach for instrument pricing decades ago.

**Tags**: `#incremental computation`, `#reactive programming`, `#dataflow`, `#functional programming`, `#Jane Street`

---

<a id="item-2"></a>
## [Kimi Work: Local AI Agent Clone of Claude/Codex](https://www.kimi.com/products/kimi-work) ⭐️ 8.0/10

Kimi Work is a desktop AI agent that runs locally on Mac and Windows, supporting local folder mounting, autonomous web browsing via WebBridge, and background Python execution. It closely replicates the features and UI of Anthropic&\#x27;s Claude/Codex products but is offered at a significantly lower price point. Kimi Work&\#x27;s aggressive pricing and local-first approach could disrupt the AI agent market by making powerful automation accessible to cost-sensitive users and enterprises concerned about data privacy. However, its blatant copying of existing tools sparks debate about intellectual property and fair competition. The agent can run up to 300 parallel agents and includes a safeguard that requires explicit user permission before modifying files or running code. Critics have noted that Kimi&\#x27;s privacy disclosure may be misleading, as it claims absolute user control while potentially sending data to cloud models.

hackernews · ms7892 · Jul 20, 17:13 · [Discussion](https://news.ycombinator.com/item?id=48981703)

**Background**: AI agents like Claude/Codex use large language models to automate complex workflows on a user&\#x27;s computer, such as coding, web research, and data analysis. Local-first agents process data on-device to enhance privacy, reduce latency, and lower cloud computing costs. Kimi Work enters this space as a low-cost alternative but has been accused of copying Codex&\#x27;s design and behavior without significant innovation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kimi.com/products/kimi-work">Kimi Work: Next-Gen Desktop AI Agent for Knowledge Workers</a></li>
<li><a href="https://www.kimi.com/resources/kimi-work-introduction">Kimi Work: The Local AI Agent for Your Desktop</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some praise the low price and local privacy benefits, calling it a &\#x27;winning product&\#x27; despite being a copy. Others criticize the &\#x27;shameless&\#x27; 1:1 copying of Codex and the misleading privacy policy. Disappointment was also expressed over the lack of a Linux client, as well as curiosity about long-running task state persistence.

**Tags**: `#AI agents`, `#local-first`, `#privacy`, `#codex clone`, `#workflow automation`

---

<a id="item-3"></a>
## [AI Outcounterexamples Human Mathematicians](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 8.0/10

A blog post discusses how AI systems are increasingly generating counterexamples to mathematical conjectures, potentially saving mathematicians time by quickly disproving false conjectures. This development could significantly accelerate mathematical research by allowing mathematicians to focus on productive conjectures rather than wasting time on false ones. The post highlights specific examples and the growing capability of AI in automated reasoning and counterexample generation, which is a non-paradigm-shift yet highly relevant development for mathematics and AI.

hackernews · artninja1988 · Jul 20, 19:03 · [Discussion](https://news.ycombinator.com/item?id=48983382)

**Background**: Mathematical conjectures are statements believed to be true but not yet proven. Counterexamples are instances that disprove a conjecture, often leading to refinement of theories. AI systems now leverage machine learning and automated reasoning to find such counterexamples efficiently.

**Discussion**: The community comments are generally positive, with users noting that AI-generated counterexamples save time and help refine mathematics. One comment shares a historical anecdote about a mathematician whose career was impacted by an incorrect corollary, suggesting AI could have prevented such issues. Another user emphasizes the importance of counterexamples in the tradition of Lakatos&\#x27; &\#x27;Proofs and Refutations&\#x27;.

**Tags**: `#mathematics`, `#AI`, `#counterexamples`, `#automated reasoning`, `#machine learning`

---

<a id="item-4"></a>
## [Cursor builds custom VCS for agent swarms, compares model economics](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10

Cursor announced it built a new version control system \(VCS\) from scratch to handle agent swarms generating up to 1,000 commits per second, and compared the cost efficiency of various AI models on a benchmark task of building SQLite in Rust from documentation. This pushes the boundaries of AI agent collaboration and highlights the need for infrastructure beyond Git. It also provides practical cost comparisons that could influence model selection for AI-assisted software development. The new VCS handles 1,000 commits per second compared to the previous 1,000 commits per hour. In the benchmark, Opus + Composer performed similarly to the full Fable system at 1/19th the cost and half the lines of code.

hackernews · jlaneve · Jul 20, 18:06 · [Discussion](https://news.ycombinator.com/item?id=48982535)

**Background**: Agent swarms involve multiple AI agents working concurrently on code, producing many changes. Traditional Git struggles with high commit volumes and lock contention. Cursor&\#x27;s custom VCS is designed for such high-throughput scenarios, enabling better coordination and conflict resolution.

<details><summary>References</summary>
<ul>
<li><a href="https://cursor.com/blog/agent-swarm-model-economics">Agent swarms and the new model economics · Cursor</a></li>
<li><a href="https://www.startuphub.ai/ai-news/technology/2026/ai-agent-swarms-rethink-model-economics">AI Agent Swarms Rethink Model Economics | StartupHub.ai</a></li>

</ul>
</details>

**Discussion**: Community responses are mixed: some question the benchmark&\#x27;s real-world relevance, while others are excited about cost efficiency and the VCS innovation. One commenter noted that Opus + Composer achieved comparable results at a fraction of the cost, sparking interest in model economics.

**Tags**: `#agent swarms`, `#AI coding`, `#version control`, `#cost efficiency`, `#software engineering`

---

<a id="item-5"></a>
## [China&\#x27;s open-weights AI models winning over US proprietary ones?](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10

A blog post argues that China&\#x27;s open-weights AI models are outperforming proprietary US models in adoption and accessibility, sparking debate on Hacker News. The debate highlights a key geopolitical and technical trend: open-weights models could reshape global AI competition by enabling wider access and innovation. The article claims 80% of startups use Chinese models, but community commenters question this figure. Llama \(Meta\) remains a prominent open-weights model, yet enterprises often prioritize data retention over openness.

hackernews · benwerd · Jul 20, 14:21 · [Discussion](https://news.ycombinator.com/item?id=48979269)

**Background**: Open-weights models publicly release trained parameters, allowing anyone to download, run, and modify them, unlike proprietary models. Examples include Llama, Mistral, and DeepSeek Coder. The debate reflects historical patterns where open or low-cost solutions eventually dominate markets.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@aruna.kolluru/exploring-the-world-of-open-source-and-open-weights-ai-aa09707b69fc">Exploring the World of Open Source and Open Weights AI | Medium</a></li>
<li><a href="https://aicoderhq.com/glossary/open-weights-model">Open - Weights Model : Definition &amp; Explanation | AI Coder HQ</a></li>
<li><a href="https://www.ai21.com/glossary/open-weights-model/">What is an Open - Weights Model ? | AI 21</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism: one noted many startups still rely on US models like Claude and Codex, while another questioned the validity of the 80% claim. Some agreed open-weights might win when hardware costs drop, but IP violation concerns were raised.

**Tags**: `#AI`, `#open-source`, `#China`, `#deep learning`, `#Hacker News`

---

<a id="item-6"></a>
## [Jellyfin founder Andrew steps down due to burnout](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10

Andrew, the founder of the open-source media server project Jellyfin, has announced his departure from the team due to severe burnout. The transition appears to be peaceful, with the project continuing under existing maintainers. This leadership change highlights the ongoing challenge of maintainer burnout in open-source software, especially for widely-used projects like Jellyfin that serve as a free alternative to proprietary services like Plex. The community&\#x27;s strong response \(over 260 comments\) underscores the project&\#x27;s importance and the emotional investment of its users. Andrew cited severe burnout and an inability to meet the role&\#x27;s demands as reasons for stepping down. Multiple community members noted that this is not an isolated incident, referencing similar burnout cases in other open-source projects like Filebrowser.

hackernews · swat535 · Jul 20, 23:15 · [Discussion](https://news.ycombinator.com/item?id=48986091)

**Background**: Jellyfin is a free, open-source media server software that allows users to stream their own media libraries to any device. It was forked from Emby in 2018 and has grown into a popular alternative to proprietary solutions like Plex. The project is maintained by volunteers, and maintainer burnout is a known issue in the open-source community.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://github.com/jellyfin/jellyfin">GitHub - jellyfin/jellyfin: The Free Software Media System - Server Backend &amp; API · GitHub</a></li>

</ul>
</details>

**Discussion**: Community commenters expressed gratitude for Andrew&\#x27;s contributions and sympathy for his burnout, while also reflecting on the broader problem of open-source sustainability. Some noted the recent Plex price hike to $750 for a lifetime pass as a driver for users to consider Jellyfin.

**Tags**: `#open-source`, `#media-server`, `#jellyfin`, `#burnout`, `#project-leadership`

---

<a id="item-7"></a>
## [Claude Tag handles 65% of PRs, Anthropic team reveals](https://simonwillison.net/2026/Jul/21/cat-and-thariq/#atom-everything) ⭐️ 8.0/10

In a fireside chat at the AI Engineer World&\#x27;s Fair, Anthropic&\#x27;s Claude Code team revealed that Claude Tag now handles 65% of their product engineering pull requests, and that features are validated internally based on user retention before public release. This provides rare visibility into how a leading AI lab uses its own tools in production, offering benchmarks for developer productivity and insights into best practices for coding agents and collaborative AI integrations. Claude Code features are first shipped to Anthropic employees and only released if they demonstrate user retention; the system prompt was recently reduced by 80% because adding examples is no longer best practice for newer models like Fable 5.

rss · Simon Willison · Jul 21, 12:54

**Background**: Claude Tag is a collaborative Slack integration that allows teams to tag @Claude with tasks, which it then breaks down and executes step-by-step. Claude Code is an agentic coding assistant that can autonomously navigate codebases and implement features. Anthropic&\#x27;s internal culture, called &quot;ant fooding,&quot; emphasizes dogfooding their own products to validate changes before external release.

<details><summary>References</summary>
<ul>
<li><a href="https://support.claude.com/en/articles/15594475-what-is-claude-tag">What is Claude Tag ? | Claude Help Center</a></li>
<li><a href="https://www.anthropic.com/news/introducing-claude-tag">Claude Tag is a new way for teams to work with Claude .</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#Claude Code`, `#Anthropic`, `#AI engineering`, `#developer productivity`, `#tool design`

---

<a id="item-8"></a>
## [AI coding agents slash reverse-engineering costs](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10

Simon Willison observes that AI coding agents have drastically reduced the effort and cost required to reverse-engineer home devices, making automation projects more feasible. This shift reduces the psychological barrier of maintenance, as cheap code means it&\#x27;s less painful to rewrite or discard if APIs change, encouraging more hobbyist and professional automation. Prior to coding agents, reverse-engineering required significant effort and commitment to maintain unstable APIs; agents lower the cost of trial and error, making the ROI positive for many projects.

rss · Simon Willison · Jul 20, 19:24

**Background**: Coding agents are AI-powered tools that can generate, debug, and modify code based on natural language prompts, greatly accelerating software development. Reverse-engineering home devices involves analyzing undocumented protocols to create custom integrations, which was traditionally time-consuming and fragile.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Hybrid_Mac_mini_and_RTX_4090_setup_for_local_AI_coding_agents">Hybrid Mac mini and RTX 4090 setup for local AI coding agents</a></li>
<li><a href="https://hackaday.com/2020/01/21/reverse-engineering-yokis-home-automation-devices/">Reverse Engineering Yokis Home Automation Devices | Hackaday</a></li>

</ul>
</details>

**Tags**: `#reverse-engineering`, `#coding agents`, `#automation`, `#AI-assisted coding`, `#software development`

---

<a id="item-9"></a>
## [Ben Thompson Proposes US Law on AI Training and Distillation](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10

Ben Thompson, a prominent tech analyst, proposed that the US should pass a law to explicitly make training data collection fair use and to prohibit terms of service that forbid model distillation, in order to help US open-weight models compete with Chinese counterparts. This proposal addresses a key hypocrisy in AI development—labs that train on unlicensed data while preventing others from distilling their models—and could reshape copyright policy and the competitive landscape for open models globally. The article also notes Alibaba&\#x27;s release of Qwen 3.8 Max, a 2.4 trillion parameter open-weight model, which Ben Thompson suggests may have been influenced by a speech from Xi Jinping encouraging open source collaboration.

rss · Simon Willison · Jul 20, 17:09

**Background**: Knowledge distillation is a technique where a smaller student model learns from a larger teacher model, often by querying the teacher&\#x27;s API. Currently, many AI companies&\#x27; terms of service prohibit such distillation. Meanwhile, the legal status of using copyrighted data for training remains contested, with some arguing it is fair use. Open-weight models, like those from Meta and Alibaba, make trained parameters available but not the full training process, differing from open-source AI.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation</a></li>
<li><a href="https://creativecommons.org/2023/02/17/fair-use-training-generative-ai/">Fair Use : Training Generative AI - Creative Commons</a></li>
<li><a href="https://www.linkedin.com/pulse/frontier-ai-models-closed-vs-open-weight-source-varadaraj-pandurangan-yrdue">Frontier AI Models: Closed vs Open Weight vs Open Source</a></li>

</ul>
</details>

**Tags**: `#AI`, `#open models`, `#copyright`, `#policy`, `#distillation`

---

<a id="item-10"></a>
## [Critical RCE in Fastjson 1.x without Gadgets](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 8.0/10

Security researcher Kirill Firsov disclosed a critical remote code execution vulnerability in Fastjson versions 1.2.68 through 1.2.83, which can be exploited without enabling autoType or relying on classpath gadgets. This vulnerability affects a widely-used JSON library in Java ecosystems, and since Fastjson 1.x is end-of-life, no official patch will be provided, forcing users to urgently migrate to Fastjson2 or enable SafeMode. The vulnerability works on JDK 8, 17, and 21, and the only mitigations are upgrading to Fastjson2 or setting SafeMode in JVM parameters or configuration files.

telegram · zaihuapd · Jul 20, 14:32

**Background**: Fastjson is a high-performance JSON serialization/deserialization library for Java developed by Alibaba. Its autoType feature, when enabled, allows polymorphic type deserialization but has been a source of vulnerabilities. Traditional RCE exploits require gadget chains—classes present on the classpath that can be chained to execute arbitrary code. This new vulnerability bypasses both autoType and gadget requirements, making it more dangerous.

<details><summary>References</summary>
<ul>
<li><a href="https://topic.alibabacloud.com/a/com-alibaba-fastjson-jsonexception-autotype-is-not-support-_1_27_32615398.html">Com. alibaba. fastjson . JSONException: autoType is not support</a></li>
<li><a href="https://stackoverflow.com/questions/11490844/whats-the-gadget-vulnerability">security - What&#x27;s the &quot; gadget vulnerability &quot;? - Stack Overflow</a></li>
<li><a href="https://github.com/alibaba/fastjson2/blob/main/docs/autotype_en.md">fastjson 2/docs/autotype_en.md at main · alibaba/ fastjson 2 · GitHub</a></li>

</ul>
</details>

**Discussion**: The disclosure has sparked urgent discussions in the security community, with many emphasizing the need to migrate away from Fastjson 1.x as soon as possible.

**Tags**: `#fastjson`, `#security`, `#rce`, `#vulnerability`, `#java`

---

<a id="item-11"></a>
## [Zhipu Completes All-Domestic Chip AI Data Center](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 8.0/10

Zhipu AI has completed construction of a 1-gigawatt data center powered entirely by domestic Chinese chips, and it has partially started operations to support its flagship GLM platform. This milestone demonstrates China&\#x27;s progress in building self-sufficient AI infrastructure despite U.S. export restrictions, potentially reducing reliance on foreign GPUs like NVIDIA&\#x27;s for large-scale AI training. The data center has a power capacity of 1 GW, enough to supply about 750,000 households, and is one of the largest facilities built by a Chinese AI lab, with multiple clusters each containing over 10,000 chips.

telegram · zaihuapd · Jul 20, 15:43

**Background**: Zhipu AI \(now branded as Z.ai\) is a Chinese AI company spun off from Tsinghua University, known for developing the open-source GLM family of large language models. Due to U.S. export controls, Chinese AI firms are under pressure to develop and deploy domestic AI chips \(e.g., Huawei Ascend\) as substitutes for advanced NVIDIA GPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zhipu_AI">Zhipu AI</a></li>
<li><a href="https://pandaily.com/china-chips-supporting-domestic-models-waic-jul2026">2026: China Chips Underpin Domestic AI Models at WAIC... - Pandaily</a></li>

</ul>
</details>

**Tags**: `#AI infrastructure`, `#domestic chips`, `#Chinese AI`, `#data center`, `#Zhipu`

---

<a id="item-12"></a>
## [Google Develops Frozen v2 AI Chip with Gemini Hardcoded](https://www.quiverquant.com/news/Google+Reportedly+Developing+%E2%80%98Frozen+v2%E2%80%99+AI+Chip+to+Boost+Gemini+Efficiency) ⭐️ 8.0/10

Google is reportedly developing a server chip codenamed &quot;Frozen v2&quot; that hardcodes parts of its Gemini AI model into silicon, targeting 6-10x better inference efficiency than current TPUs, with a planned deployment in 2028. If successful, Frozen v2 could dramatically reduce inference cost and power consumption for Gemini, alleviating internal compute shortages and positioning Google as a leader in ultra-efficient AI hardware, though the hardcoded design limits model flexibility. The chip bakes Gemini&\#x27;s neural-network architecture directly into circuitry, reducing data movement and computation overhead. It is meant to complement, not replace, Google&\#x27;s TPUs, and is part of a broader strategy to address internal capacity constraints that limit cloud service offerings.

telegram · zaihuapd · Jul 21, 01:01

**Background**: Current AI chips like TPUs keep the model in memory and shuttle data back and forth, which consumes power and time. Hardcoding model elements into silicon locks the hardware to a specific model architecture, sacrificing flexibility for efficiency. Google&\#x27;s Frozen v2 targets inference workloads, where the model is fixed and speed matters most.

<details><summary>References</summary>
<ul>
<li><a href="https://qz.com/google-gemini-chip-frozen-tpu-efficiency-072026">Google developing Gemini-specific chip called Frozen v 2</a></li>
<li><a href="https://logicity.in/en/blog/google-s-frozen-v2-chip-embeds-gemini-in-hardware-for-6-10x-gains">Google&#x27;s Frozen v 2 chip embeds Gemini in hardware for... | Logicity</a></li>
<li><a href="https://thenextweb.com/news/google-frozen-chip-gemini-silicon">Google Frozen chip : Gemini baked into the silicon</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#Google`, `#Gemini`, `#hardware acceleration`, `#inference efficiency`

---

<a id="item-13"></a>
## [Cloudflare Launches Internal DNS Service for Private Networks](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10

Cloudflare announced the general availability of its Internal DNS service on July 20, 2026, providing authoritative and recursive DNS resolution for enterprise private networks, integrated with Zero Trust and Gateway. This simplifies split-horizon DNS management by unifying public and private DNS on a single platform, extending Zero Trust policies to the DNS layer, which reduces configuration complexity and data drift for enterprise network administrators. The service uses &\#x27;DNS views&\#x27; to control which internal domains are accessible to different users and devices, and supports deployment via API, Terraform, and Cloudflare WAN. Existing Gateway customers can use it at no extra cost.

telegram · zaihuapd · Jul 21, 03:49

**Background**: Split-horizon DNS \(also known as split-view DNS\) allows a DNS server to return different responses based on the source of the query, commonly used to separate internal and external DNS resolution. Traditional implementations require separate servers or software configurations, which can lead to data inconsistency. Cloudflare&\#x27;s Internal DNS leverages its global network to unify these views, simplifying enterprise network management.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Split-horizon_DNS">Split-horizon DNS</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#DNS`, `#Zero Trust`, `#企业网络`, `#私有DNS`

---

<a id="item-14"></a>
## [TSMC to Raise Chip Prices by 5-10% from 2027](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

TSMC has reached agreements with clients to increase chip manufacturing prices by 5% to 10% starting in early 2027, covering both advanced \(sub-7nm\) and mature \(12nm and above\) process nodes. Additional premiums of 10% to 15% will apply to orders exceeding original forecasts for high-performance computing chips. This price hike signals rising costs in semiconductor manufacturing due to overseas fab expansion and advanced node development, potentially increasing chip prices across the tech industry. TSMC&\#x27;s pricing strategy will affect major clients like Apple, Nvidia, and AMD, and may reshape supply chain dynamics. The base price increase applies to all processes from 7nm to 12nm and above, with additional surcharges for high-performance computing orders that exceed forecasted volumes—up to 15% on top of the base increase. TSMC&\#x27;s chairman stated the pricing is strategic and not as abrupt as the memory chip industry&\#x27;s volatile pricing.

telegram · zaihuapd · Jul 21, 09:28

**Background**: TSMC is the world&\#x27;s largest dedicated semiconductor foundry, manufacturing chips for companies like Apple, Nvidia, and AMD. Process nodes like 7nm and 5nm refer to the transistor size, with smaller nodes offering better performance and efficiency. TSMC is ramping up 2nm production by 2025-2027 and expanding fabs overseas in the US, Japan, and Europe, which significantly increases costs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/tsmc-forecasts-2-trillion-market-opportunity-2nm-technology-jha-kc0hc">TSMC Forecasts $2 Trillion Market Opportunity for 2 nm Technology</a></li>
<li><a href="https://grokipedia.com/page/2_nm_process">2 nm process</a></li>

</ul>
</details>

**Tags**: `#TSMC`, `#semiconductor`, `#chip pricing`, `#supply chain`

---