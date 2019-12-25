---
layout: article
key: page-about
show_title: false
title: 简历
aside:
  toc: true
header: false
# footer: false
permalink: /jianli.html
sitemap: false
---
# 赵翰夫

翰夫是一名土木工程师和数据科学家. 他曾任职于美国费城市政府与中国建设部直属规划单位. 他参与过国家重点工程规划, 也为多种行业提供数据咨询服务, 包括网络信息采集, 数据挖掘, 可视化交互平台. 他的近期目标是应用大规模数据挖掘赋能业务增长.

<sup>[下载PDF ↓](/assets/赵翰夫_简历.pdf){:.button.button--secondary.button--pill}{:target="_blank"} [发邮件 ↑](mailto:{{ site.email }}){:.button.button--secondary.button--pill}{:target="_blank"} [回网站 ←](/){:.button.button--secondary.button--pill} [English Ver. →](/resume.html){:.button.button--secondary.button--pill}</sup>

## 教育

### 哥伦比亚大学
- 土木工程硕士, 毕业于2014年5月.
- 毕业设计: _绿色河滨 - 滨水功能性湿地与慢行交通网在New Rochelle的应用_ <sup>ISBN:[9781312764637](http://www.lulu.com/us/en/shop/urban-design-lab/alternative-futures-for-new-rochelle/ebook/product-21958564.html){:target="_blank"}</sup>.


### 宾夕法尼亚州立大学
- 生物工程学士, 环境工程辅修, 毕业于2012年5月.

## 独立项目

### KDD2019 CTR预测模型复现
- 复现KDD2019 DeepGBM (_Ke et al, 2019_) 神经网络与决策树结合的深度学习模型<sup>[demo](https://www.kaggle.com/hanfuzhao/deepgbm-script){:target="_blank"}</sup>.
- 使用 __`PyTorch`__ 搭建因子分解机处理稀疏数据, 获得嵌入向量.
- 使用 __`XGBoost`__ 搭建梯度提升树处理稠密数据, 获得高维特征交叉.
- 提炼提升树模型的神经网络表征, 加入之前的嵌入向量 ,一起进行端到端的离线学习和新数据的在线学习.
- 结合特征预处理, 超参数优化等技巧, 逼近论文结果.

### 政府人事数据平台产品
- 使用 __`Scrapy`__ 等采集框架处理网站和新闻流, 并清洗数据归纳出人物履历, 覆盖90%以上的副部级及以上官员.
- 以 __`Neo4j`__ 图数据库突出人物之间的关系, 结合 __`Flask`__ 和 __`Dash`__ 制作成云端数据库产品, 使用 __`Docker`__ 部署<sup>[demo](https://plenum-demo.hanfu.us/){:target="_blank"}</sup>.
- 因其健全的数据和出色的时效性, 数据库的付费订阅深受智库和投资机构青睐.


### 数据科学与机器学习的培训
- 为机构内部及友好单位进行 __`R`__ , __`Python`__, 应用统计等数据培训<sup>[demo](/data/R-Introduction){:target="_blank"}</sup>.
- 以微积分, 线性代数, 概率论等基础内容为重点, 编写机器学习系列教程 <sup>[中文](https://zh.vintageml.com){:target="_blank"}|[English](https://en.vintageml.com){:target="_blank"}</sup>.

## 工作经历

### 中国城市规划设计研究院
- 使用 __`R`__ 和 __`MongoDB`__ 搭建地理数据可视化平台, 直观展示城市规模的共享单车运营, 并以时空数据模型支持管理决策<sup>[demo](https://geodash-demo.hanfu.us/){:target="_blank"}</sup>.
- 参与北京城市副中心水资源与水环境总体规划; 参与武汉,株洲等海绵城市专项试点的规划.

### 美国费城市水务局
- 为15亿美金的城市暴雨基础建设更新项目提供技术咨询和项目管理, 帮助市政府顺利通过联邦环境署的5年阶段验收.
- 搭建雨水检测数据平台,实现数据的自动收集,处理,备份,输出表现评分以供决策.
- 项目管理首次使用新技术的试点工程实施, 协调五所合作高校的联邦环境署科研项目.
