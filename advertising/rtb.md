# 程序化购买的历史沿革及展望
## Ad Network
广告网络的主要交易模式是集中单个或多个媒体的剩余流量，以非常低的折扣价卖给广告主。另外也提供一些自动化的手段帮助众多的供需双方降低对接成本。

主要分三种类型：
- 全盲投
- 纵向行业联合
    - 纵向联合广告（Vertical Cooperative Advertising）是指纵向的两个企业(比如联想和 Intel)联合在一起共同宣传二者产品的广告。
- 人群定向

优缺点：
- 优点
    - 解决媒体的变现需求。
- 缺点
    - 价格和质量不透明
        - ad network在CPM和CPC之间做套利，从媒体那拿走的相当多的利润。
        - 以次充好，用劣质流量替代优质流量（坑广告主）。
    - 相同的媒体流量会在ad network上以低价出现，使得广告主在有可能的情况下，会尽量到adnetwork上购买，毫无疑问会和媒体现有销售渠道冲突。
    - 由于广告主对最终的投放渠道没有清晰的了解，造成他们无法对投放策略做进一步的优化。

## Ad Network优化
对于传统的ad network，他们没有义务也不想消化某个媒体的全部剩余流量。通常情况下，他们多半只是抽取每个媒体的一部分流量，例如某个特定的地域，时段或者用户频率聚合后在打包出售。这就意味着**对媒体来说并没有从根本上解决填充率的问题。**

演变出一个供应方平台SSP的产品：通过高效的协调供需双方的要求，达到媒体的收益最大化。

- 为媒体提供价格，品牌以及防作弊的保护
- 洞察广告主的需求
- 协调媒体和广告主之间的直销渠道

## RTB（Real Time Bidding）
程序化购买实际上是个更广泛的概念，多数时候是泛指由技术支持的，对购买过程进行自动化的技术的总称。

RTB的核心思想
- 透明
- 公平
- 效率

RTB身后的驱动力
- 计算和存储成本的持续下降
- 数据分析能力的大幅提高
- 市场碎片化催生技术整合
- 流动性促进市场价值的充分体现
    - RTB技术可以帮助我们建立一个交易平台，在这个平台上供求双方可以高效的交互，以充分的流动性来体现双方的需求价值，最终达到一个双赢的局面。

## 国内程序化购买现状
- 竞争激烈的DSP市场
    - 买方市场:在整个市场逐渐向程序化购买倾斜的趋势下，谁拥有客户就有话语权。
- 蓄势待发的移动端
    - 从现在看主要的竞争还局限于移动adnetwork，但这也意味着一旦移动端有了商业模式的突破，多半会在O2O领域，我们会看见从adnetwork到RTB的快速转变。

![](http://ou8qjsj0m.bkt.clouddn.com//18-1-31/4600210.jpg)

## 妨碍市场发展的阻力
RTB/adexchange的模式从某种程度上解决了填充率和运营效率。但在其他方面暴露出来的问题也在阻碍他的进一步发展。
- 公开市场上的流量总体质量偏低
    - 大量的剩余流量进入公开交易市场对媒体的直销渠道造成很大影响，特别是在没有有效的价格控制机制的情况下。
    - 不像在美国有相当数量的独立的中小媒体，中国的媒体相当比较集中，垄断对他们来说是一项非常重要的资源。造成的现状是公开市场上大量充斥了长尾流量，公开市场的总体质量偏低。
- 无法有效解决市场的透明度
    - 透明是一个公开市场的必有元素。但很可惜的是透明度还是RTB市场的主要问题，主要原因是相当多的作弊流量。
    - 在中国，大多数DSP是由传统的adnetwork演变而来，有着自己的投放系统，多数情况下DSP和network流量并存，现在很多DSP又有自己的DMP，所以很多DSP都是对广告主提供一站式的服务，但问题是在这种情况下广告主对真正的ROI更是没有清晰的了解。
- 数据的隐私和泄露问题
    - 随着整体网上行为的增多，隐私意识也会逐步建立，政策法规也会相应完善。
    - 现在很多媒体开始意识到这些数据的价值，但又没有有效的手段来变现，所以更多时候不太愿意和广告主分享他们的用户数据。

## 拥抱程序化购买，提供全方位售卖渠道
- 私有市场形成的必然性
    - 今天股票交易市场的一个现状是大概只有50%的交易是在公开市场上完成的，而剩下的则是在券商内部直接消化掉了（darkpool)。形成这个情况的原因主要有对供需双方的控制，赚取差价，节省交易费。这些在广告交易的模式里都可以找到相应的概念。(从adnetowrk到adexchange的发展路程是基本吻合)
- 公开市场上的流量质量低到无法满足广告主的投放需求
- 媒体全面走向程序化的趋势

这里看一张IAB提供的数据图，说明CPM在销售中的分布情况。可以看见一个典型的的CPM，媒体只拿到50%多一些。剩下的都被其他环节层层盘剥掉了。

![](http://ou8qjsj0m.bkt.clouddn.com//18-1-31/21121335.jpg)

## 数据为依托，多屏/跨屏的投放渠道
- 媒体数据的潜在价值
    - 很多DSP都同时拥有自己的DMP，因为竞争关系，使得DMP之间无法做到有效的数据共享。
    - 媒体可以提供用户的人口属性，注册数据等对于DSP都是非常有价值的。另外媒体的数据会比第三方DMP的更有专属性。
- 媒体作为数据供应商的独特地位
    - 在一个理想的“精准投放”的情况下，很多传统的品牌指标是DSP难以提供的。
- 多种投放渠道的涌现
    - 大量的设备都可以具备连接互联网的功能。包括可穿戴设备，智能汽车，智能家居等。对于数字营销人来说，这意味着我们有更多的渠道接触我们的受众。
- 数据是整合多屏资源的关键
    - 跨屏比多屏更重要。
    - 跨屏的难度在于有效的关联用户在各个碎片化渠道上的行为，这一点对DSP来说更是困难，数据在物理上的隔离使得他们无法在跨越多设备做用户数据的整合。
    - 媒体在这方面的优势在于作为多个渠道的拥有者，他们有能力做到后台数据的打通。