---
permalink: /
title: "Homepage"
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

I am a first-year PhD student in Population Health Sciences (Epidemiology) at Harvard T.H. Chan School of Public Health, supervised by Dr. Yuan Ma. 


pursuing a Master’s degree in Epidemiology at Johns Hopkins University (since 2023). During this period, I served as a research assistant under the guidance of Prof. Jennifer Schrack and Prof. Ciprian Crainiceanu. I’m also fortunate to collaborate with Prof. John Muschelli. Prior to this, I underwent a year of Biostatistics Master training at Renmin University of China (2022-2023) under the guidance of A. Prof. Yu Wang. My academic journey began with a B.Eng degree (2018-2022) earned at Zhejiang University, where I was under the supervision of Prof. Yu Zhang. I felt lucky to have engaged in research collaborations with Prof. Ming Chen, Prof. Baiyi Lu, and A. Prof. Li Li. I am dedicated to enhance my professional skills in the combination field of BIOS & BIOINFO & EPI and cultivate the ability of innovation.

I am intrigued by the integration of aging indicators (e.g. frailty, biological age), digital biomarkers (e.g. wearable measurement), age-related disease (e.g. Dementia, CVD), and omics (e.g. Metabonomics, Metagenomics, GWAS). Furthermore, exploring biostatistical (e.g. causal inference, functional data) and data science (e.g. transfer learning, deep learning) methods also drive my interest. (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=QmKga9sAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


Sunan Gao is an incoming PhD student in Population Health Sciences (Epidemiology) at Harvard T.H. Chan School of Public Health. He holds a B.Eng. from Zhejiang University and a Master’s in Epidemiology from Johns Hopkins University. His research integrates high-dimensional data analysis, causal inference, machine learning, and wearable device data to better understand and intervene in aging-related processes. His research experience spans high-dimensional data analysis, causal inference, machine learning, and wearable device. These experiences have shaped his passion for understanding and intervening in aging-related processes. He has co-authored over ten peer-reviewed publications and developed tools for analyzing biological age, digital signals and time series data. Outside of research, he enjoys photography, reading, traveling, and playing ball games.



# 🔥 News
- *2025.07*: &nbsp;🎉 My undergraduate work was accepted for publication in Ecotoxicology and Environmental Safety!
- *2025.05*: &nbsp; I graduated from Hopkins with an ScM degree in Epidemiology.
- *2025.05*: &nbsp; I received the [Abe Lilienfeld Scholarship Fund](https://publichealth.jhu.edu/offices-and-services/office-of-admissions-services/funding-and-scholarships/funding-for-students/fund/83/abe-lilienfeld-scholarship-fund) ($5,000) at Hopkins.
- *2025.05*: &nbsp;🎉 My Mendelian Randomization paper was accepted for publication in Food & Function.
- *2025.03*: &nbsp;🎉 My Step Harmonization paper was accepted for publication in The Journals of Gerontology: Series A.
- *2025.02*: &nbsp; I was admitted to the PhD Program in Population Health at Harvard!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Food & Function (2025)</div><img src='images/publication/FF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring causal links in the gut–brain axis: a Mendelian randomization study of gut microbiota, metabolites, and cognition](https://pubs.rsc.org/en/content/articlelanding/2012/zj/d4fo04366a/unauth)

**Sunan Gao**, Angela Y. Xiao, Siyu Zou, Tongxu Li, Heming Deng, Yu Wang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">The Journals of Gerontology: Series A (2025)</div><img src='images/publication/JGMS-A.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Comparing Step-Counting Algorithms for High-Resolution Wrist Accelerometry Data in Older Adults in the ARIC Study](https://doi.org/10.1093/gerona/glaf034)

**Sunan Gao**, Xinkai Zhou, Lily Koffman, Amal A Wanigatunga, Jennifer A Schrack, Ciprian M Crainiceanu, John Muschelli, III
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ecotoxicology and Environmental Safety (2025)</div><img src='images/publication/EES.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A new method for internal urinary metabolite exposure and dietary exposure association assessment of 3-MCPD and glycidol and their esters based on machine learning](https://www.sciencedirect.com/science/article/pii/S0147651325008954)

Yimei Tian<sup>1</sup>, **Sunan Gao**<sup>1</sup>, Fan Zhang, Xuzhi Wan, Wei Jia, Jingjing Jiao, Yilei Fan, Yu Zhang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Affective Disorders (2023)</div><img src='images/publication/JAFD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Effects of accelerated biological age on depressive symptoms in a causal reasoning framework](https://doi.org/10.1016/j.jad.2023.07.019)

**Sunan Gao**, Heming Deng, Shaobo Wen, Yu Wang
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Affective Disorders (2023)</div><img src='images/publication/BMC_logo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A machine learning-based data mining in medical examination data: a biological features-based biological age prediction model](https://doi.org/10.1186/s12859-022-04966-7)

Qing Yang<sup>1</sup>, **Sunan Gao**<sup>1</sup>, Junfen Lin, Ke Lyu, Zexu Wu, Yuhao Chen, Yinwei Qiu, Yanrong Zhao, Wei Wang, Tianxiang Lin, Huiyun Pan, Ming Chen
</div>
</div>




- <span class="journal">Food Hydrocolloids (2022)</span> [Soy protein/chitosan-based microsphere as Stable Biocompatible Vehicles of Oleanolic Acid: An Emerging Alternative Enabling the Quality Maintenance of Minimally Processed Produce](https://doi.org/10.1016/j.foodhyd.2021.107325), **Sunan Gao**, Mingyi Yang, Zisheng Luo, Zhaojun Ban, Ya Pan, Mengyun Tu, Quan Ma, Xingyu Lin, Yanqun Xu, Li Li

- [A Fresh Perspective on Examining Population Emotional Well-Being Trends by Internet Search Engine: An Emerging Composite Anxiety and Depression Index](https://doi.org/10.3390/ijerph21020202), Yu Wang, Heming Deng, **Sunan Gao**, Tongxu Li, Feifei Wang, **International Journal of Environmental Research and Public Health** 

- [Reconstructing hepatic metabolic profile and glutathione-mediated metabolic fate of acrylamide](https://doi.org/10.1016/j.envpol.2023.122508), Yong Wu, Yaoran Li, Wei Jia, Li Zhu, Xuzhi Wan, **Sunan Gao**, Yu Zhang, **International Journal of Environmental Research and Public Health** 



# 🎖 Honors and Awards
- *2025.05* Abe Lilienfeld Scholarship Fund (one student per year at BSPH, across master’s and doctoral students)
- *2023.08* Master’s Tuition Scholarship, Johns Hopkins University
- *2022.05* Outstanding Undergraduate Thesis (Top 1%)
- *2021.10* National Scholarship (Top 1%)
- *2020.10* National Scholarship (Top 1%)
- *2020.05* Gold Prize, China International Student Innovation Competition (Top 1%)
- *2019.10* National Scholarship (Top 1%)

# 📖 Educations
- *2025.08 - 2029.05 (Expected)*, Doctor of Philosophy, Harvard University, Boston, United States
- *2023.08 - 2025.05*, Master of Science, Harvard University, Baltimore, United States
- *2018.08 - 2022.08*, Bachelor of Engineering, Zhejiang University, Hangzhou, China

# 💬 Teaching Experiences
- *2024.09 - 2025.05*, Epidemiologic Methods (I-III), Tutor, Johns Hopkins
- *2024.08 - 2025.05*, Methods in Biostatistics (I-IV), Teaching Assistant, Johns Hopkins
- *2020.10 - 2021.01*, Engineering Mechanics, Tutor, Zhejiang University




