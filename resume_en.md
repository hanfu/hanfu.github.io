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

Hanfu is an urban planner and data scientist. He was employed by Philadelphia City Gov., and now China Ministry of Development's research institute. Not only was he involved in national planning programs, but also provided data consultancy across different disciplines and sectors. He is interested in practical massive data mining and collaborative intelligence.

<sup>[Download PDF ↓](/assets/jianli.pdf){:.button.button--secondary.button--pill} [Email Hanfu ↑](mailto:zhhfu29@gmail.com){:.button.button--secondary.button--pill} [Back to Site ←](/){:.button.button--secondary.button--pill} [中文版 →](/jianli.html){:.button.button--secondary.button--pill}</sup>

## Education

### Columbia University
- Master of Science in Civil Engineering, graduated in May, 2014.
- Thesis: _Green Belt - Engineered Coastal Wetland with Slow Traffic Network in City of New Rochelle_ <sup>ISBN:[9781312764637](http://www.lulu.com/us/en/shop/urban-design-lab/alternative-futures-for-new-rochelle/ebook/product-21958564.html)</sup>.

### Pennsylvania State University
- Bachelors of Science in Agricultural Engineering, minor in Environmental Engineering, graduated in May, 2012.

## Independent Projects

### KDD2019 CTR Prediction Model Implementation
- 以COLAB为计算平台, 复现KDD2019 DeepGBM (Ke et al, 2019) 神经网络与决策树结合的深度学习模型<sup>[notebook](/)</sup>.
- 使用 __`PyTorch`__ 搭建因子分解机处理稀疏数据, 获得嵌入向量.
并后接全连接神经网络.
- 使用 __`XGBoost`__ 搭建梯度提升树处理稠密数据, 并且自动生成多项特征交叉.
- 提炼提升树结果的神经网络表征, 并和嵌入向量一起训练.
- 结合特征预处理, 超参数优化等技巧, 模型表现达到Kaggle银牌, 逼近论文结果.

### CPC Member Data Portal
- Collected and cleaned Party's membership information from static and streaming sources using __`Scrapy`__, covering more than 90% officials at deputy ministerial level and above.
- Packaged data into PaaS product with __`Neo4j`__ graph database, __`Flask`__ and __`Dash`__ web frameworks, and __`Docker`__ deployment<sup>[demo](/)</sup>.
- Proofed robustness and timeliness by large amount of subscriptions from think-tanks and investment institutes.


### Data Science Advocacy
- Lectured data seminars for internal and affiliated institutes, covering __`R`__ , __`Python`__, and applied statistics<sup>[demo](/data/R-Introduction)</sup>.
- Drafting Machine Learning tutorial series, fousing on fundamentals like Calculus, Linear Algebra, Probabilities and so<sup>[English](https://en.vintageml.com)|[中文](https://zh.vintageml.com)</sup>.


## China Academy of Urban Planning and Design

### City-scale Biking Sharing Geographic Dashboard
- Identified user patterns and overloading areas using temporal-spatial models with __`Python`__.
- The visualization provided the professionals with intuitive data understanding and city-scale operation's comprehension, and data backed policy making. 

## Philadelpha Water Department

### Urban Stormwater Management
- Provided technical support and project management for the 5-year progress compliance of the City’s $1.5 billion Stormwater Infrastructure program.
- Developed interactive dashboard for stormwater monitoring data to process, store visualize data for engineering inference, using  __`R`__ and __`PostgreSQL`__<sup>[demo](/)</sup>.
- Piloted projects with first-time implemented technologies in the city.
- Coordinated federal granted research programs across five collaborating universities. 