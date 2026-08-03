---
layout: default
title: "Horizon Summary: 2026-08-03 (ZH)"
date: 2026-08-03
lang: zh
---

> 从 32 条内容中筛选出 5 条重要资讯。

---

1. [Ten advances in mathematics and theoretical computer science](#item-1) ⭐️ 9.0/10
2. [ComfyUI 宣布首日支持 MiniMax H3 视频生成模型](#item-2) ⭐️ 8.0/10
3. [Andy Pavlo joins ClickHouse to establish ClickHouse Labs](#item-3) ⭐️ 8.0/10
4. [深入解析 Kimi K3：月之暗面创新的 2.8 万亿参数 MoE 架构](#item-4) ⭐️ 8.0/10
5. [苹果起诉英国政府，反对 iCloud 加密后门指令](#item-5) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Ten advances in mathematics and theoretical computer science](https://openai.com/index/ten-advances-in-mathematics/) ⭐️ 9.0/10

OpenAI highlights ten significant breakthroughs in mathematics and theoretical computer science enabled by their advanced reasoning models.

hackernews · milkshakes · 8月3日 16:27 · [社区讨论](https://news.ycombinator.com/item?id=49157930)

**标签**: `#Artificial Intelligence`, `#Mathematics`, `#Theoretical Computer Science`, `#AI for Science`

---

<a id="item-2"></a>
## [ComfyUI 宣布首日支持 MiniMax H3 视频生成模型](https://blog.comfy.org/p/minimax-h3-day-0-support-in-comfyui) ⭐️ 8.0/10

ComfyUI 宣布首日支持 MiniMax H3 开放权重多模态模型，该模型能够生成长达 15 秒、分辨率达 2K 且带原生立体声的视频。此次集成通过剪枝模型的调制权重，将内存占用显著减少了 66%。 此次发布为开源社区带来了前沿的高分辨率视频和原生音频生成能力，允许创作者在本地运行最先进的模型。显著的内存优化为在消费级硬件上运行大型多模态模型树立了新典范。 通过剪枝调制权重（约占总参数的 40%）并将其替换为等效的查找表，该模型的内存占用从 123.6 GB 降至 42.5 GB。结合 ComfyUI 的动态显存（VRAM）卸载技术，这使得该模型能够在 RTX 3060 等显卡上运行，但在低端硬件上的生成时间仍然较长。

hackernews · vblanco · 8月3日 13:34 · [社区讨论](https://news.ycombinator.com/item?id=49155629)

**背景**: MiniMax H3 是由总部位于上海的 MiniMax 开发的全模态 AI 模型，旨在同时处理和生成文本、图像、视频和音频。ComfyUI 是一款广受欢迎的基于节点的图形用户界面，用于 Stable Diffusion 等生成式 AI 模型，因其灵活性和优化能力而深受开源社区的喜爱。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.minimax.io/blog/minimax-h3">MiniMax H3: An Open Model Breaking the Boundaries Between ...</a></li>
<li><a href="https://rits.shanghai.nyu.edu/ai/minimax-releases-h3-2k-video-with-native-audio-open-weights-promised/">MiniMax Releases H3: 2K Video With Native Audio, Open Weights ...</a></li>

</ul>
</details>

**社区讨论**: 用户对 MiniMax H3 令人惊叹的渲染质量表示兴奋，尽管有人指出某些片段仍存在“AI 平滑”痕迹。社区对调制权重剪枝技术及其是否可应用于 LLM 表现出浓厚的学术兴趣，同时也讨论了在 RTX 4070 Ti Super 等消费级显卡上的生成速度。

**标签**: `#Generative AI`, `#Video Generation`, `#ComfyUI`, `#Model Optimization`, `#Open Source`

---

<a id="item-3"></a>
## [Andy Pavlo joins ClickHouse to establish ClickHouse Labs](https://clickhouse.com/blog/andy-pavlo-joins-clickhouse) ⭐️ 8.0/10

Renowned CMU database professor Andy Pavlo has joined ClickHouse to establish ClickHouse Labs, a new research division focused on advanced database technologies.

hackernews · nikolay_sivko · 8月3日 14:09 · [社区讨论](https://news.ycombinator.com/item?id=49156011)

**标签**: `#Databases`, `#OLAP`, `#ClickHouse`, `#Database Research`, `#Industry News`

---

<a id="item-4"></a>
## [深入解析 Kimi K3：月之暗面创新的 2.8 万亿参数 MoE 架构](https://newsletter.semianalysis.com/p/kimi-k3-the-manos-the-mythos-the) ⭐️ 8.0/10

SemiAnalysis 对月之暗面（Moonshot AI）的旗舰模型 Kimi K3 进行了架构深度解析。该模型是一个拥有 2.8 万亿参数的混合专家（MoE）模型，采用了创新的内存压缩、跨深度注意力机制以及隐式专家路由技术。 Kimi K3 展示了如何通过 Kimi Delta Attention 和 Attention Residuals 等新型架构设计，在支持 100 万 token 上下文的超大规模模型中，极大地优化推理性能并降低显存占用。 该模型利用“注意力残差”（Attention Residuals）跨深度层选择性地检索表示，而不是进行均匀累加，并结合“隐式原型路由”（Latent Prototype Routing）在专家之间实现近乎完美的负载均衡。

rss · Semianalysis · 8月3日 19:42

**背景**: 传统的混合专家（MoE）模型在长上下文推理过程中，常常面临路由效率低下和显存占用过高的挑战。为了解决这些问题，先进的架构采用了跨层混合数值的深度注意力机制，以及优化的路由算法，以平衡各专业专家网络之间的计算负载。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K 3 Tech Blog: Open Frontier Intelligence</a></li>
<li><a href="https://kie.ai/blog/what-is-kimi-k3">What Is Kimi K 3 ? Moonshot's 2.8T, 1M-Context Flagship</a></li>
<li><a href="https://arxiv.org/abs/2606.05014">[2606.05014] Depth-Attention: Cross-Layer Value Mixing for ...</a></li>

</ul>
</details>

**标签**: `#LLM Architecture`, `#Machine Learning`, `#Inference Optimization`, `#AI Hardware`

---

<a id="item-5"></a>
## [苹果起诉英国政府，反对 iCloud 加密后门指令](https://www.ft.com/content/2cc9c96a-0e5b-4c33-a95a-3d11072a145c?syn-25a6b1a6=1) ⭐️ 8.0/10

苹果公司已向英国调查权力法庭提起法律申诉，挑战英国政府签发的“技术能力通知”（TCN）。该通知要求苹果为英国用户的加密 iCloud 备份创建后门，此前已导致苹果于 2025 年 2 月在英国下架了 iCloud 高级数据保护功能。 这场诉讼标志着捍卫用户隐私的技术巨头与寻求监管访问权限的政府之间全球博弈的重大升级。如果英国政府获胜，可能会为跨国国家监控树立危险先例，并削弱全球范围内的端到端加密标准。 英国的“技术能力通知”（TCN）具有域外管辖权，可强制苹果等外国公司修改其服务以协助监控。包括 Privacy International 和 Liberty 在内的隐私倡导组织也对这些秘密权力提起了申诉，法庭听证会定于下月举行。

telegram · zaihuapd · 8月3日 15:40

**背景**: 苹果的 iCloud “高级数据保护”功能提供端到端加密，这意味着解密密钥仅存储在用户的信任设备上，而非苹果的服务器上，从而使苹果自身也无法解密这些数据。根据英国的《调查权力法》，政府可以发布 TCN，强制科技公司修改其系统，而科技公司和隐私倡导者认为这从根本上损害了所有用户的安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://privacyinternational.org/long-read/5547/our-challenge-against-uks-secret-tcn-powers">Our challenge against UK's secret TCN powers | Privacy International</a></li>
<li><a href="https://support.apple.com/guide/security/advanced-data-protection-for-icloud-sec973254c5f/web">Advanced Data Protection for iCloud - Apple Support</a></li>
<li><a href="https://www.thestack.technology/uk-demands-apple-backdoor/">UK demands Apple backdoor with Technical Capability Notice</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Privacy`, `#Encryption`, `#Tech Policy`, `#Cybersecurity`

---