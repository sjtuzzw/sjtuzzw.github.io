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

I am currently advised by Prof. [Zhiqin Xu](https://ins.sjtu.edu.cn/people/xuzhiqin/). My research interests are in understanding deep learning from the training process, loss landscape, generalization and application, and also the interpretability of large language models. If you're interested in my research, please feel free to contact me (<a href="#" id="wechat-link">Wechat</a>).

{% raw %}
<script>
    // 确保脚本在 DOM 加载后执行
    document.addEventListener('DOMContentLoaded', function() {
        document.getElementById('wechat-link').addEventListener('click', function(e) {
            e.preventDefault(); // 阻止链接的默认行为
            document.getElementById('wechat-overlay').style.display = 'block';
        });
    });
</script>
{% endraw %}

<div id="wechat-overlay" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background: rgba(0,0,0,0.5); z-index:1000;">
    <div style="position:absolute; top:50%; left:50%; transform:translate(-50%, -50%); background:white; padding:20px; text-align:center;">
        <img src="/images/wechat-qrcode.jpg" alt="WeChat QR Code" style="width: 400px; height: auto;">
        <br><button onclick="document.getElementById('wechat-overlay').style.display='none';">Close</button>
    </div>
</div>

# 🔥 News
- *2025.07*: &nbsp;🎉🎉 Our project WebSailor topped GitHub trending!​​ 
- *2025.05*: &nbsp;🎉🎉 One paper accepted to ICML 2025 spotlight!
- *2025.02*: &nbsp;🎉🎉 One paper accepted to JCM (T1 journal in computational mathematics)!
- *2024.09*: &nbsp;🎉🎉 I won the 2024 China National Scholarship!
- *2024.09*: &nbsp;🎉🎉 One paper accepted to NeurIPS 2024!
- *2024.01*: &nbsp;🎉🎉 One paper accepted to ICLR 2024!
- *2024.01*: &nbsp;🎉🎉 One paper accepted to TPAMI!

# 📝 Publications 

\* denotes equal contribution, † denotes corresponding author, see the full list in [Google Scholar](https://scholar.google.com/citations?user=0Q6lKJ8AAAAJ&hl=zh-CN).

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/pic7.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WebSailor: Navigating Super-human Reasoning for Web Agent](https://arxiv.org/abs/2507.02592v1)

Kuan Li\*, **Zhongwang Zhang\***, Huifeng Yin\*†, Liwen Zhang\*, Litu Ou\*, Jialong Wu, Wenbiao Yin, Baixuan Li, Zhengwei Tao, Xinyu Wang, Weizhou Shen, Junkai Zhang, Dingchu Zhang, Xixi Wu, Yong Jiang†, Ming Yan, Pengjun Xie, Fei Huang, Jingren Zhou

- This paper presents ​​WebSailor​​, a framework for training superhuman web agents that excel at complex reasoning tasks. Key innovations include: (1) ​​SailorFog-QA​​, a synthetic dataset with high-uncertainty questions generated via graph-based sampling and obfuscation; (2) ​​Reconstructed reasoning trajectories​​ that distill expert solutions into concise action plans; and (3) ​​Duplicating Sampling Policy Optimization (DUPO)​​, an RL method that accelerates training for long-horizon tasks. WebSailor models outperform existing open-source agents and rival proprietary systems on highly challenging  benchmarks like BrowseComp. ![GitHub Repo stars](https://img.shields.io/github/stars/Alibaba-NLP/WebAgent)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML2025 spotlight</div><img src='images/pic6.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Analysis for Reasoning Bias of Language Models with Small Initialization](https://arxiv.org/abs/2502.04375)

Junjie Yao, **Zhongwang Zhang†**, Zhi-Qin John Xu†

- This paper reveals how initialization scales shape transformer-based models' task preferences: smaller scales induce reasoning bias through structured embeddings, while larger scales promote memorization. We attribute this to differential label-driven embedding dynamics, validated theoretically and empirically across architectures.
</div>
</div>

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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2021 spotlight</div><img src='images/pic1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Embedding principle of loss landscape of deep neural networks](https://proceedings.neurips.cc/paper_files/paper/2021/file/7cc532d783a7461f227a5da8ea80bfe1-Paper.pdf)

Yaoyu Zhang†, **Zhongwang Zhang**, Tao Luo, Zhi-Qin John Xu†

- This paper proves an embedding principle that the loss landscape of a deep neural network (DNN) contains all the critical points of narrower DNNs, and proposes a critical embedding such that any critical point of a narrower DNN can be embedded to a critical point/affine subspace of the target DNN with higher degeneracy while preserving the DNN output function, providing a new perspective to study the general easy optimization of wide DNNs and unraveling a potential implicit low-complexity regularization during training.
</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards -->
- *2024.09* I won the 2024 China National Scholarship!


# 📖 Educations
- *2021.09 - now*, Ph.D., School of Mathematical Sciences, Shanghai Jiao Tong University. 
- *2017.09 - 2021.06*, Undergraduate, Zhiyuan College, Shanghai Jiao Tong University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.04 - now*, Tongyi Lab, Alibaba Group.
- *2024.04 - 2025.04*, Institute for Advanced Algorithms Research.
