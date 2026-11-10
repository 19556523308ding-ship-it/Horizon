---
layout: default
title: "Horizon Summary: 2026-11-10 (EN)"
date: 2026-11-10
lang: en
---

> From 47 items, 18 important content pieces were selected

---

**Technology News**
1. [Claude Fable 5.2 and Mythos 5.2 ship with faster output and lower pricing](#item-tech-news-1) ⭐️ 9.0/10
2. [Google Gemini consumer data routed to human annotators, Workspace excluded](#item-tech-news-2) ⭐️ 8.0/10
3. [Google launches TPU 8tx and TPU 8i Max for agentic AI workloads](#item-tech-news-3) ⭐️ 8.0/10
4. [Latent prediction beats reconstruction for tactile pretraining on dexterous manipulation tasks\[R\]](#item-tech-news-4) ⭐️ 8.0/10
5. [SwarmEvolve uses latent-agent swarms on Qwen for fast math optimization](#item-tech-news-5) ⭐️ 8.0/10
6. [Amazon replaced an LLM classifier with a cheaper model, cutting ticket-classification costs](#item-tech-news-6) ⭐️ 7.0/10
7. [Payments Canada Launches the Real-Time Rail with Interac as Partner](#item-tech-news-7) ⭐️ 7.0/10
8. [Meta launches Muse Ember, a compact multimodal model with six reasoning levels](#item-tech-news-8) ⭐️ 7.0/10
9. [watched.earth shows weekly satellite passes and real captured imagery in the browser](#item-tech-news-9) ⭐️ 7.0/10
10. [XGBoost county power outage forecast outperforms NWS/SPC baselines on held-out 2025 year](#item-tech-news-10) ⭐️ 7.0/10
11. [ByteDance Releases Seedream 5.5 with 100-Round Editing and Native Transparency](#item-tech-news-11) ⭐️ 7.0/10
12. [UK Cross-Party Push to Require Phones with Abuse-Image-Blurring Software](#item-tech-news-12) ⭐️ 7.0/10
13. [OpenAI deploys Control Room to halt risky AI tasks within 35 seconds](#item-tech-news-13) ⭐️ 7.0/10

**Financial News**
1. [California voters reject billionaire wealth tax measure](#item-finance-news-1) ⭐️ 8.0/10
2. [Goldman Sachs CEO Says Demand for AI Infrastructure Financing Stays Strong](#item-finance-news-2) ⭐️ 7.0/10
3. [EU drafts Digital Fairness Act to curb addictive design and in-game spending](#item-finance-news-3) ⭐️ 7.0/10
4. [China&\#x27;s New-Energy Car Exports Jump in First Three Quarters of 2026](#item-finance-news-4) ⭐️ 7.0/10
5. [Anthropic pulled a $69.3B IPO filing over pricing error](#item-finance-news-5) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Claude Fable 5.2 and Mythos 5.2 ship with faster output and lower pricing](https://www.anthropic.com/claude-fable-and-mythos-5-2) ⭐️ 9.0/10

Anthropic released Claude Fable 5.2 and Mythos 5.2, models that share a base architecture, with strengthened coding, reasoning, and vision. Fable is available to all users, while Mythos requires access through a cybersecurity or life sciences verification program. Output is reportedly about 30% faster than version 5.1, with a 2.5x acceleration mode available, and pricing fell to USD 8 per million input tokens and USD 40 per million output tokens. During testing, Anthropic claims the model produced a formal proof of Fermat&\#x27;s Last Theorem within 30 hours.

telegram · zaihuapd · Nov 9, 19:27

**「Background」** Claude Fable and Claude Opus are Anthropic&\#x27;s widely used large language models; Opus is positioned as the top-tier model, while Fable serves a broad user base. Earlier versions \(Fable 5/5.1 versus Opus 4.8/5\) created a perception gap that some users now describe as resolved with the 5.2 update.

**「Why it matters」** For developers, the lower pricing and faster output reduce the cost of running large coding and research workloads, and a tester reported using Fable 5.2 to speed up a 600,000-line Fortran material-science codebase by 36 times. Another user&\#x27;s in-house code review found 7 serious bugs, though this is a single reported experience rather than an independently measured benchmark.

**Tags**: `#AI models`, `#Anthropic`, `#large language models`, `#formal verification`, `#model release`

---

<a id="item-tech-news-2"></a>
### [Google Gemini consumer data routed to human annotators, Workspace excluded](https://github.com/thisisme6598/gemini_files/) ⭐️ 8.0/10

A GitHub mirror posted by a user claims that consumer Gemini may route personal Google Drive files and Gmail messages to human annotators for quality review, and that this behavior is linked to the Connected Apps authorization. The post contrasts this with Workspace Gemini and Workspace Intelligence, which are stated to exclude such data from human review. The report is presented as user-observed behavior rather than an official Google announcement, and it is corroborated only by parallel user anecdotes and Google&\#x27;s prior disclosure that Google Photos data can be used to train generative AI. No official statement or technical specification has been provided to confirm the exact routing conditions or scope.

hackernews · gf74918 · Nov 9, 18:24 · [Discussion](https://news.ycombinator.com/item?id=50429426)

**「Background」** Gemini for consumers can access personal data through authorized connected tools such as Gmail and Drive, including in Connected Apps configurations. Google has previously disclosed that Google Photos data may be used to infer interests and relationships and to train generative AI, indicating that personal data is already entering training pipelines in some consumer products. Workspace products are governed by separate enterprise agreements and feature disclosures that typically distinguish them from consumer behavior.

**「Impact」** Users who authorize connected Gmail or Drive tools in consumer Gemini should assume those data contents can be read by human reviewers, and should verify their current Connected Apps settings and data permissions before sharing sensitive information. Developers and organizations relying on consumer Gemini for internal or personal data should treat it as unsuitable for unredacted confidential content until Google provides a written guarantee.

**「Community Discussion」** Commenters reported Gemini responding to queries with details that appeared to match their personal emails, supporting the concern that connected tool data may reach human reviewers. Others noted the broader pattern across tools with human annotation, while a separate commenter linked the issue to Google&\#x27;s earlier Google Photos training disclosure. These accounts are user observations and are not treated as established facts.

**Tags**: `#AI privacy`, `#human annotation`, `#Gemini`, `#data governance`, `#consumer AI`

---

<a id="item-tech-news-3"></a>
### [Google launches TPU 8tx and TPU 8i Max for agentic AI workloads](https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/) ⭐️ 8.0/10

Google announced two new TPU accelerators, TPU 8tx and TPU 8i Max, continuing a faster product cadence than its historical two-year cycle. TPU 8tx is targeted at government and strictly regulated industries for handling sensitive classified data and is designed to interoperate with AMD GPUs. TPU 8i Max addresses long-context AI applications by integrating two TPU chips in a single package to deliver higher compute and larger memory capacity. Google is positioning these chips as an alternative to NVIDIA GPUs to its growing customer base, which now includes Apple, Meta, Oracle, and Anthropic.

hackernews · \_benx\_ · Nov 9, 21:56 · [Discussion](https://news.ycombinator.com/item?id=50432831)

**「Background」** TPUs are Google&\#x27;s custom AI accelerators, and this announcement follows its earlier strategy of roughly biennial TPU releases. The company has historically emphasized scale-out architectures for large training and inference, while these new chips add specialized roles for secure environments and very long context windows.

**「Impact」** Organizations needing long-context model acceleration may gain a higher-memory Google Cloud TPU option, while regulated agencies could adopt 8tx as a government-grade accelerator co-deployed with AMD hardware. Developers currently relying on public Cloud TPUs, such as Colab users running v6e-1, may benefit if Google extends access to these newer models, though no availability timeline is stated.

**「Community Discussion」** Commenters discussed how TPUSync underpins many open-source repos, including Strata for Qwen models, and questioned why Google does not sell these chips directly. There is also demand for transparency on efficiency and cost metrics like watt/token and $/token, as well as requests for broader availability on platforms like Google Colab beyond the current v6e-1 tier.

**Tags**: `#TPU`, `#AI hardware`, `#ML infrastructure`, `#Google Cloud`, `#agentic AI`

---

<a id="item-tech-news-4"></a>
### [Latent prediction beats reconstruction for tactile pretraining on dexterous manipulation tasks\[R\]](https://www.reddit.com/r/MachineLearning/comments/1xs05uo/latent_prediction_beats_reconstruction_for/) ⭐️ 8.0/10

A new self-supervised tactile pretraining method using latent prediction outperforms reconstruction-based models on dexterous manipulation tasks, with public code and checkpoints.

reddit · r/MachineLearning · /u/Zealousideal-War7154 · Nov 9, 18:52

**Tags**: `#self-supervised learning`, `#tactile sensing`, `#robotics`, `#JEPA`, `#dexterous manipulation`

---

<a id="item-tech-news-5"></a>
### [SwarmEvolve uses latent-agent swarms on Qwen for fast math optimization](https://www.reddit.com/r/MachineLearning/comments/1xrunu7/using_latentagent_swarms_for_math_discovery_and/) ⭐️ 8.0/10

SwarmEvolve is a new open-source framework for math discovery and optimization that runs hundreds of latent-reasoning agents on Qwen3 models \(8B, 14B, and 32B\), extending the AlphaEvolve lineage. Instead of outputting reasoning text, the agents reason in latent space and share KV caches between each other, which the authors report improves throughput substantially. They claim the framework reaches scores in about 5 minutes that took OpenEvolve, ShinkaEvolve, and CodeEvolve over an hour to achieve, and that with the 8B model alone it matched the best known circle packing results. The work has been extended to Qwen3.5 and Muse models, but the code is not yet available.

reddit · r/MachineLearning · /u/QileHQ · Nov 9, 15:30

**「Background」** AlphaEvolve, developed by Google DeepMind last year, discovered a faster algorithm for multiplying 4x4 complex matrices, breaking a record that had stood since 1969. The approach lets a language model write programs, score them, and iteratively improve them through an evolutionary loop. Earlier open-source implementations of this approach, such as OpenEvolve, ShinkaEvolve, and CodeEvolve, were reported to be slow and expensive to run.

**「Impact」** If the reported speedups hold up, researchers working on program-based algorithm discovery could iterate on math and optimization problems much faster using smaller, cheaper models rather than relying on large proprietary models. Until the code is released and results are independently reproduced, the performance claims and the ability to reproduce the circle packing match should be treated as unverified.

**Tags**: `#AI optimization`, `#latent reasoning`, `#open source`, `#LLM agents`, `#mathematical discovery`

---

<a id="item-tech-news-6"></a>
### [Amazon replaced an LLM classifier with a cheaper model, cutting ticket-classification costs](https://strandsagents.com/blog/amazon-saves-millions-replacing-sonnet-with-strands-decider/) ⭐️ 7.0/10

In a production ticket-classification and routing system, Amazon replaced the LLM used to classify tickets with Strands Decider, a cheaper model, reporting savings of approximately $21,700 per million tickets processed. The classifier handled tickets including alarms, security findings, and capacity increase requests rather than only customer-support queries. The savings figure and the vendor claim come from Strands&\#x27; own blog, and are not independently verified; the headline&\#x27;s &quot;millions&quot; language follows from that per-million rate rather than an audited total. The switch illustrates a production shift from using a general LLM for a task where a smaller, specialized classifier was sufficient.

hackernews · aloukissas · Nov 10, 06:01 · [Discussion](https://news.ycombinator.com/item?id=50436640)

**「Background」** The post describes Amazon&\#x27;s replacement of a Sonnet 4.6-based LLM classifier with Strands Decider in its production ticket classification pipeline, reporting a cost reduction of about $21,700 per million tickets. Sonnet 4.6 refers to a Claude model from Anthropic&\#x27;s Claude 4.6 family, known for strong reasoning performance. Community discussion notes a broader pattern of LLM overuse in backends, with one engineer recalling an earlier ticket classification pipeline built with SVMs that trained in minutes and classified in milliseconds before the industry shifted to LLMs and back to cheaper classifiers.

**Tags**: `#LLM optimization`, `#cost efficiency`, `#production ML`, `#model selection`, `#vendor case study`

---

<a id="item-tech-news-7"></a>
### [Payments Canada Launches the Real-Time Rail with Interac as Partner](https://www.payments.ca/canada-launches-real-time-rail-bringing-247-payment-infrastructure-national-economy) ⭐️ 7.0/10

Payments Canada has launched the Real-Time Rail \(RTR\), a 24/7 nationwide real-time payment infrastructure, developed in partnership with Interac. The initial cohort of active participants includes Wealthsimple, Questbank, Peoples Trust Company, Paramount Commerce, KOHO, DoBusiness.com, Digital Commerce Bank, and Bank of America. This makes 24/7 instant payments available as a public-good backbone that banks and payment providers can build on, distinct from Interac&\#x27;s earlier proprietary e-Transfer service. Community discussion notes the comparison to the US FedNow and raises questions about whether Canada&\#x27;s major banks are participating.

hackernews · ocd · Nov 9, 16:00 · [Discussion](https://news.ycombinator.com/item?id=50427362)

**「Background」** Payments Canada, a federal Crown corporation, administers Canada&\#x27;s domestic payment settlement systems and previously relied on existing batch and same-day rails. The Real-Time Rail is being built in partnership with Interac, the domestic debit and e-Transfer network, which provides prerequisite connectivity and settlement experience for a 24/7 real-time network. The community notes this approach resembles modernizing a proprietary system such as Interac&\#x27;s e-Transfer into a public good available to any bank, rather than replacing Interac.

**「Impact」** Payments Canada says the Real-Time Rail \(RTR\) goes live in 2026, while industry coverage points to a Q3–Q4 2026 launch with industry testing beginning in Q3 and 1,800 businesses registered for access. For the participating institutions named by Payments Canada, the immediate concern is integration work against the new infrastructure; some commenters also wonder whether Canada&\#x27;s major banks are in the initial active cohort, which would determine whether the rail is immediately available to most account holders.

**「Community Discussion」** One contributor noted that US FedNow is used by only a handful of banks and charges fees such as 0.75% \(min $1, max $30\) with a discounted 0.375% tier for SoFi Plus members. Another Canadian commenter suggested the RTR appears to modernize Interac&\#x27;s proprietary e-Transfer into a public infrastructure and expressed cautious optimism while asking whether the major Canadian banks are taking part.

<details><summary>References</summary>
<ul>
<li><a href="https://thepaypers.com/payments/expert-views/canadas-real-time-rail-rtr-paradox-for-banks-fast-payments-small-error-margins">Canada ’s Real - Time Rail ( RTR ) paradox for banks</a></li>
<li><a href="https://clearingpost.com/insights/canada-rtr-q3-2026-launch/">Canada &#x27;s Real - Time Rail Targets Q3 2026 Launch | ClearingPost</a></li>

</ul>
</details>

**Tags**: `#payments infrastructure`, `#financial systems`, `#open banking`, `#public infrastructure`, `#Canada`

---

<a id="item-tech-news-8"></a>
### [Meta launches Muse Ember, a compact multimodal model with six reasoning levels](https://research.meta.ai/blog/muse-ember) ⭐️ 7.0/10

Meta AI has launched Muse Ember 1.0, its smallest and most efficient model, aimed at tool calls, coding subtasks, routing, extraction, and long document parsing. It offers six reasoning levels \(minimal, low, medium, high, xhigh, max\) and supports up to 1 million input tokens. For prompts up to 200k tokens, Ember costs $0.10/million input and $0.50/million output, with cached input priced at $0.004/million \(4% of full input\); beyond 200k, input rises to $0.30/million and output to $1.50/million. Meta positions Ember on the Artificial Analysis efficiency frontier, with xhigh at roughly $0.12 per task and max at $0.14, though the model is not open weights.

hackernews · dvaplima · Nov 9, 17:58 · [Discussion](https://news.ycombinator.com/item?id=50429024)

**「Background」** The Muse Ember 1.0 pricing tier and cache economics are comparable to those of the concurrently released GPT-6 Luna and Claude Haiku 5.5, each charging $0.10 per million input tokens under their respective threshold sizes. The cache-hit discount differs, however: Muse Ember charges $0.004 per million cached input tokens, versus $0.01 per million for both GPT-6 Luna and Claude Haiku 5.5. These models occupy different positions on the same benchmark chart, with Muse Ember \(xhigh\) scored around 34 at roughly $0.12 per task.

**Tags**: `#multimodal models`, `#model efficiency`, `#AI pricing`, `#open source`, `#computer vision`

---

<a id="item-tech-news-9"></a>
### [watched.earth shows weekly satellite passes and real captured imagery in the browser](https://www.watched.earth/) ⭐️ 7.0/10

watched.earth is a browser-based tool that, for any entered location, lists satellites that passed overhead in the past 7 days and shows the actual images captured by those satellites during those passes. It propagates more than 17,000 objects from the CelesTrak catalog with SGP4, runs the full orbit visualization on the GPU solving Kepler&\#x27;s equation every frame, and integrates Sentinel-2, Landsat, and NASA imagery. The author states the site takes about half a second to respond and does not store the user&\#x27;s location. It is a personal project, not a vendor release, and the author is soliciting feedback and contributions.

hackernews · a585gupt · Nov 9, 17:51 · [Discussion](https://news.ycombinator.com/item?id=50428907)

**「Background」** SGP4 is the standard model used to propagate two-line element sets from space-tracking catalogs into predicted orbital positions. CelesTrak maintains the public catalog of tracked objects, which is the input for most casual satellite-tracking tools. This project differs from typical pass predictors by adding the actual imagery captured at each pass rather than only predicted paths.

**「Impact」** Users can verify which satellite actually photographed a specific place by viewing the pass time series and matching it to the acquired image. A practical caveat is that Sentinel-2 image timestamps can be 5-10 minutes off from when the satellite physically crossed the selected location, which requires interpretation when correlating images to ground positions.

**Tags**: `#satellite tracking`, `#geospatial`, `#open source`, `#browser visualization`, `#Earth observation`

---

<a id="item-tech-news-10"></a>
### [XGBoost county power outage forecast outperforms NWS/SPC baselines on held-out 2025 year](https://www.reddit.com/r/MachineLearning/comments/1xs4hq8/forecasting_new_power_outages_per_county_hourly_2/) ⭐️ 7.0/10

A practitioner built an hourly model forecasting newly occurring power outages for 216 counties across Missouri and Illinois, predicting the probability that at least 5% of a county&\#x27;s customers go newly out in the 6 hours starting 2 hours from now. The model uses XGBoost on HRRR storm features \(gusts, shear, CAPE, icing\), county facts, current and neighboring outages, and trains on 2020-2024 with a held-out 2025 test set using forecasts as issued. On 2025 it achieved a PR-AUC of 0.094 versus 0.039 for a baseline rate table built from NWS warnings and SPC Day 1 outlook \(about 2.4×, with a 95% range of 2.0-3.3× from paired bootstrap over storm days\). At equal alert volume the model caught 30% of new outages at 15% precision versus 17% at 11% for the baseline; the base rate is 0.5% of county-hours, so absolute precision is low even where relative performance improves.

reddit · r/MachineLearning · /u/CarRepresentative843 · Nov 9, 21:34

**「Background」** Power outages are frequently driven by severe convective weather, and utility operators and emergency responders commonly rely on NWS warnings and SPC outlooks as the operational baseline for anticipating damage. Forecasting outage volume has previously been explored with weather features and regression or classification models, though county-level hourly probabilistic outage prediction remains uncommon. This post focuses narrowly on new outages rather than the total outage count, which the author says is harder to beat a ceiling on than predicting outages already underway.

**「Impact」** For utilities or emergency managers in the two states, adopting this model could shift alerts toward events with higher capture rates, but the low base rate means precision remains modest and decisions should account for false-alarm costs before deployment. The author also reports a preliminary transfer test where the MO/IL-trained model caught 31% versus 19% of new outages in Iowa, Indiana, and Michigan, suggesting retraining or domain adaptation is needed before expanding geographically.

**Tags**: `#machine learning`, `#forecasting`, `#weather`, `#open source`, `#applied ai`

---

<a id="item-tech-news-11"></a>
### [ByteDance Releases Seedream 5.5 with 100-Round Editing and Native Transparency](https://seed.bytedance.com/zh/blog/%E7%94%9F%E6%88%90%E6%9B%B4%E7%9C%9F%E5%AE%9E-%E7%99%BE%E8%BD%AE%E7%BC%96%E8%BE%91%E6%9B%B4%E7%A8%B3%E5%AE%9A-seedream-5-5-%E5%8F%91%E5%B8%83) ⭐️ 7.0/10

ByteDance has released Seedream 5.5, an image-generation model that supports up to 100 consecutive edits on a single work and native transparent-channel output, alongside improvements to image realism and text rendering. ByteDance reports that in its own evaluation the model achieved more than twice the usability rate of the previous version for film and office scenarios. The model is rolling out to the Jimeng, Doubao, Doubao Work, and Volcano Arkface platforms. The source is the vendor&\#x27;s own announcement, so these are claimed capabilities rather than independently verified results.

telegram · zaihuapd · Nov 9, 08:34

**「背景」** Seedream 5.5 是字節跳動 Seed 團隊於 2026 年 11 月 9 日發布的圖像創作模型，主打「同一張圖連續編輯 100 輪」的像素穩定能力與原生 RGBA 透明通道輸出，對應 2025 年 Seedream 3/4 階段在基礎文生圖與簡單局部重繪上的功能累積，此版本將重點轉向專業工作流所需的長鏈編輯與合成資產直接輸出。官方與第三方解讀（tool-2-2、tool-2-3）均指出，這一行動對應的變化是從「生成單張圖片」轉向「在多輪迭代中保持畫面結構、細節與文字可預測」。相關能力已陸續上線即夢、豆包、豆包工作與火山方舟（tool-2-1）。

<details><summary>References</summary>
<ul>
<li><a href="https://seed.bytedance.com/en/blog/more-realistic-images-more-stable-editing-across-100-rounds-introducing-seedream-5-5">Seed News - ByteDance Seed Team</a></li>
<li><a href="https://explainx.ai/blog/bytedance-seedream-5-5-100-round-editing-rgba-november-2026">Seedream 5.5: 100 Edits, RGBA, 0.4% Text Errors | explainx.ai ...</a></li>
<li><a href="https://best-ai.org/ai-news/bytedance-seedream-55-pixel-stable-editing-across-100-rounds-rgba-output-for-professionals-begvms">ByteDance Seedream 5.5: Pixel-Stable Editing Across 100 ...</a></li>

</ul>
</details>

**Tags**: `#image generation`, `#multimodal models`, `#generative AI`, `#ByteDance`, `#AI tools`

---

<a id="item-tech-news-12"></a>
### [UK Cross-Party Push to Require Phones with Abuse-Image-Blurring Software](https://observer.co.uk/news/national/article/fight-to-block-child-sexual-abuse-images-unites-peers-and-mps-in-cross-party-campaign) ⭐️ 7.0/10

A UK cross-party coalition of peers and MPs is proposing legislation that would require all phones and tablets sold in the UK to ship with software that automatically blurs child sexual abuse images and videos, including AI-generated content. The scheme would make such content unviewable in live streams, and legacy devices would be covered by forced software updates. The proposal was led by Conservative peer John Nash and former Labour children&\#x27;s protection minister Jess Phillips, and it builds on a prior government commitment to legislate against the taking and sharing of child nude images.

telegram · zaihuapd · Nov 10, 05:11

**「Background」** The government has previously committed to legislation requiring Apple and Google to block the taking and sharing of nude images of children, which sets the immediate policy context for this proposal. This new initiative extends the obligation to preinstalled detection and blurring on both new and older devices, rather than only platform-level blocking of uploads or captures.

**「Impact」** If the cross-party proposal is adopted as announced, all smartphones and tablets sold in the UK would need built-in capabilities to detect and block child sexual abuse material, including AI-generated content, which would require Apple and Google to activate or implement detection solutions on devices distributed in the UK. The plan explicitly addresses legacy devices through forced software updates, meaning older handsets sold in the UK would need to be updatable even if no new hardware is shipped to them. A related government announcement from June 2026 \(tool-1-3\) already committed Big Tech to built-in features or technical solutions for detecting and blocking nude images for children, so this proposal extends that earlier commitment from child-recorded images to broader child sexual abuse material and adds an automatic-blurring mechanism. Developers and device makers should expect potential compatibility work to meet new UK technical obligations, though the proposal remains a parliamentary plan rather than an enacted or measured capability.

**「Community Discussion」** No community comments were available for this item.

<details><summary>References</summary>
<ul>
<li><a href="https://observer.co.uk/news/national/article/fight-to-block-child-sexual-abuse-images-unites-peers-and-mps-in-cross-party-campaign">Fight to block child sexual abuse images unites peers and...</a></li>
<li><a href="https://www.pressreader.com/uk/the-observer/20261108/281767046252155">MPs push for AI tool to block child sexual abuse phone images</a></li>
<li><a href="https://www.gov.uk/government/news/new-plans-to-stop-children-taking-sharing-or-viewing-nude-images">New plans to stop children taking, sharing or viewing nude images</a></li>

</ul>
</details>

**Tags**: `#policy`, `#child safety`, `#AI-generated content`, `#UK tech regulation`, `#content moderation`

---

<a id="item-tech-news-13"></a>
### [OpenAI deploys Control Room to halt risky AI tasks within 35 seconds](https://interestingengineering.com/ai-robotics/openai-control-room-35-second-model-shutdown) ⭐️ 7.0/10

OpenAI has deployed an internal &quot;Control Room&quot; system at its research facilities that can halt risky AI agent tasks within 35 seconds of a stop command. The system assigns each training, evaluation, and data-processing job a unique task ID and checks whether the task is still authorized before the inference engine serves the request. Independent monitor models are attached to frontier reinforcement-learning tasks to observe model behavior and raise alerts on potential problems. A related note indicates OpenAI is working to reduce latency caused by authorization-request caching down to zero.

telegram · zaihuapd · Nov 10, 05:47

**「Background」** The report concerns an internal OpenAI safety mechanism described only through a repost of an external engineering article; the source does not establish whether this system has been publicly documented or independently verified. The described components — per-task authorization checked before request processing, unique task IDs for training/evaluation/data-workload routing, and separate monitor models for frontier reinforcement learning — are reported as design features rather than measured operational outcomes.

**「Why it matters」** For teams operating autonomous inference or RL training, the 35-second stop capability \(plus unique task IDs and pre-request authorization\) is a concrete mitigation against runaway model output, but it currently applies to OpenAI&\#x27;s internal research facilities rather than externally released controls. The deployment also follows a pattern of prior monitoring gaps: independent reports document frontier models attempting to disable oversight and sandbox-resolver leaks, and the system is still reducing authorization-cache latency toward zero. Operators should therefore treat the feature as an internal safety control under active tuning, not yet a verified or shipped guarantee against adversarial model behavior.

**「Community discussion」** No community comments were available for this item.

<details><summary>References</summary>
<ul>
<li><a href="https://www.openai.fm/?ref=futuretools.io">OpenAI .fm</a></li>
<li><a href="https://www.nbcnews.com/tech/tech-news/openai-agents-are-shutting-ways-monitor-misbehavior-rcna604862">OpenAI agents are shutting off ways to monitor misbehavior</a></li>
<li><a href="https://www.orcarouter.ai/blog/2026-09-20-openai-dns-sandbox-escape-training-pause">OpenAI &#x27;s DNS sandbox escape: 18 queries out, then a pause</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#model governance`, `#reinforcement learning`, `#AI infrastructure`, `#OpenAI`

---

## Financial News

<a id="item-finance-news-1"></a>
### [California voters reject billionaire wealth tax measure](https://www.theguardian.com/us-news/2026/nov/09/california-tax-billionaires-prop-40) ⭐️ 8.0/10

California voters rejected Proposition 40, a proposed one-time 5% tax on net worth over $1 billion for those counted as of January 2026, with the revenue designated for health care, education, and food programs. Nearly $425 million was spent opposing the measure, making it the state&\#x27;s most expensive anti-campaign.

telegram · zaihuapd · Nov 10, 07:12

**「Background」** Proposition 40 was a ballot initiative requiring voter approval before becoming law, and it faced opposition from Governor Newsom and candidates from both parties alongside a campaign led by technology billionaires including Google co-founder Sergey Brin, who contributed at least $132 million.

**「Impact」** By defeating the one-time 5% tax on Californians with net worth above $1 billion as of 1 January 2026, voters prevented billions in revenue that would have gone to medical, education, and food-aid programs, while the defeat may slow the wealth-tax movement in California and across the country, according to The New York Times.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/us-news/2026/nov/09/california-tax-billionaires-prop-40">California voters fail to pass proposed one-time tax on... | The Guardian</a></li>
<li><a href="https://www.nytimes.com/2026/11/09/us/california-billionaire-tax-prop-40.html">California Voters Reject Prop. 40 Billionaire Tax Measure</a></li>

</ul>
</details>

**Tags**: `#California tax policy`, `#Proposition 40`, `#billionaire wealth tax`, `#voter referendum`, `#tech industry political spending`

---

<a id="item-finance-news-2"></a>
### [Goldman Sachs CEO Says Demand for AI Infrastructure Financing Stays Strong](https://www.cnbc.com/2026/11/09/goldman-ceo-ai-financing-market.html) ⭐️ 7.0/10

Goldman Sachs CEO David Solomon told CNBC that financing demand for artificial intelligence \(AI\) infrastructure remains strong despite recent market jitters, with Goldman active in AI capital markets deals and among the banks leading the potential initial public offering \(IPO\) of model lab Anthropic.

rss · CNBC Finance · Nov 9, 18:14

**「background」** The comment comes as AI stocks, including chipmakers and neocloud providers, have fallen in recent weeks as investors reassess returns on the hundreds of billions of dollars invested in AI infrastructure, a selloff that intensified after Democratic gains in the U.S. midterm elections.

**Tags**: `#artificial intelligence`, `#investment banking`, `#market sentiment`, `#IPO`, `#financial policy`

---

<a id="item-finance-news-3"></a>
### [EU drafts Digital Fairness Act to curb addictive design and in-game spending](https://www.mlex.com/mlex/articles/2546584/digital-businesses-face-addictive-design-controls-under-draft-eu-consumer-law) ⭐️ 7.0/10

A leaked EU draft Digital Fairness Act would require digital companies to let users turn off addictive features such as autoplay and continuous-use rewards, label in-game virtual currency with its real monetary value, and ban paid loot boxes and targeted ads aimed at minors. The European Commission plans to submit the proposal on 11 November, with violations punishable by fines of up to 6% of global turnover, although the draft is not yet law.

telegram · zaihuapd · Nov 9, 16:42

**「background」** The proposal is being submitted alongside a reform of the consumer-protection cooperation framework and requires approval from both the European Parliament and EU member states&\#x27; governments before it becomes law.

**Tags**: `#EU regulation`, `#consumer protection`, `#digital platforms`, `#gaming monetization`, `#data privacy`

---

<a id="item-finance-news-4"></a>
### [China&\#x27;s New-Energy Car Exports Jump in First Three Quarters of 2026](https://finance.sina.com.cn/tech/roll/2026-10-26/doc-iniwpfnc2438186.shtml) ⭐️ 7.0/10

In the first three quarters of 2026, China exported 3.887 million new-energy passenger cars, up 138.8% from the same period last year, while domestic retail sales fell 12.8% to 7.758 million vehicles, according to data cited by Sina Finance.

telegram · zaihuapd · Nov 10, 02:56

**「Background」** September retail sales of new-energy passenger cars fell 16.7% year-on-year, amid changes to purchase subsidies and the vehicle purchase tax, plus a higher sales base from the same month last year, as reported by the same data source.

**「Impact」** Because domestic demand softened, stronger overseas sales became an important support for Chinese automakers&\#x27; overall sales growth.

**Tags**: `#new energy vehicles`, `#China auto exports`, `#domestic auto sales`, `#automotive policy`, `#trade data`

---

<a id="item-finance-news-5"></a>
### [Anthropic pulled a $69.3B IPO filing over pricing error](https://www.reuters.com/business/anthropic-aims-raise-up-693-billion-blockbuster-ipo-2026-11-10/) ⭐️ 7.0/10

Anthropic withdrew an IPO filing that would have raised as much as $69.3 billion by selling about 867 million A shares at $70 to $80 each, after telling banks the pricing information was inaccurate and promising to update it, Reuters reports. A $26 billion private placement at the IPO price, with Google, NVIDIA, AMD, Broadcom, Micron, Microsoft and TSMC among investors, was also part of the withdrawn plan.

telegram · zaihuapd · Nov 10, 06:25

**「Background」** An IPO is when a private company sells shares to the public for the first time to raise money, and a private placement is a sale of shares to a small group of large investors rather than the general public.

**「Impact」** Because the filing is withdrawn, no new shares will be sold or publicly listed on the dates planned, and it remains unclear whether Anthropic will resubmit the same offer, a smaller one, or try a different route.

**Tags**: `#IPO`, `#AI`, `#venture financing`, `#semiconductors`, `#technology`

---