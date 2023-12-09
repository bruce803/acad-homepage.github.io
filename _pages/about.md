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

#  About Me
I am an Associate Professor in the Center of Statistical Research, School of Statistics at the Southwestern University of Finance and Economics. My research interest includes Graph Neural Networks and its applications in Economics and Medical Science.

<!-- My research interest includes Graph Neural Networks. I have published more than 30 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=U2Ao6lIAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=U2Ao6lIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.10*: &nbsp;🎉🎉 One student paper was accepted by the [AAAI 2024](https://aaai.org/aaai-conference/)
- *2023.12*: &nbsp; I am visiting Imperial Colledge London now (11.2023-12.2023).
- *2023.11*: &nbsp; I am going to serve as a TPC member of IEEE the 7th International Conference on Big Data and Artificial Intelligence [(BDAI 2024)](http://www.bdai.net/).
<!-- *2023.10*: &nbsp;🎉🎉 One paper about LLM was accepted by the [Journal of Artificial Intelligence Research] -->
<!-- (https://www.jair.org/index.php/jair/issue/view/1167).-->
<!-- *2023.09*: &nbsp;🎉🎉 [第16届中国R会议](https://mp.weixin.qq.com/s/cUqMvRR2NPQ4vRf4pFPf3g)在成都西南财经大学举办. -->


# 📐 Teaching Experience
I teach **Multivariate Statistical Analysis(多元统计分析)** this semester.

[slides & code](https://github.com/binspage/multiVariateAnaCourse)

## Courses taught:

<!--
| Statistical Learning | 18'Fall   |    Optimization Theory I |19',20',21',22'Fall|              Deep Learning  |          20'Fall|
|:---------------------|:----------|    :--------------------|:---------|              :----------------------|:---------|
| Machine Learning     |18',20'Fall|   Optimization Theory II |20', 21', 22'Spring, 21'Fall|     Natural Language Processing|21'Spring|
| Python Programming       |19'Fall|   Data Science in Action      |20'Fall|                       ||
| Foundations of Data Science      |19',20'Fall|   Introduction to Machine Learning    |20'Fall|   ||
-->

| 统计学习 | 18'Fall   |    最优化理论 I |19',20',21',22'Fall|              深度学习  |          20'Fall|
|:---------------------|:----------|    :--------------------|:---------|              :----------------------|:---------|
| 机器学习     |18',20'Fall|   最优化理论 II |20', 21', 22'Spring, 21'Fall|     自然语言处理|21'Spring|
| Python 编程       |19'Fall|   数据科学实战      |20'Fall|                       ||
| 数据科学基础      |19',20'Fall|   机器学习导论   |20'Fall|   ||
    
# 📝 Publications 

## GNN in Medical Science

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2023</div><img src='images/ASD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ASD diagnosis with GNNs](https://openreview.net/pdf?id=PVU-k24tPb)
  
Lu Wei, **Bin Liu***, Jiujun He, Manxue Zhang, Yi Huang
  
[**Project**](https://openreview.net/pdf?id=PVU-k24tPb) 
- Autism Spectrum Disorder (ASD) is an intricate neurodevelopmental condition that significantly impacts socialization and is distinguished by atypical, limited, or repetitive language behaviors. Our research focuses on the diagnosis of ASD utilizing multi-modal brain image data in conjunction with Graph Neural Networks (GNNs), specifically incorporating Diffusion Tensor Imaging (DTI), structural Magnetic Resonance Imaging (sMRI), and functional Magnetic Resonance Imaging (fMRI). Additionally, our objective is to identify the pathogenic functional regions within the brain networks associated with ASD.  
</div>
</div>


## GNN in F&E

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2023</div><img src='images/industryChain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Analyze Industrial Chain with GNNs](https://www.ijcai.org/proceedings/2023/0674.pdf)
  
**Bin Liu**, Jiujun He, Ziyuan Li, Xiaoyang Huang, Xiang Zhang, Guosheng Yin
  
[**Project**](https://www.ijcai.org/proceedings/2023/0674.pdf) 
- The digital development of the industrial chain attracts more and more attention from researchers and policymakers. One of the critical issues is how the efficiency of the industrial chain is affected by external factors, such as macroeconomic policy, government regulation or monetary policy, international political factors, internal factors, such as microeconomic driver factors, and so on.  In this project, we conduct a quantitative analysis of the development of the industry chain with GNNs. 
</div>
</div>

## Conference Papers

- **Bin Liu**, Jiujun He, Ziyuan Li, Xiaoyang Huang, Xiang Zhang, Guosheng Yin. [Interpret ESG Rating’s Impact on the Industrial Chain Using Graph Neural Networks](https://www.ijcai.org/proceedings/2023/0674.pdf). **IJCAI**, 2023, Macao, China, pp. 6076-6084.
- Lu Wei, **Bin Liu***, Jiujun He, Manxue Zhang, Yi Huang. [Autistic Spectrum Disorders Diagnose with Graph Neural Networks](https://www.acmmm2023.org/list-of-accepted-papers-to-the-main-track/). **ACM Multimedia**, 2023, Ottawa, Canada, pp. 8819–8827.
- Zhuo Tan, **Bin Liu***, Guosheng Yin. [Asymmetric Self-Supervised Graph Neural Networks](https://ieeexplore.ieee.org/abstract/document/10021033/). **IEEE International Conference on Big Data**, Osaka, Japan, 2022, pp. 1369-1376.
- Jiujun He, **Bin Liu**, Xuan Yang. [Non-local Patch Mixup for Unsupervised Domain Adaptation](https://ieeexplore.ieee.org/abstract/document/10027648/). **IEEE International Conference on Data Mining (ICDM)**, Orlando, FL, USA, 2022, pp. 969-974.
- **Bin Liu**, Wang Liang, Yin Guosheng. [Learning distributed sentence vectors with bi-directional 3D convolutions](https://aclanthology.org/2020.coling-main.601.pdf). **The 28th International Conference on Computational Linguistics(COLING)**, Barcelona, Spain, 2020, pp. 6820–6830.
- **Bin Liu**, Xiaoxue Gao, Mengshuang He, Lin Liu, Guosheng Yin. [A Fast Online COVID-19 Diagnostic System with Chest CT Scans](https://www.kdd.org/kdd2020/health-day/). **The 26TH ACM SIGKDD Conference on Knowledge Discovery and Data Mining (Health Day)**, 2020, Virtual Conference.
- **Bin Liu**, Guosheng Yin. [Chinese document classification with bi-directional convolutional language model](https://dl.acm.org/doi/abs/10.1145/3397271.3401248). **The 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval**, Xi'an, China, 2020, pp. 1785–1788.
- **Bin Liu**, Zenglin Xu, Bo Dai, Haoli Bai, Xianghong Fang, Yazhou Ren, Shandian Zhe. [Learning from semantically dependent multi-tasks](https://ieeexplore.ieee.org/abstract/document/7966296). **International Joint Conference on Neural Networks (IJCNN)**, Anchorage, AK, USA, 2017, pp. 3498-3505.
- Haoli Bai, Zenglin Xu, **Bin Liu**, Yingming Li. [Hierarchical probabilistic matrix factorization with network topology for multi-relational social network](http://proceedings.mlr.press/v63/bai103.html). **Proceedings of The 8th Asian Conference on Machine Learning**,  PMLR 63:270-285, 2016.
- **Bin Liu**, Chao Song, Nianbo Liu. [Distinguishing uncertain objects with multiple features for crowdsensing](https://ieeexplore.ieee.org/abstract/document/7037224). IEEE Global Communications Conference, Austin, TX, USA, 2014, pp. 2751-2756.

## Journal Papers
- **Bin Liu**, Guosheng Yin. [Graphmax for Text Generation](). **Journal of Artificial Intelligence Research**, vol. 78, pp.823-848, Nov. 2023.
- Zhuo Tan, Yifan Zhu, **Bin Liu***. [Learning spatial-temporal feature with graph product](https://doi.org/10.1016/j.sigpro.2023.109062). **Signal Processing**, 210 (2023): 109062.
- Shaogao Lv, Linsen Wei, Qian Zhang, **Bin Liu**, Zenglin Xu. ["Improved Inference for Imputation-Based Semisupervised Learning Under Misspecified Setting"](https://ieeexplore.ieee.org/abstract/document/9439834), **IEEE Transactions on Neural Networks and Learning Systems**, vol. 33, no. 11, pp. 6346-6359, Nov. 2022.
- Zenglin Xu, **Bin Liu***, Shandian Zhe, Haoli Bai, Zihan Wang, Jennifer Neville. [Variational random function model for network modeling](), **IEEE Transactions on Neural Networks and Learning Systems**, vol. 30, no. 1, pp. 318-324, Jan. 2019.
- **Bin Liu**, Lirong He, Yingming Li, Shandian Zhe, Zenglin Xu. [NeuralCP: Bayesian Multiway Data Analysis with Neural Tensor Decomposition](https://doi.org/10.1007/s12559-018-9587-4), **Cognitive Computation**, 10, pp.1051–1061, 2018.
- **Bin Liu**, Yingming Li, Zenglin Xu. [Manifold regularized matrix completion for multi-label learning with ADMM](). **Neural Networks**, vol. 101, pp. 57-67, 2018.
- **Bin Liu**, Zenglin Xu, Shuang Wu, Fei Wang. [Manifold regularized matrix completion for multilabel classification](https://doi.org/10.1016/j.patrec.2016.04.017). **Pattern Recognition Letters**, Vol. 80, pp. 58-63, 2016.



# 🎖 Honors and Awards
- *2016.10* Best Paper Runner Up, ACML 2016. 
- *2014.07* Best Paper Candidate, GlobeCom 2014.  

# 🎓 Educations
- *2013.09 - 2017.12*, University of Electronic Science and Technology of China, Computer Science PhD.  
- *2015.09 - 2019.06*, University of Electronic Science and Technology of China, Computer Science Mphil.
- *2004.09 - 2008.09*, Liaoning University of Technology, Bachelor of Computational Mathematics

# 🏫 Visiting
- - *2016.6 - 2017.6*, University of British Columbia, visiting student working on Bioinformatics supervised by Professor Raymond Ng.  

# 💻 Employment
- *2018.04 - (now)*, Associate professor at the School of Statistics, [Southwestern University of Finance and Economics](https://www.swufe.edu.cn/), Chengdu, China.
- *2018.09 - 2020.09*, PostDoc at Department of Statistics and Actuarial Science, [The University of Hong Kong](https://github.com/), Hong Kong, China.
  
# 💬 Invited Talks
- *2023.08*, Customizing personal large-scale language model using co-occurrence statistic information, 首届机器学习与统计会议，华东师范大学，上海. 
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->



