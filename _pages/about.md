---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
/* Consolidated styling for better cohesion */
.section-details {
  margin-left: 1em;
  margin-bottom: 1em;
}

.section-details > summary {
  cursor: pointer;
  padding: 8px 12px;
  border: 2px solid #007BFF;
  border-radius: 6px;
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  font-weight: bold;
  transition: all 0.3s ease;
  display: list-item;
  list-style: none;
  position: relative;
}

.section-details > summary:hover {
  background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
  border-color: #0056b3;
  transform: translateY(-1px);
  box-shadow: 0 4px 8px rgba(0, 123, 255, 0.2);
}

.section-details > summary:before {
  /* content: "▶"; */
  position: absolute;
  left: 12px;
  transition: transform 0.3s ease;
  color: #007BFF;
  font-weight: bold;
}

.section-details[open] > summary:before {
  transform: rotate(90deg);
}

.section-details > div {
  margin-left: 1em;
  margin-top: 1em;
  padding: 1em;
  border-left: 3px solid #dee2e6;
  background-color: #f8f9fa;
}

.subsection-details {
  margin-left: 1em;
  margin-bottom: 0.5em;
}

.subsection-details > summary {
  cursor: pointer;
  padding: 6px 10px;
  border: 1px solid #6c757d;
  border-radius: 4px;
  background-color: #ffffff;
  transition: all 0.2s ease;
  font-weight: 500;
}

.subsection-details > summary:hover {
  background-color: #f1f3f4;
  border-color: #495057;
  transform: translateX(2px);
}

.subsection-details > div {
  margin-left: 1em;
  margin-top: 0.5em;
  padding: 0.75em;
  background-color: #ffffff;
  border-left: 2px solid #e9ecef;
}

.paper-button {
  display: inline-block;
  padding: 6px 12px;
  background-color: #007BFF;
  color: white;
  border-radius: 4px;
  font-size: 14px;
  text-align: center;
  cursor: pointer;
  text-decoration: none !important;
  margin-right: 8px;
  margin-bottom: 4px;
  transition: background-color 0.2s ease;
}

.paper-button:hover {
  background-color: #0056b3;
  color: white;
  text-decoration: none !important;
}
</style>

