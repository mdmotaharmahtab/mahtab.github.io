---
# Display name
title: Md. Motahar Mahtab

# Name pronunciation (optional)
name_pronunciation: Md. Motahar Mahtab

# Full name (for SEO)
first_name: Md. Motahar
last_name: Mahtab

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: AI Engineer at Delineate Inc.

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Delineate
    url: https://delineate.pro/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'md.motahar.mahtab@g.bracu.ac.bd'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev
  - icon: brands/github
    url: https://github.com/mdmotaharmahtab
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/motahar-mahtab/
  - icon: brands/google-scholar
    url: https://scholar.google.com/citations?user=3u4-1EEAAAAJ&hl=en
  # - icon: brands/instagram
  #   url: https://www.instagram.com/

education:
  - area: B.Sc in Computer Science & Engineering
    institution: BRAC University
    date_start: 2018-05-01
    date_end: 2022-05-01
    summary: |
      CGPA: 3.99

      Thesis on _BanglaBait: BanglaBait: Semi-Supervised Adversarial Approach for Clickbait Detection on Bangla Clickbait Dataset_. Supervised by [Dr. Farig Sadeque, Assistant Professor, BRAC University](https://www.cse.sds.bracu.ac.bd/faculty_profile/194/dr_farig_yousuf_sadeque). Presented papers (remotely) at 2 ACL Sponsored conferences where proceedings were published at Springer Journal and ACL Anthology.
    button:
      text: 'Read Thesis'
      url: 'https://aclanthology.org/2023.ranlp-1.81.pdf'

work:
  - position: AI Engineer
    company_name: Delineate
    company_url: 'https://delineate.pro/'
    company_logo: ''
    date_start: 2024-10-01
    date_end: ''
    summary: |2-
      Responsibilities include:
      - Incorporate searching via keywords, embedding for RAG retrieval
      - Building Multi Agentic LLM systems to query, geenrate QSP parameters
      - Employ OCR models for extraction of data from charts, figures, etc.
      - Tech Stack: LangGraph, ElasticSearch, LangChain, FastAPI.
  - position: Jr. AI Engineer
    company_name: Giga Tech Limited
    company_url: 'https://gigatechltd.com/'
    company_logo: ''
    date_start: 2022-07-01
    date_end: 2024-10-01
    summary: |
      Responsibilities include:
      - Created new state-of-the-art systems for a plethora of Bangla NLP tasks e.g. Named Entity Recognition (NER), Parts of Speech (POS), [Lemmatization](https://github.com/eblict-gigatech/BanLemma), and [Emotion recognition](https://sentiment.bangla.gov.bd).
      - The Bangla NER system included a context retrieval for entities and used a modified entity-weighted majority voting system for more correct NER classificaiton outperforming previous Bangla NER systems.
      - Used effective prompt engineering and output formatting techniques to use LLMs for faster automatic annotation for classification tasks.
      - Optimized deployment of LLMs using Optimum (for ONNX conversion) and Nvidia TensorRT(TRT) format for further optimization. Used PyTorch Profiler to identify inference bottlenecks. Used Nvidia Triton Inference Server (TIS) as the default ML inference server for concurrent request serving and scheduling, batch inference and response caching.
      - Created REST APIs using FastAPI for hosting ML inference endpoints. Used MongoDB for response caching in NVIDIA Triton.
      - Used Qdrant vector DB for fast semantic searching, Dask to analyze and query big dataframes, DVC for dataset versioning and MLflow for model, artifact and experiment versioning.
      - Created pipeline for Natural Language generation (NLG) in Bangla for both encoder models like BERT and auto-regressive models like GPT2. Analyzed and overcame common issues like repetitive text generation, and unmeaningful word generation in NLG for Bangla.
  - position: Teacher Assistant
    company_name: BRAC University
    company_url: 'https://www.bracu.ac.bd/'
    company_logo: ''
    date_start: 2020-01-01
    date_end: 2022-05-01
    summary: |2-
      Responsibilities include:
      - Helped students with different coding assignments and helped teachers in checking scripts.
      - Assisted students in conducting research in various fields and submitting papers to conferences.
      - Assisted Teachers in lab classes and helped students with different course materials during consultation hour.

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
Research Papers:
  - title: BanglaBait Semi-Supervised Adversarial Approach for Clickbait Detection on Bangla Clickbait Dataset
    url: https://aclanthology.org/2023.ranlp-1.81/
    date: '2023-09-04'
    awarder: 
    icon: Recent Advances in Natural Language Processing
    summary: |
      - First Bangla Clickbait News Article Dataset containing 15,056 data instances, each containing article title, content, clickbait/non-clickbait label, article source, article category, article publish-time, translated English title and content.
      - Investigated various semi-supervised learning methods and compared them with supervised learning methods to prove the former's superiority.
      - Code: https://github.com/mdmotaharmahtab/BanglaBait
  - title: BanLemma A Word Formation Dependent Rule and Dictionary Based Bangla Lemmatizer
    url: https://aclanthology.org/2023.findings-emnlp.240/
    date: '2023-12-01'
    awarder: The 2023 Conference on Empirical Methods in Natural Language Processing
    icon: 
    summary: |
      - State-of-the-art Bangla Rule Based Lemmatizer which proposes a novel iterative suffix stripping approach based on the part-of-speech tag of a word.
      - To create lemmatization rules, an extensive Bangla text corpus of 90.65M unique sentences are analyzed.
      - Shows superior performance than all previously published Bangla lemmatization methods on existing datasets.
      - Code: https://github.com/eblict-gigatech/BanLemma
  - title: GAN-BERT Approach for Bengali Text Classification with Few Labeled Examples
    url: https://link.springer.com/chapter/10.1007/978-3-031-20859-1_3
    date: '2023-01-21'
    awarder: International Conference on Distributed Computing and Artificial Intelligence (DCAI) 22
    icon: 
    summary: |
      - Trained state-of-the-art Transformer networks in adversarial fashion using Generative Adversarial Network (GAN) to achieve superior performance when labelled dataset size is too small. 
      - First Bangla Paper to investigate the application of GAN-BERT on Bangla text classification tasks
      
# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: PyTorch
        description: ''
        percent: 90
        icon: devicon/pytorch
      - name: Python
        description: ''
        percent: 85
        icon: devicon/python
      - name: Git
        description: ''
        percent: 80
        icon: devicon/git
      - name: Pandas
        description: ''
        percent: 87
        icon: devicon/pandas
      - name: Matplotlib
        description: ''
        percent: 75
        icon: devicon/matplotlib
      - name: FastAPI
        description: ''
        percent: 80
        icon: devicon/fastapi
      - name: MySQL
        description: ''
        percent: 70
        icon: devicon/mysql
      - name: PostgreSQL
        description: ''
        percent: 75
        icon: devicon/postgresql
      - name: Bash
        description: ''
        percent: 70
        icon: devicon/bash

Projects:
  - title: Bangla Clickbait Detector App
    url: https://github.com/mdmotaharmahtab/Bangla-Clickbait-Detector-App
    date: '2023'
    awarder: 
    icon: Recent Advances in Natural Language Processing
    summary: |
      - First Bangla Clickbait News Article Dataset containing 15,056 data instances, each containing article title, content, clickbait/non-clickbait label, article source, article category, article publish-time, translated English title and content.
      - Investigated various semi-supervised learning methods and compared them with supervised learning methods to prove the former's superiority.
      - Code: https://github.com/mdmotaharmahtab/BanglaBait
  - title: BanLemma A Word Formation Dependent Rule and Dictionary Based Bangla Lemmatizer
    url: https://aclanthology.org/2023.findings-emnlp.240/
    date: '2023-12-01'
    awarder: The 2023 Conference on Empirical Methods in Natural Language Processing
    icon: 
    summary: |
      - State-of-the-art Bangla Rule Based Lemmatizer which proposes a novel iterative suffix stripping approach based on the part-of-speech tag of a word.
      - To create lemmatization rules, an extensive Bangla text corpus of 90.65M unique sentences are analyzed.
      - Shows superior performance than all previously published Bangla lemmatization methods on existing datasets.
      - Code: https://github.com/eblict-gigatech/BanLemma
  - title: GAN-BERT Approach for Bengali Text Classification with Few Labeled Examples
    url: https://link.springer.com/chapter/10.1007/978-3-031-20859-1_3
    date: '2023-01-21'
    awarder: International Conference on Distributed Computing and Artificial Intelligence (DCAI) 22
    icon: 
    summary: |
      - Trained state-of-the-art Transformer networks in adversarial fashion using Generative Adversarial Network (GAN) to achieve superior performance when labelled dataset size is too small. 
      - First Bangla Paper to investigate the application of GAN-BERT on Bangla text classification tasks

  # - name: Hobbies
  #   color: '#eeac02'
  #   color_border: '#f0bf23'
  #   items:
  #     - name: Hiking
  #       description: ''
  #       percent: 60
  #       icon: person-simple-walk
  #     - name: Cats
  #       description: ''
  #       percent: 100
  #       icon: cat
  #     - name: Photography
  #       description: ''
  #       percent: 80
  #       icon: camera

# languages:
#   - name: English
#     percent: 100
#   - name: Chinese
#     percent: 75
#   - name: Portuguese
#     percent: 25


---

I am Md. Motahar Mahtab, a skilled Machine Learning Engineer with a strong foundation in Computer Science. I hold a B.Sc in CSE from BRAC University, where I graduated with a CGPA of 3.99. With over two years of experience, I specialize in developing and deploying Large Language Models (LLMs), downstream solutions, and optimizing LLMs for various applications.

I work with advanced ML frameworks and tools, including PyTorch, Huggingface, Weights and Biases, LangChain, LangGraph, and Triton. During my time at Giga Tech Limited, I played a crucial role in implementing LLM training and deployment, downstream solutons using LLMs, LLM optimization and deployment and Agentic Retrieval-Augmented Generation (RAG).

Currently, I am contributing to Delineate, a US-based startup that focuses on revolutionizing Quantitative Systems Pharmacology (QSP) through LLMs. I am actively seeking a PhD position in the USA to further specialize in the fields of Machine Learning and Natural Language Processing (NLP).
