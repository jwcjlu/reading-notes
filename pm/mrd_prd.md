# 产品经理的产出是什么？
## 产品设计架构
![1](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/86004303.jpg)

## 最常见的文档类型
- BRD:Business Requirements Document商业需求文档，重点放在定义项目的`商业需求`。
- MRD:Market Requirements Document，市场需求文档，重点放在为一个被提讫的新产品戒者现有产品的改迚定义`市场需求`。 
- PRD:Product Requirements Document，产品需求文档，重点放在为一个被提讫的新产品戒者现有产品的改迚定义`产品功能需求`。 
- FRD:MRD+PRD

## MRD与PRD的关系
- 不同互联网公司使用不同的文档类型，如阿里巴巴、通讯、 雅虎等，使用的是FRD文档
- MRD侧重客户、用户、市场需求的定义，通过原型的形式加以形象化，PRD侧重产品流程、功能和性能的说明， PRD文档是对MRD文档进行指标化和技术化的
- 例:
    - MRD:给客人烧一桌荤素搭配、富有营养的菜;
    - PRD:原料、操作步骤、数量、营养成分等;

# 如何写好MRD
## MRD的意义和作用
- 作用:实际意义上产品生命周期阶段的第一个文档，作用是对产品中进行市场层面的说明，直接影响到产品项目的开展，直接影响公司产品戓略的实现。
- 意义:是对市场需求的整理和记录，对整个产品过程中具有工作指导意义。
- 读者:VP、PM、RD、QA
- 重点:需求的阐述和分析，不是需求的实现。

![2](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/59697199.jpg)

![3](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/46781040.jpg)

![4](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/22039273.jpg)

![5](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/96593163.jpg)

![6](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/86406570.jpg)

## MRD撰写总结 
- MRD:市场需求文档
    - 我真的知道我要面对的市场是什么吗? 
    - 我真的知道市场的需求是什么吗?
    - 我真的知道文档的作用吗?
- MRD:多种PM工具和思想的应用
    - SWOT分析
    - Marketing思想
    - 原型塑造法
    - 市场细分矩阵
    - 目标客户矩阵确定法 
    - ......
- MRD:内容精炼但不缺失 
- MRD:结构简单但逻辑严密

## 最重要的是?
![7](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/86867798.jpg)

# 如何写好PRD
## PRD的意义和作用
- 作用:一个PRD是衡量一个产品经理整体思维的标准，一个PRD可以看出一个产品经理在某个领域的专业性。利于开发过程中开发人员评估工作量，利于大家对各功能点跟踪，利于测试时对产品功能全覆盖
- 意义:是对MRD文档的内容的技术化和指标化，贯穿产品生命周期，质量好坏直接影响到研发部门是否能够明确产品的功能和性能
- 读者:PM、RD、QA、UI、UE......
- 重点:对产品功能和性能(即“产品需求”)的详细与业说明

## 搭建框架
将产品所有功能迚行合理分觋和排序，确定PRD各节标题。

- 基本规则:
    - 按界面元素分解:上—>下，左—>右
    - 按用户操作步骤分解:提交—>展示—>展示后编辑
    - 按在系统中所处位置分解:前台—>用户管理后台—>系统管理后台
    - 按功能主次分解:主要功能—>次要/附加功能
- 基本内容
    - 产品目标(vision)
    - 目标市场和用户(target market & users)
    - 竞争对手分析(competitive summary)
    - 产品主要功能说明(feature list)
    - 功能优先级
    - 实现进度安排
    - 用例(use cases)
    - 产品非功能性需求

![8](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/56954346.jpg)

## 梳理主线
按照确定的PRD章节顺序，用`关键示例图+简要文字`描述的方式对主要功能点迚行说明
- 关注功能主线，不用过于详细的描述，也不用设计各种特殊状态和细节处理
- 产品包含的主要功能和流程都需要在PRD中完整体现
- 在主要功能点的整理过程中，对PRD的结构进行及时调整
- 完成梳理后与开发人员进行初步沟通

## 填充细节
- 对产品功能和其他相关需求进行完整说明
- 包括所有操作流程、判断逻辑、权限区别、页面 效果、特殊状态处理、错诨提示、已有功能说明等
- 此步骤完成后即可发起PRD评审

**细节说明通常会占到PRD篇幅的70%以上**

## 功能描述
![9](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/67932182.jpg)

![10](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/82595838.jpg)

## 1 从哪来，到哪去
- 页面入口
- 页面title和布局方式
- 页面初始状态
- 页面展现和功能细节，按顺序描述(左右、上下) 
- 个链接点击效果、指向地址、打开方式、刷新方式
- 浮动层整体策略 
    - 是否自动关闭
    - 右上角是否需要关闭按钮，点击效果
    - 若通过浮动层中打开页面，浮动层是否关闭 
    - 关闭后是否刷新页面
- ......

## 2 不要只考虑普通用户
若页面对不同权限用户有不同的展示需求和功能，要完整说明并提供准确的示意图，采用权限表格说明是最好的方式

![11](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/1798734.jpg)

## 3 形成条件反射的错误提示
- 输入为空
- 超过字数上限
- 含特殊字符
- 含非法字符
- 其他输入无效的情况
- 无权限
- ......

## 4 输入框里陷阱多
- 是否可以为空
- 是否有初始内容，是否默认选中
- 大小写/全半角/繁简体是否转换
- 任何输入框都需要字数上限
- 允许的字符集
- 空格出现在收尾和中间部分，或者连续多个空格的各自处理方式
- 多行文本框的连续空行、不连续空行、空格、tab键、回车键的处理方式
- 是否允许快捷键控制

## 5 事情的发展总可能脱离理想状态
对于满足一定条件才有效的功能，需要说明流程中遭遇的各种非正常情况时的处理策略 

例如:签名档不超过5个时，显示“添加一个签名档”链接

![12](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/34590806.jpg)

例如:点击找回密码链接，开始找回密码

![13](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/1646408.jpg)

## 6 不要轻易写“与线上保持一致”
- 升级类的产品戒者日常维护，可以只说明有改劢的部分
- 新产品移植或调用线上已有功能，需重新进行详细描述
- 搜索框、翻页等通用模块，可以不再单独说明
- 拿捏不准时可与项目组同事沟通达成一致

## 7 无结果页/边界限制/统一出错页
- 初始无数据、搜索无结果
- 无论实际上限或理论上限，PRD中最好给出各种边界值，并说明是否需要灵活可配置
- 除已说明的错误提示外，需要给出其他状况下系统的默认出错页
    - 全部页面错误提示 
    - 局部页面错误提示 
    - 操作类错误提示

![14](http://ou8qjsj0m.bkt.clouddn.com//17-8-27/61595239.jpg)

## 8 发布要求需说明
- 是否指定用户开通或分批开通
- 是否新旧版本AB测试
- 是否进行顺序发布
- 是否有其他发布前置条件
- 是否对上线时间有精确要求
- 是否先上线但对用户隐藏入口

## PRD撰写总结 
- PRD:产品需求文档
    - 哪些是核心需求?
    - 满足需求的最佳方式是什么? 
    - 产品流程是否完整?
- PRD:工具可以让工作变得高效，善用但不沉迷
    - Word、Excel
    - Mind Manager
    - Visio
    - Rational Rose
    - Axure RP
    - ......
- PRD:明确需求，用语准确，可维护性强 
- PRD:结构清晰，逻辑严密，可读性强