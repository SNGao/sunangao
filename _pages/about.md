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

I am a first-year PhD student in Epidemiology at Harvard T.H. Chan School of Public Health, supervised by [Dr. Yuan Ma](https://connects.catalyst.harvard.edu/Profiles/profile/123145944). Prior to this, I completed my ScM in Epidemiology at Johns Hopkins Bloomberg School of Public Health (2023-2025), where I worked as a research assistant under the guidance of [Dr. Jennifer A. Schrack](https://publichealth.jhu.edu/faculty/2686/jennifer-a-schrack) and [Dr. Ciprian Crainiceanu](https://publichealth.jhu.edu/faculty/1442/ciprian-m-crainiceanu), with additional collaborations with [Dr. John Muschelli](https://publichealth.jhu.edu/faculty/2438/john-muschelli), [Dr. Amal A. Wanigatunga](https://publichealth.jhu.edu/faculty/3809/amal-asiri-wanigatunga), [Dr. Lacey Etzkorn](https://publichealth.jhu.edu/faculty/4768/lacey-etzkorn), and [Dr. Pablo Martinez-Amezcua](https://publichealth.jhu.edu/faculty/4426/pablo-martinez-amezcua). I also underwent master training in Epidemiology and Biostatistics at Renmin University of China (2022-2023) under [Dr. Yu Wang](http://stat.ruc.edu.cn/Home/People/Faculty/01eb35dbf5fe41588f82d3150ffcf409.htm). My academic foundation was established with a Bachelor of Engineering from Zhejiang University (2018-2022), where I engaged in research collaborations with [Drs. Yu Zhang](https://person.zju.edu.cn/en/yzhang#0), [Ming Chen](https://bis.zju.edu.cn/binfo/), [Baiyi Lu](https://www.researchgate.net/profile/Baiyi-Lu-2), and [Li Li](https://person.zju.edu.cn/en/lili).

My research interests center on the intersection of aging biomarkers, wearable devices, cognitive function, and multi-omics data. I am particularly passionate about developing and applying advanced methods including causal inference, functional data analysis, and machine learning approaches. I have co-authored over 10 peer-reviewed publications and developed several R packages for analyzing complex data. 

<!--
//(Google Scholar <a href='https://scholar.google.com/citations?user=QmKga9sAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). Outside of research, I enjoy photography, traveling, and investing.
-->


# 🔥 News
- *2025.07*: &nbsp;🎉 My undergraduate work was accepted for publication in Ecotoxicology and Environmental Safety!
- *2025.05*: &nbsp; I graduated from Hopkins with an ScM degree in Epidemiology.
- *2025.05*: &nbsp; I received the [Abe Lilienfeld Scholarship Fund](https://publichealth.jhu.edu/offices-and-services/office-of-admissions-services/funding-and-scholarships/funding-for-students/fund/83/abe-lilienfeld-scholarship-fund) ($5,000) at Hopkins.
- *2025.05*: &nbsp;🎉 My Mendelian Randomization paper was accepted for publication in Food and Function.
- *2025.03*: &nbsp;🎉 My Step Harmonization paper was accepted for publication in The Journals of Gerontology: Series A.
- *2025.02*: &nbsp; I was admitted to the PhD Program in Population Health at Harvard!

# 📝 Working Projects

# 📝 Publications (peer-reviewed)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Food and Function (2025)</div><img src='images/publication/FF.png' alt="sym" width="100%"></div></div>
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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMC Bioinformatics (2022)</div><img src='images/publication/BMC_logo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A machine learning-based data mining in medical examination data: a biological features-based biological age prediction model](https://doi.org/10.1186/s12859-022-04966-7)

Qing Yang<sup>1</sup>, **Sunan Gao**<sup>1</sup>, Junfen Lin, Ke Lyu, Zexu Wu, Yuhao Chen, Yinwei Qiu, Yanrong Zhao, Wei Wang, Tianxiang Lin, Huiyun Pan, Ming Chen
</div>
</div>



- [Soy protein/chitosan-based microsphere as Stable Biocompatible Vehicles of Oleanolic Acid: An Emerging Alternative Enabling the Quality Maintenance of Minimally Processed Produce](https://doi.org/10.1016/j.foodhyd.2021.107325), **Sunan Gao**, Mingyi Yang, Zisheng Luo, Zhaojun Ban, Ya Pan, Mengyun Tu, Quan Ma, Xingyu Lin, Yanqun Xu, Li Li, <span class="journal">Food Hydrocolloids (2022)</span>

- [A Fresh Perspective on Examining Population Emotional Well-Being Trends by Internet Search Engine: An Emerging Composite Anxiety and Depression Index](https://doi.org/10.3390/ijerph21020202), Yu Wang, Heming Deng, **Sunan Gao**, Tongxu Li, Feifei Wang, <span class="journal">International Journal of Environmental Research and Public Health (2024)</span>

- [Reconstructing hepatic metabolic profile and glutathione-mediated metabolic fate of acrylamide](https://doi.org/10.1016/j.envpol.2023.122508), Yong Wu, Yaoran Li, Wei Jia, Li Zhu, Xuzhi Wan, **Sunan Gao**, Yu Zhang, <span class="journal">Environmental Pollution (2023)</span>

- [Machine learning prediction of exposure to acrylamide based on modelling of association between dietary exposure and internal biomarkers](https://doi.org/10.1016/j.fct.2022.113498), Xuzhi Wan, Yiju Zhang, **Sunan Gao**, Xinyi Shen, Wei Jia, Xingqi Pan, Pan Zhuang, Jingjing Jiao, Yu Zhang, <span class="journal">Food and Chemical Toxicology (2022)</span>

- [Atmospheric pressure plasma jet pretreatment to facilitate cassava starch modification with octenyl succinic anhydride](https://doi.org/10.1016/j.foodchem.2021.130922), Shengyang Ji, Tao Xu, Weisu Huang, **Sunan Gao**, Yongheng Zhong, Xuan Yang, Mohamed Ahmed Hassan, Baiyi Lu, <span class="journal">Food Chemistry (2022)</span>

- [The chemical composition and potential role of epicuticular and intracuticular wax in four cultivars of table grapes](https://doi.org/10.1016/j.postharvbio.2020.111430), Mingyi Yang, Zisheng Luo, **Sunan Gao**, Tarun Belwal, Lei Wang, Ming Qi, Zhaojun Ban, Bin Wu, Fengzhong Wang, Li Li, <span class="journal">Postharvest Biology and Technology (2021)</span>

- [Application progress and prospect of light-emitting diode light technology in food preservation](10.13386/j.issn1002-0306.2020080116), Juncen Dong, **Sunan Gao**, Jianchu Chen, <span class="journal">Science and Technology of Food Industry (2020)</span>



# 🎖 Honors and Awards
- *2025.05* Abe Lilienfeld Scholarship Fund (one student per year at BSPH, across master’s and doctoral students)
- *2023.08* Master’s Tuition Scholarship, Johns Hopkins University
- *2022.05* Outstanding Undergraduate Thesis (Top 1%)
- *2021.10* National Scholarship (Top 1%)
- *2020.10* National Scholarship (Top 1%)
- *2020.05* Gold Prize, China International Student Innovation Competition (Top 1%)
- *2019.10* National Scholarship (Top 1%)

# 📖 Educations
- *2025.08 - 2029.05 (Expected)*, PhD in Epidemiology, Harvard University, Boston, United States
- *2024.02 - 2025.05*, Certificate in Clinical Trial, Johns Hopkins University, Baltimore, United States
- *2023.08 - 2025.05*, ScM in Epidemiology, Johns Hopkins University, Baltimore, United States
- *2018.08 - 2022.08*, B.E. in Food Science and Engineering, Zhejiang University, Hangzhou, China
- *2018.08 - 2020.08*, Minor in Psychology, Zhejiang University, Hangzhou, China

# 💬 Teaching Experiences
- *2024.09 - 2025.05*, Epidemiologic Methods (I-III), Tutor, Johns Hopkins
- *2024.08 - 2025.05*, Methods in Biostatistics (I-IV), Teaching Assistant, Johns Hopkins
- *2020.10 - 2021.01*, Engineering Mechanics, Tutor, Zhejiang University




