![cover](https://img3.doubanio.com/view/subject/l/public/s6176453.jpg)

    作者: W.Bruce Croft / Donald Metzler / Trevor Strohman
    出版社: 机械工业出版社
    副标题: 信息检索实践
    原作名: Search Engines : Information Retrieval in Practice
    译者: 刘挺 / 秦兵 / 张宇 / 车万翔
    出版年: 2010-6-1
    页数: 309
    定价: 56.00元
    装帧: 平装
    丛书: 计算机科学丛书
    ISBN: 9787111288084

[豆瓣链接](https://book.douban.com/subject/4861766/)

- [搜索引擎架构](#%e6%90%9c%e7%b4%a2%e5%bc%95%e6%93%8e%e6%9e%b6%e6%9e%84)
  - [什么是软件架构](#%e4%bb%80%e4%b9%88%e6%98%af%e8%bd%af%e4%bb%b6%e6%9e%b6%e6%9e%84)
  - [基本的构件](#%e5%9f%ba%e6%9c%ac%e7%9a%84%e6%9e%84%e4%bb%b6)
  - [组件及其功能](#%e7%bb%84%e4%bb%b6%e5%8f%8a%e5%85%b6%e5%8a%9f%e8%83%bd)
    - [文本采集](#%e6%96%87%e6%9c%ac%e9%87%87%e9%9b%86)
    - [文本转换](#%e6%96%87%e6%9c%ac%e8%bd%ac%e6%8d%a2)
    - [索引的创建](#%e7%b4%a2%e5%bc%95%e7%9a%84%e5%88%9b%e5%bb%ba)
    - [用户交互](#%e7%94%a8%e6%88%b7%e4%ba%a4%e4%ba%92)
    - [排序](#%e6%8e%92%e5%ba%8f)
    - [评价](#%e8%af%84%e4%bb%b7)
- [信息采集与信息源](#%e4%bf%a1%e6%81%af%e9%87%87%e9%9b%86%e4%b8%8e%e4%bf%a1%e6%81%af%e6%ba%90)
  - [网络信息爬取](#%e7%bd%91%e7%bb%9c%e4%bf%a1%e6%81%af%e7%88%ac%e5%8f%96)
  - [文档信息源](#%e6%96%87%e6%a1%a3%e4%bf%a1%e6%81%af%e6%ba%90)
  - [重复检测](#%e9%87%8d%e5%a4%8d%e6%a3%80%e6%b5%8b)
  - [去除噪声](#%e5%8e%bb%e9%99%a4%e5%99%aa%e5%a3%b0)
- [文本处理](#%e6%96%87%e6%9c%ac%e5%a4%84%e7%90%86)
  - [从词到词项](#%e4%bb%8e%e8%af%8d%e5%88%b0%e8%af%8d%e9%a1%b9)
  - [文本统计](#%e6%96%87%e6%9c%ac%e7%bb%9f%e8%ae%a1)
    - [Zipf's Law](#zipfs-law)
    - [语料规模与词表大小关系Heaps(1978)](#%e8%af%ad%e6%96%99%e8%a7%84%e6%a8%a1%e4%b8%8e%e8%af%8d%e8%a1%a8%e5%a4%a7%e5%b0%8f%e5%85%b3%e7%b3%bbheaps1978)
    - [估计数据集和结果集大小](#%e4%bc%b0%e8%ae%a1%e6%95%b0%e6%8d%ae%e9%9b%86%e5%92%8c%e7%bb%93%e6%9e%9c%e9%9b%86%e5%a4%a7%e5%b0%8f)
  - [文档解析](#%e6%96%87%e6%a1%a3%e8%a7%a3%e6%9e%90)
  - [文档结构和标记](#%e6%96%87%e6%a1%a3%e7%bb%93%e6%9e%84%e5%92%8c%e6%a0%87%e8%ae%b0)
  - [链接分析](#%e9%93%be%e6%8e%a5%e5%88%86%e6%9e%90)
    - [锚文本](#%e9%94%9a%e6%96%87%e6%9c%ac)
    - [PageRank](#pagerank)
  - [信息抽取](#%e4%bf%a1%e6%81%af%e6%8a%bd%e5%8f%96)
  - [国际化](#%e5%9b%bd%e9%99%85%e5%8c%96)
- [基于索引的相关排序](#%e5%9f%ba%e4%ba%8e%e7%b4%a2%e5%bc%95%e7%9a%84%e7%9b%b8%e5%85%b3%e6%8e%92%e5%ba%8f)
  - [抽象的相关排序模型](#%e6%8a%bd%e8%b1%a1%e7%9a%84%e7%9b%b8%e5%85%b3%e6%8e%92%e5%ba%8f%e6%a8%a1%e5%9e%8b)
  - [倒排索引](#%e5%80%92%e6%8e%92%e7%b4%a2%e5%bc%95)
  - [压缩](#%e5%8e%8b%e7%bc%a9)
  - [辅助结构](#%e8%be%85%e5%8a%a9%e7%bb%93%e6%9e%84)
  - [索引构建](#%e7%b4%a2%e5%bc%95%e6%9e%84%e5%bb%ba)
    - [简单构建](#%e7%ae%80%e5%8d%95%e6%9e%84%e5%bb%ba)
    - [融合](#%e8%9e%8d%e5%90%88)
    - [更新](#%e6%9b%b4%e6%96%b0)
  - [查询处理](#%e6%9f%a5%e8%af%a2%e5%a4%84%e7%90%86)
- [查询与界面](#%e6%9f%a5%e8%af%a2%e4%b8%8e%e7%95%8c%e9%9d%a2)
  - [查询转换与提炼](#%e6%9f%a5%e8%af%a2%e8%bd%ac%e6%8d%a2%e4%b8%8e%e6%8f%90%e7%82%bc)
    - [停用词去除和词干提取](#%e5%81%9c%e7%94%a8%e8%af%8d%e5%8e%bb%e9%99%a4%e5%92%8c%e8%af%8d%e5%b9%b2%e6%8f%90%e5%8f%96)
    - [拼写检查和建议](#%e6%8b%bc%e5%86%99%e6%a3%80%e6%9f%a5%e5%92%8c%e5%bb%ba%e8%ae%ae)
    - [查询扩展](#%e6%9f%a5%e8%af%a2%e6%89%a9%e5%b1%95)
    - [相关反馈](#%e7%9b%b8%e5%85%b3%e5%8f%8d%e9%a6%88)
    - [上下文和个性化](#%e4%b8%8a%e4%b8%8b%e6%96%87%e5%92%8c%e4%b8%aa%e6%80%a7%e5%8c%96)
  - [搜索结果显示](#%e6%90%9c%e7%b4%a2%e7%bb%93%e6%9e%9c%e6%98%be%e7%a4%ba)
  - [跨语言搜索](#%e8%b7%a8%e8%af%ad%e8%a8%80%e6%90%9c%e7%b4%a2)
- [检索模型](#%e6%a3%80%e7%b4%a2%e6%a8%a1%e5%9e%8b)
  - [检索模型概述](#%e6%a3%80%e7%b4%a2%e6%a8%a1%e5%9e%8b%e6%a6%82%e8%bf%b0)
    - [布尔检索模型](#%e5%b8%83%e5%b0%94%e6%a3%80%e7%b4%a2%e6%a8%a1%e5%9e%8b)
    - [向量空间模型](#%e5%90%91%e9%87%8f%e7%a9%ba%e9%97%b4%e6%a8%a1%e5%9e%8b)
  - [概率模型](#%e6%a6%82%e7%8e%87%e6%a8%a1%e5%9e%8b)
    - [将信息检索作为分类问题](#%e5%b0%86%e4%bf%a1%e6%81%af%e6%a3%80%e7%b4%a2%e4%bd%9c%e4%b8%ba%e5%88%86%e7%b1%bb%e9%97%ae%e9%a2%98)
    - [BM25排序算法](#bm25%e6%8e%92%e5%ba%8f%e7%ae%97%e6%b3%95)
  - [基于排序的语言模型](#%e5%9f%ba%e4%ba%8e%e6%8e%92%e5%ba%8f%e7%9a%84%e8%af%ad%e8%a8%80%e6%a8%a1%e5%9e%8b)
    - [查询项似然排序](#%e6%9f%a5%e8%af%a2%e9%a1%b9%e4%bc%bc%e7%84%b6%e6%8e%92%e5%ba%8f)
    - [相关性模型和伪相关反馈](#%e7%9b%b8%e5%85%b3%e6%80%a7%e6%a8%a1%e5%9e%8b%e5%92%8c%e4%bc%aa%e7%9b%b8%e5%85%b3%e5%8f%8d%e9%a6%88)
  - [复杂查询与证据整合](#%e5%a4%8d%e6%9d%82%e6%9f%a5%e8%af%a2%e4%b8%8e%e8%af%81%e6%8d%ae%e6%95%b4%e5%90%88)
  - [机器学习和信息检索](#%e6%9c%ba%e5%99%a8%e5%ad%a6%e4%b9%a0%e5%92%8c%e4%bf%a1%e6%81%af%e6%a3%80%e7%b4%a2)
    - [排序学习](#%e6%8e%92%e5%ba%8f%e5%ad%a6%e4%b9%a0)
    - [主题模型和词汇不匹配](#%e4%b8%bb%e9%a2%98%e6%a8%a1%e5%9e%8b%e5%92%8c%e8%af%8d%e6%b1%87%e4%b8%8d%e5%8c%b9%e9%85%8d)
- [搜索引擎评价](#%e6%90%9c%e7%b4%a2%e5%bc%95%e6%93%8e%e8%af%84%e4%bb%b7)
  - [效果评价](#%e6%95%88%e6%9e%9c%e8%af%84%e4%bb%b7)
    - [召回率和准确率](#%e5%8f%ac%e5%9b%9e%e7%8e%87%e5%92%8c%e5%87%86%e7%a1%ae%e7%8e%87)
    - [平均化和插值](#%e5%b9%b3%e5%9d%87%e5%8c%96%e5%92%8c%e6%8f%92%e5%80%bc)
    - [关注排序靠前的文档](#%e5%85%b3%e6%b3%a8%e6%8e%92%e5%ba%8f%e9%9d%a0%e5%89%8d%e7%9a%84%e6%96%87%e6%a1%a3)
    - [使用用户偏好](#%e4%bd%bf%e7%94%a8%e7%94%a8%e6%88%b7%e5%81%8f%e5%a5%bd)
  - [效率评价](#%e6%95%88%e7%8e%87%e8%af%84%e4%bb%b7)
  - [训练、测试和统计](#%e8%ae%ad%e7%bb%83%e6%b5%8b%e8%af%95%e5%92%8c%e7%bb%9f%e8%ae%a1)
    - [显著性检验](#%e6%98%be%e8%91%97%e6%80%a7%e6%a3%80%e9%aa%8c)
      - [t检验(t-test)](#t%e6%a3%80%e9%aa%8ct-test)
      - [威氏符号秩次检验(Wilcoxon signed-rank test)](#%e5%a8%81%e6%b0%8f%e7%ac%a6%e5%8f%b7%e7%a7%a9%e6%ac%a1%e6%a3%80%e9%aa%8cwilcoxon-signed-rank-test)
      - [符号检验(sign test)](#%e7%ac%a6%e5%8f%b7%e6%a3%80%e9%aa%8csign-test)
    - [设置参数值](#%e8%ae%be%e7%bd%ae%e5%8f%82%e6%95%b0%e5%80%bc)
    - [在线测试](#%e5%9c%a8%e7%ba%bf%e6%b5%8b%e8%af%95)
- [分类与聚类](#%e5%88%86%e7%b1%bb%e4%b8%8e%e8%81%9a%e7%b1%bb)
  - [分类](#%e5%88%86%e7%b1%bb)
    - [朴素贝叶斯](#%e6%9c%b4%e7%b4%a0%e8%b4%9d%e5%8f%b6%e6%96%af)
      - [1.多重伯努利模型](#1%e5%a4%9a%e9%87%8d%e4%bc%af%e5%8a%aa%e5%88%a9%e6%a8%a1%e5%9e%8b)
      - [2.多项式模型](#2%e5%a4%9a%e9%a1%b9%e5%bc%8f%e6%a8%a1%e5%9e%8b)
    - [SVM](#svm)
      - [1.线性可分数据](#1%e7%ba%bf%e6%80%a7%e5%8f%af%e5%88%86%e6%95%b0%e6%8d%ae)
      - [2.线性不可分](#2%e7%ba%bf%e6%80%a7%e4%b8%8d%e5%8f%af%e5%88%86)
      - [3.核技巧](#3%e6%a0%b8%e6%8a%80%e5%b7%a7)
      - [4.非二分类](#4%e9%9d%9e%e4%ba%8c%e5%88%86%e7%b1%bb)
    - [评价](#%e8%af%84%e4%bb%b7-1)
    - [分类器和特征选择](#%e5%88%86%e7%b1%bb%e5%99%a8%e5%92%8c%e7%89%b9%e5%be%81%e9%80%89%e6%8b%a9)
    - [垃圾、情感及在线广告](#%e5%9e%83%e5%9c%be%e6%83%85%e6%84%9f%e5%8f%8a%e5%9c%a8%e7%ba%bf%e5%b9%bf%e5%91%8a)
  - [聚类](#%e8%81%9a%e7%b1%bb)
    - [层次聚类和K均值聚类](#%e5%b1%82%e6%ac%a1%e8%81%9a%e7%b1%bb%e5%92%8ck%e5%9d%87%e5%80%bc%e8%81%9a%e7%b1%bb)
    - [K近邻聚类](#k%e8%bf%91%e9%82%bb%e8%81%9a%e7%b1%bb)
- [社会化搜索](#%e7%a4%be%e4%bc%9a%e5%8c%96%e6%90%9c%e7%b4%a2)
  - [用户标签和人工索引](#%e7%94%a8%e6%88%b7%e6%a0%87%e7%ad%be%e5%92%8c%e4%ba%ba%e5%b7%a5%e7%b4%a2%e5%bc%95)
    - [搜索标签](#%e6%90%9c%e7%b4%a2%e6%a0%87%e7%ad%be)
    - [推测缺失的标签](#%e6%8e%a8%e6%b5%8b%e7%bc%ba%e5%a4%b1%e7%9a%84%e6%a0%87%e7%ad%be)
    - [浏览和标签云](#%e6%b5%8f%e8%a7%88%e5%92%8c%e6%a0%87%e7%ad%be%e4%ba%91)
  - [社区内搜索](#%e7%a4%be%e5%8c%ba%e5%86%85%e6%90%9c%e7%b4%a2)
    - [什么是社区](#%e4%bb%80%e4%b9%88%e6%98%af%e7%a4%be%e5%8c%ba)
    - [社区发现](#%e7%a4%be%e5%8c%ba%e5%8f%91%e7%8e%b0)
    - [基于社区的问答](#%e5%9f%ba%e4%ba%8e%e7%a4%be%e5%8c%ba%e7%9a%84%e9%97%ae%e7%ad%94)
    - [协同搜索](#%e5%8d%8f%e5%90%8c%e6%90%9c%e7%b4%a2)
  - [过滤与推荐](#%e8%bf%87%e6%bb%a4%e4%b8%8e%e6%8e%a8%e8%8d%90)
    - [文档过滤](#%e6%96%87%e6%a1%a3%e8%bf%87%e6%bb%a4)
    - [协同过滤](#%e5%8d%8f%e5%90%8c%e8%bf%87%e6%bb%a4)
  - [P2P搜索与元搜索](#p2p%e6%90%9c%e7%b4%a2%e4%b8%8e%e5%85%83%e6%90%9c%e7%b4%a2)

# 搜索引擎架构
## 什么是软件架构
搜索引擎的两个主要目的
- 效果（质量）
- 效率（速度）

## 基本的构件
- 索引处理(indexing process)
  - 文本采集(text acquisition)
  - 文本转换(text transformation)：将文档转换为索引项(index term)或特征(feature)。
  - 索引创建(index creation)
- 查询处理(query process)
  - 用户交互(user interaction)
  - 排序(ranking)
  - 评价(evaluation)：一个重要的任务是利用日志数据来记录和分析用户的行为。

## 组件及其功能
### 文本采集
- 爬虫(crawler)
- 信息源(feed):RSS
- 转换
  - 将HTML,XML,PDF,WORD,PPT转换成统一格式和文档的元数据格式。
  - 保证它们使用统一的编码方案进行转换。
- 文档数据库

### 文本转换
- 解析器：处理文本词素(token)序列，词素切分。
- 停用词去除
- 词干提取器(stemmer)把同一个词干(stem)得到的派生词进行归类。
- 超链接抽取和分析
- 信息抽取：抽取句法特征，如名词短语，需要某种形式的句法分析和词性标注(part-of-speech tagging)。抽取具有指定语义内容的特征，例如，命名实体(named entity)识别器，识别如人名、公司名、日期和地点等。
- 分类器
  - 给文档分配事先定义好的类别标签。
  - 判别一个文档是否是垃圾文档，以及识别文档中的广告。
  - 聚类用于事先没有定义类别标签的基础上，将相关文档聚集在一起。

### 索引的创建
- 文档统计：简单汇总和记录词、特征及文档的统计信息。结果存在查找表(lookup table)。
  - 索引项在各文档中出现次数（词及更加复杂的特征）
  - 索引项在文档中出现位置
  - 索引项在一组文档（如标记“体育”）中出现次数
  - 按照词素数量统计文档长度
- 加权：利用文档统计结果计算权值，并将权值存储在查找表中。如tf·idf
- 倒排(inversion):将文本转换组件传递过来的文档-词信息流转换为词项-文档信息，以便于建立倒排索引。
- 索引分派：将索引分发给多台计算机。

### 用户交互
- 查询输入
- 查询转换：用于在生成好序的文档之前和之后改善初始查询。
  - 文本转换技术:在查询文本上，需要进行词素切分、停用词去除和词干提取。
  - 拼写检查(spell checking)和查询建议(query suggestion):向用户提供初始查询的一些候选查询，这些候选查询可能纠正了拼写错误或是对用户所需信息的更规范描述。
  - 查询扩展(query expansion):对查询进行推荐或增加一些额外的词项，在对文档中词项的出现情况分析的基础上进行。
  - 相关反馈(relevance feedback):一种查询扩展技术，利用用户认为相关的文档中出现的词项对查询进行扩展。
- 结果输出
  - 生成网页摘要(snippets)
  - 强调(highlighting)文档中重要的词和段落
  - 对输出结果聚类以找到文档相关的类别
  - 将相应广告增加到结果中

### 排序
- 打分机制
  - $\sum_iq_id_i$ ,qi是查询中第i个词项的权值，di是文档词项的权值。
- 性能优化：降低系统的响应时间，提高查询吞吐量。
  - term-at-a-time
  - document-at-a-time
  - 安全的(safe)的优化方式与不安全的(unsafe)的优化方式
- 分布式

### 评价
- 日志
  - 点击日志(点击数据)
  - 驻留时间(dwell time)
- 排序分析
- 性能分析

# 信息采集与信息源
## 网络信息爬取
- 抓取网页
- 网络爬虫
- 时新性
- 面向主题的信息采集
- 深层网络：那些爬虫很难找到的站点（deep Web，也称hidden Web）
  - 私人站点：没有任何指向它的链接
  - 表单结果
  - 脚本页面（JavaScript，Flash）
- 网站地图(sitemap)
- 分布式信息采集

## 文档信息源
pull类型信息源常见RSS。

## 重复检测
- 完全重复文档检测：checksumming，含有相同字符当顺序不同，具有相同checksum。
- 考虑字符出现位置：cyclic redundancy check，CRC
- 近似重复检测：指纹（fingerprint），生成指纹过程：
  - 首先对文档进行分词。删除不是词的内容（空格，HTML标签等）。
  - 对于给定n，将这些词组合成n-gram。通常是相互重叠的词序列。
  - 其中的一些n-gram被选择用于表示该文档。
  - 对这些被选择的n-gram进行散列，以提高检索效率，并进一步减少文档表示的大小。
  - 将散列值进行存储。

## 去除噪声
Finn(2001):在网页中主要内容部分的文本会比网页中附加内容的文本含有更少量的HTML标签。

# 文本处理
## 从词到词项
- 搜索引擎之所以有效的原因，是文本的很多含义通过词语出现和共现的次数获得。
- 理解文本的统计性质是理解检索模型和排序算法的基础。

## 文本统计
### Zipf's Law
Zipf's Law:第r高频的词的出现次数与r成反比，或者说，一个词在词频统计表中的排名乘以它的词频(f)约等于一个常数(k):
  - $r \cdot f = k$

Zipf 可表示为：$r \cdot P_r = c$
- 其中$P_r$表示第r高频词出现的概率
- c是一常数，对于英语而言，$c \approx 0.1$

Zipf Law通常对排名靠前和靠后的预测不准确。

$r \cdot P_r$值的log-log图呈现一条直线。
- $log P_r=log(c \cdot r^{-1})=logc-logr$

### 语料规模与词表大小关系Heaps(1978)
Heaps(1978)发现，语料规模与词表大小的关系为：$v = k \cdot n^\beta$
- v为词汇量大小
- 语料中共有n个词
- k和 $\beta$是随着不同语料变化的参数
- Heaps法则预测当语料规模很小时，新词数量增长非常快。随着语料规模变大，新词数量无限增长，但是增速会变慢。

### 估计数据集和结果集大小
- 假设词的出现彼此独立
  - $P(a \cap b \cap c) = P(a) \cdot P(b) \cdot P(c)$
  - $P(a) = \frac{f_a}{N}$
  - $P(b) = \frac{f_b}{N}$
  - $P(c) = \frac{f_c}{N}$
  - $f_{abc} = N \cdot \frac{f_a}{N} \cdot \frac{f_b}{N} \cdot \frac{f_c}{N}$ 用频率近似
- 假设词的出现不独立
  - $P(a \cap b \cap c) = P(a \cap b) \cdot P(c | a \cap b)$
- 估计文档总数
  - $\frac{f_{ab}}{N} = \frac{f_a}{N} \cdot \frac{f_b}{N}$
  - $N = \frac{f_a \cdot f_b}{f_{ab}}$

## 文档解析
- 词素切分：指从文档中的字符序列中获取词的过程。
- 停用词去除
  - 停用词(stopword):第一，这些功能词极其普遍。第二，由于它们的普遍性和功能，这些词很少单独表达文档相关程度的信息。
- 词干提取（stemming）：获得一个词不同变形之间关系的文本处理过程。将一个词由变形（inflection）（如复数、时态）或者派生(derivation)产生的多种不同形式简化为一个共同的例子。
- 短语和n-gram
  - 词性标注器（part-of-speech tagger，POS）：根据上下文信息对文本中的每一个词赋予一个词性标记。一般的词性标记包括NN（单数名词）、NNS（复数名词）、VB（动词）、VBD（动词，过去时）、VBN（动词，过去分词）、IN（介词）、JJ（形容词）、CC（连词）、PRP（代词）和MD（情态动词）。
  - 任何n个词的序列都构成一个短语。这就是所谓n-gram。两个词的序列称为bigram，三个词的序列称为trigram。
  - 所有长度的n-gram构成一个Zipf分布，一些常见短语非常频繁，大量的短语只出现一次，n-gram（包括单个词）的“排名-频率”数据比只有词本身更符合Zipf分布。

## 文档结构和标记
- 从HTML tag得到的网页结构信息的有些部分，是排序算法用到的非常重要的特征。
- XML：XQuery

## 链接分析
### 锚文本
- 链接的锚文本集合可以作为链出网页额外的文本属性，可以在排序算法中使用。
- 写锚文本的人一般不是目标网页的作者。这意味着锚文本可能是从另一个角度来描述目标网页。

### PageRank
网页u的PageRank一般公式：

$PR(u) = \frac{\lambda}{N} + (1-\lambda) \cdot \sum_{v \in B_u} \frac{PR(v)}{L_v}$

- $B_u$：指向u的网页集合
- $L_v$：网页v中包含的外链数
- N：需要考虑的网页数
- $\lambda$：进入任何网页的概率，一般取0.15

这个公式也可表达为矩阵等式：R=TR,R是矩阵T的特征向量。

其中R为PageRank向量，T为随机游走模型转移概率矩阵。元素 $T_{ij}$ 表示网页i进入网页j的概率，并且

$T_{ij}=\frac{\lambda}{N}+(1-\lambda)\frac{1}{L_i}$

## 信息抽取
`命名实体识别`（named entity recognition）：一个命名实体是表达特定应用感兴趣的某一个事物的词或词序列。最一般的例子是人名、公司名或机构名、地名、时间和日期表达式、数量和货币值。

```
Fred Smith,who lives at 10 Water Street,Springfield,MA, is a long-time collector of tropical fish.
```

`隐马尔可夫模型`的信息抽取：给定一个句子，找到一个实体类别序列，使得产生这个句子的概率最大。自由状态转移时产生的输出是可见的（可以被观察到的）：潜在的状态是隐藏的（hidden）。

对于上面例子，识别器将找到：

```
<start><name><not-an-entity><location><not-an-entity><end>
```
时，对于那个模型，其概率最高。Viterbi算法可以在HMM模型中找到最大概率的状态序列。

使用这种方法识别命名实体的核心问题是，句子模型中的概率必须从训练数据估计出来。为了估计转义和输出概率，使用人工标注了正确实体标签的文本作为训练数据。从这个训练数据，可以直接估计出某个类别产生词的概率（输出概率）和类别之间的转移概率。

## 国际化
字符编码是搜索引擎处理非英语语言时的核心问题。

词素切分对于很多语言很重要，有其是CJK家族。

# 基于索引的相关排序
## 抽象的相关排序模型
- 主题（topical）特征
- 质量（quality）特征
  - 链接到该文档的网页数量
  - 这个页面上次更新至今的天数

相关排序函数R：$R(Q,D)=\sum_ig_i(Q)f_i(D)$
- $f_i$是某个特征函数，它从文档文本中获得一个数值。
- $g_i$是一个相似特征函数，它从查询中获得一个值。

## 倒排索引
- 通常认为单词是文档的一部分，但是如果转变这个想法，认为文档是附着在单词上的，这样的索引就被称作倒排（inverted）了。
- 每个索引项有其自身的倒排列表（inverted list），它们含有和该项相关的数据。
- 在搜索引擎中，数据可能是文档列表或者单词所在位置的列表。列表的每个项被称作posting，在posting中，指向特定文档或位置的部分称作指针（pointer）。

## 压缩
- 某处理器每秒处理p个倒排表的posting。
- 该处理器附在每秒能够提供m个posting的存储器上。
- 压缩率为r。
- 处理速度为d的压缩因子。
- 当不使用压缩时，r=1，d=1。任何可行的压缩技术使得r>1,d<1。
- 理想情况是选择一种使得min(mr,dp)最大的压缩方法，这将发生在mr=dp时。
- 有损（lossless）压缩 、无损（lossy）压缩

## 辅助结构
倒排文件通常存储在一个文件中，在倒排文件中，还有一个被称作词汇（vocabulary或lexicon）的目录结构，它包含一个从索引到倒排文件字节偏移量的查找表。

迄今为止介绍的搜索引擎都是返回文档编号的列表和分数。一个真正面向用户的搜索引擎，需要显示关于每个文档的文本信息，如文档标题，URL或者文本摘要。

## 索引构建
### 简单构建
```
procudure BuildIndex(D)       # D是一个文本文档集
  I <- HashTable()            # 倒排表存储
  n <- 0                      # 文档编号
  for all ducuments d in D do
    n <- n + 1
    T <- Parse(d)             # 将文档分拆成标记
    Remove duplicates from T
    for all tokens t in T do
      if It not in I then
          It <- Array()
      end if
      It.append(n)
    end for
  end for
  return I
end procudure
```

两点限制
- 它要求所有的倒排表都存于内存中，对于较大文档集，会存在问题。
- 算法是顺序的，不便于并行。

### 融合
内存问题的典型解法是融合（merging）。可以构建倒排表结构I直到内存耗尽。这时，将部分索引I写到磁盘上，然后开始建造新的索引。最终，磁盘存放了许多部分索引，I1,I2,I3,...,In。然后系统将这些文件融合为一个。

### 更新
索引合并和结果合并。

## 查询处理
- document-at-a-time评价
- term-at-a-time评价
- 优化技术
  - 倒排表跳转
  - 联合处理
  - 阈值方法
  - MaxScore
  - 提早终止
  - 缓存：文档中词频遵从zipf分布

# 查询与界面
## 查询转换与提炼
### 停用词去除和词干提取
### 拼写检查和建议
- 拼写检查工具：拼写字典（spelling dictionary），编辑距离（edit distance）
- 拼写矫正：噪声通道模型（noisy channel model），一个人在自觉上要输出（即写出）词w，是根据概率分布P(w)，然后这人要去写出词w，但是声音通道（大体上相当于人的大脑）使得这个人以概率P(e|w)写了词e。
  - 语言模型（language model）：P(w)
  - 错误模型（error model）：P(e|w)
  - 一个词的语言模型概率可以采用这个词在文本中出现的概率和它接着前一个词出现的概率混合形式（mixture）来计算：$\lambda P(w)+(1-\lambda)P(w|w_p)$
    - $\lambda$是描述两个概率相对重要程度的参数
    - $P(w|w_p)$ 是词w在词$w_p$之后出现概率
  - 错误模型（error model）：P(e|w)的概率估计
    - 简单方法：假定所有具有相同编辑距离的错误有相等的概率，并且仅考虑在一个确定的编辑距离以内的字符串（通常取编辑距离为1或2）。
    - 复杂方法：对于一些确定类型的错误发生可能性进行概率估计，例如，当想要输入e时输入a，这些概率估计是通过对大规模的文本集中查找一些正确拼写和不正确拼写的词对获得的。

### 查询扩展
- 衡量词项相关性
  - 戴斯系数（Dice's coefficient）:$\frac{2 \cdot n_{ab}}{n_a+n_b} \triangleq \frac{n_{ab}}{n_a+n_b}$
    - $\triangleq$指公式是排序相等的
  - 互信息（mutual information）用来衡量词之间能够相互独立出现的程度：$log\frac{P(a,b)}{P(a)P(b)}$
    - P(a)给定大小的文本窗口中词a出现的概率
    - P(b)给定大小的文本窗口中词b出现的概率
    - P(a,b)给定大小的文本窗口中词a和b同时出现的概率
  - 期望互信息：根据概率P(a,b)对互信息进行加权处理：
    - $P(a,b) \cdot log\frac{P(a,b)}{P(a)P(b)}$
  - 皮尔森 $\chi^2$检验：计算两个词共现的观测值与这两个词在互相独立条件下共现的期望值的比值，并根据期望值对这个比值进行归一化处理 $\frac{(n_{ab}-N \cdot \frac{n_b}{N} \cdot \frac{n_b}{N})^2}{N \cdot \frac{n_a}{N} \cdot \frac{n_b}{N}} \triangleq \frac{(n_{ab}-\frac{1}{N} \cdot n_a \cdot n_b)^2}{n_a \cdot n_b}$

### 相关反馈
在相关反馈中，不是让用户从词项列表中或可替换的查询中进行选择，而是让用户指出哪些文档是感兴趣的（即相关的），以及哪些是完全离题的（即不相关的）。根据这些信息，系统通过增加词项或对原始词项重新分配权重，自动地改写查询，并用改写的查询生成新的文档排序。

### 上下文和个性化
- 让用户根据预定义的类别对自己进行描述。
- 本地搜索（local search），从查询中或者从提交查询的设备的位置信息中获得的地理信息，并根据这些信息调整排序结果。

## 搜索结果显示
- 搜索结果页面与页面摘要：自动文摘技术可以分为查询无关文摘和查询相关文摘。
- 广告与搜索：关键词一般是从网页内容中选取，然后用这些关键词去搜索广告数据库，选择可以与网页内容一起展示的广告。
- 结果聚类：聚类是将检索结果文档按照内容相似聚成一组并标记每个组，使得用户能够很快浏览到相关类别。
  - 逐面分类法（faceted classification）：由一些类别组成，通常这些类别被组织成层次形式，每个类别用一组层面来描述与其相关的一些重要属性。

## 跨语言搜索
- 统计机器翻译模型，平行语料库（parallel corpora）。在平行语料库中的句子采用人工或自动方式对齐。
- 自动音译（transliteration）：用来处理人名问题。 

# 检索模型
## 检索模型概述
一篇文档如果被判定和一个查询是同一个主题，那么它们是主题相关的。

用户相关性考虑用户在判定相关性时涉及的所有因素。这些因素包括文档的年代、语言、目标受众、新颖性等。

相关性是二元还是多元的：二元相关性就是简单地判定一篇文档是相关的还是非相关的。

### 布尔检索模型
假设在检索到的集合中，所有文档关于相关性都是等价的，同时也假设了相关性是二元的。

### 向量空间模型
一篇文档Di表示为索引词项的一个向量：$D_i=((d_{i1},d_{i2}, ..., d_{it}))$

可以表示为一个词项权值的矩阵：

$$
\begin{matrix} 
& term1 & term2 & \cdots & termt \\\\
doc1 & d_{11} & d_{12} & \cdots & d_{1t} \\\\
doc2 & d_{21} & d_{22} & \cdots & d_{2t} \\\\
\vdots & \vdots & \vdots & \cdots & \vdots \\\\
docn & d_{n1} & d_{n2} & \cdots & d_{nt} 
\end{matrix}
$$

文档可以通过计算表示文档和查询的点之间的距离来进行排序。

余弦相关性：$cos(D_i,Q)=\frac{\sum_{j=1}^t d_{ij} \cdot q_j}{\sqrt{\sum_{j=1}^t d_{ij}^2 \cdot \sum_{j=1}^t q_j^2}}$

tf表示文档中词项的频率，反映了一个词项在文档Di（或查询项）中的重要性。$tf_{ik}=\frac{f_{ik}}{\sum_{j=1}^t f_{ij}}$

idf反映了文档数据集中词项重要性。如果在其中出现过一个词项的文档越多，这个词项在文档之间就越没有区分性，也就对检索越没有用。$idf_k=log\frac{N}{n_k}$

Rocchio(1971)：一种根据用户判定的相关文档来修改查询项的算法，这个算法会使得相关文档向量的平均向量和非相关文档向量的平均向量之间的差异化最大。$q_j'=\alpha \cdot q_j=\beta \cdot \frac{1}{|Rel|}\sum_{D_i in Rel}d_{ij}- \gamma \cdot \frac{1}{|Norel|}\sum_{D_i \in Norel}d_{ij}$
  - $q_j$查询项j的初始权重
  - Rel用户选定的相关文档集合
  - Norel非相关文档集合
  - |.|返回一个集合的大小
  - $d_{ij}$ 是文档i中第j个词项的权值
  - $\alpha,\beta,\gamma$控制每个部分影响的参数，合理的数值分别是8，16，4

## 概率模型
### 将信息检索作为分类问题
当P(R|D)>P(NR|D)时，判定文档D是相关的，其中P(R|D)是相关性的条件概率，P(NR|D)是非相关性的条件概率。

$P(R|D)=\frac{P(D|R)P(R)}{P(D)}$

P（R）是相关性的先验概率（任何文档都是相关的可能性）。将判定一篇文档相关的条件（P(R|D)>P(NR|D)）代入：

$\frac{P(D|R)}{P(D|NR)}>\frac{P(NR)}{P(R)}$

左边部分称为似然比。搜索引擎只需要排序文档，不需要做出分类判断。如果采用似然比作为分值，排序较高的是那些对于属于相关集合具有较高似然值的文档。

假设文档由词项组成，相关文档和不相关文档表示为词项的集合：
- 文档表示为一组二元向量特征，$D=(d_1,d_2,...,d_t)$，其中$d_i$表示词项i出现在文档中，反之为0。
- 朴素贝叶斯假设：词项独立性，这意味着可以 $\prod_{i=1}^t P(d_i|R)$ 来估计P(D|R)，类似可以计算P(D|NR)。

$\frac{P(D|R)}{P(D|NR)}=\prod_{i:d_i=1}\frac{p_i}{s_i} \cdot \prod_{i:d_i=0}\frac{1-p_i}{1-s_i}$
- $p_i$是词项i在相关集合的某篇文档中出现（出现为1）的概率。
- $s_i$是词项i在不相关集合的某篇文档中出现（出现为1）的概率。
- $\prod_{i:d_i=1}$ 文档中值是1的词项概率的连乘。

数学推导：

$\prod_{i:d_i=1}\frac{p_i}{s_i} \cdot (\prod_{i:d=1}\frac{1-s_i}{1-p_i} \cdot \prod_{i:d_i=1}\frac{1-p_i}{1-s_i})\prod_{i:d=0}\frac{1-p_i}{1-s_i}$

$=\prod_{i:d_i=1}\frac{p_i(1-s_i)}{s_i(1-p_i)} \cdot \prod_i\frac{1-p_i}{1-s_i}$

第二项连乘涵盖所有词项，也能覆盖所有文档，所以对于排序能够忽略掉。取对数控制精度问题:

$\sum_{i:d_i=1}log\frac{p_i(1-s_i)}{s_i(1-p_i)}$

假设，在其他信息存在的基础上，查询项中那个没有出现的词项对于相关文档和非相关文档具有相同的出现概率（即pi=si）。也就是说，给定一个文档，文档的分值可以简单地将匹配到的词项概率求和即可。

如果没有相关集合的其他信息，可以额外假设pi是一个常数，si可以被近似估计为整个文档数据集中的词项出现情况（依据是相关文档的数量远小于整体文档集合的大小），假定pi=0.5，给定词项i的权值为

$log\frac{0.5(1-\frac{n_i}{N})}{\frac{n_i}{N}(1-0.5)}=log\frac{N-n_i}{n_i}$

假定：
- N整个文档数据集中所有文档数量
- R和这个查询相关的文档数量
- ni包含词项i的文档数量
- ri包含词项i的相关文档数量

则:
- $p_i=\frac{r_i}{R}$
- $s_i=\frac{n_i-r_i}{N-R}$

在每个数值上加0.5，整体数值上加1:
- $p_i=\frac{r_i+0.5}{R+1}$
- $s_i=\frac{n_i-r_i+0.5}{N-R+1}$

$\sum_{i:d_i=q_i=1}log\frac{(r_i+0.5)/(R-r_i+0.5)}{(n_i-r_i+0.5)/(N-n_i-R+r_i+0.5)}$

### BM25排序算法
通过加入文档权值和查询项权值，拓展了二元独立模型的得分函数：
$\sum_{i \in Q}log\frac{(r_i+0.5)/(R-r_i+0.5)}{(n_i-r_i+0.5)/(N-n_i-R+r_i+0.5)} \cdot \frac{(k_1+1)f_i}{K+f_i} \cdot \frac{(k_2+1)qf_i}{k_2+qf_i}$

- $f_i$词项i在文档中的频率
- ${qf}_i$词项i在查询中的频率
- k1,k2,K经验设定参数

## 基于排序的语言模型
一元语言模型就是语言中词汇的概率分布。例如，如果文档数据集中只包含5个不同的词语，这个集合一个可能的语言模型是(0.2,0.1,0.35.0.25,0.1)，其中每个数值表示词语出现的概率。如果将每个文档看成是词汇的一个序列，那么语言模型的概率就是预测序列中下一个词语的概率。

n元语言模型使用更长序列来预测词语。一个n元模型预测词语时考察前面的n-1个词语。

将文档表示为语言模型后，同样能够将查询的主题表示为语言模型。这种情况下，语言模型是主题的一种表示。这种主题是搜索信息的人在写下查询时头脑中所想的内容。这就导致了三种基于语言模型的检索概率值：一种是基于从文档语言模型生成查询文本的概率；一种是基于从查询项语言模型生成文档文本的概率；一种是基于对比查询语言模型和文档主题语言模型的结果。

### 查询项似然排序
$P(D|Q) \triangleq P(Q|D)P(D)$

- $\triangleq$ 排序等价
- P(D)文档先验概率
- P(Q|D)给定文档后查询的似然函数

P(D)被假设是始终如一（对所有文档都一样），不影响排序结果。所以检索模型通过P(Q|D)来排序文档，这个概率值采用文档一元语言模型来计算：

$P(Q|D)=\prod_{i=1}^nP(q_i|D)$
- qi是查询项中的词，查询项中有n和词。

估计语言模型概率值：

$P(q_i|D)=\frac{f_{q_i,D}}{|D|}$
- $f_{q_i,D}$ 是词语qi在文档集合D中出现次数。
- |D|表示D中词语的数量。

平滑技术用于避免这种估计问题以及数据稀疏问题，一般的方法是降低（或者打折）文档文本中出现词语的估计概率，并对文本中未出现的词语赋给估计的“剩余”概率。未出现词语的概率通常都是基于整个文档数据集中词语的出现频率来进行估计。如果P(qi|C)是文档集合C的数据集语言模型中词语i的出现概率，那么文档中未出现词语的估计概率为 $\alpha_DP(q_i|C)$ ，其中 $\alpha_D$ 是控制赋予未见词语概率的系数。为了保证概率值和为1，文档中一个出现过的词语的概率估计为:

$(1-\alpha_D)P(q_i|D)+\alpha_DP(q_i|C)$

Jelinek-Mercer平滑方法估计 $P(q_i|D)$

$P(q_i|D)=(1-\lambda)\frac{f_{q_i,D}}{|D|}+\lambda\frac{c_{q_i}}{|C|}$
- $\alpha_D=\lambda$
- 估计词语qi的概率为 $\frac{C_{qi}}{|C|}$
- $C_{qi}$ 是文档数据集中查询词出现的次数
- |C|是集合中所有词语出现的次数总和

文档得分公式： $logP(Q|D)=\sum_{i=1}^nlog(1-\lambda)\frac{f_{q_i,D}}{|D|}+\lambda\frac{c_{qi}}{|C|}$

狄利克雷平滑方法估计 $P(q_i|D)$

$p(q_i|D)=\frac{f_{q_i,D}+\mu\frac{c_{qi}}{|C|}}{|D|+\mu}$
- $\alpha_D=\frac{\mu}{|D|+\mu}$

文档得分公式： $logP(Q|D)=\sum_{i=1}^nlog\frac{f_{q_i,D}+\mu\frac{c_{qi}}{|C|}}{|D|+\mu}$

### 相关性模型和伪相关反馈
如果能够从一个查询估计一个相关性模型，那么就能将这个语言模型和文档模型直接进行对比。文档会根据文档模型和相关性模型的相似程度进行排序。

Kullback-Leibler分散度（KL-分散度），能够度量两个概率分布的差异。给定真实的概率分布P以及另外一个用于估计P的概率分布Q，KL-分散度定义为：

$KL(P||Q)=\sum_xP(x)log\frac{P(x)}{Q(x)}$

利用相关性模型进行排序的概括步骤：
1. 根据对查询Q的查询似然得分对文档排序；
2. 选择排序靠前的某个数目的文档构成集合C；
3. 利用估计概率P(w,q1,...,qn)来计算相关性模型概率P(w|R)；
4. 利用KL-分散度来对文档进行再次排序：

$\sum_wP(w|R)logP(w|D)$

## 复杂查询与证据整合
高效检索需要将与文档可能相关的许多片段的证据组合起来。

贝叶斯网络是一种用于区分一组事件和事件之间依赖关系的概率模型。这种网络是有向无环图(DAG)。图中的节点表示带有一组可能输出的事件，弧表示事件之间的依存关系。

## 机器学习和信息检索
### 排序学习
Ranking SVM的输入是针对一组查询的偏序排序信息的一组训练集合

$(q_1,r_1),(q_2,r_2), \cdots,(q_n,r_n)$

其中qi是一个查询，ri是所需排序的文档关于查询的部分排序信息或相关性级别。这意味着，如果去、文档$d_a$应该比$d_b$排序更高，那么$(d_a,d_b) \in r_i$，否则 $(d_a,d_b) \notin r_i$。

学习一个线性排序函数$\vec{w} \cdot \vec{d_a}$，其中$\vec{w}$是一个用于通过学习调整的权值向量，$\vec{d_a}$是文档$d_a$的特征表示向量。

$mini:\frac{1}{2} \vec{w} \cdot \vec{w}+C\sum\xi_{i,j,k}$

subject to:

$\forall (d_i,d_j) \in r_1:\vec{w} \cdot \vec{d_i} > \vec{w} \cdot \vec{d_j} + 1 - \xi_{i,j,1}$

$\forall (d_i,d_j) \in r_n:\vec{w} \cdot \vec{d_i} > \vec{w} \cdot \vec{d_j} + 1 - \xi_{i,j,n}$

$\forall i \forall j \forall k:\xi_{i,j,k} \ge 0$

### 主题模型和词汇不匹配
生成一篇文档的LDA过程：

1. 对每个文档D，根据参数$\alpha$在一个狄利特雷分布中选择一个多项式分布$\theta_D$。
1. 对文档D中的每个词语位置：
    1. 从多项式分布$\theta_D$中选择一个主题z。
    1. 从$P(w|z,\beta)$中选择一个词语w，$P(w|z,\beta)$是给定主题z和参数$\beta$时的多项式条件概率。

搜索应用采用LDA的主要问题：估计模型中的概率比较费事。

# 搜索引擎评价
## 效果评价
### 召回率和准确率
- A是相关文档集合，B是被检索到的文档集合
- 召回率$R=\frac{|A \cap B|}{|A|}$
- 准确率$P=\frac{|A \cap B|}{|B|}$
- 虚报率$=\frac{|\bar{A} \cap B|}{|\bar{A}|}$
- $F=\frac{1}{\frac{1}{2}(\frac{1}{R}+\frac{1}{P})}=\frac{2RP}{R+P}$
- 位置p的准确率（precision of p）：如果一个排序位置p的准确率比另一个排序高，召回率也会较高。
  - 最常用的P@10和P@20的准确率度量。
  - 暗示搜索任务已经变为在给定排序中找到尽可能相关的文档，而不是找到尽可能多的相关文档。
- 当召回率从0.0到1.0每次增加0.1这一标准值时，计算准确率的相应变化。
  - 优点在于，可以用于评价所有排序结果中的相关文档，而不仅仅是那些靠前的文档。
- 计算当一个额外的相关文档被检出（也就是当召回率增加）时，准确率的平均值。

### 平均化和插值
- 平均准确率(Mean Average Precision,MAP):平均准确率为每个查询的相关排序结果赋予一个评价数字，从多个查询中总结该排序算法性能的最简单的途径，就是对这些数字进行平均。
- 标准召回率等级是0.0到1.0，增量为0.1.为了获得每个查询在这些召回率等级下的准确率，必须进行插值。

### 关注排序靠前的文档
- 排序倒数(reciprocal rank)定义为返回第一个相关文档位置的倒数。平均排序倒数MRR(mean reciprocal rank)是针对一组查询的排序倒数平均值。
- 对于网络搜索而言，DCG(discounted cumulative gain)是一种较为普遍的评价方法。这种方法基于两点假设：
  - 高相关的文档比边缘相关的文档要有用的多。
  - 一个相关文档的排序位置越靠后，对于用户的价值就越低，因为它们很少会被用户查到。
  - DCG方法是在一个特定的排序p的前提下，计算总的增益：$DCG_p=rel_1+\sum_{i=2}^p\frac{rel_i}{log_2i}$
    - $rel_i$指的是检索回的文档中排序为i的文档的相关性等级。
    - $log_2i$是一种损失因子(discount or reduction factor)。

### 使用用户偏好
- Kendall $\tau$系数
  - 使用偏好描述的两个排序结果，P是两种排序中一致的偏好的数量，Q代表不一致的数量。
  - 这个估计值在1（当两个排序中用户偏好全部一致时）到-1（当偏好全部不一致时）之间变化。
  - $\tau=\frac{P-Q}{P+Q}$
- BPREF
  - 偏好来自二元相关判决的情况。
  - 对于一个返回了R个相关文档的查询，仅考察前R个不相关文档，相当于使用RxR个用户偏好。
  - $BPREF=\frac{1}{R}\sum_{d_r}(1-\frac{N_{d_r}}{R})$
    - $d_r$是一个相关文档，$N_{d_r}$给出了排序高于$d_r$的不相关文档的数量（考察不相关文档集R）
    - 另一种定义$BPREF=\frac{P}{P+Q}$

## 效率评价
- 基于`查询流量(query throughput)`的方法，记为每秒处理的查询数量，它并不捕捉`延迟(latency)`。

## 训练、测试和统计
### 显著性检验
使用某种评价方法对比两个不同检索算法产生的排序结果。零假设：两个检索算法在效果评价方面有什么差别。

表8-6 针对10个查询，“B-A”列出两个算法之间效果评价值的不同

| 查询 | A | B | B-A |
| --- | -- | -- | -- |
| 1 | 25 | 35 | 10 |
| 2 | 43 | 84 | 41 |
| 3 | 39 | 15 | -24 |
| 4 | 75 | 75 | 0 |
| 5 | 43 | 68 | 25 |
| 6 | 15 | 85 | 70 |
| 7 | 20 | 80 | 60 |
| 8 | 52 | 50 | -2 |
| 9 | 49 | 58 | 9 |
| 10 | 50 | 75 | 25 |

#### t检验(t-test)
t检验首先假定采样的数值符合正态分布。这种假设指的是这两种算法的效果评价值之间的差值是正态分布的一个样例。这种情况下的零假设是指效果评价值之间的差值分布的平均值为0。

- $\bar{B-A}=21.4$
- $\sigma_{B-A}=29.1$
- $t=2.33$

对于单侧检验，p-value=0.02，这在假设$\alpha=0.05$时，可以证明这两个算法的差别是显著的。因此，t检验可以否定零假设，并得出B比A有效的论证。

#### 威氏符号秩次检验(Wilcoxon signed-rank test)
假定算法A和B之间的效果评价值的差值可以被排序，但是差值的尺度并不重要。

表8-6 9个非0的差值，将它们的绝对值进行排序：

```
2,9,10,24,25,25,41,60,70
```

相应的符号秩次为：

```
-1,+2,+3,-4,+5.5,+5.5,+7,+8,+9
```

排序值累加，得到w=35。对于单侧检验而言，获得p-value=0.025，这在假设$\alpha=0.05$时，否定零假设。

#### 符号检验(sign test)
零假设是指$P(B>A)=P(A>B)=\frac{1}{2}$，这意味着显示B比A“好”的数据对的数量和A比B“好”的数据对的数量是相同的。


### 设置参数值
- 交叉检验(cross-validation)
- 强制法(brute-force)，穷举可能的参数
- 最优化技术

### 在线测试
- 优点
  - 允许真实用户参与到系统中。
  - 并不片面，这是因为这种评价方法是在真实的用户数据集上进行的。
- 缺陷
  - 采集的数据噪声比较大。
  - 使得实时通讯量以一种不利的方式进行潜在的改变（有可能大幅度降低检索的效果，从而导致用户的离开）。

# 分类与聚类
## 分类
### 朴素贝叶斯
$P(C|D)=\frac{P(D|C)P(C)}{P(D)}=\frac{P(D|C)P(C)}{\sum_{c \in C}P(D|C=c)P(C=c)}$

垃圾邮件分类场景：

- D：文档
- C：类别（垃圾邮件或者非垃圾邮件）

给定文档d（随机变量D的一个输出）以及类别集合$C=c_1,\cdots,c_N$（随机变量C的输出），可以用贝叶斯规则计算文档d属于每一个类别$c_i$的可能性$P(c_1|d),\cdots,P(c_N|d)$，然后可以将文档d标注为概率最大的那一类。对文档d的贝叶斯分类：

$Class(d)=arg\ max_{c \in C}P(c|d)=arg\ max_{c \in C}\frac{P(d|c)P(c)}{\sum_{c \in C}P(d|c)P(c)}$

估计先验概率P(c):$P(c)=\frac{N_c}{N}$

- $N_c$：训练样本中已经标注为c的样例
- N：训练样本总数

估计P(d|c):

简化（naive）：文档d可以归结为元素（term）的集合。假设元素（term）之间彼此是独立的。$P(d|c)=\prod_{i=1}^n P(w_i|c)$

因此，需要估计在词表V中的每个词在每个类c的概率$P(w_i|c)$

P(c|d)改写为：$P(c|d)=\frac{P(d|c)P(c)}{\sum_{c \in C}P(d|c)P(c)}=\frac{\prod_{i=1}^VP(w_i|c)P(c)}{\sum_{c \in C}\prod_{i=1}^V P(w_i|c)P(c)}$

剩下的事情就是描述如何估计P(w|c)。

#### 1.多重伯努利模型
给定一个类c，为在词表中的每一个term定义一个二值随机变量$w_i$。概率$P(w_i=1|c)$可以解释为“类别c生成wi的概率”。$P(w_i=0|c)$可以解释为“类别c不生成wi的概率”。

用最大似然估计来估计概率：$P(w|c)=\frac{df_{w,c}}{N_c}$

- $df_{w,c}$是在类别c中包含w的文本数量
- $N_c$是训练样本中类别c的文本数量

采用多重伯努利模型，文档的似然估计P(d|c)写为：$P(d|c)=\prod_{w \in V} P(w|c)^{\delta(w,d)}(1-P(w|c))^{1-\delta(w,d)}$

- $\delta(w,D)$为1，当且仅当w在文档d中。

训练数据稀疏->零概率问题->贝叶斯平滑：$P(w|c)=\frac{df_{w,c}+\alpha_w}{N_c+\alpha_w+\beta_w}$

- $\alpha_w,\beta_w$是依赖于w的参数。
- 一种选择是对所有的w设置$\alpha_w=1,\beta_w=0$，得到估计：$P(w|c)=\frac{df_{w,c}+1}{N_c+1}$
- 另一个选择是对所有w设置$\alpha_w=\mu \frac{N_w}{N},\beta_w=\mu(1-\frac{N_w}{N})$，这里$N_w$是训练文本中包含w的所有文本数，$\mu$是可调参数。得到估计：$P(w|c)=\frac{df_{w,c}+\mu \frac{N_w}{N}}{N_c+\mu}$

#### 2.多项式模型
多重伯努利模型假定词的频率是二值的（“词出现”、“词不出现”），多项式模型假定词的出现是零或者多次（“词出现0次”、“词出现1次”...）。

最大似然估计：$P(w|c)=\frac{tf_{w,c}}{|c|}$

- $tf_{w,c}$是训练集中类别c中w出现的次数。|c|表示训练集中类别c中词的总数。

由于词是根据多项式分布来描述，对于给定类别c，文本的最大似然估计：$P(d|c)=P(|d|)(tf_{w_1,d},tf_{w_2,d},\cdots,tf_{w_V,d})!\prod_{w \in V} P(w|c)^{tf_{w,d}} \propto  \prod_{w \in V} P(w|c)^{tf_{w,d}}$

- $tf_{w,d}$是文档d中w的出现次数
- |d|是文档d中的总词数
- P(|d|)是长度为|d|的文本的生成概率
- $(tf_{w_1,d},tf_{w_2,d},\cdots,tf_{w_V,d})$是多项式系数
- P(|d|)及多项式系数是依赖于文档的，对于分类，可以忽略

词似然的贝叶斯平滑估计：$P(w|c)=\frac{tf_{w,c}+\alpha_w}{|c|+\sum_{w \in V}\alpha_w}$

- $\alpha_w$是依赖于w的参数
- 对所有的w设置$\alpha_w=1$，得到估计：：$P(w|c)=\frac{tf_{w,c}+1}{|c|+|V|}$
- 设置$\alpha_w=\mu\frac{cf_w}{|C|}$，这里$cf_w$是在训练集中w出现的次数，|C|是训练集中词的总数，$\mu$是可调参数，得到估计：：$P(w|c)=\frac{tf_{w,c}+\mu\frac{cf_w}{|C|}}{|c|+\mu}$，即Dirichlet平滑语言模型估计

### SVM
SVM的目标是发现一个分离正例和反例的超平面。

#### 1.线性可分数据
最大化分离定义：假设$x^-$是训练集中与超平面最近的反例，$x^+$是训练集中与超平面最近的正例，定义边缘（margin）为$x^-$到超平面加上$x^+$到超平面的距离。边缘可以计算如下：

$Margion(w)=\frac{|w \cdot x^-|+(w \cdot x^+)}{\lVert w \rVert}$

为了简化问题，通常假设$w \cdot x^- =-1,w \cdot x^+=1$，这个假设不能改变对问题的解法，使边缘等于$\frac{2}{\lVert w \rVert}$。另一个等价的公式：

$min:\ \frac{1}{2}\lVert w \rVert^2$

subject to:

$w \cdot x_i \ge 1 \forall i\ s.t.\ Class(i)=+$

$w \cdot x_i \le -1 \forall i\ s.t.\ Class(i)=-$

#### 2.线性不可分
惩罚因子（关键损失函数）：

$$L(x)=
\begin{cases}
max(1-w \cdot x,0)& if\ Class(i)=+\\\\
max(1+w \cdot x,0)& if\ Class(i)=-
\end{cases}$$

这个损失函数合并进SVM最优化如下：

$min:\ \frac{1}{2}\lVert w \rVert^2+C\sum_{i=1}^N \xi_i$

subject to:

$w \cdot x_i \ge 1-\xi_i\ \forall i\ s.t.\ Class(i)=+$

$w \cdot x_i \le -1+\xi_i\ \forall i\ s.t.\ Class(i)=-$

$\xi_i \ge 0\ \forall i $

这里$\xi_i$称为允许目标值被违反的松弛变量。

#### 3.核技巧
在线性不可分的情况下，将它们变换或映射到高维空间，得到线性可分的点的集合。

#### 4.非二分类
- One vs All，OVA：假设K大于2，训练K个分类器，每次将第k类看作正例，其他所有类看出反例。x被划分到的类别是分类器的值$w \cdot x$中最大的那一类。
- One vs One，OVO：对所有的分类K训练全组合个分类器（K(K-1)/2），每一次x被划分到c类，对c的投票被记录，最后，x被划分到具有最多投票的类别中。

### 评价
详见第8章。

### 分类器和特征选择
1. 生成模型
    1. 贝叶斯分类器
    1. 首先根据P(c)生成一个类，然后根据P(d|c)生成文档。生成模型模仿人类实际生成（撰写）文档的方式。
1. 判别模型
    1. SVM分类器
    1. 不会去模拟文本和类别的生成过程，而是直接模拟对给定的输入文本赋予类别。
1. 非参数分类器
    1. knn分类器
    1. 去除所有分布假设让数据“自己说话”。
1. 特征选择
    1. 目的是在最初的特征空间中，找到能够代表原特征空间的主要特征的特征子集，这既能提高效率同时又不会过多地影响其有效性。
    1. 信息增益（information gain）是文本分类中应用最广泛的特征选择方法。
    1. 特征f的信息增益度量的实现f之后P(C)的熵的变化：$IG(w)=H(C)-H(C|w)=-\sum_{c \in C}P(c)log P(c)+\sum_{w \in\{0,1\}}P(w)\sum_{c \in C}P(c|w)logP(c|w)$
        1. H(C)是P(C)的熵
        1. H(C|w)称为条件熵

### 垃圾、情感及在线广告
1. 垃圾
    1. 垃圾邮件
    1. 垃圾广告
    1. 垃圾网页
        1. 链接垃圾：垃圾信息制造者用各种办法人为地提高他们网页的链接分值。
        1. 词垃圾：试图改变文本的表示，以便能被某些查询或者关键词检索。
            1. 倾销：用许多不相关的词（常常是整个词典）填充文本，导致文本被任何查询检索，因为几乎包含了查询词的每一种组合，这起到了加强召回率的作用。
            1. 短语拼接：从多种来源合并词和句子。
            1. 编织：将垃圾词加入到有效的文本中，如新闻故事。
1. 情感：词汇线索确定感情。
    1. 正面情感指示词：“great”、“nice”、“amazing”
    1. 负面情感指示词：“awful”、“terrible”、“bad”
1. 分类广告
    1. 将查询或网页正文的文本项划分为语义层次，这个层次由手工构建，包括6000多个节点，每一个节点代表一个独立的语义类，层次越深，类别约明确。
    1. 对广告清单中的每一个广告进行预分类。

## 聚类
### 层次聚类和K均值聚类
层次聚类分为两类：

1. 分裂聚类：自顶向下的方法，从一个包含所有实例的簇开始。每一次迭代时，它从现有的簇中选择一个簇分成两个簇。不断进行这个过程，直到总共产生K个簇。
1. 聚合聚类：自底向上的方法。每次将两个现有的簇合并成一个新的簇。当剩余K个簇时，算法停止。

K均值聚类：保持K个簇不变，每次迭代中，每个实例要么保留在原有簇中，要么被分配到一个其他的簇中。这个过程不断重复，直到满足停止要求。

### K近邻聚类
层次聚类和K均值聚类的特点是：簇之间不重叠。K近邻聚类，围绕每个实例形成一个簇。对于输入实例x，根据某个距离衡量标准，距离x最近的K个点和x本身构成一个簇。实际上每一个输入实例都对应一个簇，因此会产生N个簇。

# 社会化搜索
## 用户标签和人工索引
### 搜索标签
- 挑战
  - 对于复杂项目，标签是非常稀疏的表示方式。查询关键词与标签关键词之间没有重叠（词表不匹配（vocabulary mismatch）问题）。解决办法：1.提取词干；2.通过伪相关反馈丰富稀疏标签
  - 标签内含噪声。由于是由用户创建的，这些标签可能是偏离主题的、不适当的、拼写错误的甚至是垃圾信息。

### 推测缺失的标签
- 对出现在文本中的每一个词项计算权重，然后选择k个权值最高的词项作为预测的标签。如tfidf。
- 标签推测问题也视为分类问题。给定标签的固定本体或大众分类，目标是为每一个标签训练出一个二元分类器。
- 新颖性（novelty）问题：选择既相关又不冗余的标签。
  - 最大边缘相关（maximal marginal relevance，MMR），MMR选择标签时，标签之间不是彼此独立，而是迭代地选择标签，一次为项目添加一个标签。给定一个项目i及相应的标签集合Ti，MMR选择下一个标签时，最大化公式：$MMR(t;T_i)=(\lambda Sim_{item}(t,i)-(1-\lambda)max_{t \in T_i}Sim_{tag}(t_i,t)$
    - $Sim_{item}$ 度量标签t与项目i相似度的方程。
    - $Sim_{tag}$ 度量两个标签间的相似度。
    - $\lambda$平衡相关性($\lambda=1$)和新颖性($\lambda=0$)。

### 浏览和标签云
标签云：描绘标签的流行度或重要性。

## 社区内搜索
### 什么是社区
在线社区可以由用户、组织、网页或任何有意义的在线实体构成。

### 社区发现
- 发现社区的两个标准。一是这组实体（节点）之间按照某些相似度度量必须彼此相似。二是这组实体之间的交互多于其他实体的交互。
- 给定一个实体图，必须识别出一个实体子集，该子集内节点可能是社区成员。我们称这些实体为候选实体（candidate entity）。
- HITS算法

### 基于社区的问答
- 优点为针对复杂或晦涩的信息需求，用户可以得到答案，能够看到关于同一主题的不同观点，可以与其他具有共同兴趣、问题或目标的用户进行交流。不足之处在于，对于某一问题，可能没有任何回复，需要等待很长时间（几天）才能获取答案，以及得到的答案可能是错误的、误导的、冒犯的甚至是无用的垃圾。
- 研究表明，低质量的答案往往是回答低质量的问题。

### 协同搜索
协同搜索使一组具有相同搜索目的的用户共同搜索。

## 过滤与推荐
### 文档过滤
- 两个主要组成部分。首先，用户的长期信息需求必须精确地表示。另外，对于新来的文档，必须采用一种决策机制来判别哪些描述文件与该文档相关。
- 用户的长期信息需求通常称为过滤描述文件（filtering profile）或描述文件（profile）。
- 两种典型的过滤模型。一种是静态模型，静态模型是指用户的描述文件不随时间改变，因为模型一直被使用。第二种称为自适应模型，指用户描述文件随时间变化。

### 协同过滤
考虑描述文件（或用户）之间的关系，并且利用这些信息改善进入的项目与描述文件（或用户）间匹配的过滤技术，称为协同过滤。

## P2P搜索与元搜索
- 元搜索引擎从不同的搜索引擎采集相对小规模的搜索结果，并将搜索结果融合以获得更好的搜索效果。
- 一个P2P搜索应用则通常拥有大批节点，每一个节点有相对较小的数据，而且对其他节点的情况知之甚少。

