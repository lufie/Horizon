---
layout: default
title: "Horizon Summary: 2026-07-11 (ZH)"
date: 2026-07-11
lang: zh
---

> 从 38 条内容中筛选出 5 条重要资讯。

---

1. [Apple sues OpenAI, accuses ex-employees of stealing trade secrets](#item-1) ⭐️ 9.0/10
2. [GPT-5.6 Sol Ultra produces proof of the Cycle Double Cover Conjecture (pdf)](#item-2) ⭐️ 9.0/10
3. [sgl-project/sglang released v0.5.15](#item-3) ⭐️ 8.0/10
4. [QuadRF can spot drones and see WiFi through my wall](#item-4) ⭐️ 8.0/10
5. [应对利用住宅代理的恶意网络爬虫的艰难斗争](#item-5) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Apple sues OpenAI, accuses ex-employees of stealing trade secrets](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 9.0/10

Apple has filed a lawsuit against OpenAI, accusing the AI company of recruiting ex-employees who systematically stole confidential trade secrets and hardware information.

hackernews · stock_toaster · 7月10日 20:47 · [社区讨论](https://news.ycombinator.com/item?id=48865019)

**标签**: `#Artificial Intelligence`, `#Intellectual Property`, `#Apple`, `#OpenAI`, `#Tech Law`

---

<a id="item-2"></a>
## [GPT-5.6 Sol Ultra produces proof of the Cycle Double Cover Conjecture (pdf)](https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf) ⭐️ 9.0/10

An OpenAI model has reportedly generated a proof for the Cycle Double Cover Conjecture, a major unsolved problem in graph theory, utilizing highly detailed prompting strategies.

hackernews · scrlk · 7月10日 18:29 · [社区讨论](https://news.ycombinator.com/item?id=48863490)

**标签**: `#Artificial Intelligence`, `#Mathematics`, `#Graph Theory`, `#AI Research`, `#Prompt Engineering`

---

<a id="item-3"></a>
## [sgl-project/sglang released v0.5.15](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 8.0/10

SGLang v0.5.15 introduces major performance enhancements, including optimized GLM-5.2 serving on Blackwell GPUs, Speculative Decoding V2 by default, and IndexShare MTP.

github · Fridge003 · 7月10日 22:58

**标签**: `#LLM Serving`, `#Machine Learning`, `#Performance Optimization`, `#SGLang`, `#GPU Acceleration`

---

<a id="item-4"></a>
## [QuadRF can spot drones and see WiFi through my wall](https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/) ⭐️ 8.0/10

Jeff Geerling reviews QuadRF, an open-source software-defined radio tool that visualizes RF signals in real-time, allowing users to detect drones and map WiFi signals through walls.

hackernews · speckx · 7月10日 15:59 · [社区讨论](https://news.ycombinator.com/item?id=48861717)

**标签**: `#SDR`, `#Hardware`, `#Wireless`, `#Augmented Reality`, `#Open Source`

---

<a id="item-5"></a>
## [应对利用住宅代理的恶意网络爬虫的艰难斗争](https://lwn.net/SubscriberLink/1080822/990a8a5e2d379085/) ⭐️ 8.0/10

LWN 发布了一份更新，详细阐述了在防御恶意网络爬虫方面面临的持续挑战。这些爬虫越来越多地通过住宅代理（residential proxies）路由其流量，以绕过传统的基于 IP 的封锁。该更新强调，面对这些复杂的爬虫网络，诸如工作量证明（PoW）挑战等缓解技术正显得力不从心。 随着人工智能公司和数据中间商大肆抓取网页，传统的防御机制正在失效，威胁到独立网站的生存。如果这一问题得不到解决，这场军备竞赛可能会迫使网站采用侵入性的反机器人防火墙，最终损害开放网络并把合法用户拒之门外。 住宅代理网络利用了数百万台被入侵或受利益驱动的用户设备，使其流量与合法用户难以区分。因此，像 Anubis 这样的工作量证明（PoW）防御手段宣告失效，因为爬虫可以轻易地将计算谜题的求解工作分摊到这个庞大的被劫持住宅设备池中。

hackernews · chmaynard · 7月10日 19:38 · [社区讨论](https://news.ycombinator.com/item?id=48864252)

**背景**: 住宅代理通过互联网服务提供商（ISP）分配的真实家庭网络连接来路由流量，这使得它们与数据中心 IP 相比具有极高的可信度。工作量证明（PoW）机器人缓解技术是一种防御机制，它要求客户端浏览器在访问网站前解决一个密码学谜题，旨在从经济和计算成本上增加自动化爬取的难度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://v2-frontier-make.vercel.app/blog/residential-datacenter-mobile-proxies-explained">Proxy Types Explained : Residential vs Mobile | Coronium.io</a></li>
<li><a href="https://www.geetest.com/en/article/proof-of-work-captcha">Proof-of-Work CAPTCHA: Benefits, Limitations, and Its Role in Modern Bot Mitigation</a></li>

</ul>
</details>

**社区讨论**: 用户对 Anubis 等 PoW 工具表示失望，指出它们给合法用户（尤其是那些开启了严格隐私设置的用户）设置了巨大的障碍。许多人认为，激进的反爬虫措施有破坏开放网络并将控制权集中到 Cloudflare 等实体手中的风险，而另一些人则强调了网络存档的合理需求。

**标签**: `#Web Scraping`, `#Cybersecurity`, `#Networking`, `#Internet Policy`

---