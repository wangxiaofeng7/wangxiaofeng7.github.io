---
permalink: /
title: "HomePage"
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

Dr. XiaoFeng Wang has been working on cybersecurity for more than two decades.  He is a Fellow of the ACM, IEEE and AAAS. He was a James H. Rudy Professor of Luddy School of Informatics, Computing and Engineering, Indiana University at Bloomington.  During the past 21 years, he also served IU in multiple administrative roles, including the Associate Dean for Research, a Co-Director of Center for Security and Privacy in Informatics, Computing and Engineering, and the Director of the Master of Science in Secure Computing (MSSC) program.

Nation-wide, Dr. Wang is the founder, and was the Director/Lead PI of Center for Distributed Confidential Computing (CDCC), a Frontiers Project in Secure and Trustworthy Computing funded by the National Science Foundation. The project is a multi-institution effort, involving faculty from IU (Lead), CMU, Duke, OSU, Penn State, Purdue, Spelman and Yale. The center aims at laying the technological foundations for practical data-in-use protection based on Trusted Execution Environments (TEE) over today and tomorrow’s cloud and edge platforms, which is critical to the advance of AI and data science.

Dr. Wang served as the Chair of ACM Special Interest Group on Security, Audit and Control (SIGSAC), from 2021 to 2025. He was also TPC Co-Chair of the ACM Conference on Computer and Communications Security (CCS), the ACM’s flagship security and privacy conference, during 2018 and 2019. In the past 20 years, Dr. Wang has been working on a broad range of research topics in systems security and data privacy. He is considered to be one of the most prominent systems security and privacy researchers, a top author according to online statistics such as [CSRankings](https://csrankings.org/#/fromyear/2014/toyear/2024/index?sec&us), [System Security Circus](https://www.s3.eurecom.fr/~balzarot/security-circus/authors.html) (Eurecom), and [Top Authors, the Systems Cirus](https://nebelwelt.net/pubstats/top-authors-sys_sec.html) (EPFL). Dr. Wang is known for his high-impact research on security analysis of real-world systems and biomedical data privacy. Particularly, the projects he led on side-channel analysis and mitigation, payment and single-sign-on API integrations, Android and iOS security and IoT protection have changed the way the industry built computing systems. Also he is a pioneer researcher on human genome privacy and a co-founder of the iDASH Genome Privacy Competition that contributes to reducing the gap between security and cryptography research and real-world demands for biomedical data sharing and computing protection. More recently, he is actively working on TEE-based Data-in-Use protection for supporting AI, Trustworthy AI, and application of AI technologies (such as NLP and deep learning) to protect computing systems, LTE/5G networks in particular.

For his work, Dr. Wang has received numerous awards, including Award for Outstanding Research in Privacy Enhancing Technologies (the PET Award), Best Practical Paper Award at the 32nd IEEE Symposium on Security and Privacy (IEEE S&P; Oakland), and two Distinguished Paper Awards at the 26th Network and Distributed System Security Symposium (NDSS). His work has been extensively reported by public media, including CNN, MSNBC, Forbes, Slashdot, Nature News, etc. Dr. Wang’s research has been supported by NSF, NIH, ARO, IARPA, and other federal funding agencies and industry. Since joining IU in 2004, Dr. Wang has been serving as PI on research projects totaling nearly $23 million (by 2022). 

For more information, please refer to [**his CV**]({{https://wangxiaofeng7.github.io}}/downloads/CV-xiaofeng_wang.pdf).

<!---

My research interest includes system security and AI security. I have published more than 100 papers at the top 4 security conferences with total <a href='https://scholar.google.com/citations?user=pONu-5EAAAAj'>google scholar citations <strong><span id='total_cit'>18000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=pONu-5EAAAAj'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

-->


# 🔥 Recent News Reports
- *2024.02*: Analysis on Underground Markets for Large Language Models ( [TechPolicy](https://www.techpolicy.press/studying-black-market-for-large-language-models-researchers-find-openai-models-power-malicious-services/), [Lemonde](https://www.lemonde.fr/sciences/article/2024/02/13/intelligence-artificielle-les-chatbots-gangrenes-par-les-cybercriminels_6216174_1650684.html), [WSJ](https://www.wsj.com/articles/welcome-to-the-era-of-badgpts-a104afa8), [FastCompany](https://www.fastcompany.com/91184474/black-market-ai-chatbots-thriving) )
- *2023.12*: Analysis on Information Leaks from Large Language Models ( [NYTime](https://www.nytimes.com/interactive/2023/12/22/technology/openai-chatgpt-privacy-exploit.html) )
- *2022.12*: Winning Two Tracks of NeurIPS’22 Trojan Detection Challenge ( [NeurIPS](https://news.iu.edu/luddy/live/news/44191-luddy-school-gets-pair-of-wins-in-trojan-detection) )
- *2022.08*: NSF SaTC Frontiers Award for CDCC ( [IUB](https://news.iu.edu/stories/2022/08/iub/releases/04-nsf-cybersecurity-awards-distributed-data-user-privacy.html), [NSF](https://beta.nsf.gov/news/nsf-announces-awards-advance-cybersecurity-efforts) )


<!---
# 📝 Recent Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🎖 Selected Honors and Awards
- 2024, ACM Fellow (Class 2023): for contributions to systems security and privacy
- 2023, AAAS Fellow (Class 2022): for distinguished contributions to the field of systems security and data privacy, particularly for security analysis and protection of computing systems and protection of human genomic data
- 2019, Distinguished Paper Award, the 26th Network and Distributed System Security Symposium (NDSS): for the research on cybercrime analysis
- 2019, Distinguished Paper Award, the 26th Network and Distributed System Security Symposium (NDSS): for the research on genomic privacy
- 2019, IEEE Fellow (Computer Society): for contributions to system security and genomic privacy
- 2017, James H. Rudy Professorship, Indiana University
- 2016, Best Paper Award in Applied Cyber Security Research, 3rd Place, CSAW’16 (NYU- Poly Cyber Security Awareness Week): for the work on cyber threat intelligence gathering
- 2014, Best Paper Award in Applied Cyber Security Research, 3rd Place, CSAW’14 (NYU- Poly Cyber Security Awareness Week): for the work on security risks in Android customization
- 2014, Third place in National Security Innovation Competition: for the work on Android secure upgrading
- 2013, Finalist for the Best Applied Security Paper Award, CSAW’13 (NYU-Poly Cyber Security Awareness Week): for the work on dedicated hosts on malicious web infrastructures
- 2011, PET Award for my research on Genome Privacy
- 2011, PET Award runner-up for my research on side-channel information leaks in web applications
- 2011, Best Practical Paper Award , the 32nd IEEE Symposium on Security and Privacy

<!---
# 📖 Teaching
- Fall 2005~Now: I430/520/B649, “Security for Networked Systems”, An upper-level undergraduate and graduate course, IUB
- Spring 2007~Now: I521, “Malware: Threat and Defense”, A graduate course, IUB
- Spring 2006~2009: I231, Mathematic Foundations for Cybersecurity, A second-year undergraduate course, IUB
- Spring 2005: I400, Introduction to Information Security, A third and forth year undergraduate course, IUB
- Spring 2002: 18440, Internet Security, Teaching Assistant, An upper-level undergraduate and graduate course, Carnegie Mellon University
-->

# 💬 Selected Recent Talks
- 2024, Distinguished Lecture for Institute of Data Science, Hong Kong University
- 2024, Keynote for the 19th ACM ASIA Conference on Computer and Communications Security (ACM ASIACCS)
- 2024, Invited Seminar for Cybersecurity and Privacy (CySeP) Summer School, an ACM Europe Summer School organized by KTH Royal Institute of Technology in Stockholm, Sweden
- 2021, Invited Talk at the UK Security and Privacy Seminar 
- 2021, Invited Talk at Institute for Assured Autonomy at Johns Hopkins University
- 2020, Keynote for 14th International Conference on Network and System Security, Melbourne, Australia
- 2019, Keynote for SIGSAC at ACM Turing Celebration Conference, China
- 2018, Keynote at the 3rd Singapore Cybersecurity R&D Conference (SG-CRC’18)

<!---
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
