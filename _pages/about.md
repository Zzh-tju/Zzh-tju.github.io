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

## About me

Zhaohui Zheng is currently a postdoctoral fellow at the HK PolyU, working on Visual-Language Models and object detection with Prof. [Lei Zhang](https://www4.comp.polyu.edu.hk/~cslzhang/).
Before that, he received his Ph.D. from Nankai University in 2025 under the supervision of Prof. [Ming-Ming Cheng](https://mmcheng.net/), and his M.S. degree in computational mathematics from Tianjin University in 2021 under the supervision of Prof. Ping Wang.
He received the CCF-CV Academic Emerging Scholar Award in 2023.
 <a href='https://scholar.google.com/citations?user=0X71NDYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=Citation"></a>

## Professional Experience

2025 - 202X: <b>Department of Computing</b> - The HK PolyU, Hong Kong, China

2021 - 2025: <b>Computer science</b> - Nankai University, Tianjin, China

2018 - 2021: <b>Computational mathematics</b> - Tianjin University, Tianjin, China

2014 - 2018: <b>Applied mathematics</b> - Zhengzhou University, Zhengzhou, China

<span class='anchor' id='-experience'></span>

## Research Interests

My research interests are Visual-Language Models, object detection, instance segmentation, and knowledge distillation. 

See my recent publications for more details.

<span class='anchor' id='-new'></span>

## News

+ I received the National Scholarship for doctoral students.
+ One paper accepted by T-PAMI'24
+ One paper accepted by CVPR'24
+ I received the CCF-CV Academic Emerging Scholar Award in 2023.
+ One paper accepted by ICCV'23
+ One paper accepted by T-PAMI'23
+ One paper accepted by CVPR'22
+ One paper accepted by T-CYB'22
+ One paper accepted by AAAI'20

<span class='anchor' id='-collaborator'></span>

## Collaborator

+ Ming-Ming Cheng, Nankai University
+ Qibin Hou, Nankai University
+ Xiang Li, Nankai University
+ Chenyu Ming, Nankai University
+ Jiabao Wang, Nankai University
+ Yuxuan Li, Nankai University
  
+ Jian Yang, Nanjing University of Science and Technology
  
+ Wangmeng Zuo, Harbin Institute of Technology
+ Dongwei Ren, Harbin Institute of Technology
  
+ Qinghua Hu, Tianjin University
+ Ping Wang, Tianjin University
+ Rongguang Ye, Tianjin University
+ Wei Liu, Tianjin University
  
+ Jinze Li, People’s Public Security University of China

<span class='anchor' id='-pub'></span>

## Journal Publications ([Google Scholar](https://scholar.google.com/citations?user=0X71NDYAAAAJ&hl=en))

#### "*" means authors contributed equally and "#" means corresponding author.

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Zone Evaluation: Revealing Spatial Bias in Object Detection</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Yuming Chen, Qibin Hou#, Xiang Li, Ping Wang, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2024</p>   
  <p style="line-height:15px"> <a href="https://ieeexplore.ieee.org/abstract/document/10547427">[Arxiv]</a> <a href="https://github.com/Zzh-tju/ZoneEval" class="redlink">[Code]</a> </p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Localization distillation for object detection</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Rongguang Ye, Qibin Hou#, Dongwei Ren, Ping Wang, Wangmeng Zuo, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023</p>   
  <p style="line-height:15px"> <a href="https://ieeexplore.ieee.org/abstract/document/10052761">[Arxiv]</a> <a href="https://github.com/HikariTJU/LD" class="redlink">[Code]</a> </p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Enhancing geometric factors in model learning and inference for object detection and instance segmentation</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Ping Wang, Dongwei Ren#, Wei Liu, Rongguang Ye, Qinghua Hu, Wangmeng Zuo</p> 
  <p style="line-height:15px">IEEE Transactions on Cybernetics (TCYB), 2022</p>   
  <p style="line-height:15px"> <a href="https://ieeexplore.ieee.org/abstract/document/9523600/">[Arxiv]</a> <a href="https://github.com/Zzh-tju/CIoU" class="redlink">[Code]</a> <b>ESI Highly Cited Paper</b> </p>   
  </sub>
</blockquote>

## Conference Publications ([Google Scholar](https://scholar.google.com/citations?user=0X71NDYAAAAJ&hl=en))

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Distance-IoU loss: Faster and better learning for bounding box regression</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Ping Wang, Wei Liu, Jinze Li, Rongguang Ye, Dongwei Ren#</p> 
  <p style="line-height:15px">Proceedings of the AAAI Conference on Artificial Intelligence (AAAI), 2020</p>   
  <p style="line-height:15px"> <a href="https://doi.org/10.1609/aaai.v34i07.6999">[Arxiv]</a> <a href="https://github.com/Zzh-tju/DIoU">[Code]</a> <b>Most influential AAAI 2020 paper, Top-2</b> <a href="https://www.paperdigest.org/2024/05/most-influential-aaai-papers-2024-05/">[Paper digest]</a> </p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Localization distillation for dense object detection</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>*, Rongguang Ye*, Ping Wang, Dongwei Ren, Wangmeng Zuo, Qibin Hou#, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2022</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Localization_Distillation_for_Dense_Object_Detection_CVPR_2022_paper.pdf">[Arxiv]</a> <a href="https://github.com/HikariTJU/LD">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>CrossKD: Cross-Head Knowledge Distillation for Dense Object Detection</h4>   
  <sub><p style="line-height:15px"> Jiabao Wang*, Yuming Chen*, <b>Zhaohui Zheng</b>, Xiang Li, Ming-Ming Cheng, Qibin Hou#</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/CVPR2024/html/Wang_CrossKD_Cross-Head_Knowledge_Distillation_for_Object_Detection_CVPR_2024_paper.html">[Arxiv]</a> <a href="https://github.com/jbwang1997/CrossKD">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Large selective kernel network for remote sensing object detection</h4>   
  <sub><p style="line-height:15px"> Yuxuan Li, Qibin Hou, <b>Zhaohui Zheng</b>, Ming-Ming Cheng, Jian Yang#, Xiang Li#</p> 
  <p style="line-height:15px">IEEE International Conference on Computer Vision (ICCV), 2023</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Li_Large_Selective_Kernel_Network_for_Remote_Sensing_Object_Detection_ICCV_2023_paper.html">[Arxiv]</a> <a href="https://github.com/VCIP-RGBD/DFormer">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Strip R-CNN: Large Strip Convolution for Remote Sensing Object Detection</h4>   
  <sub><p style="line-height:15px"> Xinbin Yuan, ZhaoHui Zheng, Yuxuan Li, Xialei Liu, Li Liu, Xiang Li, Qibin Hou#, Ming-Ming Cheng#</p> 
  <p style="line-height:15px">AAAI, 2026</p>  
  <p style="line-height:15px"> <a href="https://arxiv.org/abs/2501.03775">[Arxiv 2025.01]</a> <a href="https://github.com/YXB-NKU/Strip-R-CNN">[Code]</a></p>   
  </sub>
</blockquote>

## Preprint

## Academic Services

+ Reviewers for TPAMI/CVPR/NeurIPS/ICML/ICLR etc.

<span class='anchor' id='-awards'></span>

## Honors and Awards

+ CCF-CV Academic Emerging Scholar Award, 2023.
+ National Scholarship for doctoral students, 2024.




