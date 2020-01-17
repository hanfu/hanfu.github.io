---
layout: article
key: page-about
show_title: false
title: Resume
aside:
  toc: true
header: false
# footer: false
permalink: /resume.html
sitemap: false
---
# Hanfu Zhao

Hanfu is a civil engineer and data scientist. He was employed by Philadelphia City Gov., and now China Ministry of Development's research institute. Not only was he involved in national civil programs, but also provided data consultancy across different disciplines and sectors. He is interested in practical massive data mining and collaborative intelligence.

<sup>[Download PDF ↓](/assets/HZhao_Resume.pdf){:.button.button--secondary.button--pill}{:target="_blank"} [Email Hanfu ↑](mailto:{{ site.email }}){:.button.button--secondary.button--pill}{:target="_blank"} [Back to Site ←](/){:.button.button--secondary.button--pill} [中文版 →](/jianli.html){:.button.button--secondary.button--pill}</sup>

## Education

### Columbia University
- Master of Science in Civil Engineering, graduated in May, 2014.
- Thesis: _Green Belt - Engineered Coastal Wetland with Slow Traffic Network in City of New Rochelle_ <sup>ISBN:[9781312764637](http://www.lulu.com/us/en/shop/urban-design-lab/alternative-futures-for-new-rochelle/ebook/product-21958564.html){:target="_blank"}</sup>.


### Pennsylvania State University
- Bachelors of Science in Biological Engineering, minor in Environmental Engineering, graduated in May, 2012.

## Independent Projects

### KDD2019 CTR Prediction Model Implementation
- Implemented KDD2019 DeepGBM (_Ke et al, 2019_), a Deep-Learning model combining Neural Network and Gradient Boosting Decision Tree<sup>[demo](https://www.kaggle.com/hanfuzhao/deepgbm-script){:target="_blank"}</sup>.
- Used Factorization Machine to embed sparse categorical features using __`PyTorch`__.
- Used Gradient Boosting Decision Tree to automate high-order feature crossings on dense numerical inputs using __`XGBoost`__.
- Distilled GBDT's information to Neural Network representation, joined with the previous embedded vectors, then trained the model in both End-to-End Offline Learning mode, and Online Learning mode for streaming data.
- Applied appropriate feature pre-processing and hyperparameter tuning to reach paper's result.

### CPC Member Data Portal
- Collected and cleaned Party's membership information from static and streaming sources to chronological records using __`Scrapy`__, covering more than 90% officials at deputy ministerial level and above.
- Packaged data to cloud service with __`Neo4j`__ graph database, __`Flask`__ and __`Dash`__ web frameworks, and __`Docker`__ deployment<sup>[demo](https://plenum-demo.hanfu.us/){:target="_blank"}</sup>.


### Data Science Advocacy
- Lectured data seminars for internal and affiliated institutes, covering __`R`__ , __`Python`__, and applied statistics<sup>[demo](/data/R-Introduction){:target="_blank"}</sup>.
- Drafting Machine Learning tutorial series, focusing on the fundamentals like Calculus, Linear Algebra, Probabilities and so<sup>[English](https://en.vintageml.com){:target="_blank"}|[中文](https://zh.vintageml.com){:target="_blank"}</sup>.


## Work Experience

### China Academy of Urban Planning and Design
- Developed geographic dashboard with __`R`__ and __`MongoDB`__ to provide visual understanding over city-scale bike sharing operations<sup>[demo](https://geodash-demo.hanfu.us/){:target="_blank"}</sup>.
- Provided technical support for Beijing Sub-Center Water Resources and Water Ecology Masterplan, and state level Sponge City Pilot Program in Wuhan and Zhuzhou with expertise in stormwater management.


### Philadelphia Water Department
- Provided project management and technical support for the 5-year progress compliance of the City’s $1.5 billion Stormwater Infrastructure program.
- Developed interactive dashboard for stormwater monitoring data to process, store visualize data for engineering inference.
- Piloted projects with first-time implemented technologies in the city.
- Coordinated federal granted research programs across five collaborating universities. 