---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of this page is available here: [Jesson's Curriculum Vitae](/assets/jesson_cv.pdf).

Research interests
======
AI safety and trustworthy machine learning — with a current focus on large language
models: alignment, reinforcement learning, agentic RL, and adversarial robustness.

Education
======
* M.S. in Computer Science, University of Southern California, 2025 – present
* B.Eng. in Computer Science, School of Computer Science, Wuhan University, 2021 – 2025
  * Exchange student, EECS Department, UC Berkeley, Jan. 2024 – May 2024
  * Wuhan University Excellent Exchange Student Scholarship (top 0.4%)

Research experience
======
* Jan. 2024 – May 2025: Research Intern
  * EECS Department, UC Berkeley
  * Advised by Prof. [David Wagner](https://people.eecs.berkeley.edu/~daw/) and Postdoc [Zhanhao Hu](https://whothu.github.io/)
  * *JULI: Jailbreak Large Language Models by Self-Introspection* (May 2024 – May 2025). Jailbreaking
    LLMs by manipulating token log probabilities through a tiny plug-in block, BiasNet. JULI relies
    solely on the target model's top-5 predicted token log probabilities, so it works against
    API-only models in a black-box setting. The released fine-tuned models have over 4,000
    downloads on Hugging Face.
  * *Reject Option: Eradicating Harmful Content with a Tiny Classifier* (Jan. 2024 – May 2024).
    Detecting and rejecting harmful LLM responses with a classifier of only a few linear layers,
    matching the performance of Llama Guard.

* Sept. 2022 – Jan. 2024: Research Intern
  * CSE Department, Hong Kong University of Science and Technology
  * Advised by Prof. Qian Zhang
  * *MobHAR: Imperceptible Knowledge Transfer for Human Activity Recognition on Mobile Devices*
    (Aug. 2023 – Jan. 2024). A user-centric HAR customization framework built on an adversarial
    mechanism that enables imperceptible knowledge transfer. Accepted at IMWUT.
  * *ARTEMIS: Defending Against Backdoor Attacks via Distribution Shift* (Dec. 2022 – Jul. 2023).
    A backdoor defense that uses distribution shift to close the feature-space gap between poisoned
    and benign samples. Accepted at IEEE TDSC.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Languages: Python, C++
* Frameworks and tools: PyTorch, Git
