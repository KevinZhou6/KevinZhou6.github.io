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





# 🔥 News
- *2024.04*: &nbsp;🎉🎉 One paper is accepted by IEEE SMC24 oral!
- *2022.12*: &nbsp;🎉🎉 I win the National Scholarship (1%)!
  
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2024 workshop</div><img src='images/rldf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reinforcement Learning from Multi-role Debates as Feedback for Bias Mitigation in LLMs](https://github.com/Hunter-Wrynn/RLDF)

Ruoxi Cheng†, **Haoxuan Ma†**, Shuirong Cao†, Jiaqi Li, Aihua Pei, Zhiqiang Wang‡, Pengliang Ji, Haoyu Wang, Jiaqi Huo​​
(† Equal contribution,)

[**Project Page**](https://github.com/Hunter-Wrynn/RLDF) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- we propose Reinforcement Learning from Multi-role Debates as Feedback (RLDF), a novel approach for bias mitigation
replacing human feedback in traditional RLHF. We utilize
LLMs in multi-role debates to create a dataset that includes
both high-bias and low-bias instances for training the reward
model in reinforcement learning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2024</div><img src='images/leverlm.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lever LM: Configuring In-Context Sequence to Lever Large Vision Language Models](https://github.com/ForJadeForest/Lever-LM)

Xu Yang, Yingzhe Peng, **Haoxuan Ma**, Shuo Xu, Chi Zhang, Yucheng Han, Hanwang Zhang


[**Project Page**](https://github.com/ForJadeForest/Lever-LM) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- We propose to use a tiny Language Model (LM), e.g., a Transformer with 67M parameters, to lever much larger Vision-Language Models (LVLMs) with 9B parameters. Specifically, we use this tiny Lever-LM to configure effective in-context demonstration (ICD) sequences to improve the In-Context Learinng (ICL) performance of LVLMs
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/drirl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Inverse Reinforcement Learning with Dynamic Reward Scaling for LLM Alignment](https://hunter-wrynn.github.io/)

Ruoxi Cheng†, **Haoxuan Ma†**, Weixin Wang†, Zhiqiang Wang, Xiaoshuang Jia, Simeng Qin, Xiaochun Cao, Yang Liu, Xiaojun Jia († Equal contribution)

[**Project Page**](https://hunter-wrynn.github.io/) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- we propose DR-IRL, which Dynamically adjusts Rewards through Inverse Reinforcement Learning. We first construct a balanced safety dataset of seven harmful categories using Chain-of-Draft (CoD) template prompts. Then we train category - specific reward models using this dataset as demonstration via IRL. Finally, we propose GRPO-S, Group Relative Policy Optimization-Scaling, a variant of GRPO that scales the reward in optimization to tast difficulty—data-level hardness by CLIP similarity, model-level responsiveness by reward gaps.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/fmla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Masked-image Language Alignment](https://hunter-wrynn.github.io/)

YiCheng Xiao†, Yu Chen†, **Haoxuan Ma†**, Jiale Hong†, Caorui Li, Lingxiang Wu, Zheng Wang, Kuan Zhu, Haiyun Guo, Jinqiao Wang († equal contribution)

[**Project Page**](https://hunter-wrynn.github.io/) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- We propose Fine-grained Masked-image Language Alignment (FMLA), a novel fine-tuning approach that utilizes the local semantic alignment between masks and complex long texts. Our FMLA model can effectively represent images at any granularity (whether local or global) while leveraging the LLM to process complex long texts. This makes it the first model capable of simultaneously meeting demands for local visual prompts input and long text input, consequently overcomes the granularity limitations in both the visual and textual domains.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/segbins.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SegBins: Self-Supervised Monocular Depth Estimation Based On Depth Bins And Semantic Segmentation](https://hunter-wrynn.github.io/)

Yicheng Xiao†, **Haoxuan Ma†**, Zhenhao Shen, Jinfei Qi, RuiFeng Xie, Zixiang Zhang, Haoxiao Wang, Weijie Wang, Peilin Sun, Jiale Hong, Jingyang Fan, Xiaolin Fang, Haiyun Guo, Jinqiao Wang († equal contribution)

[**Project Page**](https://hunter-wrynn.github.io/) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- We propose a new self-supervised monocular depth estimation framework, which innovatively proposes that the framework enhances spatial interaction information and applies multi-layer feature fusion information to extract potential geometric priors of scenes in images, and finally classifies them into multiple depth bin to obtain probabilities, which are combined to form depth. 

</div>
</div>



# 🎖 Honors and Awards
- *2024.11* President's Scholarship (top 1%) in Southeast University
- *2023.11* Zhishan Scholarship in Southeast University
- *2023.09* Suzhou Industrial Scholarship in Southeast University
- *2023.06* Merit Student in Southeast University.
- *2022.11* Zhishan Scholarship in Southeast University
- *2022.09* Lenovo Research Institute Scholarship in Southeast University


# 📖 Educations
- *2021.08 - 2025.05 (now)*, Southeast University, College of Computer Science and Technology.
 
# 💻 Internships
- *2024.07 - 2025.03*, [Shanghai AI Lab](https://www.shlab.org.cn/), China.
