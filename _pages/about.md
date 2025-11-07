---
permalink: /
title: <p align="center">Sizhe Chen (陈思哲)</p>
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
  
Biography
------
Hi! I am a CS Ph.D. candidate at [UC Berkeley](https://eecs.berkeley.edu) in [Berkeley AI Research (BAIR)](https://bair.berkeley.edu), where I am fortunately advised by Prof. [David Wagner](https://people.eecs.berkeley.edu/~daw), with additional thesis committee members: [Raluca Ada Popa](https://people.eecs.berkeley.edu/~raluca), [Sewon Min](https://www.sewonmin.com), and [Eric Wallace](https://www.ericswallace.com). Supported by Google- and Meta-[BAIR Commons](https://bcommons.berkeley.edu/home), I am working with [Chawin Sitawari](https://chawins.github.io) and [Arman Zharmagambetov](https://arman-z.github.io), and have worked with [Chuan Guo](https://sites.google.com/view/chuanguo) and [Nicholas Carlini](https://nicholas.carlini.com). I got my M.Eng. (National Scholarship) and B.Eng. (Summa Cum Laude) from [Shanghai Jiao Tong University](http://en.sjtu.edu.cn) advised by Prof. [Xiaolin Huang](http://www.pami.sjtu.edu.cn/en/xiaolin), see my previous [SoP](https://drive.google.com/file/d/1nmocMJFOmw_5_N1roe96Vszhhg7zhaZS/view?usp=sharing).

I study **AI security** in real-world applications. Currently, I am defending against [prompt injection attacks](https://www.ibm.com/topics/prompt-injection), the [top-1 threat](https://genai.owasp.org/llm-top-10/) to AI agents. Prompt injection has caused actual harm on multiple AI systems from [Google](https://embracethered.com/blog/posts/2023/google-bard-data-exfiltration/), [OpenAI](https://embracethered.com/blog/posts/2025/chatgpt-operator-prompt-injection-exploits), [Anthropic](https://embracethered.com/blog/posts/2024/claude-computer-use-c2-the-zombais-are-coming), [Slack](https://promptarmor.substack.com/p/data-exfiltration-from-slack-ai-via), etc. To open up broader usage of LLMs in agents, I develop principled, general, and practical prompt injection defenses. Our state-of-the-art open robust LLMs, [Meta-SecAlign](https://arxiv.org/pdf/2507.02735) (**ready for [commercial usage](https://www.llama.com/llama3_3/license/)**), have an order of magnitude less attack success rates against various prompt injections, and have been downloaded by 10k times in 3 months. <a href='https://scholar.google.com/citations?user=lp5ujPsAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/Sizhe-Chen/Sizhe-Chen.github.io/google-scholar-stats/gs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

I am fortunate to have mentored or worked with lots of talented students: [Yizhu Wang](https://yizhu-joy.github.io), [Jing Qian](https://jing-qian-98.github.io), [Shutong Wu](https://cychomatica.github.io), Zhixing Ye, etc. With [David Wagner](https://people.eecs.berkeley.edu/~daw), I am looking for a 2026 Summer intern who is applying to 2027 Fall PhD programs.

Invited Talks
------
+ **Securing LLMs Against Prompt Injection for Agentic Applications** [![](https://img.shields.io/badge/Talk-edca82)](https://docs.google.com/document/d/1pip5y_HGU4qjN0K6NEFuI379RPdL9T6o/edit?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1Xy_njupWCAN56NMsQV22hD7uShg5oBP8/view?usp=sharing) [![](https://img.shields.io/badge/Media-75291c)](https://bair.berkeley.edu/blog/2025/04/11/prompt-injection-defense) <br/> Penn State University: Guest Lecture at Threats and Cybersecurity 2025 <br/> Cornell University (Cornell-Tech Campus): Guest Lecture at [Trustworthy AI](https://trustworthy-ai-2025.github.io/) 2025 <br/> Google DeepMind: Adversarial Machine Learning Seminar 2025 <br/> Duke University: Guest Lecture at [Generative AI: Foundations, Applications, and Safety](https://ece590-genai.github.io) 2025 <br/> UC Berkeley: Security Seminar 2024 <br/> Hong Kong Baptist University: TMLR Young Scientist Seminar 2024 <br/> Shanghai Jiao Tong University: PAMI Group Seminar 2024
+ **On the Learning Preference of Deep Neural Networks** [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/11G7gn0-_sAsLTc5vKi6econZlCZdR0Kg/view?usp=sharing) <br/> ICLR Oral Track 2023 <br/> AI Time Youth Ph.D. Talk 2023
+ **Subspace Adversarial Training** [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1NaF_bZkrPvfsScLfVcjPqcPVQ3CW8hoK/view?usp=sharing) <br/> CVPR Oral Track 2022
+ **Adversarial Attacks and Defenses** [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1i6CIrdynqdidqgoTACkSmJEVQm7xRT0S/view?usp=sharing) <br/> Northeastern University: Security Seminar 2022

Selected Publications
------
+ **Defending Against Prompt Injection with DataFilter** <br/> Yizhu Wang,  **Sizhe Chen**, Raghad Alkhudair, Basel Alomair, David Wagner <br/> [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2510.19207) [![](https://img.shields.io/badge/DataFilter-8B-FFD21E)](https://huggingface.co/JoyYizhu/DataFilter) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/yizhu-joy/DataFilter) <br/> 
+ **Meta SecAlign: A Secure Foundation LLM Against Prompt Injection Attacks** <br/> **Sizhe Chen**\*, Arman Zharmagambetov, David Wagner, Chuan Guo\* <br/> [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2507.02735) [![](https://img.shields.io/badge/Meta%20SecAlign-8B-FFD21E)](https://huggingface.co/facebook/Meta-SecAlign-8B) [![](https://img.shields.io/badge/Meta%20SecAlign-70B-FFD21E)](https://huggingface.co/facebook/Meta-SecAlign-70B) [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1JbbgKPQVQ-Pa5LVYWyR4Eo5ckNyrZiPw/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1Xy_njupWCAN56NMsQV22hD7uShg5oBP8/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/facebookresearch/Meta_SecAlign) <br/> 
Meta-SecAlign-70B is the first open-source LLM with built-in prompt injection defense and commercial-grade performance, and greatly outperforms gpt-4o and gemini-2.5-flash and is comparable to gpt-5 in agentic (tool/web) utility and security.
+ **Defending Against Prompt Injection with a Few DefensiveTokens** <br/> **Sizhe Chen**, Yizhu Wang, Nicholas Carlini, Chawin Sitawarin, David Wagner <br/> [![](https://img.shields.io/badge/AISec%20Spotlight-2025-e1dd72)](https://arxiv.org/abs/2507.07974) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2507.07974) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1P6AfgGCqV5r3lU8Us8ehLDN6tpajDSm-/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/DefensiveToken)
+ **SecAlign: Defending Against Prompt Injection with Preference Optimization** <br/> **Sizhe Chen**, Arman Zharmagambetov, Saeed Mahloujifar, Kamalika Chaudhuri, David Wagner, Chuan Guo <br/> [![](https://img.shields.io/badge/CCS-2025-e1dd72)](http://arxiv.org/abs/2410.05451) [![M](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2410.05451) [![](https://img.shields.io/badge/Website-097770)](https://sizhe-chen.github.io/SecAlign-Website) [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1-HFnET2azKniaS4k5dvgVwoRLa4Eg584/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1SwaQrsNdmr7QJ9sPzfTXcjT2ZXA4w6nJ/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/facebookresearch/SecAlign) <br/> SecAlign aims at a prompt-injection-robust LLM that prefers (and thus output) the secure response over the insecure one. 
+ **StruQ: Defending Against Prompt Injection with Structured Queries** <br/> **Sizhe Chen**, Julien Piet, Chawin Sitawarin, David Wagner <br/> [![](https://img.shields.io/badge/USENIX%20Security-2025-e1dd72)](https://www.usenix.org/system/files/usenixsecurity25-chen-sizhe.pdf) [![](https://img.shields.io/badge/Paper-a8c66c)](http://arxiv.org/pdf/2402.06363)  [![](https://img.shields.io/badge/Website-097770)](https://sizhe-chen.github.io/StruQ-Website) [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1UUz4t43sGqFOPZqNxf8izR--iLAl16QX/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1FkTHIhGAaPtFwf91tgBad-sE7PEJnySJ/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/StruQ) <br/> StruQ is a general framework for prompt injection defense by separating the prompt (user instruction) and data into two channels. 
+ **One-Pixel Shortcut: On the Learning Preference of Deep Neural Networks** <br/> Shutong Wu\*, **Sizhe Chen**\*, Cihang Xie, Xiaolin Huang <br/> [![](https://img.shields.io/badge/ICLR%20Spotlight-2023-e1dd72)](https://openreview.net/forum?id=p7G8t5FVn2h) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2205.12141)  [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1p5SSuoGPcQCMul9N7pmp_1ON_xupKeoD/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://iclr.cc/virtual/2023/oral/12603) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1maneRbPHAbKd8-toYXnAcpqabNhciOEK/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/cychomatica/One-Pixel-Shotcut)
+ **Universal Adversarial Attack on Attention and the Resulting Dataset DAmageNet** <br/> **Sizhe Chen**, Zhengbao He, Chengjin Sun, Jie Yang, Xiaolin Huang <br/> [![](https://img.shields.io/badge/IEEE%20TPAMI-2022-e1dd72)](https://ieeexplore.ieee.org/document/9238430) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2001.06325) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1KkcXy5No_hQ7wiqN5aawTpoBkms2jAy3/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/DAmageNet)
+ **Subspace Adversarial Training** <br/> Tao Li, Yingwen Wu, **Sizhe Chen**, Kun Fang, Xiaolin Huang <br/> [![](https://img.shields.io/badge/CVPR%20Oral-2022-e1dd72)](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Subspace_Adversarial_Training_CVPR_2022_paper) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2111.12229)  [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1AMKDIKvcaOmG1Y-p9aWDsoJzhOrrsFv3/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://drive.google.com/file/d/1NCwOfILYPF6SOudDrHp4t9Q1lu-BfPFf/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1NaF_bZkrPvfsScLfVcjPqcPVQ3CW8hoK/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/nblt/Sub-AT)

Services
------
+ **Reviewer**: CCS 2024/2025/2026, SaTML 2025/2026, NeurIPS 2023/2025, ICML 2024/2025, ICLR 2023/2024/2025/2026, CVPR 2023/2024/2025, ICCV 2023, ECCV 2022/2024, IEEE TPAMI, Machine Learning, Pattern Recognition
+ **UC Berkeley EECS Student Reviewer**: Faculty Hiring Committee 2024, Ph.D. Admission Committee 2024, Equal Access to Application Assistance 2024

Awards
------
+ **Research Fundings**: Meta-BAIR Commons 2024-2026, Google-BAIR Commons 2024-2026, UC Berkeley EECS Departmental Fellowship 2023, NeurIPS 2022 and ICLR 2023 Travel Support
+ **Degree Awards**: SJTU Best Bachelor's Thesis (1%) 2020, SJTU Outstanding Graduate 2022/2023
+ **Scholarship**: China National Scholarship (0.2%) 2021/2022, Kwang-Hua Scholarship 2019, Arawana Scholarship 2017

Misc
------
+ I practice neatness and minimalism.
+ I love to sing, attend concerts, photograph, hike, ski, play badminton and table tennis.
+ I write [blogs](http://xhslink.com/5JP3XI) (in Chinese yet) about my thoughts and experience.
+ My [Erdös number](https://en.wikipedia.org/wiki/Erd%C5%91s_number) is 3 due to my collaboration with [Chuan Guo](https://sites.google.com/view/chuanguo). <br/>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 60%;
  padding: 5px;
}

.column2 {
  float: left;
  width: 40%;
  padding: 5px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body> 

<div class="row">
  <div class="column" style="">
    <img src="https://github.com/Sizhe-Chen/Sizhe-Chen.github.io/blob/master/images/piano.jpg?raw=true"/>
  </div>
  <div class="column2" style="">
    <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=RDdNMEkPYOvHnn4Mr-0kAnakB8Z_o6113sJcvEWqA_4"></script>
  </div>
</div>

</body>
</html>
