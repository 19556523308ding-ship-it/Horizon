---
layout: default
title: "Horizon Summary: 2026-11-15 (EN)"
date: 2026-11-15
lang: en
---

> From 36 items, 12 important content pieces were selected

---

**Technology News**
1. [SpaceX Starship Flight 15 achieves first tower catch of an orbit-returning upper stage](#item-tech-news-1) ⭐️ 8.0/10
2. [Project Zero stages disclosure window from 90 days to 30 days](#item-tech-news-2) ⭐️ 8.0/10
3. [FAA 全国停飞起因：换铜线升级引发路由故障](#item-tech-news-3) ⭐️ 8.0/10
4. [Lovable apps expose passport details and more than 200K private messages](#item-tech-news-4) ⭐️ 7.0/10
5. [EFF asks appeals court to require warrants for ALPR database searches](#item-tech-news-5) ⭐️ 7.0/10
6. [Show HN: DeepSeek V3 implemented in ~200 lines of pure JAX](#item-tech-news-6) ⭐️ 7.0/10
7. [PyPI&\#x27;s redesigned project pages with clearer security signals are now live](#item-tech-news-7) ⭐️ 7.0/10
8. [datasette-llm 0.1a11 adds OpenAI-compatible endpoint support for local LLMs](#item-tech-news-8) ⭐️ 7.0/10
9. [LongMemEval-S benchmark reaches 96.0% with official judge and a tuned top-20 retrieval configuration](#item-tech-news-9) ⭐️ 7.0/10
10. [Cloudflare Open-Sources Kitesurf, a Workers-Based Stateless Browser for AI Agents](#item-tech-news-10) ⭐️ 7.0/10

**Financial News**
1. [Nvidia&\#x27;s founder resigns as policy and ETF flows reshape the AI trade](#item-finance-news-1) ⭐️ 7.0/10
2. [Eric Trump-backed robot startup misses payroll after CEO&\#x27;s $4.6 million company loan](#item-finance-news-2) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [SpaceX Starship Flight 15 achieves first tower catch of an orbit-returning upper stage](https://www.spacex.com/launches/starship-flight-15) ⭐️ 8.0/10

SpaceX said Starship Flight 15 completed roughly a 22.5-hour flight and about 14 orbits before returning to its Texas launch site, where it was caught for the first time by the launch tower&\#x27;s mechanical arms after an orbital return. The booster \(Super Heavy\) did not return to the tower as planned and instead splashed down in the Gulf of Mexico, so two-stage simultaneous recovery has not yet been achieved. The mission deployed 26 next-generation Starlink V3 satellites, which SpaceX did not identify with a model number or count. This is announced mission status from SpaceX rather than an independently verified result.

hackernews · ls612 · Nov 14, 21:22 · [Discussion](https://news.ycombinator.com/item?id=50500963)

**「Why this matters」** Previous Starship test flights used the tower arms for suborbital booster or ship touchdowns or held the ship briefly while it descended, but none had yet caught the upper stage after it returned from orbit. Flight 15 therefore represents the first tower catch of a vehicle that completed an orbital flight and atmospheric reentry, the capability needed for routine upper-stage reuse and refueling.

**「Effect on reuse and cost」** If the spacecraft&\#x27;s heat shield survives and the catch becomes routine, Starship can return the upper stage for refurbishment and reflight, which is the path SpaceX needs to reach the low per-orbit costs that drive payload pricing. Until the booster is also recoverable by catch and the spacecraft is re-flown, the cost benefit remains potential rather than demonstrated, and the 26 Starlink V3 satellites&\#x27; subsequent reflight cadence has not been established.

**「Community reaction」** Commenters largely celebrated the milestone, with some arguing that a 100% reusable stack is materially better than the roughly 60% reusability they attribute to Falcon 9 by cost, and noting that catching both stages would have required more propellant. Other comments expressed general emotional enthusiasm without technical detail; no substantive disagreement about the result or its verification was present.

**Tags**: `#SpaceX`, `#Starship`, `#reusability`, `#aerospace engineering`, `#launch systems`

---

<a id="item-tech-news-2"></a>
### [Project Zero stages disclosure window from 90 days to 30 days](https://projectzero.google/2026/11/disclosure-policy.html) ⭐️ 8.0/10

Google Project Zero is reducing its standard vulnerability disclosure window from 90 days to 30 days on a staged schedule: Full 90 days applies from today \(November 14, 2026\), Full 60 days begins February 2, 2027, and Full 30 days begins January 3, 2028. The policy change is published on Project Zero&\#x27;s blog \(projectzero.google/2026/11/disclosure-policy.html\) and takes effect immediately, ahead of the staged milestones. It is a planned policy change, not a capability that has been independently measured against actual vendor remediation performance.

hackernews · hacb · Nov 14, 11:13 · [Discussion](https://news.ycombinator.com/item?id=50496051)

**「Background」** Project Zero previously used a 90-day disclosure window before a full fix, a standard that had long set the de facto deadline many vendors plan their patches around. The staged rollout \(90 → 60 → 30\) is intended to give vendors and the research community time to adapt to the shorter deadline rather than switching to 30 days overnight.

**「Impact」** Vendors that normally need more than 30 days to verify and fix a flaw will face earlier public disclosure, which for at least some organizations such as Ubuntu could mean disclosure before a fix is available. The shorter window also raises a practical consideration for researchers: with less time to hold a report, the leverage of disclosure as a driver for patching shifts.

**「Community discussion」** Commenters expressed concern that the change disadvantages vendors with long remediation cycles, with one specifically noting Ubuntu will need more time, and others questioned whether Google is using its size to force prioritization or whether earlier disclosure would actually help vendors get patches. One participant said they would prefer immediate disclosure, arguing nothing else will compel the reported company to fix the issue.

**Tags**: `#vulnerability disclosure`, `#security policy`, `#Project Zero`, `#bug bounty`, `#software engineering`

---

<a id="item-tech-news-3"></a>
### [FAA 全国停飞起因：换铜线升级引发路由故障](https://www.theverge.com/transportation/1033898/faa-ground-stop-sean-duffy-faa-copper-wire) ⭐️ 8.0/10

A routine copper-to-fiber upgrade at a remote FAA facility caused a router failure that led to a nationwide flight ground stop, with the root cause still under investigation.

telegram · zaihuapd · Nov 15, 02:10

**Tags**: `#critical infrastructure`, `#networking`, `#air traffic control`, `#incident analysis`, `#FAA`

---

<a id="item-tech-news-4"></a>
### [Lovable apps expose passport details and more than 200K private messages](https://www.crissyfield.de/research/lovable-en/) ⭐️ 7.0/10

Security research reports that apps built with Lovable may expose passport details and over 200K private messages, sparking discussion about Lovable, Supabase, and row-level security.

hackernews · armcat · Nov 14, 17:43 · [Discussion](https://news.ycombinator.com/item?id=50499017)

**Tags**: `#security research`, `#AI-generated apps`, `#data exposure`, `#row-level security`, `#open source platforms`

---

<a id="item-tech-news-5"></a>
### [EFF asks appeals court to require warrants for ALPR database searches](https://www.eff.org/deeplinks/2026/11/were-asking-appeals-court-require-warrant-alpr-searches) ⭐️ 7.0/10

The EFF has filed a brief in an unnamed U.S. appeals court asking that searches of automatic license plate reader \(ALPR\) databases require a warrant. The brief argues that the vast, interconnected network of ALPRs that constantly tracks drivers nationwide constitutes a &\#x27;search&\#x27; under the Fourth Amendment. Published on November 15, 2026, the EFF&\#x27;s filing presents this as a legal claim rather than a court ruling or policy change, so no legal standard has yet been established. No details about the specific case, docket number, court, or scheduled arguments are available in the source.

hackernews · nobody9999 · Nov 15, 02:00 · [Discussion](https://news.ycombinator.com/item?id=50503255)

**「Background」** Automatic license plate reader \(ALPR\) systems scan and log vehicle license plates, and historically many agencies retained the resulting records indefinitely rather than deleting non-match captures. Because no single federal rule governed those retention and access practices, several states enacted their own restrictions, and the most detailed existing model cited in community discussion is New Hampshire&\#x27;s RSA 261:75-b, which limits LPR use to law enforcement, requires deletion of non-hit images within 3 minutes, and restricts uploads of non-hit imagery \[tool-2-1\]\[tool-2-2\]. The 2026 Recording Law update notes that New Hampshire&\#x27;s 2027 sunset provision was repealed, leaving the ALPR rules in place \[tool-2-2\].

**「What the community said」** Commenters largely supported the EFF&\#x27;s framing, with one user adding that New Hampshire&\#x27;s statute already limits ALPR collection \(deleting non-hit plate images within 3 minutes, prohibiting storage of non-plate subjects, and forbidding uploading non-hit imagery\) but arguing a warrant should still be required to access stored data. Another user pressed for an even stricter rule: storing only plates under an active warrant, while a third linked the ALPR debate to the coming availability of facial and object recognition.

<details><summary>References</summary>
<ul>
<li><a href="https://www.recordinglaw.com/us-laws/automated-license-plate-readers/new-hampshire-alpr-laws/">New Hampshire License Plate Reader Laws (2026) | Recording Law</a></li>

</ul>
</details>

**Tags**: `#privacy law`, `#civil liberties`, `#law enforcement technology`, `#Fourth Amendment`, `#open source policy`

---

<a id="item-tech-news-6"></a>
### [Show HN: DeepSeek V3 implemented in ~200 lines of pure JAX](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) ⭐️ 7.0/10

Developer VaibhaavTiwari published a ~200-line, first-principles JAX reimplementation of the DeepSeek V3 architecture at github.com/Vaibhaav-Tiwari/deepseek-v3-jax. It is a teaching and reference implementation, not a new model release or an algorithmic change to DeepSeek V3 itself. The community reports that it runs end-to-end on consumer AMD hardware \(for example, an RX 7600 XT with 16GB VRAM\) via ROCm, making it a practical learning tool for people rebuilding large language models.

hackernews · VaibhaavTiwari · Nov 14, 15:04 · [Discussion](https://news.ycombinator.com/item?id=50497589)

**「Background」** DeepSeek V3 is a large language model released by DeepSeek that uses a mixture-of-experts \(MoE\) architecture with shared dense layers, multi-head latent attention, and block-wise feed-forward networks. It was published with model weights made available for research and inference under a license, and its scale—over 600B parameters with ~37B active per token—made a full implementation unusually large and complex. JAX is a numerical computing library by Google built on NumPy-style APIs, XLA compilation, and composable transformations like jit, vmap, and grad, commonly used for prototyping ML models on both CPUs and accelerators.

**「Community discussion」** Readers praise recreating a model from first principles for building intuition and want similar visual or interactive explanations of architecture. One user found it the first project that runs end-to-end on Fedora with ROCm on an RX 7600 XT, noting two JAX plugin gotchas: setting HSA\_OVERRIDE\_GFX\_VERSION=11.0.0 to bypass rejection of gfx1102 and an additional environment variable cut off in the comment.

**Tags**: `#jax`, `#llm`, `#open-source`, `#deep-learning`

---

<a id="item-tech-news-7"></a>
### [PyPI&\#x27;s redesigned project pages with clearer security signals are now live](https://blog.pypi.org/posts/2026-11-06-ui-updates-complete/) ⭐️ 7.0/10

PyPI has launched redesigned project pages that display clearer security signals to help users assess package trust. The update is a UI/UX change to project pages and makes provenance information more visible, but its practical value depends on adoption by pip and CI/CD tooling. Community comments indicate the signals include sigstore-style keyless signatures for packages with provenance and distinguish between previously benign projects that were compromised versus genuinely malicious ones.

hackernews · rbanffy · Nov 14, 15:40 · [Discussion](https://news.ycombinator.com/item?id=50497892)

**「Background」** Package provenance and signing are part of a broader software supply chain security effort. The PyPI project page redesign surfaces this information alongside package files, allowing users to see whether a given package has verifiable provenance.

**「Impact」** For most developers who install packages via \`pip install\` rather than reviewing project pages, the visibility change has limited direct effect unless pip and CI/CD tools begin consuming the same signals. Users should verify whether their tooling acts on provenance data before assuming these signals will automatically block compromised or unverified packages.

**「Community Discussion」** Some users expressed support for expanding sigstore-style keyless signing and called for broader CI/CD tool support, while others warned that tying trust to large cloud platforms could create lock-in. One commenter noted the signals help detect previously benign projects whose PyPI entries were compromised without access to their private keys, rather than detecting malicious projects outright.

**Tags**: `#software supply chain`, `#PyPI`, `#package security`, `#sigstore`, `#open source`

---

<a id="item-tech-news-8"></a>
### [datasette-llm 0.1a11 adds OpenAI-compatible endpoint support for local LLMs](https://simonwillison.net/2026/Nov/14/datasette-llm/) ⭐️ 7.0/10

datasette-llm 0.1a11 adds support for OpenAI-compatible endpoints, letting Datasette use LLMs hosted anywhere that implement the OpenAI protocol. This enables configuration for local models via LM Studio, Ollama, or llama.cpp, including the recently released llama.cpp v1.0.0. A concrete example configures a local model named lmstudio-qwen with api\_base pointing to http://localhost:1234/v1, powering a Datasette Agent instance launched through uvx.

rss · Simon Willison · Nov 14, 23:59

**「Background」** datasette-llm is the intermediate plugin for Datasette that allows Datasette plugins to use an LLM by providing a shared configuration for the model endpoint. Datasette Agent is a chat-driven data exploration plugin that relies on that shared configuration to send tool calls such as SQL queries to the configured LLM. The v1.0.0 milestone of llama.cpp is one of the third-party local inference servers now exposed through the OpenAI pseudo-standard protocol that this release makes addressable.

**「Impact」** Developers can now run Datasette Agent with locally hosted models instead of requiring an OpenAI API key, avoiding cloud costs and network latency for on-premises or offline workflows. The trade-off is that the local model determines capabilities and throughput, and users must host and maintain the model-serving endpoint themselves.

**「Community discussion」** No community comments were provided for this release.

**Tags**: `#open source`, `#LLM`, `#software engineering`, `#local AI`, `#data tools`

---

<a id="item-tech-news-9"></a>
### [LongMemEval-S benchmark reaches 96.0% with official judge and a tuned top-20 retrieval configuration](https://www.reddit.com/r/MachineLearning/comments/1xwnloh/longmemevals_960_with_the_official_judge_and_what/) ⭐️ 7.0/10

A reproducible LongMemEval-S evaluation achieved 96.0% accuracy using the official answer prompt and the unmodified gpt-4o-2024-08-06 judge on all 500 questions, with per-question answers and judge labels made public. The configuration uses the Papr-ai memory retrieval system with Papr-Embed 0.6B, a gemini flash 2.5 reranker, and a single-turn answer model. This score is comparable to earlier published results: Chronos reported 95.6% with full context and multi-turn agents, and Hindsight reported 94.6% at 43.6k tokens per question using a different judge. The authors caution that 96.0% was tuned on this specific dataset after reviewing top-5 misses, so top-20 retrieval is not a free improvement.

reddit · r/MachineLearning · /u/remoteinspace · Nov 15, 05:40

**「Background」** LongMemEval-S is a retrieval-augmented generation benchmark evaluating long-context memory and temporal reasoning across 500 questions. Prior reported scores on the same benchmark, such as Chronos&\#x27;s 95.6% and Hindsight&\#x27;s 94.6%, used different retrieval strategies, model architectures, and judging criteria, which makes direct numerical comparison imperfect.

**「Impact」** For practitioners, the key finding is that retrieval recall is near saturation: evidence for 460 of 470 answerable questions \(97.9%\) already appears in the top 5, and expanding to top 20 yields 11 gains versus 8 losses \(net +3\). This suggests that additional retrieval budget rarely pays off and that further gains come from the reader rather than retrieval. Teams tuning retrieval-augmented systems should treat top-20 as a dataset-specific tuning choice, given the self-reported ±3 run-to-run variance and the absence of question-type labels in retrieval or answering.

**Tags**: `#retrieval-augmented generation`, `#benchmarking`, `#long-context reasoning`, `#open source`, `#machine learning`

---

<a id="item-tech-news-10"></a>
### [Cloudflare Open-Sources Kitesurf, a Workers-Based Stateless Browser for AI Agents](https://www.phoronix.com/news/Cloudflare-Kitesurf-Open-Source) ⭐️ 7.0/10

Cloudflare has open-sourced Kitesurf, an Apache 2.0–licensed, stateless browser built on Cloudflare Workers, targeted at AI agents. Kitesurf parses HTML, handles CSS, and executes JavaScript without relying on a Chromium browser container. Cloudflare says the approach uses less CPU and memory than Chromium and can scale on demand across the global Workers network. The code has been published on GitHub, though the performance comparisons and adoption remain vendor claims rather than independently measured results.

telegram · zaihuapd · Nov 14, 09:33

**「背景」** Cloudflare Kitesurf 是一个基于 Cloudflare Workers 构建的实验性浏览器引擎，用于 AI 代理，已于 GitHub 上以 Apache 2.0 协议开源 \(tool-2-2, tool-2-1\)。要运行 Kitesurf 需使用 Cloudflare Workers 的 Dynamic Workers（为每个页面创建隔离的 worker），该功能属于 Workers Paid 套餐 \(tool-2-1\)。Kitesurf 在 Beta 阶段免费，但位于 Cloudflare Browser Run 内部，并受账户配额限制，作为 Cloudflare Agents Week 的一部分发布 \(tool-2-3\)。

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/cloudflare/kitesurf">GitHub - cloudflare / kitesurf : Kitesurf is an experimental browser ...</a></li>
<li><a href="https://developers.cloudflare.com/changelog/post/2026-11-12-kitesurf-open-source/">Kitesurf is now open source · Changelog | Cloudflare Docs</a></li>
<li><a href="https://www.everydev.ai/tools/kitesurf">Kitesurf - Headless Browser for AI Agents | EveryDev. ai</a></li>

</ul>
</details>

**Tags**: `#open source`, `#AI agents`, `#cloud infrastructure`, `#web rendering`, `#developer tools`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Nvidia&\#x27;s founder resigns as policy and ETF flows reshape the AI trade](https://www.cnbc.com/2026/11/14/nvidia-ai-trade-data-centers-congress.html) ⭐️ 7.0/10

After Nvidia founder and CEO Jensen Huang resigned, interim CEO and CFO Colette Kress took over while Nvidia&\#x27;s shares fell to $162.85 following its longest losing streak since 2012; analyst Dan Ives of Yorkville Ives cut its price target to $225 from $300 while keeping a buy rating, and investors shifted toward other AI players as Democratic control of Congress raised the possibility of slower data-center permitting.

rss · CNBC Finance · Nov 14, 15:50

**「background」** The resignation came after a week in which a Democratic Party sweep on Nov. 3 gave that party control of Congress, prompting experts to discuss spillovers to peers such as AMD and Broadcom and to ETFs before Nvidia&\#x27;s third-quarter earnings were released.

**「impact」** If Democratic lawmakers slow the pace of data-center construction, existing compute could become scarcer and more valuable for hyperscalers and smaller cloud firms, according to the interviewed experts; AMD and Broadcom rose nearly 13% and showed similar gains as investors reassessed the AI trade.

**Tags**: `#semiconductor industry`, `#corporate governance`, `#ETF flows`, `#AI infrastructure`, `#US policy`

---

<a id="item-finance-news-2"></a>
### [Eric Trump-backed robot startup misses payroll after CEO&\#x27;s $4.6 million company loan](https://www.cnbc.com/2026/11/14/foundation-payroll-ceo-loan.html) ⭐️ 7.0/10

Foundation Future Industries, a military humanoid robot maker advised by Eric Trump, missed payroll on Oct. 30 as cash reserves dwindled, according to people with direct knowledge of the matter. The shortfall follows a $4.6 million loan the company&\#x27;s CEO and co-founder, Sankaet Pathak, took from the firm last year to buy a $4.6 million luxury home in Sausalito, California, according to those people and corroborated by public records.

rss · CNBC Finance · Nov 14, 12:00

**「background」** The situation has attracted scrutiny because Pathak claims the company is close to unveiling a next-generation, weapons-ready robot and is seeking hundreds of millions of dollars in new funding at a $3 billion valuation, while Eric Trump serves as chief strategy advisor. A widely repeated claim that Foundation won $24 million in Pentagon contracts is, on the basis of an anonymous source, actually government research contracts won by Boardwalk Robotics, a Florida firm Foundation acquired in late 2024.

**「impact」** The missed paychecks could threaten the startup itself if Pathak does not secure fresh funding, insiders say, while the single-board-member structure that permitted the large loan is raising corporate governance concerns among potential investors, according to the same people.

**Tags**: `#defense technology`, `#payroll failure`, `#corporate governance`, `#startup financing`, `#government contracts`

---