Hey, this is Sadra! I'm currently studying PhD in Computer Science at USC, working at the intersection of Human-Computer Interaction (HCI) and Natural Language Processing (NLP), i.e., making LLMs better friends of humans.
My current research focuses on helping people make better decisions using LLMs.
On the side (and honestly, all the time), I build and maintain scientific software tools with a great team of open-source enthusiasts.
I'm always looking for ways to make technology and science more accessible, and fun—believing that open-source software is an ideal contribution to scientific communities that value transparency and reproducibility.
I enjoy watching movies and hunting for new places whenever I travel in my free time.
I'm always curious to meet new people and hear about their journeys, so shoot me an email or DM me on any social media!
<details class="section-details">
<summary><b>CS PhD @ USC ✌️</b></summary><div>
The main problem I'm trying to solve is the integration of AI systems into human workflows—specifically, answering the question: "What is the core part of a task that AI cannot do, and how can AI assist humans in doing that?"
Helping humans tackle the hardest parts of their jobs—with AI as a consultant—is the overarching meta-goal of my current research.
To address this, I've explored several domains where large language models (LLMs) have been introduced but face full-integration challenges. These include software developers trusting code agents for programming, strategic decision-making in the board game Diplomacy, patients navigating conflicting medical advice, users with different knowledge backgrounds asking factual questions and researchers looking for scientific discussions in social media.
<br><br>
I'm currently in my second year and looking forward to exploring more domains to develop a taxonomy of these challenges and a framework that identifies the right interaction patterns and integration points for AI.
Throughout this journey, I've had the great opportunity to work with the Adaptive Computing Experience (ACE) Lab (Souti Chattopadhyay's lab @ GCS) and [CUTE LAB NAME] (Jonathan May's lab @ ISI).
<br><br>
You can find some of my publications below:
  <!-- Philipp's paper -->
  <details class="subsection-details">
    <summary>[ICSE25] <b>Trust dynamics in AI-assisted development: Definitions, factors, and implications,</b> <b><u>Sadra Sabouri</u></b>, Philipp Eibl, Xinyi Zhou, Morteza Ziyadi, Nenad Medvidovic, Lars Lindemann, Souti Chattopadhyay</summary><div>
    <a href="https://www.amazon.science/publications/trust-dynamics-in-ai-assisted-development-definitions-factors-and-implications" class="paper-button">Paper</a><br>
    We investigate how developers define, evaluate, and evolve trust in AI-generated code suggestions through a mixed-method study involving surveys and observations. We found that while comprehensibility and perceived correctness are key to trust decisions, developers often revise their choices, accepting only 52% of AI suggestions, highlighting the need for better real-time support and offering four validated guidelines to improve developer-AI collaboration.
  </div></details>
  <details class="subsection-details">
    <summary>[ACL25] <b>ELI-Why: Evaluating the Pedagogical Utility of Language Model Explanations,</b> Brihi Joshi, Keyu He, Sahana Ramnath, <b><u>Sadra Sabouri</u></b>, Kaitlyn Zhou, Souti Chattopadhyay, Swabha Swayamdipta, Xiang Ren</summary><div>
    <a href="https://arxiv.org/pdf/2506.14200" class="paper-button">Paper</a>
    <a href="https://github.com/INK-USC/ELI-Why" class="paper-button">Code</a>
    <a href="https://huggingface.co/collections/INK-USC/eli-why-6849086c86556f7a2dd7c686"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Data-blue"></a><br>
    We investigate how well language models adapt explanations to learners with varying educational backgrounds using ELI-Why, a benchmark of 13.4K "Why" questions. Through two human studies, we found that GPT-4 explanations align with intended grade levels only 50% of the time and are rated 20% less suitable for learners' needs compared to layperson-curated responses, revealing limitations in their pedagogical adaptability.
  </div></details>
<br>
Always happy to chat, collaborate, or just hear what you're working on; feel free to reach out!
</div></details>
<hr>
<details class="section-details">
<summary><b>Open World Developer 🌐</b></summary><div>
Open-sourcing research in NLP has lead to breakthroughs like ChatGPT, but generative AI also makes it easier to produce convincing yet flawed content in research communities.
This poses a sense of Frankenstein-Trojan threat to scientific integrity.
Committed to open science and reproducibility, I focus on building scientific software that ensures transparency.
With a group of my friends, I co-founded <a href="https://github.com/openscilab/">OpenSciLab</a> to develop open-source tools toward this goal.
<br><br>
Below is a topic-based summary of my work, including those through OpenSciLab, dataset releases and independent projects:
  <details class="subsection-details">
    <summary>Natural Language Processing and Large Language Models</summary><div>
    <!-- exprand -->
    <!-- tocount -->
    <!-- xnum -->
      <details class="subsection-details">
      <summary>Memor: Managing and Transferring Conversational Memory Across LLMs</summary><div>
      <a href="https://github.com/openscilab/memor/"><img src="https://img.shields.io/github/stars/openscilab/memor.svg?style=social&logo=github&label=Stars"></a>
      <a href="https://github.com/openscilab/memor/"><img src="https://img.shields.io/github/forks/openscilab/memor.svg?style=social&logo=github&label=Forks"></a>
      <a href="http://pepy.tech/project/memor"><img src="http://pepy.tech/badge/memor"></a><br>
      Memor is designed to help users manage the memory of their interactions with Large Language Models (LLMs). It enables users to access and utilize the history of their conversations when prompting LLMs. That would create a more personalized and context-aware experience. Users can select specific parts of past interactions with one LLM and share them with another. By bridging the gap between isolated LLM instances, Memor revolutionizes the way users interact with AI by making transitions between models smoother.
      </div></details>
      <details class="subsection-details">
      <summary>[JAIAI] <b>naab: A ready-to-use plug-and-play corpus for Farsi,</b> <b><u>Sadra Sabouri</u></b>, Elnaz Rahmati, Soroush Gooran, Hossein Sameti</summary><div>
      <a href="https://arxiv.org/pdf/2208.13486" class="paper-button">Paper</a>
      <a href="https://huggingface.co/datasets/SLPL/naab"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Data-blue"></a><br>
      The issue of large training data is (was at that time :D) emerging more in lower resource languages - like Farsi. We propose naab a hue cleaned and ready-to-use open-source textual corpus in Farsi. It contains about 130GB of data, 250 million paragraphs, and 15 billion words. The project name is derived from the Farsi word NAAB which means pure and high grade.
      </div></details>
      <details class="subsection-details">
      <summary>[ALP@NAACL25] <b>Parsipy: NLP toolkit for historical persian texts in Python,</b> Farhan Farsi, Parnian Fazel, Sepand Haghighi, <b><u>Sadra Sabouri</u></b>, Farzaneh Goshtasb, Nadia Hajipour, Ehsaneddin Asgari, Hossein Sameti</summary><div>
      <a href="https://aclanthology.org/2025.alp-1.17.pdf" class="paper-button">Paper</a><br>
      The study of historical languages presents unique challenges due to their complex orthographic systems, fragmentary textual evidence, and the absence of standardized digital representations of text in those languages. This work introduces an NLP toolkit designed to facilitate the analysis of historical Persian languages by offering modules for tokenization, lemmatization, part-of-speech tagging, phoneme-to-transliteration conversion, and word embedding.
      </div></details>
      <details class="subsection-details">
      <summary>[LoResMT@NAACL25] <b>PahGen: Generating Ancient Pahlavi Text via Grammar-guided Zero-shot Translation,</b> Farhan Farsi, Parnian Fazel, Farzaneh Goshtasb, Nadia Hajipour, <b><u>Sadra Sabouri</u></b>, Ehsaneddin Asgari, Hossein Sameti</summary><div>
      <a href="https://aclanthology.org/2025.loresmt-1.16.pdf" class="paper-button">Paper</a><br>
      Due to Pahlavi (middle Persian)'s limited digital presence and the scarcity of comprehensive linguistic resources, Pahlavi is at risk of extinction. This study introduces a framework to translate English text into Pahlavi. Our approach combines grammar-guided term extraction with zero-shot translation, leveraging large language models (LLMs) to generate syntactically and semantically accurate Pahlavi sentences. Finally using our framework, we generate a novel dataset of 360 expert-validated parallel English-Pahlavi texts.
      </div></details>
      <details class="subsection-details">
      <summary>[DialDoc@ACL22] <b>Docalog: Multi-document Dialogue System using Transformer-based Span Retrieval,</b> Sayed Hesam Alavian, Ali Satvaty, <b><u>Sadra Sabouri</u></b>, Ehsaneddin Asgari, Hossein Sameti</summary><div>
      <a href="https://aclanthology.org/2022.dialdoc-1.16.pdf" class="paper-button">Paper</a><br>
      This paper discusses our proposed approach, Docalog, for the DialDoc-22 (MultiDoc2Dial) shared task which was part of my BSc. thesis. Docalog, has a three-stage pipeline consisting of (1) a document retriever model, (2) an answer span prediction model, and (3) an ultimate span picker deciding on the most likely answer span, out of all predicted spans.
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Speech Processing</summary><div>
      <details class="subsection-details">
        <summary>Nava: OS-Native Sound Engine in Python</summary><div>
        <a href="https://github.com/openscilab/nava/"><img src="https://img.shields.io/github/stars/openscilab/nava.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/openscilab/nava/"><img src="https://img.shields.io/github/forks/openscilab/nava.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/nava"><img src="http://pepy.tech/badge/nava"></a><br>
        Nava allows users to play sound in Python without any dependencies or platform restrictions. It is a cross-platform solution that runs on any operating system, including Windows, macOS, and Linux. Its lightweight and easy-to-use design makes Nava an ideal choice for developers looking to add sound functionality to their Python programs.
      </div></details>
      <details class="subsection-details">
        <summary>Sharif-Wav2Vec2.0: Wave2Vec2.0 Speech Processing Model Tailored for Farsi</summary><div>
        <a href="https://huggingface.co/SLPL/Sharif-wav2vec2"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue"></a><br>
        The base model fine-tuned on 108 hours of Commonvoice's Farsi audio. Token set and the language models of that model changed to support special nuances of Farsi which wasn't there in English.
        More technically, we trained a 5gram using kenlm toolkit and used it in the processor which increased our accuracy on online ASR.
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Machine Learning (ML)</summary><div>
      <details class="subsection-details">
        <summary>PyCM: Multi-class confusion matrix library in Python</summary><div>
        <a href="https://github.com/sepandhaghighi/pycm/"><img src="https://img.shields.io/github/stars/sepandhaghighi/pycm.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/sepandhaghighi/pycm/"><img src="https://img.shields.io/github/forks/sepandhaghighi/pycm.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/pycm"><img src="http://pepy.tech/badge/pycm"></a><br>
        PyCM is a tool for post-classification model evaluation that supports most class and overall statistic parameters. PyCM targeted mainly the data scientists that need a broad array of metrics for predictive models and accurate evaluation of a large variety of classifiers.
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Network</summary><div>
      <details class="subsection-details">
        <summary>PyRGG: Python Random Graph Generator</summary><div>
        <a href="https://github.com/sepandhaghighi/pyrgg/"><img src="https://img.shields.io/github/stars/sepandhaghighi/pyrgg.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/sepandhaghighi/pyrgg/"><img src="https://img.shields.io/github/forks/sepandhaghighi/pyrgg.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/pyrgg"><img src="http://pepy.tech/badge/pyrgg"></a><br>
        PyRGG synthesizes random graph which can be useful in networks simulation. It supports multiple graph file formats, such as DIMACS-Graph files. It can generate graphs of various sizes and using different generation methods such as Erdős–Rényi-Gilbert, Erdős–Rényi, Stochastic Block Model.
      </div></details>
      <details class="subsection-details">
        <summary>IPSpot: A Python Tool to Fetch the System's IP Address</summary><div>
        <a href="https://github.com/openscilab/ipspot"><img src="https://img.shields.io/github/stars/openscilab/ipspot.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/openscilab/ipspot"><img src="https://img.shields.io/github/forks/openscilab/ipspot.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/ipspot"><img src="http://pepy.tech/badge/ipspot"></a><br>
        IPSpot retrieves the system's IP address and location information. It supports public and private IPv4 and IPv6 detection using multiple API providers with a fallback mechanism for reliability.
      </div></details>
      <details class="subsection-details">
        <summary><b>Pymilo: A python library for ml I/O,</b> AmirHosein Rostami, Sepand Haghighi, <b><u>Sadra Sabouri</u></b>, Alireza Zolanvari</summary><div>
        <a href="https://arxiv.org/pdf/2501.00528" class="paper-button">Paper</a>
        <a href="https://github.com/openscilab/pymilo"><img src="https://img.shields.io/github/stars/openscilab/pymilo.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/openscilab/pymilo"><img src="https://img.shields.io/github/forks/openscilab/pymilo.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/pymilo"><img src="http://pepy.tech/badge/pymilo"></a><br>
        PyMilo addresses the limitations of existing Machine Learning (ML) model storage formats by providing a transparent, reliable, and safe method for exporting and deploying trained models. Current formats, such as pickle and other binary formats, have significant problems, such as reliability, safety, and transparency issues. In contrast, PyMilo serializes ML models in a transparent non-executable format, enabling straightforward and safe model exchange.
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Art</summary><div>
      <details class="subsection-details">
        <summary><b>Samila: A Generative Art Generator,</b> <b><u>Sadra Sabouri</u></b>, Sepand Haghighi, Elena Masrour</summary><div>
        <a href="https://arxiv.org/pdf/2504.04298" class="paper-button">Paper</a>
        <a href="https://github.com/sepandhaghighi/samila"><img src="https://img.shields.io/github/stars/sepandhaghighi/samila.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/sepandhaghighi/samila"><img src="https://img.shields.io/github/forks/sepandhaghighi/samila.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/samila"><img src="http://pepy.tech/badge/samila"></a><br>
        Samila lets you create images by randomly permuting many thousand points. The position of every single point is calculated by a formula, which has random parameters. Because of the randomness of the generation process you nearly can't reproduce any image unless you have the right seed for it. I highly encourage you to take a look at the paper if you're interested.
      </div></details>
      <details class="subsection-details">
        <summary>Art: ASCII art library for Python</summary><div>
        <a href="https://github.com/sepandhaghighi/art"><img src="https://img.shields.io/github/stars/sepandhaghighi/art.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/sepandhaghighi/art"><img src="https://img.shields.io/github/forks/sepandhaghighi/art.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/art"><img src="http://pepy.tech/badge/art"></a><br>
        Art does the "smart" placement of typed special characters or letters to make a visual shape that is spread over multiple lines of text.
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Human Computer Interaction (HCI)</summary><div>
      <details class="subsection-details">
        <!-- Add Nafas' Paper with Studies -->
        <summary><b>Nafas: Breathing Gymnastics Application,</b> <b><u>Sadra Sabouri</u></b>, Sepand Haghighi</summary><div>
        <a href="https://github.com/sepandhaghighi/nafas"><img src="https://img.shields.io/github/stars/sepandhaghighi/nafas.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/sepandhaghighi/nafas"><img src="https://img.shields.io/github/forks/sepandhaghighi/nafas.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/nafas"><img src="http://pepy.tech/badge/nafas"></a><br>
        Nafas is a collection of breathing gymnastics designed to reduce the exhaustion of long working hours with computer. With multiple breathing patterns, Nafas helps you find your way to a detoxified energetic workday and also improves your concentration by increasing the oxygen level. 
        <!-- We ran a user study to understand the library's users and tailor the features and programs to their style. -->
      </div></details>
      <details class="subsection-details">
        <summary>mytimer: A Timer for Command Line Enthusiasts</summary><div>
        <a href="https://github.com/sepandhaghighi/mytimer"><img src="https://img.shields.io/github/stars/sepandhaghighi/mytimer.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/sepandhaghighi/mytimer"><img src="https://img.shields.io/github/forks/sepandhaghighi/mytimer.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/mytimer"><img src="http://pepy.tech/badge/mytimer"></a><br>
        MyTimer aims to provide a simple yet comprehensive timer for terminal users. This project allows users to set timers directly from their command line interface, making it convenient for those who spend a significant amount of time working in the terminal!
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Chemical Data Science</summary><div>
    <!-- Amin's paper -->
      <details class="subsection-details">
        <summary><b>Experimental dataset of electrochemical efficiency of a Direct Borohydride Fuel Cell (DBFC) with Pd/C, Pt/C and Pd decorated Ni–Co/rGO anode catalysts,</b> Sarmin Hamidi, <b><u>Sadra Sabouri</u></b>, Sepand Haghighi, Kasra Askari</summary><div>
        <a href="https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/60c74a3e469df423a9f43ce2/original/experimental-dataset-of-electrochemical-efficiency-of-a-direct-borohydride-fuel-cell-dbfc-with-pd-c-pt-c-and-pd-decorated-ni-co-r-go-anode-catalysts.pdf" class="paper-button">Paper</a>
        <a href="https://github.com/ECSIM/dbfc-dataset"><img src="https://img.shields.io/github/stars/ECSIM/dbfc-dataset.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/ECSIM/dbfc-dataset"><img src="https://img.shields.io/github/forks/ECSIM/dbfc-dataset.svg?style=social&logo=github&label=Forks"></a><br>
        Dataset includes Direct Borohydride Fuel Cell (DBFC) impedance and polarization test in anode with Pd/C, Pt/C and Pd decorated Ni–Co/rGO catalysts. Voltage, power density and resistance of DBFC change as a function of weight percent of Sodium Borohydride (%), applied voltage and amount of anode catalyst loading that are evaluated by polarization and impedance curves with using appropriate equivalent circuit of fuel cell.
      </div></details>
      <details class="subsection-details">
        <summary>OPEM: Open Source PEM Fuel Cell Simulation Tool</summary><div>
        <a href="https://github.com/ECSIM/opem"><img src="https://img.shields.io/github/stars/ECSIM/opem.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/ECSIM/opem"><img src="https://img.shields.io/github/forks/ECSIM/opem.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/opem"><img src="http://pepy.tech/badge/opem"></a><br>
        The Open-Source PEMFC Simulation Tool (OPEM) is a modeling tool for evaluating the performance of proton exchange membrane fuel cells. This package is a combination of models (static/dynamic) that predict the optimum operating parameters of PEMFC. OPEM contained generic models that will accept as input, not only values of the operating variables such as anode and cathode feed gas, pressure and compositions, cell temperature and current density, but also cell parameters including the active area and membrane thickness.
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Biomedical Data Science</summary><div>
      <!-- drux -->
      <details class="subsection-details">
        <summary>OPR: Optimized Primer Design Tool</summary><div>
        <a href="https://github.com/openscilab/opr"><img src="https://img.shields.io/github/stars/openscilab/opr.svg?style=social&logo=github&label=Stars"></a>
        <a href="https://github.com/openscilab/opr"><img src="https://img.shields.io/github/forks/openscilab/opr.svg?style=social&logo=github&label=Forks"></a>
        <a href="http://pepy.tech/project/opr"><img src="http://pepy.tech/badge/opr"></a><br>
        OPR is an open-source Python package designed to simplify and streamline primer design and analysis for biologists and bioinformaticians. It enables users to design, validate, and optimize primers with ease, catering to a wide range of applications such as PCR, qPCR, and sequencing. 
      </div></details>
  </div></details>
  <details class="subsection-details">
    <summary>Environmental Data Science</summary><div>
      <details class="subsection-details">
        <summary>[AGU-WRR24] <b>Representative sample size for estimating saturated hydraulic conductivity via machine learning: A proof‐of‐concept study,</b> Amin Ahmadisharaf, Reza Nematirad, <b><u>Sadra Sabouri</u></b>, Yakov Pachepsky, Behzad Ghanbarian</summary><div>
        <a href="https://agupubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1029/2023WR036783" class="paper-button">Paper</a><br>
        Machine learning is widely used across disciplines, but hydrology has often overlooked the impact of data heterogeneity and sample size. In this study, we used ~18k soil samples from the USKSAT database to analyze how training size affects ML accuracy in estimating saturated hydraulic conductivity (Ks). Using XGBoost and repeated random subsets, we found that even with large datasets, learning and validation curves didn't plateau.
      </div></details>
  </div></details>
</div></details>

### News

Mar 2025: Python Software Foundation (PSF) granted our work, [Nava library](https://github.com/openscilab/nava), for adding new OS-based sound engines, and integrating into notebooks.

Feb 2025: Nlnet granted our work, [PyCM library](https://github.com/sepandhaghighi/pycm), for a year through NGI0 Commons Fund for adding new features such as distance similarity matrix, data distribution analysis, hardware benchmarking of the library.

Jan 2025: My paper [Trust dynamics in AI-assisted development: Definitions, factors, and implications](https://www.amazon.science/publications/trust-dynamics-in-ai-assisted-development-definitions-factors-and-implications) got accepted into International Conference on Software Engineering (ICSE) 2025. I will present my work remotely in searly May.

Sep 2024: I was awarded a [Trelis AI Grant](https://trelis.com/trelis-ai-grants/) for developing a RESTful API for PyCM, enhancing accessibility to machine learning statistical post-processing tools.

May 2024: Python Software Foundation (PSF) granted our work, [ASCII Art library](https://github.com/sepandhaghighi/art), for developing the library and add new features like multi-line arts, and supporting custom fonts.
