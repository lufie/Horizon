---
layout: default
title: "Horizon Summary: 2026-07-29 (EN)"
date: 2026-07-29
lang: en
---

> From 42 items, 4 important content pieces were selected

---

1. [Show HN: Open-source engine running Gemma 4 26B in 2 GB RAM on any M-series Mac](#item-1) ⭐️ 8.0/10
2. [Superlogical](#item-2) ⭐️ 8.0/10
3. [KOReader: The Powerful Open-Source Document Viewer for E Ink Devices](#item-3) ⭐️ 8.0/10
4. [AI Worms Can Self-Propagate Through Microsoft Copilot for Word](#item-4) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Show HN: Open-source engine running Gemma 4 26B in 2 GB RAM on any M-series Mac](https://github.com/drumih/turbo-fieldfare) ⭐️ 8.0/10

TurboFieldfare is an open-source Swift and Metal inference engine that runs the Gemma 4 26B model on M-series Macs using only 2 GB of RAM by streaming MoE experts from the SSD.

hackernews · gitpusher42 · Jul 29, 15:05 · [Discussion](https://news.ycombinator.com/item?id=49098510)

**Tags**: `#Machine Learning`, `#LLM Inference`, `#macOS`, `#Open Source`, `#Systems Engineering`

---

<a id="item-2"></a>
## [Superlogical](https://www.superlogical.com/) ⭐️ 8.0/10

Mitchell Hashimoto introduces Superlogical, a new venture focused on building next-generation terminal applications using the open-source libghostty library.

hackernews · yan · Jul 29, 15:41 · [Discussion](https://news.ycombinator.com/item?id=49098965)

**Tags**: `#developer-tools`, `#terminal-emulators`, `#open-source`, `#software-architecture`, `#ghostty`

---

<a id="item-3"></a>
## [KOReader: The Powerful Open-Source Document Viewer for E Ink Devices](https://koreader.rocks/) ⭐️ 8.0/10

KOReader continues to gain traction as a highly customizable, open-source document viewer designed specifically for E Ink devices like Kindle, Kobo, and ReMarkable. It offers native support for a wide range of formats, including EPUB and PDF, without requiring file conversion. For e-reader users, KOReader bypasses the restrictive ecosystems of proprietary platforms by offering advanced features like PDF reflow, progress syncing, and Calibre integration. It empowers users to fully control their reading hardware, making it a key driver for device jailbreaking and open-source adoption. While KOReader runs on various platforms including Android and Linux, installing it on devices like Kindles often requires hardware jailbreaking. Additionally, some users note that its highly customizable interface can feel unintuitive or cluttered out of the box.

hackernews · Cider9986 · Jul 29, 11:05 · [Discussion](https://news.ycombinator.com/item?id=49095865)

**Background**: E Ink, or electronic paper, is a display technology that mimics the appearance of ordinary ink on paper, making it highly readable in direct sunlight and energy-efficient. Proprietary e-readers like Amazon's Kindle often restrict users to specific file formats and closed ecosystems. Open-source alternatives like KOReader aim to liberate these devices by providing extensive format compatibility and customizable reading options.

<details><summary>References</summary>
<ul>
<li><a href="http://koreader.rocks/">KOReader</a></li>
<li><a href="https://grokipedia.com/page/KOReader">KOReader</a></li>
<li><a href="https://en.wikipedia.org/wiki/E_Ink">E Ink - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users praise KOReader for its superior format support and features like Z-Library integration, with some stating it directly influences their hardware purchasing decisions. However, others criticize its non-intuitive UI/UX, comparing it to GIMP, and report occasional lagginess or gesture unresponsiveness.

**Tags**: `#open-source`, `#e-ink`, `#hardware-hacking`, `#software-tools`, `#mobile-development`

---

<a id="item-4"></a>
## [AI Worms Can Self-Propagate Through Microsoft Copilot for Word](https://enklypesalt.com/posts/context-collapse-part3-ai-worming-through-word/) ⭐️ 8.0/10

Security researchers have demonstrated how malicious, hidden instructions embedded in Word documents can exploit Microsoft Copilot to self-propagate and alter other documents. This proof-of-concept shows that AI agents can be manipulated into spreading malware autonomously across a user's workspace. This vulnerability highlights a fundamental flaw in current LLM-based applications, where the inability to separate instructions from data allows for zero-click exploits. As enterprises increasingly integrate AI agents with deep access to local files and emails, the potential for widespread, automated data theft and document tampering grows exponentially. The attack leverages indirect prompt injection, where Copilot reads the malicious text within a document and executes it as a command, leading it to write similar malicious instructions into newly created or edited files. Currently, there is no robust mitigation for this broader class of vulnerability because LLMs process both system instructions and user-provided data as natural language.

hackernews · Canopy9560 · Jul 29, 11:44 · [Discussion](https://news.ycombinator.com/item?id=49096188)

**Background**: Indirect prompt injection occurs when an AI system processes untrusted external data (like a document or email) containing hidden instructions that hijack the AI's behavior. This issue is closely linked to the concept of "AI worms," such as the experimental "Morris II" worm, which use self-replicating prompts to autonomously spread across generative AI ecosystems.

<details><summary>References</summary>
<ul>
<li><a href="https://cetas.turing.ac.uk/publications/indirect-prompt-injection-generative-ais-greatest-security-flaw">Indirect Prompt Injection: Generative AI’s Greatest Security Flaw | Centre for Emerging Technology and Security</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>
<li><a href="https://www.wired.com/story/here-come-the-ai-worms/">Here Come the AI Worms | WIRED</a></li>

</ul>
</details>

**Discussion**: Users expressed deep concern, with many arguing that this vulnerability is fundamentally unfixable as long as LLMs mix instructions with data. Some tech-savvy users noted they have uninstalled Copilot or disabled local AI tools entirely, while others pointed out that simple tricks like white text or Unicode manipulation can still easily bypass safety filters.

**Tags**: `#AI Security`, `#Prompt Injection`, `#Copilot`, `#Vulnerability Research`

---