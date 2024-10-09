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

I am a fourth-year Ph.D. student at [School of Mathematical Sciences](https://math.sjtu.edu.cn/Default/index/), [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/).  Before that, I received my Bachelor's degree from Zhiyuan College of [SJTU](https://www.sjtu.edu.cn/) in 2021.

I am currently advised by Prof. [Zhiqin Xu](https://ins.sjtu.edu.cn/people/xuzhiqin/). My research interests are in understanding deep learning from the training process, loss landscape, generalization and application, and also the interpretability of large language models.


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 I won the 2024 China National Scholarship!
- *2024.09*: &nbsp;🎉🎉 One paper accepted to NeurIPS 2024!
- *2024.01*: &nbsp;🎉🎉 One paper accepted to ICLR 2024!
- *2024.01*: &nbsp;🎉🎉 One paper accepted to TPAMI!

# 📝 Publications 

\* denotes equal contribution, † denotes corresponding author, see the full list in [Google Scholar](https://scholar.google.com/citations?user=0Q6lKJ8AAAAJ&hl=zh-CN).

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/pic5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Implicit Regularization of Dropout](https://ieeexplore.ieee.org/abstract/document/10412142)

**Zhongwang Zhang**, Zhi-Qin John Xu†

- This paper proposes a theoretical derivation of an implicit regularization of dropout, which is validated through experiments and numerically studied to understand how dropout improves generalization during neural network training by promoting weight condensation and finding flatter solutions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2024</div><img src='images/pic4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stochastic Modified Equations and Dynamics of Dropout Algorithm](https://openreview.net/pdf?id=Bpkhu2ExxU)

**Zhongwang Zhang**, Yuqing Li†, Tao Luo†, Zhi-Qin John Xu†

- This paper proposes a rigorous theoretical derivation of the stochastic modified equations to approximate the discrete iterative process of dropout and empirically investigates the mechanisms by which dropout facilitates the identification of flatter minima through intuitive approximations exploiting the structural analogies in the Hessian of loss landscape and the covariance of dropout.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2024</div><img src='images/pic3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Initialization is Critical to Whether Transformers Fit Composite Functions by Inference or Memorizing](https://arxiv.org/pdf/2405.05409)

**Zhongwang Zhang**, Pengxiao Lin, Zhiwei Wang, Yaoyu Zhang, Zhi-Qin John Xu†

- This paper investigates the mechanisms of how transformers behave on unseen compositional tasks using anchor functions, revealing that the parameter initialization scale determines whether the model learns inferential solutions that capture the underlying compositional primitives or symmetric solutions that simply memorize mappings, and provides insights into the role of initialization scale in shaping the type of solution learned and their ability to generalize compositional functions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/pic2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Anchor function: a type of benchmark functions for studying language models](https://arxiv.org/pdf/2401.08309)

**Zhongwang Zhang\***, Zhiwei Wang\*, Junjie Yao, Zhangchen Zhou, Xiaolong Li, Weinan E, Zhi-Qin John Xu†

- This paper introduces the concept of an anchor function, a type of benchmark function designed for studying language models in learning tasks that follow an "anchor-key" pattern, which serves as a valuable and accessible framework for exploring various tasks, and demonstrates its utility by revealing two basic operations by attention structures in language models: shifting tokens and broadcasting one token from one position to many positions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2021 spotlight</div><img src='images/pic1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Embedding principle of loss landscape of deep neural networks](https://proceedings.neurips.cc/paper_files/paper/2021/file/7cc532d783a7461f227a5da8ea80bfe1-Paper.pdf)

Yaoyu Zhang†, **Zhongwang Zhang**, Tao Luo, Zhi-Qin John Xu†

- This paper proves an embedding principle that the loss landscape of a deep neural network (DNN) contains all the critical points of narrower DNNs, and proposes a critical embedding such that any critical point of a narrower DNN can be embedded to a critical point/affine subspace of the target DNN with higher degeneracy while preserving the DNN output function, providing a new perspective to study the general easy optimization of wide DNNs and unraveling a potential implicit low-complexity regularization during training.
</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2021.09 - now*, Ph.D., School of Mathematical Sciences, Shanghai Jiao Tong University. 
- *2017.09 - 2021.06*, Undergraduate, Zhiyuan College, Shanghai Jiao Tong University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
