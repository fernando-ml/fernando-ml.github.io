---
title: "Admissions in the Age of AI: Detecting AI-Generated Application Materials in Higher Education"
collection: publications
permalink: /publication/2024-03-18-AdmisionsAI
excerpt: '<u>Submited</u>'
date: 2024-03-18
venue: 'SIAM Conference on Data Mining'
citation: 'Yijun Zhao, <b>Fernando Martinez</b>, Haoran Xue, Gary M. Weiss ”Admissions in the Age of AI: Detecting AI-Generated Application Materials in Higher Education,” SDM24.'
---
Recent advancements in Artificial Intelligence (AI), such as ChatGPT, have blurred the boundaries between human and AI-generated content. This has led to a pressing need to detect AI-generated text. While achieving a universally effective detection model remains challenging, this paper demonstrates that domain and task specific detection models can attain high accuracy. This study focuses on the higher education domain, specifically graduate admissions materials, where the challenge lies in identifying AI-generated Statements of Intent (SOIs) and Letters of Recommendation (LORs). Detecting such application materials is essential to ensure that applicants are evaluated on their true merits and abilities, and to foster an equitable and trustworthy admissions process. Our research is based on 3,841 LORs and 1,552 SOIs extracted from the application records of Fordham University's Master's programs in Computer Science and Data Science. To facilitate the construction of classification models, we generated an AI counterpart for each LOR and SOI using the GPT-3.5 Turbo API with prompts derived from the applicant's admission data. We further leverage an open-access GPT-wiki-intro dataset to validate our approach. Our experiments yield promising results in accurately detecting AI-generated SOIs and LORs. Additionally, we present a comparative analysis of the word frequency and statistical characteristics of the text, which provides convincing evidence of ChatGPT's distinctive vocabulary and paragraph structure compared to human-generated text. The code for this study is available on GitHub, and the models can be executed on user-provided data via an interactive web interface.

[Code](https://github.com/ferdmartin/appdocs){: .btn}