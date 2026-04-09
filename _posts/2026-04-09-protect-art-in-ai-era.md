---
layout: post
title: AI时代怎么保护自己的作品？
date: 2026-04-09 16:00:00 +0800
categories: [AI Security, Artist]
tags: [ai security, data poisoning, masking]
author: pHX
---

很多画画的人受困于自己作品未经自己的允许被人拿去喂了AI。
最近因为看到影视飓风关于AI视频的那期，不由开始担心AI被用于诈骗等行为的可能。
加上之前看到很多同人太太（不只是画手，还有写文的）因为AI苦恼不已，鉴AI的各有各有的说法……

于是准备了解有没有关于AI安全的研究，以及在现在AI时代版权保护和法律都还没规范的时候，可以保护创作者的研究。

先说两个比较重要的绘画作品的保护研究，都是由UChicago SAND Lab develop的，且都是免费的：

1. !(Glaze)[https://glaze.cs.uchicago.edu/what-is-glaze.html] 
	- 2023年3月launch，有超过850万下载量。
	- 类似于隐形衣，防止AI算法识别、复制艺术家的风格。
	- 除了APP还有web version（因为本地跑Glaze有一些内存要求）。
2. Nightshade
	- 2024年1月launch，超过250万下载量。
	- 比Glaze的防御性保护，Nightshade更偏向攻击类，采用数据投毒，目的让AI混淆基础概念，比如把狗识别成车这样。

不过Glaze和Nightshade也不是万无一失的，后续也有新的针对Glaze和Nightshade研究的GLEAN和LightShed。
感觉就和安全攻防一样，有防御保护措施，也就会有能破解的，然后保护措施会更加完善。

2025年的对抗性AI研究：
1. **StableGuard**：在训练过程中，无缝嵌入二进制水印，来证明版权归属，也能定位被篡改的区域。
	- arXiv:2509.17993
2. **Silverer**：专门针对个人照片保护的工具，用来防止犯罪分子利用社交媒体上的照片制作例如诈骗视频等深度伪造。由澳大利亚联邦警察和莫纳什大学的AiLECS实验室联合推出。
3. **Receler**：概念擦除，让训练好的模型彻底忘记某个特定概念。可用于版权清理（比如艺术家要求撤销非法使用其艺术风格的训练模型）。
	-  arXiv:2311.17717v3


## 参考：
- The AI lab waging a guerrilla war over exploitative AI - by By Melissa Heikkila on November 13, 2024 https://www.technologyreview.com/2024/11/13/1106837/ai-data-posioning-nightshade-glaze-art-university-of-chicago-exploitation/ 
- LightShed Bypasses Leading AI Art Protection Tools https://trust-lightshed.github.io/
- StableGuard: Towards Unified Copyright Protection and Tamper Localization in Latent Diffusion Models https://arxiv.org/abs/2509.17993
- AFP and Monash University poison data to combat AI-generative crime [https://www.cyberdaily.au/tech/12881-afp-and-monash-uni-join-forces-to-fight-ai-generative-crime#:~:text=This%20will%20alter%20the%20pixels,them%20appear%20quickly%20soon%20after.](https://www.afp.gov.au/news-centre/media-release/afp-and-monash-university-poison-data-combat-ai-generative-crime#:~:text=%E2%80%9CCurrently%2C%20these%20AI%2Dgenerated,user%2C%E2%80%9D%20Cmdr%20Nelson%20said.)
- Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers https://arxiv.org/abs/2311.17717v3
- Beyond Fixed Anchors: Precisely Erasing Concepts with Sibling Exclusive Counterparts https://arxiv.org/html/2510.16342v1
- Glaze https://nightshade.cs.uchicago.edu/aboutus.html

### Notes
首发在小红书平台，搬运过来 :)