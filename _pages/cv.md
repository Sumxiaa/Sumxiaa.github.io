---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[[PDF]](http://araachie.github.io/files/CV_Aram_Davtyan.pdf)

## Education

* **PhD in Computer Science** - University of Bern, 2020-present  
  **_Topics:_** Learning object interactions, Video generation  
  Advisor: Prof. Paolo Favaro

* **Specialist Degree in Fundamental Mathematics and Mechanics** - Moscow State University, 2020  
  With specialization in Theory of Functions and Functional Analisys  
  **_Thesis Title:_** Spectral analysis of the operator in the generalized ’t Hooft model
  
* **Diploma in Computer Science** - Yandex School of Data Science, 2018  
  With specialization in Data Analisys in Applied Sciences  
  **_Thesis Title:_** Optimization of oil production via construction of forecast models on injection wells operation modes

## Professional Experience

* **Specialist** - Inline Group, 2017-2021  
  Applying machine learning to various problems in oil industry.

* **Software Engineer** - Yandex, 2019-2020  
  Developing the backend of a high-load service (Yandex.Navigator) responsible for building optimal routes in the automobile graph with respect to the realtime traffic. This included implementing algorithms on road graphs and improving quality of the service via supervised and reinforcement learning techniques (C++ and Python).
  
## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Skills

* **Programming:**  
  C/C++, Python, SQL, MapReduce, SVN, git, LaTeX
  
* **Frameworks:**  
  PyTorch, Tensorflow, SciPy, Numpy, OpenCV
  
* **Languages:**  
  English (C1), German (B2), Russian (native), Armenian (native)

## Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
