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
Liu Bin is an Associate Professor of the Center of Statistical Research, School of Statistics at the Southwestern University of Finance and Economics.

<!-- My research interest includes Graph Neural Networks. I have published more than 30 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=U2Ao6lIAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=U2Ao6lIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2023 2016</div><img src='images/ASD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

Lu Wei, **Bin Liu***, Jiujun He, Manxue Zhang, Yi Huang

[**Project**](https://openreview.net/pdf?id=PVU-k24tPb) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Autism spectrum disorder (ASD) is a complex neurodevelopmental disorder that affects socialization and is characterized by abnormal, restricted, or repetitive language behaviors. Symptoms typically start to appear around the age of 2, making early diagnosis essential for treatment. One standardized screening method is an autism-specific interview with children's parents. However, this diagnostic process requires highly experienced physicians, making questionnaire-based screening less effective. Recently, imaging-based diagnosis has emerged as a more objective option. In this paper, we propose a graph neural network-based model for ASD diagnosis using Diffusion Tensor Imaging (DTI)  and functional Magnetic Resonance Imaging (fMRI) data. We first calculate the correlations of 90 brain regions based on the automated anatomical labeling (AAL) template using brain imaging data of DTI and fMRI. This enables the construction of a comprehensive network map that delineates the interconnections among various brain regions. Subsequently, we propose to utilize a graph neural network for the purpose of diagnosing ASD, wherein the graph derived from DTI serves as the adjacency matrix, while the map of the fMRI is utilized as the node features. To improve the performance of diagnosis, we introduce a regularization of maximum inter-class graph distance and minimum intra-class graph distance, in addition to graph classification. We then calculate the correlation matrix between functional areas based on the obtained 90 implicit features corresponding to the nodes of functional areas and their 90 eigenvalues. We also perform hypothesis tests on the 90 eigenvalues corresponding to ASD negative and positive groups in turn to discover the pathogenic functional areas by comparing the eigenvalue distributions between the two groups. Our experiments on 138 real-world samples demonstrate the superior performance of our proposed model for diagnosis. 
</div>

</div>

- **Bin Liu**, Jiujun He, Ziyuan Li, Xiaoyang Huang, Xiang Zhang, Guosheng Yin. [Interpret ESG Rating’s Impact on the Industrial Chain Using Graph Neural Networks](https://www.ijcai.org/proceedings/2023/0674.pdf). **IJCAI**, 2023, Macao, China.
- Lu Wei, **Bin Liu***, Jiujun He, Manxue Zhang, Yi Huang. [Autistic Spectrum Disorders Diagnose with Graph Neural Networks](https://www.acmmm2023.org/list-of-accepted-papers-to-the-main-track/). **ACM Multimedia**, 2023, Ottawa, Canada.
- Zhuo Tan, **Bin Liu***, Guosheng Yin. [Asymmetric Self-Supervised Graph Neural Networks](https://ieeexplore.ieee.org/abstract/document/10021033/). **IEEE International Conference on Big Data**, Osaka, Japan, 2022, pp. 1369-1376.
- Jiujun He, **Bin Liu**, Xuan Yang. [Non-local Patch Mixup for Unsupervised Domain Adaptation](https://ieeexplore.ieee.org/abstract/document/10027648/). 2022 IEEE International Conference on Data Mining (ICDM), Orlando, FL, USA, 2022, pp. 969-974.

- Zhuo Tan, Yifan Zhu, **Bin Liu***. [Learning spatial-temporal feature with graph product](https://doi.org/10.1016/j.sigpro.2023.109062). **Signal Processing 210 (2023): 109062**
- Shaogao Lv, Linsen Wei, Qian Zhang, **Bin Liu**, Zenglin Xu. ["Improved Inference for Imputation-Based Semisupervised Learning Under Misspecified Setting"](https://ieeexplore.ieee.org/abstract/document/9439834), IEEE Transactions on Neural Networks and Learning Systems, vol. 33, no. 11, pp. 6346-6359, Nov. 2022





- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2016.10* Best Paper Runner Up, ACML 2016. 
- *2014.07* Best Paper Candidate, GlobeCom 2014.  

# 📖 Educations
- *2013.09 - 2017.12 (now)*, University of Electronic Science and Technology of China, Computer Science PhD.  
- *2015.09 - 2019.06*, University of Electronic Science and Technology of China, Computer Science Mphil.
- *2004.09 - 2008.09*, Liaoning University of Technology, Bachelor of Computational Mathematics

# 📖 Visiting
- - *2016.6 - 2017.6 *, University of British Columbia, visiting student working on Bioinformatics supervised by Professor Raymond Ng.  

# 💻 Employment
- *2013.09 - 2017.12 (now)*, Associate professor at the School of Statistics, [Southwestern University of Finance and Economics](https://www.swufe.edu.cn/), Chengdu, China.
- *2018.09 - 2020.09*, PostDoc at Department of Statistics and Actuarial Science, [The University of Hong Kong](https://github.com/), Hong Kong, China.
  
# 💬 Invited Talks
- *2023.08*, Customizing personal large-scale language model using co-occurrence statistic information, 首届机器学习与统计会议，华东师范大学，上海. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)



