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

# Diffusion Classifiers

This is the website for diffusion classifiers, that leveraging a single diffusion model for robust classification.

Diffusion classifiers are inherently robust against O.O.D. data and adversarial examples. Some intriguing mathematical properties allow us to directly prove its robustness lower bound for adversarial examples and O.O.D. data.



## Vanilla Diffusion Classifier ([paper](https://arxiv.org/abs/2305.15241)) ([code](https://github.com/huanranchen/DiffusionClassifier))

![image](images/flows/DC.png)

- directly using a single diffusion model as generative classifiers.
- solving $\max_y \log p(x|y)$ via enumeration, since $p(y|x)=\text{softmax}(\log p(x|y))$


## Noised Diffusion Classifier ([paper](https://arxiv.org/abs/2305.15241)) ([code](https://github.com/huanranchen/NoisedDiffusionClassifiers))



## Likelihood Maximization: an efficient approximate posterior inference ([paper](https://github.com/huanranchen/DiffusionClassifier))


## 📝 Diffusion Classifiers Papers


### Robust Classification via a Single Diffusion Model
**Huanran Chen**, Yinpeng Dong, Zhengyi Wang, Xiao Yang, Chengqi Duan, Hang Su, Jun Zhu    
- Proposing diffusion classifier, directly use diffusion models as classifiers without discriminative training.
- Demonstrating the robustness of diffusion classifier on O.O.D. data and adversarial examples.
- Deriving the optimal solution of diffusion models, a theoretical tools for analyzing diffusion models.
- Proposing an efficient approximate marginal inference, Likelihood Maximization.
-  [[ICML2024](https://arxiv.org/abs/2305.15241)] [[Github](https://github.com/huanranchen/DiffusionClassifier)]


### Your Diffusion Model is Secretly a Certifiably Robust Classifier
**Huanran Chen**, Yinpeng Dong, Shitong Shao, Zhongkai Hao, Xiao Yang, Hang Su, Jun Zhu       
- Deriving two evidence lower bounds (ELBOs) for log likelihood on noisy data.
- Constructing two new diffusion classfiers base on these ELBOs.
- Deriving the analytical form for the gradient of diffusion classifiers (without UNet Jacobian).
- Deriving three Lipschitzness and robustness lower bound for these diffusion classifiers.
- Achieving state-of-the-art certified robustness (highest provable lower bound).
-  [[arxiv](https://arxiv.org/abs/2402.02316)] [[Github](https://github.com/huanranchen/NoisedDiffusionClassifiers)]





# 📧 Emails

I truly believe that great ideas and improvements come from open discussions and debates in academia. If you have any thoughts, disagreements with my work, or fresh ideas you'd like to share, I'd be really grateful to hear from you.

If you've got any questions about my research or if you've tried reaching out through GitHub issues and haven't heard back, please don't hesitate to drop me an email. I’m always here to chat or help out in any way I can.

**If you are inclined to discuss publication or citation numbers, rely on numerical indicators to quantify individuals, or compare me to others, please refrain from contacting me. I am only interested in discussing intriguing problems and insights, not metrics.**

My preferred email: huanran_chen@outlook.com

Please avoid sending emails to huanranchen@bit.edu.cn, as I won't be able to access this account much longer.


