按照[学习文档](https://github.com/InternLM/Tutorial/blob/camp2/helloworld/hello_world.md)部署

# 部署InternLM2-Chat-1.8B模型
* 1. 配置基础环境
* 2. 下载InternLM2-Chat-1.8B 模型
* 3. 运行 cli_demo

**运行结果**
![chat1.8B](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/chat_1.8B_demo.png?raw=true)

# 实战：部署实战营优秀作品 八戒-Chat-1.8B 模型

**运行结果**
![bajie_chat](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/%E5%85%AB%E6%88%92_chat_demo.png?raw=true)
  
#  使用Lagent运行InternLM2-Chat-7B 模型

![Lagent](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/lagent.png?raw=true)

> Lagent即“ Language Agent”,轻量级、开源的基于大语言模型的智能体框架。
> 
> 理解Agent智能体概念：一个能够执行任务、做出决策、并与用户或环境进行交互的系统。
> 
> 模型是智能体的大脑，他提供了智能体进行决策所需的知识和逻辑。智能体是模型的手脚，它将模型的决策应用到实际的情境中，与用户或环境进行交互。

**运行结果**

![lagent_web_demo](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/lagent_web_demo.png?raw=true)

# 进阶作业 #

## 使用huggingface_python包下载InternLM2-Chat-7B模型和config.json文件到本地 ##

![error](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/download_error.png?raw=true)

>> 多次报同样错，排查之后了解到可能是因为网络原因需要换源，所以在[huggingface镜像站](https://hf-mirror.com/internlm/internlm2-chat-7b)同时下载了模型与json文件。

![download](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/internlm2-chat-7b.png?raw=true)

## 完成浦语·灵笔2的图文创作 

![chuangzuo](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/%E5%9B%BE%E6%96%87%E7%94%9F%E6%88%90.png?raw=true)


## 完成浦语·灵笔2的视觉问答 

![vision](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/%E5%9B%BE%E6%96%87%E7%90%86%E8%A7%A3.png?raw=true)

>模型能力有待加强，除了图片理解偏差之外，前面还有多次回答无法理解图片，在我给出是否能分析图片的prompt之后才开始对图片进行处理。

## 完成Lagent工具调用数据分析Demo部署

![lagent](https://github.com/KJXXbear/InternLM_practice/blob/main/images/ch2/lagent_web_demo.png?raw=true)

