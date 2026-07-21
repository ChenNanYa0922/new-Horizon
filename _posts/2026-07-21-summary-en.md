---
layout: default
title: "Horizon Summary: 2026-07-21 (EN)"
date: 2026-07-21
lang: en
---

> From 43 items, 12 important content pieces were selected

---

1. [Hacker wipes Romania&\#x27;s land registry database](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 9.0/10
2. [Ben Thompson proposes US law to legalize AI data training as fair use](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 9.0/10
3. [Critical No-Gadget RCE in Fastjson 1.x, No Patch Available](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10
4. [Z. AI Completes 1GW Data Center with Domestic Chips](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10
5. [Jane Street&\#x27;s Incremental Library for Incremental Computation](https://github.com/janestreet/incremental) ⭐️ 8.0/10
6. [China&\#x27;s open-weights AI strategy gaining ground](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10
7. [Perfection in Software Is Not Over-Engineering](https://var0.xyz/posts/perfection-is-not-over-engineering.html) ⭐️ 8.0/10
8. [Jellyfin Founder Andrew Steps Down from Project Leadership](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10
9. [SSAO Critique: Corners Don&\#x27;t Look Like That](https://nothings.org/gamedev/ssao/) ⭐️ 8.0/10
10. [Coincidex: Continual Learning Without Replay Buffers](https://www.reddit.com/r/MachineLearning/comments/1v1rmbb/exploring_continual_learning_without_replay/) ⭐️ 8.0/10
11. [Training an Agnostic Harness for LLMs with PyTorch-like Framework](https://www.reddit.com/r/MachineLearning/comments/1v1qbl7/training_a_harness_for_modelagnostic_and/) ⭐️ 8.0/10
12. [Cloudflare Launches Internal DNS Service with Zero Trust Integration](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Hacker wipes Romania&\#x27;s land registry database](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 9.0/10

A hacker wiped Romania&\#x27;s entire land registry database, forcing the National Agency for Cadastre and Land Registration \(ANCPI\) to rebuild its network from scratch and migrate applications to the government cloud. This incident threatens the proof of land ownership for millions of Romanians, potentially causing legal and economic chaos if backups were unavailable. It highlights the vulnerability of critical national infrastructure to cyberattacks and the importance of offline backups. Officials claim to have offline backups and are migrating to the government cloud, with completion expected by July 22. The hacker was identified as Zakaria Mahdjoub from Algeria, which has an extradition treaty with Romania.

hackernews · speckx · Jul 20, 13:28 · [Discussion](https://news.ycombinator.com/item?id=48978605)

**Background**: A land registry database is a critical national system that records property ownership, used for legal transactions, taxation, and land management. Offline backups—copies stored separately from the main system—are essential for recovering data after a catastrophic failure or cyberattack. Cloud migration involves moving applications and data to centralized government-managed data centers.

**Discussion**: Comments note that the agency had offline backups, preventing long-term disruption. Some Romanian users attribute the incident to government corruption in IT contracts, while security firm KELA doxxed the hacker as Zakaria Mahdjoub from Algeria.

**Tags**: `#cybersecurity`, `#critical infrastructure`, `#data breach`, `#Romania`, `#land registry`

---

<a id="item-2"></a>
## [Ben Thompson proposes US law to legalize AI data training as fair use](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 9.0/10

Ben Thompson, a respected tech analyst, proposed that the US pass a law explicitly classifying data collection for AI model training as fair use and prohibiting terms of service that forbid model distillation. Separately, Alibaba released Qwen 3.8 Max, a 2.4 trillion parameter open-weights model, reversing an earlier decision not to release a previous version. This proposal targets the inconsistency where AI labs train on unlicensed data yet block others from distilling their models, and could help US open models better compete with Chinese counterparts. The release of Qwen 3.8 Max as open weights signals a shift toward greater openness in Chinese AI, potentially influenced by policy direction. Qwen 3.8 Max is a 2.4 trillion parameter model, nearly as large as the 2.8 trillion parameter Kimi K3. Ben Thompson suggests that Alibaba&\#x27;s reversal to release it as open weights may have been influenced by a recent speech by Xi Jinping encouraging open source and collaboration.

rss · Simon Willison · Jul 20, 17:09

**Background**: Model distillation is a technique where a smaller &\#x27;student&\#x27; model learns from a larger &\#x27;teacher&\#x27; model by querying its API, effectively transferring knowledge. Many AI companies ban distillation in their terms of service, yet they themselves train on data scraped from the web without explicit permission, a practice that may not be clearly legal under current copyright law. Fair use is a legal doctrine that allows limited use of copyrighted material without permission; making explicit that training data collection is fair use would protect AI companies from lawsuits.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://www.datacamp.com/blog/distillation-llm">LLM Distillation Explained: Applications, Implementation &amp; More</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#distillation`, `#fair use`, `#Chinese AI`, `#open models`

---

<a id="item-3"></a>
## [Critical No-Gadget RCE in Fastjson 1.x, No Patch Available](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10

A remote code execution vulnerability affecting Fastjson versions 1.2.68 to 1.2.83 has been disclosed, requiring no gadget or autoType support to exploit. The library reached end-of-life in October 2024, so no security patch will be provided. This vulnerability is critical because Fastjson is widely used in Java applications for JSON parsing, and the exploit works on JDK 8, 17, and 21 without special conditions. Affected users must urgently migrate to Fastjson2 or enable SafeMode to prevent potential remote code execution attacks. The vulnerability does not require autoType support or classpath gadgets, making it more dangerous than previous Fastjson flaws. The only mitigations are upgrading to Fastjson2 or enabling SafeMode, which has been available since version 1.2.68 and completely disables autoType.

telegram · zaihuapd · Jul 20, 14:32

**Background**: Fastjson is a popular JSON parsing library for Java developed by Alibaba, known for its performance but also historically prone to deserialization vulnerabilities. AutoType support, when enabled, allows restoring type information during deserialization, which can be exploited if not carefully restricted. SafeMode was introduced in version 1.2.68 as a security feature to completely disable AutoType, but users must opt in manually. The disclosed vulnerability bypasses previous restrictions and works even without AutoType, making it especially severe.

<details><summary>References</summary>
<ul>
<li><a href="https://nsfocusglobal.com/fastjson-1-2-62-and-earlier-remote-code-execution-vulnerability-threat-alert/">Fastjson 1.2.62 and Earlier Remote Code Execution Vulnerability ...</a></li>
<li><a href="https://github.com/alibaba/fastjson/wiki/fastjson_safemode_en">fastjson _ safemode _en · alibaba/ fastjson Wiki · GitHub</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#Fastjson`, `#RCE`, `#Java`

---

<a id="item-4"></a>
## [Z. AI Completes 1GW Data Center with Domestic Chips](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10

Z. AI \(formerly Zhipu AI\) has completed construction of a 1-gigawatt data center that uses exclusively domestically produced AI chips, and it has begun partial operation. The facility will train the company&\#x27;s GLM large language model. This marks a significant milestone for China&\#x27;s AI infrastructure self-sufficiency, demonstrating the ability to build large-scale AI training facilities without relying on restricted NVIDIA chips. It reduces dependence on foreign technology and advances China&\#x27;s goal of technological independence. The data center has a power capacity of 1 GW, equivalent to powering about 750,000 homes simultaneously. Z. AI operates multiple computing clusters each with over 10,000 chips, and this is one of the largest facilities built by a Chinese AI lab.

telegram · zaihuapd · Jul 20, 15:43

**Background**: Due to US export restrictions, China&\#x27;s AI labs have faced difficulty acquiring high-end GPUs like NVIDIA&\#x27;s H100. Z. AI \(formerly Zhipu AI\) is a leading Chinese AI company known for its open-source GLM model series, released under the MIT License in July 2025. This data center, built entirely with domestic chips, is a critical step in Beijing&\#x27;s push for chip self-sufficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai">Z. AI Completes Giant Data Center With Chinese Chips to... - Bloomberg</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z. ai - Wikipedia</a></li>
<li><a href="https://news.aibase.com/news/29736">Zhipu AI Launches 1GW Domestic AI Computing Center and...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#data center`, `#domestic chips`, `#self-sufficiency`, `#infrastructure`

---

<a id="item-5"></a>
## [Jane Street&\#x27;s Incremental Library for Incremental Computation](https://github.com/janestreet/incremental) ⭐️ 8.0/10

Jane Street has open-sourced Incremental, a library that implements incremental computation, enabling efficient recomputation of only the outputs that depend on changed data. This library makes high-performance incremental computation accessible to a wider audience, with potential applications in reactive UIs, build systems, and data processing pipelines. Incremental is written in OCaml and draws on decades of functional programming research; it is conceptually similar to reactive signals in JavaScript frameworks like Vue and SolidJS.

hackernews · handfuloflight · Jul 21, 03:50 · [Discussion](https://news.ycombinator.com/item?id=48987822)

**Background**: Incremental computing is a technique that updates the output of a computation when only a small part of the input changes, avoiding a full recomputation. This approach is used in build systems \(e.g., Make\) and spreadsheet recalculations. The Incremental library by Jane Street provides a general-purpose mechanism for this in OCaml.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Incremental_computation">Incremental computation</a></li>
<li><a href="https://angular.dev/essentials/signals">Reactivity with signals • Angular</a></li>

</ul>
</details>

**Discussion**: Commenters noted the similarity to reactive signals in modern JS frameworks and discussed related systems like Differential Dataflow and DBSP. Some recalled historical uses in finance, such as Goldman Sachs&\#x27; approach to instrument pricing.

**Tags**: `#incremental-computation`, `#functional-programming`, `#reactive-programming`, `#jane-street`

---

<a id="item-6"></a>
## [China&\#x27;s open-weights AI strategy gaining ground](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10

A widely-discussed article argues that China&\#x27;s open-weights AI models are outperforming US proprietary models, citing adoption by a majority of startups. This shift could reshape the global AI landscape, favoring open ecosystems over locked-down proprietary systems and potentially accelerating innovation in China. The article references claims that 80% of startups use Chinese models, though some commenters question this statistic, noting their own experience with US models.

hackernews · benwerd · Jul 20, 14:21 · [Discussion](https://news.ycombinator.com/item?id=48979269)

**Background**: Open-weight AI models make their trained parameters publicly available, allowing anyone to download and run them. This contrasts with proprietary models like OpenAI&\#x27;s GPT-4, which are only accessible via API. The debate over open vs. closed AI ecosystems involves trade-offs between transparency, innovation speed, and control.

<details><summary>References</summary>
<ul>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://center-forward.org/basic/emerging-ai-open-vs-closed-source/">Emerging AI: Open vs Closed Source - Center Forward</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some agreed that open models historically win, citing examples like Linux. Others were skeptical of the article&\#x27;s claims, noting that enterprises prioritize data retention and existing vendor relationships. One commenter pointed out the article&\#x27;s similarity to Palantir CEO&\#x27;s statements, questioning neutrality.

**Tags**: `#AI`, `#open-source`, `#China`, `#LLMs`, `#technology strategy`

---

<a id="item-7"></a>
## [Perfection in Software Is Not Over-Engineering](https://var0.xyz/posts/perfection-is-not-over-engineering.html) ⭐️ 8.0/10

An article by var0.xyz argues that perfectionism in software engineering should not be conflated with over-engineering, emphasizing the importance of solving the right problem and resisting a toxic product mindset. This challenges common anti-perfectionism tropes in software development, encouraging engineers to take pride in their work without fear of being labeled over-engineers; the article has sparked substantial community discussion. The article stresses that true over-engineering is solving the wrong problem, not striving for perfection, and warns that a product mindset can become toxic when it ignores quality and user needs.

hackernews · var0xyz · Jul 20, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48979120)

**Background**: Over-engineering is often criticized in software development, with principles like YAGNI \(&\#x27;You Ain&\#x27;t Gonna Need It&\#x27;\) discouraging unnecessary complexity. However, the article distinguishes between over-engineering and careful, thoughtful design that considers all constraints, arguing that perfectionism, when focused on the right problem, is not over-engineering.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Overengineering">Overengineering - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Technical_debt">Technical debt</a></li>
<li><a href="https://medium.com/agileinsider/what-is-the-product-mindset-af06e01adf70">What is the Product Mindset?. Learning to navigate an uncertain world | by Chris Butler | Agile Insider | Medium</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with the article, with some noting that requirements are often implicit and that over-engineering can arise from optimizing for nonexistent constraints. There is also discussion about the toxicity of the product mindset and the importance of engineers understanding user needs.

**Tags**: `#software engineering`, `#technical debt`, `#product mindset`, `#code quality`, `#engineering culture`

---

<a id="item-8"></a>
## [Jellyfin Founder Andrew Steps Down from Project Leadership](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10

Jellyfin founder Andrew \(cube00\) announced his departure from the project, citing severe burnout and health risks. He stated he could no longer meet the demands of the role. Andrew&\#x27;s departure highlights the sustainability challenges of open-source projects and the widespread issue of maintainer burnout, especially amid Plex&\#x27;s price increase that drives users to free alternatives like Jellyfin. It raises questions about project governance and future development. Plex recently raised its lifetime Plex Pass price to $750, prompting users to seek self-hosted alternatives. In his departure note, Andrew emphasized that FLOSS works and is in demand, but acknowledged severe burnout among maintainers.

hackernews · swat535 · Jul 20, 23:15 · [Discussion](https://news.ycombinator.com/item?id=48986091)

**Background**: Jellyfin is a free open-source media server software, forked from Emby in 2018 as an alternative to proprietary solutions like Plex. It allows users to host their own media libraries and stream to various devices without subscription fees. The project is maintained by volunteers, and leadership changes can impact its stability and future direction.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://github.com/jellyfin/jellyfin">GitHub - jellyfin/jellyfin: The Free Software Media System - Server Backend &amp; API · GitHub</a></li>

</ul>
</details>

**Discussion**: Community comments are largely positive, with many users thanking Andrew and contributors for their work and praising Jellyfin as an excellent Plex alternative. Some note that Plex&\#x27;s price increase motivated them to explore open-source options. Several comments also highlight the broader issue of maintainer burnout in the open-source ecosystem.

**Tags**: `#jellyfin`, `#plex`, `#open-source`, `#media-server`, `#leadership`

---

<a id="item-9"></a>
## [SSAO Critique: Corners Don&\#x27;t Look Like That](https://nothings.org/gamedev/ssao/) ⭐️ 8.0/10

The author of the 2012 article &\#x27;Corners Don&\#x27;t Look Like That&\#x27; argues that screen-space ambient occlusion \(SSAO\) produces unrealistic darkening in corners, contrasting with real-world ambient occlusion behavior. This critique sparked long-running debate in game development about whether perfect realism or visual appeal should take priority when using real-time rendering techniques like SSAO, influencing how developers balance performance and visual quality. SSAO was introduced by Crytek in 2007 with Crysis and became widely used due to its low cost, but the article highlights that its assumption of uniform ambient lighting leads to incorrect corner darkening, especially in scenes with strong directional lights.

hackernews · firephox · Jul 20, 15:07 · [Discussion](https://news.ycombinator.com/item?id=48979931)

**Background**: Ambient occlusion \(AO\) is a shading technique that approximates how much ambient light reaches a point, darkening areas like corners and crevices. Screen-space ambient occlusion \(SSAO\) is a real-time approximation that uses depth buffers to compute occlusion, trading accuracy for performance. SSAO has been a staple in games since the late 2000s, but its limitations have led to newer methods like HBAO and FidelityFX CACAO.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Screen_space_ambient_occlusion">Screen space ambient occlusion - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ambient_occlusion">Ambient occlusion - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Comments show mixed sentiment: some agree realism isn&\#x27;t always the goal and SSAO can still look good when dialed back, while others criticize its unrealistic appearance and note improvements like CACAO. There&\#x27;s consensus that SSAO was a practical compromise for its time, but modern solutions are better.

**Tags**: `#game development`, `#rendering`, `#ambient occlusion`, `#SSAO`, `#computer graphics`

---

<a id="item-10"></a>
## [Coincidex: Continual Learning Without Replay Buffers](https://www.reddit.com/r/MachineLearning/comments/1v1rmbb/exploring_continual_learning_without_replay/) ⭐️ 8.0/10

The authors introduce Coincidex, an open-source framework that uses dynamic task-similarity routing to enable continual learning without relying on replay buffers or hand-tuned task masks. This approach addresses critical memory and privacy limitations of replay buffers, offering a lightweight alternative for sequential task learning in resource-constrained or privacy-sensitive environments. Coincidex operates as a single layer swap that computes an online task-similarity matrix to route data; it performs well on clean task boundaries but struggles with highly chaotic, long-tail task sequences with large distribution shifts.

reddit · r/MachineLearning · /u/theawkwardbong · Jul 20, 17:13

**Background**: Continual learning aims to learn from a stream of tasks without forgetting previous knowledge, a challenge known as catastrophic forgetting. Traditional solutions like replay buffers store past data to reinforce learning, but they introduce memory overhead and privacy concerns. Task-similarity routing is a technique that dynamically directs inputs to appropriate model components based on learned similarity measures, potentially bypassing the need for stored examples.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@dhruvansh26/early-results-for-task-based-model-routing-using-sae-features-b3a839285bde">Early Results for Task -Based Model Routing using SAE... | Medium</a></li>

</ul>
</details>

**Tags**: `#continual learning`, `#catastrophic forgetting`, `#task-similarity routing`, `#replay buffer`, `#open-source`

---

<a id="item-11"></a>
## [Training an Agnostic Harness for LLMs with PyTorch-like Framework](https://www.reddit.com/r/MachineLearning/comments/1v1qbl7/training_a_harness_for_modelagnostic_and/) ⭐️ 8.0/10

The project introduces a PyTorch-like training framework for a harness that, once trained, can improve the capabilities of any large language model \(LLM\) across different task environments without modifying the LLM itself. The author demonstrates results on Terminal-Bench 2.0 and SWE-Bench tasks, showing that the trained harness transfers to unseen task environments. This approach could significantly reduce the cost and effort of adapting LLMs to new tasks and environments, as a single trained harness works across multiple models and tasks. It aligns with the trend toward reusable infrastructure rather than model-centric retraining. The framework uses a &\#x27;StrictPareto\(\)&\#x27; criterion and &\#x27;GreedyMonotonic\(\)&\#x27; optimizer to evaluate and improve harness behavior through agent-driven self-improvement cycles. The harness is trained with a frozen task LLM and then can be swapped to any other LLM via an OpenAI-compatible API.

reddit · r/MachineLearning · /u/Megadragon9 · Jul 20, 16:26

**Background**: An agent harness is a software layer that sits between an LLM and its environment, managing tool calls, memory, and planning without altering the model&\#x27;s weights. Traditional approaches require fine-tuning the LLM for each new task, which is expensive and not portable. This project instead trains the harness itself to be model- and task-agnostic, drawing inspiration from reinforcement learning and Pareto optimization.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/workofart/harness-training">GitHub - workofart/harness-training: Train a harness to improve its...</a></li>
<li><a href="https://parallel.ai/articles/what-is-an-agent-harness">What is an agent harness in the context of large-language models? | Parallel Web Systems | Infrastructure for intelligence on the web</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#training framework`, `#model-agnostic`, `#harness training`, `#PyTorch`

---

<a id="item-12"></a>
## [Cloudflare Launches Internal DNS Service with Zero Trust Integration](https://blog.cloudflare.com/internal-dns/) ⭐️ 8.0/10

Cloudflare has announced the general availability of its Internal DNS service, which provides authoritative and recursive DNS resolution for enterprise private networks, unified with public DNS and Zero Trust policies on a single global network. This simplifies split-horizon DNS management by eliminating data drift between separate public and private DNS systems, and extends Zero Trust security policies to the DNS resolution layer, benefiting enterprise network security and operations. Existing Cloudflare Gateway customers can enable Internal DNS at no additional cost. The service supports configuration via API, Terraform, and Cloudflare WAN, and allows administrators to set resolver policies that determine which internal DNS views different users and devices can access.

telegram · zaihuapd · Jul 21, 03:49

**Background**: Traditional split-horizon DNS involves providing different DNS responses based on the source address of the request, often requiring separate servers or complex configurations. Cloudflare&\#x27;s Internal DNS integrates this into a single platform along with its Zero Trust network access and secure web gateway offerings, reducing operational overhead and security gaps.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Split-horizon_DNS">Split-horizon DNS</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#DNS`, `#Zero Trust`, `#Enterprise Networking`, `#Network Security`

---