# DeepSeek | 中文官网、DeepSeek网页版、API 调用和本地部署教程 | 最全使用指南~ 【2025年3月更新】

> 更新：2025/03/01        

轻松使用 **DeepSeek 网页版**，**快速稳定、不卡顿**，**支持 DeepSeek R1 满血版 以及 ChatGPT o1、o3 大模型**。   
本指南提供全面的 **DeepSeek 使用说明**，包含[**DeepSeek 官网平替**](https://chat.yixiaai.com)、[**DeepSeek网页版**](https://chat.yixiaai.com)、**API使用**、**DeepSeek 本地部署教程**，助您顺畅使用 DeepSeek 和 ChatGPT ~

---

## DeepSeek 是什么？

**DeepSeek** 是由深度求索（DeepSeek）自主研发的高性能大语言模型，以其开源、轻量化和强大的多场景适应能力受到广泛关注。   

为用户提供**智能对话、推理、AI搜索、文件处理、翻译、解题、创意写作、编程**等多种服务。   

最新发布的 DeepSeek R1 满血版不仅在性能上媲美了 OpenAI 的 o1、o3，且以对手 3% 的超低成本实现了这一突破。

## DeepSeek 官网

* **DeepSeek 网页版：**[官网【总是繁忙】](https://www.deepseek.com/)  、  [🔥官网平替（快速稳定）](https://chat.yixiaai.com)
* **DeepSeek 客户端：**[访问](https://download.deepseek.com/app/)
* **DeepSeek API：**[访问](https://platform.deepseek.com/)
* **服务器繁忙？查看状态：**[访问](https://status.deepseek.com/)

## 已接入 DeepSeek R1（官方平替）

* **🔥AI智慧岛：**[chat.deepseek-free.org](https://chat.yixiaai.com) - **DeepSeek网页版**，支持 **DeepSeep R1满血版**、V3模型~
* **🔥一下 AI：**[www.yixiaai.com](https://www.yixiaai.com/) - **AI大模型**，支持DeepSeek、ChatGPT 和 Claude最好的模型
* **秘塔 AI：**[访问](https://metaso.cn/)
* **纳米 AI：**[访问](https://www.n.cn/)
* **Cursor：**[访问](https://www.cursor.com/)
* **POE：**[访问](https://poe.com/DeepSeek-R1)
* **国家超算互联网：**[访问](https://chat.scnet.cn/)

## DeepSeek 入门指南

* **🔥清华大学 《DeepSeek 从入门到精通》：**[PDF](https://mp.weixin.qq.com/s/urum7plpWBxFPlBEnLNaLA)
* **DeepSeek 提示库：**[访问](https://api-docs.deepseek.com/zh-cn/prompt-library/)

---

## DeepSeek 的模型介绍：

- **DeepSeek LLM**：基础大型语言模型系列，含7B和67B规格。其中DeepSeek LLM 7B Chat是7B规格聊天交互模型，DeepSeek LLM 67B Chat是67B规格聊天交互模型，还推出了性能超其他开源模型的16B参数版本混合专家模型。
- **DeepSeek-Coder**：专为代码生成打造的模型，专注于代码生成、补全、修复及数学推理任务。其升级版本DeepSeek-Coder V2在代码智能领域有显著突破。
- **DeepSeek-Coder V2**：在 DeepSeek-V2 中间检查点基础上，额外预训练了 6 万亿 tokens 的代码和自然语言数据，显著增强了编码与数学推理能力，同时保持通用语言任务的表现。其支持的编程语言从 86 种扩展至 338 种，覆盖主流及小众语言，适应多样化开发需求。DeepSeek-Coder-V2 凭借其 MoE 架构、大规模预训练和多语言支持，成为代码智能领域的标杆开源模型。其在编码、数学推理和通用任务中的表现，挑战了闭源模型的垄断地位。
- **DeepSeek-V2**：发布于2024 年上半年，DeepSeekMoE的改进版，采用更多数据，提升数据质量并优化了训练流程，专注于文本生成、代码生成和低成本训练。
- **DeepSeek-V2.5**：是 V2 系列的升级版本，于 2024 年 9 月发布，介于 V2 和 V3 之间。
- **DeepSeek-V3**：发布于2024 年 12 月，第三代模型，性能强劲。通过 FP8 混合精度训练、无辅助损失负载均衡等技术创新，V3 实现了高效训练与推理，并支持 128K 长上下文处理。V3 的生成速度从 V2 的 20 TPS 提升至 60 TPS，速度提升 3 倍。V3在知识问答、长文本处理、代码生成等领域表现超越其他开源模型，并在数学竞赛中超越闭源模型如 GPT-4o。该模型推出后，在开放源代码模型中位居榜首。
- **DeepSeek-R1**：**R1满血版**，专注于推理能力的模型，通过强化学习与多阶段训练流程深度优化。包括DeepSeek-R1-Zero，是早期版本，完全基于强化学习训练；还有DeepSeek-R1-32B，有320亿参数，可在24GB显存显卡上流畅运行；DeepSeek-R1-8B有80亿参数，适用于8GB显存显卡。
- **DeepSeek-VL**：视觉语言模型，能处理图像与文本信息融合，DeepSeek-VL2是其升级版，多模态理解能力更强。
- **DeepSeekMath**：专注于数学推理的模型。
- **DeepSeek-Prover**：用于定理证明的模型，通过大规模合成数据训练，DeepSeek-Prover V1.5结合强化学习与蒙特卡洛树搜索技术进行了优化。
- **Janus-Pro-7B**：基于视觉的模型，于2025年1月27日推出。

## DeepSeek 的主要功能：

- **智能对话**：能与用户进行高智商、顺滑的对话，像朋友一样交流，为用户答疑解惑。
- **AI搜索**：可全网搜索，让用户实时掌握信息，无论是知识查询还是热点追踪，都能快速搞定。
- **文件上传**：支持上传文献书籍、资料报告等各类文件，帮助用户梳理重点，快速提取关键信息。
- **准确翻译**：提供准确流畅的翻译服务，帮助用户跨越语言障碍，轻松融入多语言环境。
- **智能解题**：可以解决理科难题，提供详细的解题思路和步骤，是学习的好帮手。
- **创意写作**：能根据指令自动生成创意文案，撰写各类文章和报告，快速构建内容框架，提升写作效率。
- **高效编程**：支持多种编程语言，可快速定位问题并生成代码，提高编程速度和质量。

---

## DeepSeek 本地部署攻略：

推荐使用 Ollama 工具进行本地部署。Ollama不仅支持 DeepSeek，还可以运行其他多种AI模型~

### 1. 下载 Ollama

首先访问[Ollama官方网站](https://ollama.com)，根据你电脑的系统，下载对应版本的 Ollama，然后安装即可。

Ollama是一个用于本地运行和管理 AI 模型的工具，用于与各种模型进行交互。

[![1](https://chatknow.lify.vip/imgs/ds/1.png)](https://chatknow.lify.vip/imgs/ds/1.png)

你也可以在电脑上看到 Ollama 的图标，双击打开即可。

[![2](https://chatknow.lify.vip/imgs/ds/2.png)](https://chatknow.lify.vip/imgs/ds/2.png)

### 2. 下载 DeepSeek R1 模型

接下来需要打开电脑的终端命令行工具，输入命令 **ollama run deepseek-r1:32b**，后面的是模型尺寸

[![3](https://chatknow.lify.vip/imgs/ds/0.png)](https://chatknow.lify.vip/imgs/ds/0.png)

接着就可以正常下载 DeepSeek R1模型了

[![4](https://chatknow.lify.vip/imgs/ds/4.png)](https://chatknow.lify.vip/imgs/ds/4.png)

### 3. 测试 DeepSeek

下载完成后，直接在终端与 DeepSeek 对话，例如输入：“介绍一下你自己”。然后等待 DeepSeek 思考并回复即可。

[![5](https://chatknow.lify.vip/imgs/ds/3.png)](https://chatknow.lify.vip/imgs/ds/3.png)


### 4. 常用命令
整理一些常用 Ollama 命令，使用时将 {model_name} 替换成具体模型名称

- **安装模型**：ollama pull {model_name}
- **运行模型**：ollama run {model_name}
- **删除模型**：ollama rm {model_name}
- **列出已安装模型**：ollama list

## DeepSeek 模型云部署

* **🔥硅基流动 x 华为云：**[注册](https://cloud.siliconflow.cn/) 
* **微软 Azure：**[注册](https://ai.azure.com/)
* **英伟达 ：**[注册](https://build.nvidia.com/deepseek-ai/deepseek-r1)
* **Cloudflare：**[注册](https://developers.cloudflare.com/workers-ai/models/)
* **Gitee AI：**[注册](https://ai.gitee.com/serverless-api)
* **亚马逊 AWS：**[注册](https://aws.amazon.com/cn/blogs/aws/deepseek-r1-models-now-available-on-aws)
* **阿里云：**[注册](https://pai.console.aliyun.com/#/quick-start/) 、 [教程](https://help.aliyun.com/zh/pai/user-guide/one-click-deployment-deepseek-v3-model)
* **腾讯云：**[注册](https://cloud.tencent.com/product/hai) 、 [教程](https://cloud.tencent.com/developer/article/2492543)
* **百度智能云：**[注册](https://cloud.baidu.com/)
* **火山引擎：**[注册](https://www.volcengine.com/)
* **京东云：**[注册](https://www.jdcloud.com/) 、 [教程](https://docs.jdcloud.com/cn/yanxi-cap/practice-DeepSeek)
* **华为昇腾社区：**[注册](https://www.hiascend.com/software/modelzoo/models) 、 [教程](https://www.hiascend.com/software/modelzoo/models/detail/68457b8a51324310aad9a0f55c3e56e3)
* **联通云电脑：**[注册](https://www.cucloud.cn/product/cuc.html)
* **电信天翼云电脑：**[注册](https://www.ctyun.cn/products/tyydn)
* **移动云：**[注册](https://ecloud.10086.cn/portal)
* **讯飞开放平台：**[注册](https://www.xfyun.cn/)
