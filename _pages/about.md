---
permalink: /
title: <p align="center">Sizhe Chen（陈思哲）</p>
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
  
Biography
------
Hi! I am a Computer Science Ph.D. student at [UC Berkeley](https://eecs.berkeley.edu), where I am fortunately advised by Prof. [David Wagner](https://people.eecs.berkeley.edu/~daw) in [Berkeley AI Research (BAIR)](https://bair.berkeley.edu). I am working with [Chuan Guo](https://sites.google.com/view/chuanguo) at [Meta FAIR](https://ai.meta.com/research) as a visiting researcher, and with [Nicholas Carlini](https://nicholas.carlini.com) and [Chawin Sitawari](https://chawins.github.io) at [Google DeepMind](https://deepmind.google); the two collaborations are supported by two [BAIR Commons](https://bcommons.berkeley.edu/home) from them. I got my M.Eng. (National Scholarship) and B.Eng. (Summa Cum Laude) from [Shanghai Jiao Tong University](http://en.sjtu.edu.cn) advised by Prof. [Xiaolin Huang](http://www.pami.sjtu.edu.cn/en/xiaolin) (also with Prof. [Cihang Xie](https://cihangxie.github.io) when working on [attacks to vision models](https://drive.google.com/file/d/1nmocMJFOmw_5_N1roe96Vszhhg7zhaZS/view?usp=sharing)).

My research focuses on **AI security** in real-world applications. I am currently working on **prompt injection defense** ([SecAlign](https://arxiv.org/pdf/2410.05451), [StruQ](http://arxiv.org/pdf/2402.06363), [Jatmo](https://arxiv.org/pdf/2312.17673)) for safely using LLMs in systems (e.g., as agents). [Prompt injection attack](https://www.ibm.com/topics/prompt-injection) is listed as the [#1 threat](https://owasp.org/www-project-top-10-for-large-language-model-applications) to LLM-integrated applications, where an LLM input contains a trusted prompt (instruction) and an untrusted data (user documents, web retrieval, results from API calls, etc) with potentially injected instructions (Ignore previous instructions and ...) to arbitrarily manipulate the LLM. <a href='https://scholar.google.com/citations?user=lp5ujPsAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/Sizhe-Chen/Sizhe-Chen.github.io/google-scholar-stats/gs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

I am fortunate to have mentored lots of talented students (and some from underrepresentative groups): [Yizhu Wang](https://cn.linkedin.com/in/yizhu-wang-b738242a3), [Jing Qian](https://jing-qian-98.github.io), [Shutong Wu](https://cychomatica.github.io), [Zhixing Ye](https://ieeexplore.ieee.org/author/37089933329), [Hend Alzahrani](https://sa.linkedin.com/in/hend-alzahrani), and [Zhengbao He](https://openreview.net/profile?id=~Zhengbao_He1). Feel free to drop me an email to connect! I accept approximation on my name's [pronunciation](https://www.chinesenametools.com/meaning/result?first_name=%E6%80%9D%E5%93%B2).

Invited Talks
------
+ **Prompt Injection Defenses** [![](https://img.shields.io/badge/Talk-edca82)](https://docs.google.com/document/d/1pip5y_HGU4qjN0K6NEFuI379RPdL9T6o/edit?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1baUbgFMILhPWBeGrm67XXy_H-jO7raRa/view?usp=sharing) [![](https://img.shields.io/badge/Lecture-bf2c34)](https://drive.google.com/file/d/1g0BVB5HCMjJU4IBGWfdUVope4gr5V_cL/view?usp=sharing) [![](https://img.shields.io/badge/Media-75291c)](https://bair.berkeley.edu/blog/2025/04/07/prompt_injection_defense) <br/> Guest Lecture at [Generative AI: Foundations, Applications, and Safety (Duke)](https://ece590-genai.github.io) 2025 <br/> UC Berkeley Security Seminar 2024 <br/> Hong Kong Baptist University TMLR Young Scientist Seminar 2024 <br/> Shanghai Jiao Tong University PAMI Group Seminar 2024
+ **On the Learning Preference of Deep Neural Networks** [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/11G7gn0-_sAsLTc5vKi6econZlCZdR0Kg/view?usp=sharing) <br/> ICLR Oral Track 2023 <br/> AI Time Youth Ph.D. Talk 2023
+ **Subspace Adversarial Training** [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1NaF_bZkrPvfsScLfVcjPqcPVQ3CW8hoK/view?usp=sharing) <br/> CVPR Oral Track 2022
+ **Adversarial Attacks and Defenses** [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1i6CIrdynqdidqgoTACkSmJEVQm7xRT0S/view?usp=sharing) <br/> Northeastern University Security Seminar 2022

Selected Publications
------
+ **SecAlign: Defending Against Prompt Injection with Preference Optimization** <br/> **Sizhe Chen**, Arman Zharmagambetov, Saeed Mahloujifar, Kamalika Chaudhuri, David Wagner, Chuan Guo <br/> [![](https://img.shields.io/badge/CCS-2025-e1dd72)](http://arxiv.org/abs/2410.05451) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2410.05451) [![](https://img.shields.io/badge/Website-097770)](https://sizhe-chen.github.io/SecAlign-Website) [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1-HFnET2azKniaS4k5dvgVwoRLa4Eg584/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://docs.google.com/document/d/1pip5y_HGU4qjN0K6NEFuI379RPdL9T6o/edit?usp=sharing)  [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1baUbgFMILhPWBeGrm67XXy_H-jO7raRa/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/facebookresearch/SecAlign) <br/> **SecAlign** adopts a new view to treat the **security against prompt injection** as a preference in optimization. Among all possible responses, a secure LLM is expected to prefer and thus output the secure one over the insecure one. For this security property, we build our preference dataset, where the "input" contains a prompt injection; the "desirable output" responds to the benign instruction; and the "undesirable output" responds to the injected instruction. Preference optimization on this dataset reduces various strong optimization-based attack success rates to <10% on state-of-the-art LLMs without non-trivial utility loss.
+ **StruQ: Defending Against Prompt Injection with Structured Queries** <br/> **Sizhe Chen**, Julien Piet, Chawin Sitawarin, David Wagner <br/> [![](https://img.shields.io/badge/USENIX%20Security-2025-e1dd72)](http://arxiv.org/abs/2402.06363) [![](https://img.shields.io/badge/Paper-a8c66c)](http://arxiv.org/pdf/2402.06363)  [![](https://img.shields.io/badge/Website-097770)](https://sizhe-chen.github.io/StruQ-Website) [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1UUz4t43sGqFOPZqNxf8izR--iLAl16QX/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://simons.berkeley.edu/talks/david-wagner-uc-berkeley-2024-10-14) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1baUbgFMILhPWBeGrm67XXy_H-jO7raRa/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/StruQ) <br/> **StruQ** is a general approach for **prompt injection defense** by separating the prompt and data into two channels. This system is made of a secure front-end that formats a prompt and data into a special format, and a specially trained LLM that can produce high-quality outputs from these inputs. We augment the SFT dataset with examples that additionally include instructions in data besides in prompt, and do SFT on the model to ignore instructions in data. Preserving utility, StruQ stops all existing (optimization-free) prompt injections to an attack success rate of <2%.
+ **One-Pixel Shortcut: On the Learning Preference of Deep Neural Networks** <br/> Shutong Wu\*, **Sizhe Chen\***, Cihang Xie, Xiaolin Huang <br/> [![](https://img.shields.io/badge/ICLR%20Spotlight-2023-e1dd72)](https://openreview.net/forum?id=p7G8t5FVn2h) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2205.12141)  [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1p5SSuoGPcQCMul9N7pmp_1ON_xupKeoD/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://iclr.cc/virtual/2023/oral/12603) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1maneRbPHAbKd8-toYXnAcpqabNhciOEK/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/cychomatica/One-Pixel-Shotcut) <br/> **OPS** perturbs only one pixel in each image to **poison model training** from the view of shortcut learning. OPS uses a heuristic model-agnostic search to find the pixel: perturbing in-class images at the same position to the same target value that could mostly and stably alter the original images. OPS degrades the model accuracy on clean data to almost an untrained counterpart. The perturbations, for the first time, are crafted within seconds (CIFAR-10) or minutes (ImageNet) and cannot be erased by adversarial training.
+ **Adversarial Attack on Attackers: Post-Process to Mitigate Black-Box Score-Based Attacks** <br/> **Sizhe Chen**, Zhehao Huang, Qinghua Tao, Yingwen Wu, Cihang Xie, Xiaolin Huang <br/> [![](https://img.shields.io/badge/NeurIPS-2022-e1dd72)](https://openreview.net/forum?id=7hhH95QKKDX) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2205.12134)  [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1DaVrjP0uTaolardNIYQDNO9z9NsH7ziM/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://drive.google.com/file/d/1e7tsEvbT10R750eldANDAlLRxqwT2pgg/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1oexH2EjV0k9tBNOHkesHD9lIJlQKoE1o/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/AAA) <br/> **AAA** proposes a new direction to especially **defend against score-based query attacks** by maintaining predictions while disrupting gradients. We note that the efficient and realistic score-based attacks could be easily misled if the model logits are perturbed to create a periodically reverse loss trend. AAA secures WideResNet-28 with 80.59% accuracy under attack, compared to 67.44% from the best prior adversarial training defense. AAA does not hurt the accuracy, calibration, or inference speed, and can be directly plugged into any trained classifiers.
+ **Universal Adversarial Attack on Attention and the Resulting Dataset DAmageNet** <br/> **Sizhe Chen**, Zhengbao He, Chengjin Sun, Jie Yang, Xiaolin Huang <br/> [![](https://img.shields.io/badge/IEEE%20TPAMI-2022-e1dd72)](https://ieeexplore.ieee.org/document/9238430) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2001.06325) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1KkcXy5No_hQ7wiqN5aawTpoBkms2jAy3/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/DAmageNet) <br/> **AoA** follows the proposed principle that **transfer attacks** should seek for features that are shared across different architectures, which tend to reveal their common vulnerabilities. We note that the attention heatmap (from the model interpretation tool) could be a shared feature, and constrain the attention as our attack loss, which improves the attack transferability by 30%. We apply AoA to generate 50K adversarial samples from the ImageNet validation set to get the **DAmageNet**, leading to >85% error rate on 13 undefended models and >70% error rate on most defended models.
+ **Subspace Adversarial Training** <br/> Tao Li, Yingwen Wu, **Sizhe Chen**, Kun Fang, Xiaolin Huang <br/> [![](https://img.shields.io/badge/CVPR%20Oral-2022-e1dd72)](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Subspace_Adversarial_Training_CVPR_2022_paper) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2111.12229)  [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/1AMKDIKvcaOmG1Y-p9aWDsoJzhOrrsFv3/view?usp=sharing) [![](https://img.shields.io/badge/Talk-edca82)](https://drive.google.com/file/d/1NCwOfILYPF6SOudDrHp4t9Q1lu-BfPFf/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1NaF_bZkrPvfsScLfVcjPqcPVQ3CW8hoK/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/nblt/Sub-AT) <br/> **Sub-AT** approaches catastrophic overfitting and robust overfitting in **adversarial training** (AT) by constraining AT in a carefully extracted subspace. Sub-AT saves checkpoints during the regular training and performs SVD on the parameter matrix (each vector is a squeezed checkpoint) to get mutually orthogonal bases of the subspace. Then Sub-AT projects gradients to those bases in the remaining training, i.e., only alters very few independent parameters like the following LoRA. 1-step Sub-AT achieves a competitive performance v.s. standard 10-step AT, with even 40% less computation than standard 1-step AT.

Other Publications
------
+ **Jatmo: Prompt Injection Defense by Task-Specific Finetuning** <br/> Julien Piet, Maha Alrashed, Chawin Sitawarin, **Sizhe Chen**, Zeming Wei, Elizabeth Sun, Basel Alomair, David Wagner <br/> [![](https://img.shields.io/badge/ESORICS-2024-e1dd72)](https://dl.acm.org/doi/abs/10.1007/978-3-031-70879-4_6) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2312.17673) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1dz23r986NxCFWXYuIMBQvHZ4Eg4liq_o/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/wagner-group/prompt-injection-defense)
+ **Can LLMs Follow Simple Rules?** <br/> Norman Mu, Sarah Chen, Zifan Wang, **Sizhe Chen**, David Karamardian, Lulwa Aljeraisy, Basel Alomair, Dan Hendrycks, David Wagner <br/> [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2311.04235) [![](https://img.shields.io/badge/Website-097770)](https://eecs.berkeley.edu/~normanmu/llm_rules) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/normster/llm_rules)
+ **Self-Ensemble Protection: Training Checkpoints Are Good Data Protectors** <br/> **Sizhe Chen**, Geng Yuan, Xinwen Cheng, Yifan Gong, Minghai Qin, Yanzhi Wang, Xiaolin Huang <br/> [![](https://img.shields.io/badge/ICLR-2023-e1dd72)](https://openreview.net/forum?id=9MO7bjoAfIA) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2211.12005)  [![](https://img.shields.io/badge/Poster-1b6535)](https://drive.google.com/file/d/171xgU_zcwvP0X9hlq1W-CJG4giCCxJIu/view?usp=sharing) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1dIwpAVxqozog63t5J1ql2BUxBYaxSMky/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/SEP)
+ **Query Attack by Multi-Identity Surrogates** <br/> **Sizhe Chen**, Zhehao Huang, Qinghua Tao, Xiaolin Huang <br/> [![](https://img.shields.io/badge/IEEE%20TAI-2023-e1dd72)](https://ieeexplore.ieee.org/document/10070787) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2105.15010) [![](https://img.shields.io/badge/Slides-f47a60)](https://drive.google.com/file/d/1ExOSIkz45BwYQKN1nfxtpxuBeg9gNut0/view?usp=sharing) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/QueryNet)
+ **Measuring the Transferability of $\ell_\infty$ Attacks by the $\ell_2$ Norm** <br/> **Sizhe Chen**, Qinghua Tao, Zhixing Ye, Xiaolin Huang <br/> [![](https://img.shields.io/badge/ICASSP-2023-e1dd72)](https://ieeexplore.ieee.org/document/10096892) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2102.10343) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/FairAttack)
+ **Unifying Gradients to Improve Real-World Robustness for Deep Networks** <br/> Yingwen Wu, **Sizhe Chen**, Kun Fang, Xiaolin Huang <br/> [![](https://img.shields.io/badge/ACM%20TIST-2023-e1dd72)](https://dl.acm.org/doi/abs/10.1145/3617895) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2208.06228) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/snowien/UniG-pytorch)
+ **Relevance Attack on Detectors** <br/> **Sizhe Chen**, Fan He, Xiaolin Huang, Kun Zhang <br/> [![](https://img.shields.io/badge/Pattern%20Recognition-2022-e1dd72)](https://www.sciencedirect.com/science/article/abs/pii/S0031320321006671) [![](https://img.shields.io/badge/Paper-a8c66c)](https://arxiv.org/pdf/2008.06822) [![](https://img.shields.io/badge/Code-4d5198)](https://github.com/Sizhe-Chen/RAD)

Services
------
+ **Reviewer**: SaTML 2025, CCS 2024, ICML 2024/2025, NeurIPS 2023/2025, ICLR 2023/2024/2025, CVPR 2023/2024/2025, ICCV 2023, ECCV 2022/2024, IEEE TPAMI, Machine Learning, Pattern Recognition
+ **UC Berkeley EECS Student Reviewer**: Faculty Hiring Committee 2024, Ph.D. Admission Committee 2024, Equal Access to Application Assistance 2024

Awards
------
+ **Research Fundings**: Meta-BAIR Commons 2024, Google-BAIR Commons 2024, UC Berkeley EECS Departmental Fellowship 2023, NeurIPS 2022 / ICLR 2023 Travel Support
+ **Degree Awards**: SJTU Extraordinary Bachelor's Thesis (1%, Summa Cum Laude equivalent) 2020, SJTU Outstanding Graduate 2022/2023
+ **Scholarship**: China National Scholarship (0.2%) 2021/2022, Kwang-Hua Scholarship 2019, Arawana Scholarship 2017

Misc
------
+ I practice neatness and minimalism.
+ I play table tennis, play badminton, and ski.
+ I love to sing, attend classic or pop concerts, and travel to large cities.
+ I write [blogs (CN)](http://xhslink.com/5JP3XI) about my thoughts and experience. <br/>

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
