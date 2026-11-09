---
layout: default
title: "Horizon Summary: 2026-11-09 (ZH)"
date: 2026-11-09
lang: zh
---

> 从 40 条内容中筛选出 15 条重要资讯。

---

**科技新闻**
1. [剑桥团队 AI 辅助设计禽流感候选疫苗，动物试验显示广谱保护](#item-tech-news-1) ⭐️ 9.0/10
2. [Frontier3DBench: 11 coding-agent configurations tested on 3D objects, scenes, and interactive worlds](#item-tech-news-2) ⭐️ 8.0/10
3. [iOS 沙盒逃逸漏洞 worse\_query 公开 PoC，影响 iOS 26.x 及 27.2/27.3 beta](#item-tech-news-3) ⭐️ 8.0/10
4. [KetchUp：基于 Rust 与 WebGPU 的开源 SketchUp 替代方案](#item-tech-news-4) ⭐️ 7.0/10
5. [Third-party article claims most Toyota/Lexus cars can be remotely unlocked; scope unverified](#item-tech-news-5) ⭐️ 7.0/10
6. [Chimera Vocal Synth](#item-tech-news-6) ⭐️ 7.0/10
7. [Outlook.com 开始拒收无 DMARC 配置的发件域名](#item-tech-news-7) ⭐️ 7.0/10
8. [AI 泡沫是否存在？一篇质疑该说法的技术与经济辨析](#item-tech-news-8) ⭐️ 7.0/10
9. [Dux: Free open-source Wayland desktop shell gains file manager, theming, and atomic distro support](#item-tech-news-9) ⭐️ 7.0/10
10. [llama-modchip claims 284B DeepSeek inference on 64GB RAM without a GPU, performance questioned](#item-tech-news-10) ⭐️ 7.0/10
11. [用 &lt;details&gt;/&lt;summary&gt; 折叠 AI 生成的冗长 PR 描述](#item-tech-news-11) ⭐️ 7.0/10
12. [parse\_number\(\) as a SQLite extension: C vs Rust](#item-tech-news-12) ⭐️ 7.0/10
13. [NASA 计划 2028 年底发射 PROMISE 月球车](#item-tech-news-13) ⭐️ 7.0/10

**财经新闻**
1. [中国继续暂停对美 24%加征关税，保留 10%税率](#item-finance-news-1) ⭐️ 8.0/10
2. [Epoch AI 估算：中国六家 AI 企业年化营收约 110 亿美元，为美企十分之一](#item-finance-news-2) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [剑桥团队 AI 辅助设计禽流感候选疫苗，动物试验显示广谱保护](https://www.cam.ac.uk/stories/ai-developed-vaccines-against-viruses) ⭐️ 9.0/10

Cambridge team&\#x27;s AI-designed avian flu vaccine candidate demonstrated broad-spectrum protection in mice and ferrets, outperforming WHO-based controls, with human trials planned.

telegram · zaihuapd · 11月9日 03:00

**标签**: `#AI drug discovery`, `#vaccine development`, `#avian influenza`, `#broad-spectrum immunity`, `#preclinical research`

---

<a id="item-tech-news-2"></a>
### [Frontier3DBench: 11 coding-agent configurations tested on 3D objects, scenes, and interactive worlds](https://www.reddit.com/r/MachineLearning/comments/1xrhg3a/can_coding_agents_build_interactive_3d_worlds/) ⭐️ 8.0/10

Einsia&\#x27;s Frontier3DBench evaluates 11 model-harness configurations across 145 tasks in nine categories, testing whether the same coding agent can build editable 3D objects, assemble scenes, and run interactive worlds in Unreal Engine. The evaluation uses 165 world submissions scored through rendered views, scene inspection, and runtime tests. GPT-6.1-sol leads overall and on object and scene tasks, while GPT-6-astra leads interactive worlds; MiniMax-M3.1-Flash ranks sixth overall but second on scene editing. Every configuration scores lower on reference-based reconstruction than text-driven generation, and across world submissions local mechanisms score 83.08 out of 100 versus 30.26 for stateful workflows.

reddit · r/MachineLearning · /u/OliviaYii · 11月9日 03:41

**「Background」** This benchmark extends earlier AI 3D-generation work by adding a multi-stage progression: generating individual assets, then composing them into scenes, then producing runnable environments with persistent state. Prior evaluations often stop at visual quality of static meshes; Frontier3DBench adds behavior tests on running Unreal Engine worlds. The paper and code are open at lab.einsia.ai/frontier3dbench and GitHub&\#x27;s Einsia/Frontier3D.

**「Impact」** Developers using these agents should expect stateful, interactive-world generation to lag behind single-asset text-driven generation by a wide margin; the 83.08 vs 30.26 gap means agents should be tested against runtime behavior rather than static outputs before integration into pipeline tooling.

**标签**: `#AI agents`, `#3D generation`, `#machine learning benchmarks`, `#open source evaluation`, `#game engines`

---

<a id="item-tech-news-3"></a>
### [iOS 沙盒逃逸漏洞 worse\_query 公开 PoC，影响 iOS 26.x 及 27.2/27.3 beta](https://x.com/forcequitOS/status/2119475139528020218?) ⭐️ 8.0/10

11 月 8 日，forcequitOS 公开发布名为 worse\_query 的 iOS 沙盒逃逸 PoC，其影响版本被描述为 iOS 26.0–26.7.2 以及 27.2（含 27.3 beta）；PoC 可在 App Group 配置后访问系统路径并修改应用数据。worse\_query 被描述为 bad\_query 的继任者，社区已出现基于它的 GestaltX 等工具。来源是 Telegram 转发的一条 X 帖子，未附独立验证材料。

telegram · zaihuapd · 11月9日 02:36

**「相关背景」** iOS 沙盒（sandbox）是强制隔离应用数据与系统资源的机制，沙盒逃逸意味着恶意或实验性代码能读写本应受保护的系统路径与相邻应用数据。此前类似的 App Group 机制滥用型研究（如 bad\_query）已展示过同类风险，worse\_query 被其发布方定位为该类研究的后续工作。

**「影响」** 已安装上述版本且授权或可配置 App Group 的受信任开发者/测试人员需评估 PoC 暴露的风险；普通用户在未授权第三方扩展时风险较低。受影响方应暂缓使用该 PoC 及其衍生工具，并关注苹果后续版本修复。

**「社区讨论」** 暂无可用社区评论。

**标签**: `#iOS security`, `#sandbox escape`, `#zero-day`, `#mobile exploit`, `#open source tooling`

---

<a id="item-tech-news-4"></a>
### [KetchUp：基于 Rust 与 WebGPU 的开源 SketchUp 替代方案](https://ketchup3d.github.io/app/) ⭐️ 7.0/10

KetchUp 是一个用 Rust 编写、基于 WebGPU 构建的开源 3D 建模软件，定位为 SketchUp 的替代方案。该项目目前作为开源桌面 CAD 工具发布，其官网（ketchup3d.github.io/app/）已公开。与 SketchUp 当前仅限网页、且桌面版需订阅付费的模式相比，KetchUp 走的是免费开源路线。社区讨论显示项目吸引了大量关注，但其工程成熟度与市场影响力尚未得到独立验证。

hackernews · dcoulmbe · 11月8日 22:35 · [社区讨论](https://news.ycombinator.com/item?id=50418176)

**「背景」** SketchUp 原开发者 Trimble 已将重心转向基于网页的 UI，并先后取消了免费版本与永久授权模式，使得免费使用桌面版 SketchUp 不再可行。这种转向在长期用户中引发了不满，也为第三方替代方案创造了空间。

**「影响」** 对于依赖 SketchUp 桌面版进行轻量级 3D 建模的个人用户（如家庭装修建模者），KetchUp 提供了无需订阅即可继续使用桌面编辑器的选择；但其能否无缝打开并编辑现有的 SketchUp 文件、以及功能完整度，仍需实际测试确认。

**「社区讨论」** Hacker News 上的讨论既表达了对替代工具的欢迎，也提出了更深层的问题：一方面，用户反映 Trimble 的许可政策损害了长期体验；另一方面，有人开始质疑是否应转而用 AI 工具（如 Claude 或 codex）自行构建所需软件，而非学习现有产品的完整流程。

**标签**: `#open source`, `#CAD`, `#Rust`, `#WebGPU`, `#3D modeling`

---

<a id="item-tech-news-5"></a>
### [Third-party article claims most Toyota/Lexus cars can be remotely unlocked; scope unverified](https://shubs.io/unlocking-any-car-from-x-brand-in-most-of-the-world/) ⭐️ 7.0/10

一份第三方文章声称可通过联网漏洞远程解锁某大品牌的多数汽车，社区将品牌识别为丰田/雷克萨斯，但文章本身未提供可核验的技术细节或独立验证。文章与评论中的“任何车型”说法缺乏证据支持，评论者亦指出年代较旧的车型（如 2009 款凯美瑞、第四代 Hilux）未必受影响。目前仅有文章链接与 HN 评论，无法确认漏洞细节、受影响的具体年份/平台或是否已向厂商披露。

hackernews · infosecau · 11月9日 00:10 · [社区讨论](https://news.ycombinator.com/item?id=50419215)

**「背景」** 联网汽车常依赖在线账户、移动 App 与云端通信实现远程解锁、定位与诊断等功能，这些通道一旦被误配或存在认证缺陷，可能成为远程攻击面。此类汽车安全议题近年持续受到关注，但本次报道未给出可追溯的漏洞编号、CVSS 评分或厂商响应记录。

**「影响」** 若该漏洞属实，车主可能面临未经授权远程开启车门的风险，建议受影响车主检查官方 App 权限、保持固件与车机软件更新至厂商最新状态，并仅在官方渠道获取安全公告；在缺乏独立验证前不应将其视为已确认的普遍缺陷。

**「社区讨论」** 部分评论认为“任何车型”的表述过强，并以自家旧款车型为例质疑受影响范围；另有评论担忧“常在线汽车”会导致车主对车辆控制权下降、数据被跟踪或转售，并将此视为服务条款与商业模式问题而非单一技术缺陷。评论中的品牌识别仅为主观观察，不代表对文章结论的确认。

**标签**: `#automotive security`, `#connected cars`, `#vulnerability disclosure`, `#privacy`, `#open source discussion`

---

<a id="item-tech-news-6"></a>
### [Chimera Vocal Synth](https://chimera-vocal-synth.vercel.app/) ⭐️ 7.0/10

An interactive web-based vocal synthesis tool with community-driven examples and diverse practical applications.

hackernews · nmstoker · 11月8日 22:36 · [社区讨论](https://news.ycombinator.com/item?id=50418182)

**标签**: `#vocal synthesis`, `#open source`, `#AI audio`, `#browser technology`, `#human-computer interaction`

---

<a id="item-tech-news-7"></a>
### [Outlook.com 开始拒收无 DMARC 配置的发件域名](https://mailroute.net/blog/outlook-rejecting-email-without-dmarc) ⭐️ 7.0/10

Outlook.com 已开始拒收未配置 DMARC 的发件域邮件，以邮件身份验证失败的形式返回 5xx 永久投递错误。这一政策变化使缺乏 DMARC 记录的小规模发件方、自建邮件服务器及部分 VPS 托管的邮件服务面临邮件无法送达的问题。社区对此反应不一，有人认为是必要的反垃圾措施，也有人质疑该变更缺乏透明度且同时存在非公开的黑名单机制。

hackernews · xmddmx · 11月8日 19:20 · [社区讨论](https://news.ycombinator.com/item?id=50416158)

**「背景」** DMARC（Domain-based Message Authentication, Reporting &amp; Conformance）是一种电子邮件身份验证协议，允许发件域所有者指定当 SPF 或 DKIM 验证失败时收件服务器应采取的措施。许多邮件服务商已逐步要求发件方配置 DMARC 以提升反垃圾邮件效果，Outlook.com 的此项变更是此类趋势的最新一步。

**「影响」** 尚未配置 DMARC 记录的个人或组织域名所发送的邮件将被 Outlook.com 拒收，发件方需立即添加 DMARC 记录以恢复投递。部分管理员还反映 Outlook 存在不公开的黑名单机制，即使 SPF/DKIM/DMARC 全部正确配置，邮件仍可能被静默丢弃而无法送达收件箱。

**「社区讨论」** 部分社区成员认为拒绝无 DMARC 域邮件是合理且必要的反垃圾措施，但对缺乏透明通知表示不满；另有管理员指出 Outlook 长期以来对某些域/IP 存在非公开屏蔽，即使完整验证配置也会被静默丢弃邮件。

**标签**: `#email infrastructure`, `#DMARC`, `#Microsoft`, `#spam prevention`, `#system administration`

---

<a id="item-tech-news-8"></a>
### [AI 泡沫是否存在？一篇质疑该说法的技术与经济辨析](https://matteoraso.github.io/im-not-convinced-the-ai-bubble-exists.html#im-not-convinced-the-ai-bubble-exists) ⭐️ 7.0/10

技术作者 matteoraso 发文质疑当前 AI 领域存在“泡沫”的说法，主张尽管估值高企，但技术效用与增长潜力真实存在。论证聚焦三个层面：技术成熟度（是否仍局限于 next-token 预测）、公司财务动态（收入增长 vs. 利润率）、以及历史类比（铁路、半导体等先例）。文章与 Hacker News 评论区共同构成了技术性辩论，但作者与评论均明确承认缺乏新的实测数据，结论仍属推测。

hackernews · matteoraso · 11月8日 23:44 · [社区讨论](https://news.ycombinator.com/item?id=50418975)

**「背景」** “AI 泡沫论”认为当前对大模型的资本投入远超其商业回报能力，可能重演历史上技术革命初期的投机热潮。该辩论的核心前提是判断 LLM 是否仅为 next-token 预测机，这一技术定性直接决定长期商业价值判断。历史先例如铁路、半导体、塑料和网络的公用事业价值早期已被普遍认知，但商业化成熟耗时漫长。

**「影响」** 对 AI 实验室与企业买家的实际影响是：如果模型商业化进入实验/token 消耗阶段尾声且价格战开始，利润率可能承压，而非仅收入增长。评论指出企业买家作为闭源模型主要消费者可能正被低价开源模型竞争所取代，这可能使价值更多流向消费者或公司而非 AI 实验室本身。

**「社区讨论」** HN 评论中主要分歧在于：一方认为泡沫关乎投资者耐心与套现动机而非技术潜力（swatcoder）；另一方指出只要核心技术仍是 next-token 预测，无论增加推理代理或智能体群集，本质上不会成为 AGI（treebeard901）。财务层面有观点强调“收入增长”不等同于“利润增长”，并列出 Anthropic IPO 重估、开源模型效率持续改善、数据中心债务大幅折价等看跌信号（fraywing、maxnevermind）。这些均为社区观点而非经核实的事实。

**标签**: `#artificial intelligence`, `#machine learning`, `#technology industry`, `#LLM`, `#investment analysis`

---

<a id="item-tech-news-9"></a>
### [Dux: Free open-source Wayland desktop shell gains file manager, theming, and atomic distro support](https://duxlabs.dev/) ⭐️ 7.0/10

Dux is a free, open-source Wayland desktop shell that combines a window manager with an integrated file manager and theming, and now adds official support for atomic Linux distributions such as Bazzite. It was previously known as Dank Material Shell \(DMS\) and has rebranded to Dux, with its latest release being version 2.0. The project is currently in active development and still maturing, which some users flag alongside the project&\#x27;s install script delivery method.

hackernews · indigodaddy · 11月8日 19:08 · [社区讨论](https://news.ycombinator.com/item?id=50416053)

**「背景」** A Wayland desktop shell \(or compositor\) is the program that draws the screen, handles input, and manages windows under the Wayland display server protocol. Dux/previous DMS is a newly developed, user-focused compositor that bundles a file manager and theming rather than treating them as separate components.

**「影响」** Atomic-distro users such as those on Bazzite can now run the shell without the manual workaround that previously made installation awkward on those systems. Conversely, the \`curl \| sh\` installation approach raises trust concerns for some users, who argue such projects should be packaged and reviewed through distro repositories before being trusted unconditionally.

**「社区讨论」** Long-term users describe the experience as &\#x27;slick&\#x27; and good enough to help mainstream the Niri compositor, while a contributor noted the earlier &\#x27;Dank&\#x27; name was officially dropped in the 2.0 release. Others raise concerns about maturity relative to alternatives like Hyprland or Sway, note a perceived similarity to Android, and question the safety of the unauthenticated install script.

**标签**: `#Wayland`, `#open source`, `#desktop shell`, `#Linux`, `#atomic distros`

---

<a id="item-tech-news-10"></a>
### [llama-modchip claims 284B DeepSeek inference on 64GB RAM without a GPU, performance questioned](https://github.com/synchopate/llama-modchip) ⭐️ 7.0/10

GitHub 项目 llama-modchip（synchopate/llama-modchip，2026-11-08 被 Hacker News 讨论）声称无需 GPU、仅用 64GB RAM 即可运行 284B 参数的 DeepSeek 模型。评论质疑该仓库是否真正实现了 DeepSeek 的「modchip 配置」，有人实测其在 Nemotron 模型上的 CPU 推理速度仅与普通 llama.cpp 相当（prefill 阶段似乎更快）。项目未提供独立基准，且其核心方法被部分评论认为是「难以看懂的密集文字」。

hackernews · joshcsimmons · 11月8日 10:22 · [社区讨论](https://news.ycombinator.com/item?id=50411961)

**「背景」** 大型语言模型在 CPU 上运行依赖量化（如 llama.cpp 的 IQ3\_S、4-bit 量化）降低显存占用；社区经验表明 4-bit 通常是在模型规模与性能之间的最优折中点，低于 4-bit 或低于 8-bit（对语音等专用模型）会显著降低质量。

**「影响」** 如果该仓库能可靠运行，用户可在不购买独立 GPU 的情况下本地部署超大模型；但实际采用前应自行验证量化后的输出质量与推理速度，因为其性能表现尚未被独立确认。

**「社区讨论」** 评论者 aappleby 指出该仓库似乎没有设置 DeepSeek 的 modchip 选项，实测其在 Nemotron 上的 CPU 推理速度仅与普通 llama.cpp 相当；antirez 则用 128GB 统一内存可跑代码代理（prefill 约 300 tok/s）的案例说明低资源方案的潜力。

**标签**: `#local AI`, `#quantization`, `#CPU inference`, `#LLM deployment`, `#open source`

---

<a id="item-tech-news-11"></a>
### [用 &lt;details&gt;/&lt;summary&gt; 折叠 AI 生成的冗长 PR 描述](https://simonwillison.net/2026/Nov/9/details-summary/) ⭐️ 7.0/10

Simon Willison 提出把 AI 编码代理（如 Claude Code、Codex）生成的冗长 PR 描述藏进 HTML 的 &lt;details&gt;/&lt;summary&gt; 元素，让 PR 只先展示一段人工作为的高层说明。示例中 &lt;details&gt; 的 &lt;summary&gt; 写的是模型名与 effort 等级（例如 &quot;Claude Opus 5.5&quot;），折叠体中则放置完整的代理生成描述。该技术的关键点在于 GitHub Markdown 原生支持 &lt;details&gt;/&lt;summary&gt;，可直接把标签放进 issue 或 PR 正文，无需任何扩展。作者已在 datasette、datasette-agent、llm 等多个仓库的 PR 中试用，并把这一用法作为面向 PR 审阅者的“人工筛选承诺”：折叠后的完整内容仍保留，只把开篇摘要交给人的判断来把控质量。

rss · Simon Willison · 11月9日 04:25

**「背景」** 随着 Claude Code、Codex 等 AI 编码代理成为常见的 PR 创建方式，代理生成的 PR 描述往往全面而冗长，导致审阅者在打开 PR 时需要吸收大量信息。HTML 的 &lt;details&gt;/&lt;summary&gt; 元素本身是 Web 标准组件，会在 Markdown 渲染为可展开的标题；作者建议利用 GitHub 对这些原生标签的支持来解决这个工作流可读性问题。

**「影响」** 审阅者在 PR 列表和预览中只会先看到作者精选的简短说明与可能附带的截图，展开后才看到代理生成的完整内容，因此可在不丢失信息的前提下降低一次性阅读负担。团队若想推广该做法，需要在贡献指南中明确“&lt;details&gt;/&lt;summary&gt; 折叠写法”并约定 &lt;summary&gt; 的格式（如模型名 + effort 等级），避免折叠内容与人类摘要脱节。

**「社区讨论」** 该帖未收到任何评论，因此无法提供来自社区的意见或实际体验。作者个人提到的一个缺口是 GitHub Markdown 编辑器缺少一键插入 &lt;details&gt;/&lt;summary&gt; 的按钮，这既是输入便利性问题，也被视为推广该用法的一个阻碍。

**标签**: `#software engineering`, `#AI coding agents`, `#developer workflow`, `#open source`, `#HTML`

---

<a id="item-tech-news-12"></a>
### [parse\_number\(\) as a SQLite extension: C vs Rust](https://simonwillison.net/2026/Nov/8/sqlite-parse-number-c-vs-rust/) ⭐️ 7.0/10

A technical comparison of implementing a SQLite parse\_number\(\) extension in C versus Rust, examining performance, code complexity, and binary size.

rss · Simon Willison · 11月8日 22:26

**标签**: `#SQLite`, `#C programming`, `#Rust programming`, `#database extensions`, `#performance comparison`

---

<a id="item-tech-news-13"></a>
### [NASA 计划 2028 年底发射 PROMISE 月球车](https://www.scientificamerican.com/article/nasa-reveals-new-lunar-rover-promise-to-launch-to-moon-in-2028/) ⭐️ 7.0/10

NASA 计划于 2028 年底用蓝色起源（Blue Origin）的着陆器发射 PROMISE 月球车，在月球南极附近开展为期 18 个月的任务。该车以“毅力号”和“好奇号”火星车为设计参考，配备钻头和仪器，用于勘察水冰等月壤资源，并研究辐射与月表环境。NASA 称该任务将为未来的月球基地建设和载人任务探路，同时计划部署着陆器与通信卫星等基础设施。

telegram · zaihuapd · 11月8日 08:32

**「背景」** PROMISE（Planetary Resource In-Situ Science Explorer）是美国国家航空航天局（NASA）规划的无人月球车任务，设计参考为“毅力号”（Perseverance）和“好奇号”（Curiosity）火星车，将使用蓝色起源（Blue Origin）的着陆器在月球南极附近开展为期 18 个月的探测任务，重点研究月壤、辐射及资源分布，为未来载人月球基地行动探路。

**「影响」** 若按计划实施，该任务将把着陆器与通信卫星等基础设施的部署节奏推向 2020 年代后期，要求相关载荷、通信与轨道保障团队提前适配 2028 年的发射窗口与月球南极环境。

**标签**: `#space systems`, `#lunar exploration`, `#NASA`, `#hardware`, `#robotics`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [中国继续暂停对美 24%加征关税，保留 10%税率](https://mp.weixin.qq.com/s/nNxJB3y0YA_2zJvOK6onUQ) ⭐️ 8.0/10

国务院关税税则委员会宣布，经国务院批准，自 2026 年 11 月 10 日 13 时 01 分起 2 个月内，继续暂停实施 24%的对美加征关税税率，保留 10%的加征关税税率。该调整是为落实中美两国元首华盛顿会晤达成的成果共识，依据关税法、海关法、对外贸易法等法律法规作出。

telegram · zaihuapd · 11月9日 04:03

**「背景」** 中国在 2025 年 11 月曾首次宣布暂停 24% 对美加征关税、保留 10% 税率，为期 90 天；本次系该措施的延续，并明确以中美元首在华盛顿会晤达成的共识为政策依据。

**「影响」** 这一暂停将降低两类商品在两个月内的实际进口成本：受暂停的 24%加征关税覆盖的品类适用更低税率，而仅保留 10%的部分则相对此前水平有所上升，主要影响进口美国商品的贸易商、相关供应链企业以及终端消费者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chwang.com/article/192183294433">重磅！ 中 美 联合发布声明：双方均保留 10 % 关 税 -出海网</a></li>

</ul>
</details>

**标签**: `#tariffs`, `#US-China trade`, `#trade policy`, `#customs`, `#economic policy`

---

<a id="item-finance-news-2"></a>
### [Epoch AI 估算：中国六家 AI 企业年化营收约 110 亿美元，为美企十分之一](https://cn.nikkei.com/china/ccompany/64644-2026-11-09-10-14-47.html) ⭐️ 7.0/10

AI 数据库机构 Epoch AI 估算，OpenAI 与 Anthropic 的 AI 相关年化收入合计约 1050 亿美元，而字节跳动、阿里巴巴/Qwen、智谱/GLM、月之暗面/Kimi、DeepSeek、MiniMax 等六家中国企业的合计年化收入约为 110 亿美元，约相当于前者的 10.5%。其中字节跳动相关收入约 40 亿美元，为中国企业中最高。这些数字均为基于不同月份数据的估算，并非审计后的实际财报。

telegram · zaihuapd · 11月9日 03:12

**「背景」** Epoch AI 根据开源、低价和激烈价格竞争的中国 AI 市场特点，采用不同月份数据进行估算；其 OpenRouter 平台数据显示，GLM-5 的调用中第三方服务占 75%，DeepSeek V4 Pro 约七成来自外部使用。

**「影响」** 该比较主要反映中美头部 AI 公司在商业化规模上的差距，有助于理解开源普及、低定价和第三方调用在中国市场中的实际变现程度。

**标签**: `#AI industry`, `#revenue comparison`, `#China tech`, `#market analysis`, `#Epoch AI`

---