---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a junior year undergraduate from TSAIL, with keen interest in Trustworthy ML and diffusion models. My aspiration is to elevate AI to the realm of science, moving beyond its current engineering-focused approach. My preferred research paradigm involves observing phenomena, proposing multiple explanations, constructing various theories, validating corollaries, and ultimately deriving solutions or methodologies. I'm eager to connect with anyone who shares this vision for AI or appreciates the same research approach.

Currently, most people formalize AI problems as a mapping from input to output, using neural networks to learn this mapping end-to-end through direct training, thereby achieving the desired functionality. Recent trends, like scaling up these learning paradigms in pursuit of AGI, have gained traction. However, I believe that the academic community should delve deeper into whether fundamental issues exist within this learning paradigm that cannot be resolved by merely scaling up—for example, adversarial examples still pose significant risks in large models, and it remains questionable whether these models learn probabilistic distributions or reasoning. On the other hand, we should also explore broader learning paradigms and design fundamentally different storage structures, optimization methods, and mapping techniques. This ensures that if the current learning paradigm proves unscalable, we will still have numerous alternatives to explore, preventing research in this field from reaching an impasse.

Based on the aspiration of "establishing a science for AI", all my research revolves around two main themes mentioned before: "exploring the fundamental issues of the current paradigm" and "creating fundamentally different learning paradigms."

# 📝 Diffusion Classifiers Papers


## Robust Classification via a Single Diffusion Model
**Huanran Chen**, Yinpeng Dong, Zhengyi Wang, Xiao Yang, Chengqi Duan, Hang Su, Jun Zhu    
- Proposing diffusion classifier, directly use diffusion models as classifiers without discriminative training.
- Demonstrating the robustness of diffusion classifier on O.O.D. data and adversarial examples.
- Deriving the optimal solution of diffusion models, a theoretical tools for analyzing diffusion models.
- Proposing an efficient approximate marginal inference, Likelihood Maximization.
-  [[ICML2024](https://arxiv.org/abs/2305.15241)]


## Your Diffusion Model is Secretly a Certifiably Robust Classifier
**Huanran Chen**, Yinpeng Dong, Shitong Shao, Zhongkai Hao, Xiao Yang, Hang Su, Jun Zhu       
- Deriving two evidence lower bounds (ELBOs) for log likelihood on noisy data.
- Constructing two new diffusion classfiers base on these ELBOs.
- Deriving the analytical form for the gradient of diffusion classifiers (without UNet Jacobian).
- Deriving three Lipschitzness and robustness lower bound for these diffusion classifiers.
- Achieving state-of-the-art certified robustness (highest provable lower bound).
-  [[arxiv](https://arxiv.org/abs/2402.02316)]





# 📧 Emails

I truly believe that great ideas and improvements come from open discussions and debates in academia. If you have any thoughts, disagreements with my work, or fresh ideas you'd like to share, I'd be really grateful to hear from you.

If you've got any questions about my research or if you've tried reaching out through GitHub issues and haven't heard back, please don't hesitate to drop me an email. I’m always here to chat or help out in any way I can.

**If you are inclined to discuss publication or citation numbers, rely on numerical indicators to quantify individuals, or compare me to others, please refrain from contacting me. I am only interested in discussing intriguing problems and insights, not metrics.**

My preferred email: huanran_chen@outlook.com

Please avoid sending emails to huanranchen@bit.edu.cn, as I won't be able to access this account much longer.


