---
layout: default
title: "Horizon Summary: 2026-07-29 (ZH)"
date: 2026-07-29
lang: zh
---

> 从 42 条内容中筛选出 4 条重要资讯。

---

1. [Show HN: Open-source engine running Gemma 4 26B in 2 GB RAM on any M-series Mac](#item-1) ⭐️ 8.0/10
2. [Superlogical](#item-2) ⭐️ 8.0/10
3. [KOReader：面向电子墨水屏设备的开源文档阅读器](#item-3) ⭐️ 8.0/10
4. [AI 蠕虫可通过 Microsoft Copilot for Word 进行自我传播](#item-4) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Show HN: Open-source engine running Gemma 4 26B in 2 GB RAM on any M-series Mac](https://github.com/drumih/turbo-fieldfare) ⭐️ 8.0/10

TurboFieldfare is an open-source Swift and Metal inference engine that runs the Gemma 4 26B model on M-series Macs using only 2 GB of RAM by streaming MoE experts from the SSD.

hackernews · gitpusher42 · 7月29日 15:05 · [社区讨论](https://news.ycombinator.com/item?id=49098510)

**标签**: `#Machine Learning`, `#LLM Inference`, `#macOS`, `#Open Source`, `#Systems Engineering`

---

<a id="item-2"></a>
## [Superlogical](https://www.superlogical.com/) ⭐️ 8.0/10

Mitchell Hashimoto introduces Superlogical, a new venture focused on building next-generation terminal applications using the open-source libghostty library.

hackernews · yan · 7月29日 15:41 · [社区讨论](https://news.ycombinator.com/item?id=49098965)

**标签**: `#developer-tools`, `#terminal-emulators`, `#open-source`, `#software-architecture`, `#ghostty`

---

<a id="item-3"></a>
## [KOReader：面向电子墨水屏设备的开源文档阅读器](https://koreader.rocks/) ⭐️ 8.0/10

KOReader 作为一款专为 Kindle、Kobo 和 ReMarkable 等电子墨水屏（E Ink）设备设计的开源、高度可定制文档阅读器，持续受到广泛关注。它原生支持 EPUB、PDF 等多种格式，无需用户进行繁琐的文件格式转换。 对于电子书阅读器用户而言，KOReader 通过提供 PDF 重排、阅读进度同步和 Calibre 关联等高级功能，摆脱了闭源平台的生态限制。它赋予了用户对阅读硬件的完全控制权，成为推动设备越狱和开源软件普及的重要力量。 尽管 KOReader 支持 Android 和 Linux 等多种平台，但在 Kindle 等设备上安装通常需要进行系统越狱。此外，部分用户指出，其高度可定制的界面在开箱即用时可能会显得不够直观或较为繁杂。

hackernews · Cider9986 · 7月29日 11:05 · [社区讨论](https://news.ycombinator.com/item?id=49095865)

**背景**: E Ink（电子墨水屏）是一种模拟纸张上普通墨水外观的显示技术，在阳光直射下具有极佳的可读性且非常省电。亚马逊 Kindle 等闭源电子阅读器通常会将用户限制在特定的文件格式和封闭的生态系统中。像 KOReader 这样的开源替代方案旨在通过提供广泛的格式兼容性和可定制的阅读选项，来解放这些硬件设备。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://koreader.rocks/">KOReader</a></li>
<li><a href="https://grokipedia.com/page/KOReader">KOReader</a></li>
<li><a href="https://en.wikipedia.org/wiki/E_Ink">E Ink - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 用户盛赞 KOReader 卓越的格式支持以及集成 Z-Library 等实用功能，有人甚至表示这直接影响了他们对硬件设备的购买决策。然而，也有部分用户批评其用户界面（UI/UX）不够直观，将其比作阅读器领域的 GIMP，并反映存在偶尔卡顿或手势响应不灵敏的问题。

**标签**: `#open-source`, `#e-ink`, `#hardware-hacking`, `#software-tools`, `#mobile-development`

---

<a id="item-4"></a>
## [AI 蠕虫可通过 Microsoft Copilot for Word 进行自我传播](https://enklypesalt.com/posts/context-collapse-part3-ai-worming-through-word/) ⭐️ 8.0/10

安全研究人员演示了嵌入在 Word 文档中的恶意隐藏指令如何利用 Microsoft Copilot 进行自我传播并修改其他文档。这一概念验证表明，AI 智能体可能会被操纵，从而在用户的工作空间中自主传播恶意软件。 该漏洞突显了当前基于大语言模型（LLM）的应用中存在的一个根本性缺陷，即无法将指令与数据分离，从而导致了“零点击”漏洞利用。随着企业越来越多地集成对本地文件和电子邮件具有深度访问权限的 AI 智能体，大规模、自动化的数据窃取和文档篡改的潜在风险呈指数级增长。 该攻击利用了间接提示词注入（indirect prompt injection），即 Copilot 读取文档中的恶意文本并将其作为命令执行，从而引导其将类似的恶意指令写入新创建或编辑的文件中。目前，对于这类更广泛的漏洞尚无有效的防御手段，因为 LLM 将系统指令和用户提供的数据都作为自然语言进行处理。

hackernews · Canopy9560 · 7月29日 11:44 · [社区讨论](https://news.ycombinator.com/item?id=49096188)

**背景**: 间接提示词注入是指 AI 系统在处理包含隐藏指令的不可信外部数据（如文档或电子邮件）时，其行为被劫持。这一问题与“AI 蠕虫”（例如实验性的 “Morris II” 蠕虫）的概念密切相关，此类蠕虫利用自我复制的提示词在生成式 AI 生态系统中自主传播。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cetas.turing.ac.uk/publications/indirect-prompt-injection-generative-ais-greatest-security-flaw">Indirect Prompt Injection: Generative AI’s Greatest Security Flaw | Centre for Emerging Technology and Security</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>
<li><a href="https://www.wired.com/story/here-come-the-ai-worms/">Here Come the AI Worms | WIRED</a></li>

</ul>
</details>

**社区讨论**: 用户对此表示深切担忧，许多人认为，只要 LLM 仍然混淆指令与数据，该漏洞在根本上就是无法修复的。一些技术用户表示他们已经卸载了 Copilot 或完全禁用了本地 AI 工具，而另一些人则指出，使用白文字体或 Unicode 字符混淆等简单技巧仍能轻易绕过安全过滤器。

**标签**: `#AI Security`, `#Prompt Injection`, `#Copilot`, `#Vulnerability Research`

---