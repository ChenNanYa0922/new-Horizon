---
layout: default
title: "Horizon Summary: 2026-07-21 (EN)"
date: 2026-07-21
lang: en
---

> From 44 items, 14 important content pieces were selected

---

1. [AI Outpaces Human Mathematicians in Finding Counterexamples](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 9.0/10
2. [Critical RCE in Fastjson 1.x without Gadget \(Versions 1.2.68-1.2.83\)](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10
3. [Zhipu AI Completes 1 GW Data Center with All Domestic Chips](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10
4. [Qwen-Image-3.0: High-Detail, Long-Context Image Generation](https://qwen.ai/blog?id=qwen-image-3.0) ⭐️ 8.0/10
5. [Jane Street Releases Incremental Library for Incremental Computation](https://github.com/janestreet/incremental) ⭐️ 8.0/10
6. [Agent Swarms Build SQLite at 1000 Commits/Second](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10
7. [China&\#x27;s open-weights AI strategy is winning](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10
8. [Jellyfin founder Andrew steps down due to burnout](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10
9. [Hacker wipes Romania&\#x27;s land registry database](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 8.0/10
10. [AI Coding Agents Make Reverse-Engineering Cheap](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10
11. [Ben Thompson Proposes US Fair Use Law for AI](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10
12. [EU May Trade Biometric Data for US Visa-Free Travel](https://edri.org/our-work/the-eu-is-about-to-sell-our-most-sensitive-data-to-the-us-for-visa-free-travel/) ⭐️ 8.0/10
13. [EU Fines AliExpress €550 Million for Counterfeit Goods](https://thebalkanchronicle.com/en/business/eu-fines-aliexpress-550-million-counterfeit-goods-2026/) ⭐️ 8.0/10
14. [TSMC to raise chip prices 5-10% from 2027](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [AI Outpaces Human Mathematicians in Finding Counterexamples](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 9.0/10

AI systems have begun discovering counterexamples to mathematical conjectures faster than human mathematicians, marking a milestone in AI-assisted mathematics. This shift could save researchers years of wasted effort on false conjectures and transform mathematical practice, making AI a creative partner in discovery. The AI uses automated theorem proving and machine learning to explore large solution spaces, but it is not yet capable of fully replacing human intuition and creative reasoning.

hackernews · artninja1988 · Jul 20, 19:03 · [Discussion](https://news.ycombinator.com/item?id=48983382)

**Background**: Automated theorem proving \(ATP\) is a subfield of computer science that uses programs to prove mathematical theorems automatically. Counterexamples are crucial in mathematics because they refute conjectures and help refine definitions, as famously discussed in Imre Lakatos&\#x27;s book &\#x27;Proofs and Refutations&\#x27;. Recent advances in AI have enabled systems to actively generate counterexamples, augmenting human research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving</a></li>
<li><a href="https://www.linkedin.com/pulse/ai-challenges-foundational-conjecture-pure-mathematics-odwec">AI Challenges a Foundational Conjecture in Pure Mathematics ...</a></li>
<li><a href="https://haltmal.com/ai-literacy-responsible-use/human-mathematicians-are-being-outcounterexampled/">Human Mathematicians Are Being Outcounterexampled - Halt Mal</a></li>

</ul>
</details>

**Discussion**: The community largely views this as a positive development, noting it prevents wasted effort and highlights the importance of counterexamples. Some commenters shared anecdotes, such as Yitang Zhang&\#x27;s career being derailed by an incorrect corollary, underscoring the value of AI in detecting errors early.

**Tags**: `#AI`, `#mathematics`, `#automated theorem proving`, `#counterexamples`, `#machine learning`

---

<a id="item-2"></a>
## [Critical RCE in Fastjson 1.x without Gadget \(Versions 1.2.68-1.2.83\)](https://x.com/k_firsov/status/2078872293745570032) ⭐️ 9.0/10

Security researcher Kirill Firsov disclosed a high-severity remote code execution vulnerability in Fastjson 1.x versions 1.2.68 to 1.2.83. The exploit does not require enabling autoType or any classpath gadget and works on JDK 8, 17, and 21. This vulnerability is critical because Fastjson 1.x is widely used in Java applications, especially in China, and no official patch will be released since maintenance ended in October 2024. Users must upgrade to Fastjson2 or enable SafeMode to mitigate the risk. The vulnerability affects Fastjson 1.2.68 through 1.2.83 and does not rely on any known gadget chains, making it more dangerous as it bypasses typical defenses. The only official mitigation proposed by the researcher is migrating to Fastjson2 or enabling SafeMode, which completely disables autoType.

telegram · zaihuapd · Jul 20, 14:32

**Background**: Fastjson is a popular JSON library for Java developed by Alibaba. In Java deserialization, a &\#x27;gadget chain&\#x27; is a sequence of classes that, when deserialized, can execute arbitrary code. Previous Fastjson vulnerabilities often required specific gadgets present in the classpath. SafeMode, introduced in Fastjson 1.2.68, disables autoType completely to prevent deserialization attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://unicorn-dev.medium.com/gadget-chains-in-java-how-unsafe-deserialization-leads-to-rce-88b17409c7aa">Gadget chains in Java : how unsafe deserialization leads to... | Medium</a></li>
<li><a href="https://github.com/alibaba/fastjson/wiki/fastjson_safemode">fastjson_safemode · alibaba/fastjson Wiki</a></li>

</ul>
</details>

**Tags**: `#fastjson`, `#rce`, `#vulnerability`, `#security`, `#java`

---

<a id="item-3"></a>
## [Zhipu AI Completes 1 GW Data Center with All Domestic Chips](https://www.bloomberg.com/news/articles/2026-07-20/z-ai-completes-giant-data-center-with-chinese-chips-to-train-ai) ⭐️ 9.0/10

Zhipu AI has completed a massive 1-gigawatt data center powered entirely by domestically produced chips and has begun partial operations to train its GLM large language model. This marks a major milestone in China&\#x27;s push for semiconductor self-sufficiency, demonstrating that domestic chips can support large-scale AI training infrastructure. The data center has a capacity of 1 GW, enough to power about 750,000 homes. Zhipu operates multiple computing clusters, each with over 10,000 chips.

telegram · zaihuapd · Jul 20, 15:43

**Background**: Zhipu AI is a Beijing-based company that developed the GLM family of open-source large language models. Due to export restrictions, Chinese AI firms cannot purchase NVIDIA&\#x27;s latest GPUs and are increasingly adopting domestic alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z. ai - Wikipedia</a></li>
<li><a href="https://pandaily.com/china-domestic-ai-compute-revolution-tipping-point-jul2026">China &#x27;s Domestic AI Compute Revolution Reaches... - Pandaily</a></li>
<li><a href="https://wccftech.com/chinas-domestic-chip-shipments-to-surge-to-5-million-unites-this-year-says-report/">China &#x27;s Domestic Chip Shipments To Surge To 5 Million Unites This...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#data center`, `#domestic chips`, `#Zhipu`, `#infrastructure`

---

<a id="item-4"></a>
## [Qwen-Image-3.0: High-Detail, Long-Context Image Generation](https://qwen.ai/blog?id=qwen-image-3.0) ⭐️ 8.0/10

Qwen-Image-3.0 is a new image generation model that supports up to 4.5k token input, enabling generation of high-density content like nine-grid info-graphics, newspapers, and multilayered interfaces. It also improves detail accuracy for small text \(10 px\), formulas, and micro-textures, and supports 12 languages and over 100 art styles. This release shifts image generation from purely aesthetic to practical, making it useful for real-world tasks like creating educational materials, UI mockups, and multilingual content. It addresses key limitations of previous models in handling long, complex prompts and fine details. The model can generate content with up to 4.5k tokens in a single run, including multi-panel layouts and text-heavy designs. It also supports web-connected generation to produce more authentic images based on real-world information.

hackernews · ilreb · Jul 21, 08:44 · [Discussion](https://news.ycombinator.com/item?id=48989701)

**Background**: Qwen is a family of large language and multimodal models developed by Alibaba Cloud. Previous image generation models often struggled with rendering long text passages and maintaining consistency across multiple images. Qwen-Image-3.0 builds on these models with enhancements in detail and context handling.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>
<li><a href="https://qwen.ai/">Qwen Studio</a></li>
<li><a href="https://huggingface.co/Qwen">Qwen (Qwen)</a></li>

</ul>
</details>

**Discussion**: Community comments were mixed: some expressed skepticism about using such models for online shopping or real estate, noting that AI tends to flatter products. Others pointed out technical issues, such as broken Arabic text in the hero image and a mobile UI bug. Additionally, meta keywords contained many NSFW references, which drew attention.

**Tags**: `#AI`, `#image generation`, `#Qwen`, `#multimodal`, `#Qwen-Image`

---

<a id="item-5"></a>
## [Jane Street Releases Incremental Library for Incremental Computation](https://github.com/janestreet/incremental) ⭐️ 8.0/10

Jane Street has open-sourced Incremental, a library for incremental computation that efficiently recomputes only the affected parts of a computation graph when inputs change. Incremental computation is a foundational technique for efficient updates in reactive systems, and a library like Incremental can improve performance in applications ranging from UI frameworks to financial models. The library is written in OCaml and implements a DAG-based incremental computation model. It automatically tracks dependencies and updates only the necessary computations, similar to signals in JavaScript UI frameworks and systems like Differential Dataflow.

hackernews · handfuloflight · Jul 21, 03:50 · [Discussion](https://news.ycombinator.com/item?id=48987822)

**Background**: Incremental computation is a technique that avoids full recomputation by updating only outputs affected by a change, commonly used in spreadsheets and build systems. Jane Street, a quantitative trading firm, is a prominent user of OCaml and has built many internal libraries that they occasionally open-source. Their Incremental library provides a principled way to manage state updates in reactive programs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Incremental_computation">Incremental computation</a></li>
<li><a href="https://github.com/TimelyDataflow/differential-dataflow">GitHub - TimelyDataflow/differential-dataflow: An implementation of differential dataflow using timely dataflow on Rust. · GitHub</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights comparisons to JavaScript signals \(Vue, SolidJS\), build systems, and Differential Dataflow. Commenters note the library&\#x27;s similarity to earlier systems like Javelin in Clojure and mention historical implementations at Goldman Sachs. Overall sentiment is positive, with users appreciating the well-engineered approach.

**Tags**: `#incremental computation`, `#reactive programming`, `#Jane Street`, `#libraries`, `#dataflow`

---

<a id="item-6"></a>
## [Agent Swarms Build SQLite at 1000 Commits/Second](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 8.0/10

Cursor demonstrated that a swarm of AI agents, using a custom-built version control system, built SQLite from scratch in Rust solely from its documentation, achieving a peak rate of 1000 commits per second. This experiment pushes the boundaries of autonomous AI coding, suggesting that large-scale agent coordination can tackle complex engineering tasks, though it raises questions about whether success stems from model memorization or genuine reasoning. The custom VCS was built from scratch to handle the high throughput of up to 1000 commits per second, and it also serves as a coordination layer where collisions become visible, enabling more sophisticated agent coordination mechanisms.

hackernews · jlaneve · Jul 20, 18:06 · [Discussion](https://news.ycombinator.com/item?id=48982535)

**Background**: Large language models \(LLMs\) like GPT-4 can either memorize training data or reason about novel problems. Agent swarms involve multiple LLM-powered agents collaborating on a task, which introduces challenges in coordination and version control. Version control systems \(VCS\) track changes and enable collaboration, but traditional VCS like Git are not designed for the high commit rates of agent swarms.

<details><summary>References</summary>
<ul>
<li><a href="https://cursor.com/blog/agent-swarm-model-economics">Agent swarms and the new model economics · Cursor</a></li>
<li><a href="https://techxplore.com/news/2025-11-ai-brain-reveals-memory.html">Mapping AI&#x27;s brain reveals memory and reasoning are not located in the same place</a></li>
<li><a href="https://medium.com/@sahysahy/how-i-built-version-control-for-ai-agents-1f6b69abc860">How I Built Version-Control For AI Agents | by Shay Livni | Medium</a></li>

</ul>
</details>

**Discussion**: Commenters expressed excitement about the future potential of agent swarms, but also raised critical concerns: the SQLite source code likely appears in the training data, and the Rust rewrite \(Turso&\#x27;s\) may also be memorized, casting doubt on whether the swarm demonstrated genuine novel reasoning rather than recall.

**Tags**: `#agent swarms`, `#AI coding`, `#LLM capabilities`, `#software engineering`, `#version control`

---

<a id="item-7"></a>
## [China&\#x27;s open-weights AI strategy is winning](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 8.0/10

An article argues that China&\#x27;s open-weights AI models, such as Qwen and DeepSeek, are outperforming US proprietary models, citing that 80% of startups are using Chinese models and historical precedents where open or low-end solutions defeated proprietary ones. This challenges US dominance in AI and suggests that open strategies may be more effective than proprietary ones, potentially reshaping the global AI landscape and influencing national AI strategies. The article draws parallels to past tech market shifts \(e.g., PCs vs. mainframes, Linux vs. UNIX\) and notes that open-weights models allow customization but are not fully open-source. Community comments express skepticism about the 80% startup figure and question the success of open-weights models like Llama for Meta.

hackernews · benwerd · Jul 20, 14:21 · [Discussion](https://news.ycombinator.com/item?id=48979269)

**Background**: Open-weights AI models release their trained parameters publicly, enabling users to fine-tune and deploy them, but the training code and data may not be fully open. This contrasts with fully open-source models, which provide complete access to code and data, and proprietary models, which are closed. Major open-weights models include Llama, Qwen, and DeepSeek.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@aruna.kolluru/exploring-the-world-of-open-source-and-open-weights-ai-aa09707b69fc">Exploring the World of Open Source and Open Weights AI | Medium</a></li>
<li><a href="https://llm-stats.com/">AI Leaderboard 2026: Compare &amp; Rank 300+ Top AI Models by...</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some agree that open-weights will win once hardware costs drop, while others are skeptical of the 80% startup claim and argue that enterprises prioritize data privacy over openness. There is also doubt that Llama&\#x27;s success benefits Meta directly, and concerns that the article may reflect biased views from Palantir&\#x27;s CEO.

**Tags**: `#AI`, `#open-source`, `#China`, `#geopolitics`, `#large language models`

---

<a id="item-8"></a>
## [Jellyfin founder Andrew steps down due to burnout](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 8.0/10

Andrew, the founder of the open-source media server Jellyfin, announced his departure from the project leadership due to severe burnout, emphasizing the need for sustainable FLOSS maintenance. This event highlights the ongoing challenge of burnout in open-source communities, where maintainers often bear heavy unpaid workloads. It underscores the importance of sustainable practices and community support for long-term project health. Andrew cited mental health risks and inability to perform duties as reasons, but noted that the project will continue under new leadership. The transition appears peaceful, with no forks or conflicts reported.

hackernews · swat535 · Jul 20, 23:15 · [Discussion](https://news.ycombinator.com/item?id=48986091)

**Background**: Jellyfin is a free, open-source media server that allows users to manage and stream personal media collections, serving as an alternative to proprietary solutions like Plex and Emby. FLOSS stands for Free/Libre and Open Source Software, a model that relies on volunteer contributions but often faces sustainability challenges.

<details><summary>References</summary>
<ul>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://en.wikipedia.org/wiki/Free_and_open-source_software">Free and open-source software - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments expressed gratitude for Andrew&\#x27;s contributions and empathy for his burnout. Users shared positive experiences with Jellyfin, while some highlighted the broader issue of FLOSS maintainer burnout, citing similar departures in other projects.

**Tags**: `#open-source`, `#Jellyfin`, `#burnout`, `#FLOSS`, `#community`

---

<a id="item-9"></a>
## [Hacker wipes Romania&\#x27;s land registry database](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 8.0/10

A hacker successfully wiped Romania&\#x27;s entire land registry database, paralyzing real-estate transactions and halting property registrations nationwide. Officials are now rebuilding from offline backups and migrating systems to the government cloud. This attack on critical national infrastructure threatens property rights and the real-estate market, potentially causing long-term societal disruption. It underscores the vulnerability of government systems to ransomware and the importance of offline backups and secure cloud migration. The hacker, identified as Zakaria Mahdjoub from Algeria, allegedly wiped the database after a failed extortion attempt. Romania&\#x27;s Special Telecommunications Service \(STS\) is coordinating the migration to the Government Cloud, expected to complete by July 22.

hackernews · speckx · Jul 20, 13:28 · [Discussion](https://news.ycombinator.com/item?id=48978605)

**Background**: The Romanian Land Registry \(ANCPI\) maintains official records of property ownership, boundaries, and encumbrances, which are essential for legal transactions and mortgage registration. A database wipe could cause chaos in proving ownership, but offline backups appear to have been preserved. The incident echoes a previous South Korean government data center fire that destroyed 900TB of data without external backups.

<details><summary>References</summary>
<ul>
<li><a href="https://cybernews.com/security/hacker-deletes-romanian-land-registry-database/">Hacker deletes country’s entire land registry database ... | Cybernews</a></li>
<li><a href="https://romanianlawoffice.com/land-registry-romania.htm">Romanian Land Registry , Land Book in Romania , Register Title in...</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the availability of offline backups likely prevented a major societal crisis, but some attributed the breach to government corruption in IT contracting. The hacker&\#x27;s identification and the existence of an extradition treaty between Romania and Algeria were also discussed, raising questions about potential prosecution.

**Tags**: `#cybersecurity`, `#critical infrastructure`, `#data breach`, `#hacking`, `#Romania`

---

<a id="item-10"></a>
## [AI Coding Agents Make Reverse-Engineering Cheap](https://simonwillison.net/2026/Jul/20/cheap-reverse-engineering/#atom-everything) ⭐️ 8.0/10

Coding agents have significantly reduced the cost and effort of reverse-engineering and automating home devices, lowering the barrier to entry for hobbyists and developers. This shift changes the ROI calculus for reverse-engineering, making it viable for small projects and reducing the psychological burden of potential future maintenance. The key change is that even if the reverse-engineered API breaks, the low cost of rewriting code with agents makes starting over acceptable.

rss · Simon Willison · Jul 20, 19:24

**Background**: Coding agents are AI-powered tools that assist in writing code, often by generating scripts from natural language descriptions. Reverse-engineering home devices typically involves intercepting and decoding communication protocols to control them programmatically, which was previously time-consuming and fragile.

<details><summary>References</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/components-of-a-coding-agent">Components of A Coding Agent - by Sebastian Raschka, PhD</a></li>
<li><a href="https://packages.ecosyste.ms/registries/npmjs.org/packages/agents-reverse-engineer">agents - reverse - engineer | npmjs.org | Ecosyste.ms: Packages</a></li>

</ul>
</details>

**Tags**: `#reverse-engineering`, `#AI agents`, `#home automation`, `#software economics`

---

<a id="item-11"></a>
## [Ben Thompson Proposes US Fair Use Law for AI](https://simonwillison.net/2026/Jul/20/afraid-of-chinese-models/#atom-everything) ⭐️ 8.0/10

Ben Thompson proposed US legislation to make training data fair use and prohibit distillation bans, aiming to help US open models compete with Chinese models. Additionally, Alibaba released Qwen 3.8 Max, a 2.4T parameter model, as open weights. This proposal directly confronts the contradiction of labs banning distillation while training on unlicensed data, and could level the playing field for US open models. Meanwhile, China&\#x27;s release of Qwen 3.8 Max under open weights indicates a policy shift toward open-source collaboration. The proposed law would apply to U.S. companies and make distillation bans unenforceable. Distillation is technically difficult to prevent. Qwen 3.8 Max features 2.4 trillion parameters, comparable to Kimi K3&\#x27;s 2.8T. Xi Jinping recently encouraged open source and sharing.

rss · Simon Willison · Jul 20, 17:09

**Background**: Fair use is a legal doctrine that allows limited use of copyrighted material without permission; its application to AI training data is currently disputed in courts. Model distillation is a technique where a smaller &\#x27;student&\#x27; model learns from a larger &\#x27;teacher&\#x27; model&\#x27;s outputs. Open weight models release trained parameters but not the full training code or data, limiting transparency.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@creed_1732/5-powerful-ways-ai-model-distillation-is-revolutionizing-affordable-machine-learning-and-why-its-c239cc039b63">5 Powerful Ways AI Model Distillation Is Revolutionizing... | Medium</a></li>
<li><a href="https://www.jdsupra.com/legalnews/the-art-and-legality-of-imitation-4462776/">The Art (and Legality) of Imitation: Navigating the Murky Waters of Fair ...</a></li>
<li><a href="https://www.linkedin.com/pulse/frontier-ai-models-closed-vs-open-weight-source-varadaraj-pandurangan-yrdue">Frontier AI Models: Closed vs Open Weight vs Open Source</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#distillation`, `#open source`, `#copyright`, `#fair use`

---

<a id="item-12"></a>
## [EU May Trade Biometric Data for US Visa-Free Travel](https://edri.org/our-work/the-eu-is-about-to-sell-our-most-sensitive-data-to-the-us-for-visa-free-travel/) ⭐️ 8.0/10

The European Commission is negotiating an Enhanced Border Security Partnership \(EBSP\) framework with the Trump administration, under which the EU would grant the US access to its biometric databases in exchange for maintaining visa-free travel for EU citizens. Leaked drafts reveal the EU has largely accepted US demands for unrestricted access to sensitive personal data. This deal could set a dangerous precedent for mass surveillance and privacy violations, as biometric data is inherently sensitive and irreplaceable. If approved, it would affect hundreds of millions of EU citizens and undermine European data protection standards. The EBSP framework involves automated exchange of traveler personal data for screening and identity verification, including biometrics and &\#x27;risk indicators&\#x27; based on political views. EDRi warns the arrangement could systematically transmit data to the US, potentially threatening freedom of expression and human rights.

telegram · zaihuapd · Jul 20, 15:08

**Background**: The Enhanced Border Security Partnership \(EBSP\) is a proposed agreement between the EU and US aimed at strengthening border security cooperation. Biometric data includes fingerprints, facial images, and iris scans—information that cannot be changed like a password. The US currently requires visa-free travel partners to meet certain security conditions, and this deal would expand data sharing beyond existing agreements like the Passenger Name Record \(PNR\) scheme.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ic.work/article/eu-us-visa-waiver-biometric-data-access-talks">欧盟赴美免签谈判，正把生物识别数据库推上桌面 - ic.work</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#biometric data`, `#EU-US relations`, `#digital rights`, `#data sharing`

---

<a id="item-13"></a>
## [EU Fines AliExpress €550 Million for Counterfeit Goods](https://thebalkanchronicle.com/en/business/eu-fines-aliexpress-550-million-counterfeit-goods-2026/) ⭐️ 8.0/10

The European Commission fined AliExpress €550 million on July 20, 2025 for failing to prevent counterfeit and illegal goods on its platform, under the Digital Services Act \(DSA\). This is the first major DSA enforcement against a major e-commerce platform, setting a precedent for platform accountability on counterfeit goods and potentially impacting how online marketplaces operate in the EU. The investigation found that unsafe toys and dangerous cosmetics remained listed for weeks after being flagged. AliExpress called the fine &\#x27;disproportionate&\#x27; and must submit a remediation plan by October 20, 2026.

telegram · zaihuapd · Jul 21, 01:44

**Background**: The Digital Services Act \(DSA\) is an EU regulation that entered into force in 2022, imposing strict obligations on online platforms for content moderation and transparency. Very Large Online Platforms \(VLOPs\) like AliExpress face the highest standards, including proactive measures against illegal and counterfeit goods.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_Services_Act">Digital Services Act</a></li>

</ul>
</details>

**Tags**: `#e-commerce`, `#regulation`, `#EU`, `#counterfeit goods`, `#Digital Services Act`

---

<a id="item-14"></a>
## [TSMC to raise chip prices 5-10% from 2027](https://asia.nikkei.com/business/technology/exclusive-tsmc-to-raise-chipmaking-prices-by-up-to-10-from-2027) ⭐️ 8.0/10

TSMC has reached agreements with clients to increase chip manufacturing prices by 5% to 10% starting early 2027, covering both advanced nodes below 7nm and mature nodes above 12nm. Orders for high-performance computing chips exceeding original forecasts will face an additional 10% to 15% premium. This price hike reflects rising costs in materials, equipment, and overseas fabrication plants, signaling a strategic shift in TSMC&\#x27;s pricing that will impact major tech clients like Apple, NVIDIA, and AMD. It may also influence global semiconductor supply chains and end-user device prices. TSMC&\#x27;s CFO noted that overseas fab expansion and 2nm volume production will continue to pressure profit margins. Chairman C.C. Wei emphasized that pricing is strategic and not a sudden sharp increase like in memory chips, aiming to keep clients viable.

telegram · zaihuapd · Jul 21, 09:28

**Background**: Advanced semiconductor nodes \(e.g., 7nm, 5nm, 3nm, 2nm\) offer higher performance and density for applications like AI, mobile, and high-performance computing. Mature nodes \(e.g., 12nm, 28nm, 45nm\) are used for automotive, IoT, and other cost-sensitive applications where performance trade-offs are acceptable. TSMC is the world&\#x27;s largest dedicated semiconductor foundry, producing chips for numerous leading tech companies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.eejournal.com/article/are-we-ready-for-the-2nm-process-node/">Are We Ready for the 2 nm Process Node ? – EEJournal</a></li>
<li><a href="https://anysilicon.com/semiconductor-technology-node-history-roadmap/">Semiconductor Technology Node History and Roadmap - AnySilicon</a></li>
<li><a href="https://semiengineering.com/legacy-process-nodes-are-critical-to-many-industries/">Legacy Process Nodes Are Critical To Many Industries</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#TSMC`, `#chip pricing`, `#supply chain`, `#manufacturing costs`

---