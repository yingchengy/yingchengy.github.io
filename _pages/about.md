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

I am currently a postdoc working in Cross-Media Intelligent Computing Lab at Fudan University.

I received my Ph.D. from Fudan University in June 2023, under the supervision of [Rui Feng](https://faculty.fudan.edu.cn/fengrui/zh_CN/index.htm). 
My research interest includes multimodal representation learning and knowledge infusion. I have published 10+ papers  <a href='https://scholar.google.com/citations?user=wsmBf7oAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI conferences such as TMM, ACM MM and ICASSP.

<!-- I graduated from Fudan University (复旦大学) with a master’s degree. I was a member of [Fudan NLP Group (复旦大学自然语言处理实验室)](https://nlp.fudan.edu.cn), advised by [Xuanjing Huang (黄萱菁)](https://xuanjing-huang.github.io) and [Zhongyu Wei (魏忠钰)](http://www.fudan-disc.com/people). -->


# 🔥 News
- *2024.12*: &nbsp;🎉 A total of three papers are accepted by AAAI 2025, COLING 2025 and ICASSP 2025.
- *2024.09*: &nbsp;🎉 One paper is accepted by NeurIPS 2024.
- *2024.07*: &nbsp;🎉 One paper is accepted by ACM MM 2024.
- *2024.05*: &nbsp;🎉 One paper is accepted by KDD 2024.

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->

<!-- **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div> -->
<!-- </div> -->
- `NeurIPS 2024` **Mixtures of Experts for Audio-Visual Learning**      
**Ying Cheng**, Yang Li, Junjie He, Rui Feng [[paper](https://openreview.net/pdf?id=SNmuKbU0am)]

- `ACM MM 2021` **Exploring Logical Reasoning for Referring Expression Comprehension**  
**Ying Cheng**, Ruize Wang, Jiashuo Yu, Rui-Wei Zhao, Yuejie Zhang, Rui Feng [[paper](https://dl.acm.org/doi/abs/10.1145/3474085.3475677)]

- `ACM MM 2020` **Look, Listen, and Attend: Co-Attention Network for Self-Supervised Audio-Visual Representation Learning**    
**Ying Cheng**, Ruize Wang, Zhihao Pan, Rui Feng, Yuejie Zhang [[paper](https://arxiv.org/pdf/2008.05789)]

- `ICASSP 2021` **Improving Multimodal Speech Enhancement by Incorporating Self-Supervised and Curriculum Learning**     
**Ying Cheng**, Mengyu He, Jiashuo Yu, Rui Feng [[paper](https://ieeexplore.ieee.org/abstract/document/9413431)]

- `KDD 2024` **ADSNet: Cross-Domain LTV Prediction with an Adaptive Siamese Network in Advertising**      
Ruize Wang, Hui Xu, **Ying Cheng**, Qi He, Xing Zhou, Rui Feng, Wei Xu, Lei Huang, Jie Jiang [[paper](https://arxiv.org/abs/2406.10517v1)]

- `AAAI 2025` **AS-Det: Active Sampling for Adaptive 3D Object Detection in Point Clouds**      
Ziheng Ding, Xiaze Zhang, Qi Jing, **Ying Cheng***, Rui Feng* [[paper]()]

- `COLING 2025` **RoBGuard: Enhancing LLMs to Assess Risk of Bias in Clinical Trial Documents**      
Changkai Ji, Bowen Zhao, Zhuoyao Wang, Yingwen Wang, Yuejie Zhang, **Ying Cheng**, Rui Feng and Xiaobo Zhang [[paper]()]

- `ICASSP 2025` **Uncertainty-Aware Dynamic Fusion for Multimodal Clinical Prediction Tasks**      
Jiayu Guo, **Ying Cheng**, Wen He, Yuejie Zhang, Rui Feng*, Xiaobo Zhang* [[paper]()]

- `ACM MM 2024` **DeepPointMap2: Accurate and Robust LiDAR-Visual SLAM with Neural Descriptors**      
Xiaze Zhang, Ziheng Ding, Qi Jing, **Ying Cheng**, Wenchao Ding, Rui Feng [[paper](https://openreview.net/pdf?id=05PCDMN4Dk)]

- `ACM MM 2024` **CT^2C-QA: Multimodal Question Answering over Chinese Text, Table and Chart**      
Bowen Zhao, Tianhao Cheng, Yuejie Zhang, **Ying Cheng**, Rui Feng, Xiaobo Zhang [[paper](https://arxiv.org/pdf/2410.21414)]

- `TMM 2023` **Self-Supervised Learning of Music-Dance Representation through Explicit-Implicit Rhythm Synchronization**     
Jiashuo Yu, Junfu Pu, **Ying Cheng**, Rui Feng, Ying Shan [[paper](https://arxiv.org/abs/2207.03190)]

- `ACM MM 2022` **MM-Pyramid: Multimodal Pyramid Attentional Network for Audio-Visual Event Localization**     
Jiashuo Yu, **Ying Cheng**, Ruiwei Zhao, Rui Feng [[paper](https://arxiv.org/pdf/2111.12374)]

- `ACM MM 2022` **Modality-Aware Contrastive Instance Learning with Self-Distillation for Weakly-Supervised Audio-Visual Violence Detection**     
Jiashuo Yu, Jinyu Liu, **Ying Cheng**, Rui Feng, Yuejie Zhang [[paper](https://arxiv.org/pdf/2207.05500)]

- `ACM MM 2022` **IDEA: Increasing Text Diversity via Online Multi-Label Recognition for Vision-Language Pre-training**     
Xinyu Huang, Youcai Zhang, **Ying Cheng**, Weiwei Tian, Rui-Wei Zhao, Rui Feng, Yuejie Zhang, Yaqian Li, Yandong Guo, Xiaobo Zhang [[paper](https://arxiv.org/pdf/2207.05333)]

- `ICME 2022` **Self-Supervised Video Representation Learning with Motion-Contrastive Perception**     
Jinyu Liu, **Ying Cheng**, Yuejie Zhang, Ruiwei Zhao, Rui Feng* [[paper](https://arxiv.org/pdf/2204.04607)]

- `ICME 2021` **MPN: Multimodal Parallel Network for Audio-Visual Event Localization**     
Jiashuo Yu, **Ying Cheng**, Rui Feng [[paper](https://arxiv.org/pdf/2104.02971)]

- `COLING 2020` **Keep it Consistent: Topic-Aware Storytelling from an Image Stream via Iterative Multi-agent Communication**     
Ruize Wang, Zhongyu Wei, **Ying Cheng**, Piji Li, Haijun Shan, Ji Zhang, Qi Zhang, Xuanjing Huang [[paper](https://arxiv.org/abs/1911.04192)]


# 📖 Educations
- *2018.09 - 2023.06*, Fudan University  
    Bachelor-PhD in Computer Science
- *2014.09 - 2018.06*, Yunnan University  
    Bachelor of Science in Communication Engineering

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2020.05 - 2020.09*, Alibaba · DAMO, Hangzhou.  
  Mentor: [Dr. Fenglin Li](https://scholar.google.com.hk/citations?user=xo_dfnMAAAAJ&hl=zh-CN)
- *2019.10 - 2020.04*, Natural Language Computing Group, Microsoft Research Asia (MSRA), Beijing.   
  Mentor: [Dr. Duyu Tang](https://scholar.google.com.hk/citations?user=9uz-D-kAAAAJ&hl=zh-CN) -->


# 🎖 Honors and Awards
- Outstanding Graduates of Shanghai, *2023*
- National Scholarship of Ph.D (Top 1%), *2021*
- National Scholarship of Ph.D (Top 1%), *2020*
- Outstanding Graduates of Yunnan Province, *2018*
- Bao Gang Education Scholarship (Top 1%), *2017*
- National Undergraduate Electronics Design Contest - National First Prize, *2017*
- Microsoft Imagine Cup Global Student Technology Competition - National Third Prize & Regional First Prize, *2017*
- National Undergraduate Mathematical Contest - National Second Prize, *2016*
- Google College Student Mobile Internet Innovation Challenge - Silver Award, *2016*
