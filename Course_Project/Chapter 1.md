# **书生·浦语大模型全链路开源体系**

整体介绍书生·浦语大模型的全链路开源体系

# 大模型是发展通用人工智能的重要途径

目前研究倾向于一个模型应对多模态、多任务场景
![kaiyuan](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch1/1711887032124.png?raw=true)
# 书生·浦语大模型开源历程

* 20230607 InternLM 发布
* 20240117 InternLM2 开源
  
# 书生·浦语 2.0 体系
 面向不同使用需求每个规格包含三个模型版本：InternLM2-Base、InternLM2、InternLM2-Chat
 ![InternLM2](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch1/1711887652238.png?raw=true)
 * 7B
      轻量且性能不俗，适用于研究和应用
 * 20B
      模型综合能力更强，可有效支持更加复杂的使用场景

推荐使用InternLM2作为基座模型进行下游任务微调

**新一代数据清洗过滤技术**
* 多维度数据价值评估
* 高质量语料驱动的数据富集
* 有针对性的数据补齐

# 书生·浦语 2.0 的主要亮点
![liangdian](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch1/1711887932803.png?raw=true)
  在重点能力评测上InternLM2-Chat-20B可以比肩GPT3.5

  * 贴心可靠的AI助手
  * 充满人文关怀的对话
  * 富有想象力的创作
  * 工作调用能力升级
  * 强大的内生计算能力
  * 代码解释器：更上一层楼
  * 实用的数据分析功能
# 从模型到应用典型流程
![liucheng](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch1/1711888473400.png?raw=true)
书生·浦语大模型提供全链路开源开放体系
![kaiyuantixi](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch1/1711888772713.png?raw=true)
**数据集**

[数据集获取](https://opendatalab.org.cn/)

书生·万卷 1.0：符合主流中国价值观的中文语料

总数据量2TB，包含：文本数据集，图像文本数据集，视频数据集

书生·万卷 CC：安全、信息密度更高的英文语料

* 时间跨度长
* 来源丰富多样
* 安全密度高

**预训练**

* 高可扩展
* 极致性能优化
* 兼容主流
* 开箱即用

**微调**

1.增量续训 

  **2.有监督微调**

**评测**

20240130 正式发布司南大模型评测体系 OpenCompass 2.0

* 中立全面的性能榜单
* 大模型评测全栈工具链
* 高质量评测基准社区

**部署**

LMDeploy:提供大模型在GPU上部署的全流程解决方案，包括模型轻量化、推理和服务

**智能体**

轻量级智能体框架 Lagent

支持多种类型的智能体能力

灵活支持多种大语言模型

简单易扩展，支持丰富的工具

* 代码解数学题
* 零样本泛化：多模态AI工具使用
  
多模态智能体工具箱 AgentLego
![AgentLego](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch1/1711890426746.png?raw=true)




















