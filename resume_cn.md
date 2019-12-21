---
layout: article
key: page-about
show_title: false
aside:
  toc: true
header: false
# footer: false
permalink: /jianli.html
sitemap: false
---
# 赵翰夫

翰夫是一位城市规划师和数据分析师. 他曾任职于美国费城市政府与中国建设部直属规划单位. 他参与国家重点工程规划, 也为多种行业提供数据咨询服务, 包括网络信息采集, 数据挖掘, 可视化交互平台. 他的近期目标是应用大规模数据挖掘赋能业务增长.


[English Ver. →](/resume.html){:.button.button--secondary.button--pill} 
[下载PDF ↓](/assets/jianli.pdf){:.button.button--secondary.button--pill} 
[发邮件 ↑](mailto:zhhfu29@gmail.com){:.button.button--secondary.button--pill}
[回网站 ←](/){:.button.button--secondary.button--pill}

## 教育

### 哥伦比亚大学
- 土木工程硕士, 2014.05
- 毕业设计: 绿色河滨 - 滨水功能性湿地与慢行交通网在New Rochelle的应用, ISBN:[9781312764637](http://www.lulu.com/us/en/shop/urban-design-lab/alternative-futures-for-new-rochelle/ebook/product-21958564.html)

### 宾夕法尼亚州立大学
- 农业工程学士, 环境工程辅修, 2012.05

# 工作

## 中国城市规划设计研究院

### 城市共享单车的数据平台
- 使用 __`Flask`__ 全栈框架和 __`Dash`__ 可视化工具搭建了地理数据平台, [demo](/).
- 使用 __`Python`__ 建立时序模型, 找出显著的用户习惯和异常区域.
- 辅助行业人员对城市规模的共享单车运营进行直观了解, 制定管理机制.

## 美国费城市水务局

### 费城绿色基建项目规划
- 为总投入15亿美金的城市基础建设更新项目提供技术咨询和项目管理, 帮助市政府满足联邦环境署的5年阶段验收.
- 使用 __`R`__ 和 __`PostgreSQL`__ 搭建雨水检测数据平台,实现数据的自动收集,处理,备份,输出表现评分以供决策.
- 项目管理新技术首次使用的试点实施, 协调五所合作高校的联邦环境署科研项目.


## 项目

### Kaggle的广告网站CTR预估竞赛
- 以COLAB为计算平台, 实现类似KDD2019 DeepGBM的神经网络与决策树结合的深度学习模型, [notebook](/)
- 神经网络部分使用Tensorflow开源框架, 用FM结构处理稀疏数据并后接全连接神经网络
- 决策树部分使用XGBoost开源框架, 负责处理稠密数据并且自动生成多项特征交叉
- 模型融合, 验证, 
- 成绩达到Kaggle银牌


### 政府人事数据库产品
- 使用Scrapy等收集官方人事网站, 追踪新闻流, 并清洗数据归纳出人物履历, 覆盖了两千余名副部级及以上官员
- 以 __`Neo4j`__ 图数据库储存, 结合Flask和Dash制作成PaaS数据库产品, 使用 __`Docker`__ 云端部署, [demo](/).
- 是目前可找到的最全面最有时效性的官方人事数据库, 主要客户为智库和投资机构.


### 数据科学与机器学习的培训
- 为内部及友好单位进行[ __`R`__ ](/data/R-Introduction)和 __`Python`__ 培训
- 为机器学习的数学等基础课程编写系列教程 [祖传机器学习](https://zh.vintageml.com)(中文), [Vintage Machine Learning](https://en.vintageml.com) (English)