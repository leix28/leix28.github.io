---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

### About Me

I'm an Applied Scientist at [Amazon AWS](https://www.amazon.science/author/lei-xu). My research covers a wide range of topics in natural language processing and machine learning. 
Recently, my work has focused on the application of large language models in the medical domain. 
My long-term objective is to pave the way for robust and deployable LLM applications. 
This involves addressing various challenges such as improving data quality, optimizing task-specific model performance, and developing reliable evaluation methods.

I received my Ph.D. in Computer Science from [MIT](http://www.mit.edu) in 2023, and my B.Eng. from [Tsinghua University](http://www.tsinghua.edu.cn). 


### News

- **Dec 2024**: Check out our AAAI 2025 paper *[CriSPO: Multi-Aspect Critique-Suggestion-guided Automatic Prompt Optimization for Text Generation](https://arxiv.org/pdf/2410.02748)* for more effective automatic prompt engineering!
- **Oct 2024**: Our paper *[Salient Information Prompting to Steer Content in Prompt-based Abstractive Summarization](https://arxiv.org/pdf/2410.02741)* is accepted to EMNLP 2024 Industry Track. [\[code\]](https://github.com/amazon-science/SigExt)
- **May 2024**: Our position paper *[ConSiDERS-The-Human Evaluation Framework: Rethinking Human Evaluation for Generative Large Language Models](https://arxiv.org/pdf/2405.18638)* is accepted to ACL 2024 main conference.
- **Jul. 2023**: AWS Announces [HealthScribe](https://aws.amazon.com/healthscribe/) Service.
- **Feb. 2023**: I joined Amazon AWS as an applied scientist.


### Selected Projects

##### Robustness of Text Classifiers

With deployment of large language models, the security and robustness of these models have become a real issue. In this project, we thoroughly explore how well text classifiers can handle attacks from different angles. We developed [R&R](https://arxiv.org/pdf/2104.08453.pdf) and [SP-Attack](https://arxiv.org/pdf/2401.17196.pdf) for traditional transformer-based text classifiers. We also proposed [AToP/BToP](https://arxiv.org/pdf/2204.05239.pdf) attacks for prompt-based language models. And we're putting effort into defending against these attacks with [In Situ Augmentation](/misc/paper/ICONIP_fibber_defense.pdf). 

##### Synthetic Tabular Generation
In this project, we aim to generate synthetic tabular data, which can help remove the barriers in data sharing. We started with an LSTM-based [TGAN](https://arxiv.org/pdf/1811.11264.pdf) model, then further improved it by proposing [CTGAN](https://arxiv.org/pdf/1907.00503.pdf). 