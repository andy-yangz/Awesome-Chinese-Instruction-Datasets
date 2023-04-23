# Awesome Chinese Instruction Tuning Dataset

 ![GitHub stars](https://img.shields.io/github/stars/andy-yangz/Awesome-Chinese-Instruction-Datasets.svg?color=red&style=for-the-badge) 
 ![GitHub forks](https://img.shields.io/github/forks/andy-yangz/Awesome-Chinese-Instruction-Datasets.svg?style=for-the-badge) 
 ![GitHub activity](https://img.shields.io/github/last-commit/andy-yangz/Awesome-Chinese-Instruction-Datasets?color=yellow&style=for-the-badge) 

  [![Star History Chart](https://api.star-history.com/svg?repos=andy-yangz/Awesome-Chinese-Instruction-Datasets&type=Date)](https://star-history.com/#andy-yangz/Awesome-RLHF&Date)


用来训类 ChatGPT 模型的中文指令数据集收集。

数据标签：

- 数据生成方式：
  - HG（Human Generated）：人类生成数据，包括人工标注，以及使用类ChatGPT系统自然获得的数据
  - MG (Machine Generated)：答案是通过机器生成的
  - SI（Self Instruct）：通过 [Self-Instruct](https://arxiv.org/abs/2212.10560) 方法搜集的数据
  - TP (Templated)：抓取一些数据然后通过模板生成的
  - TSL（Translated）：翻译的数据
  - MIX：混合数据

<!-- TOC -->

- [Awesome Chinese Instruction Tuning Dataset](#awesome-chinese-instruction-tuning-dataset)
  - [数据集](#数据集)
    - [Belle|2M|SI](#belle2msi)
    - [Alpaca-GPT4|49k|MG-GPT4](#alpaca-gpt449kmg-gpt4)
    - [COIG|190k|MIX](#coig190kmix)
    - [HC3-ZH|13k|MG-ChatGPT](#hc3-zh13kmg-chatgpt)
    - [MOSS-002-SFT|590k|MG-`text-davinci-003`](#moss-002-sft590kmg-text-davinci-003)
    - [shareGPT\_cn|26k|TSL](#sharegpt_cn26ktsl)
    - [OASST1-zh|2k|HG](#oasst1-zh2khg)

<!-- /TOC -->

## 数据集

### [Belle|2M|SI](https://github.com/LianjiaTech/BELLE)

简介：看数据主要通过 Self-Instruct 生成的两百万指令和回答数据

论文：https://github.com/LianjiaTech/BELLE/tree/main/docs

机构：链家

许可：[gpl-3.0](https://huggingface.co/datasets?license=license:gpl-3.0)

### [Alpaca-GPT4|49k|MG-GPT4](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM/blob/main/data/alpaca_gpt4_data_zh.json)

简介：Alpaca 获得的 ShareGPT 的52k Instruction，通过GPT4进行翻译，然后对 GPT 4 的回答进行抓取

论文：https://arxiv.org/abs/2304.03277

机构：微软

许可：[Apache-2.0 license【](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM/blob/main/LICENSE)

### [COIG|190k|MIX](https://huggingface.co/datasets/BAAI/COIG)

简介：从各个来源比如考试题和 LeetCode 搜集到的通过模板构建，还有翻译英文的 Instruction 数据

论文：https://arxiv.org/abs/2304.07987

机构：智源

许可：Apache 2.0 license

### [HC3-ZH|13k|MG-ChatGPT](https://huggingface.co/datasets/Hello-SimpleAI/HC3-Chinese)

简介：从各个来源如百科、贴吧、法律、金融等网站抓取下来问题，然后抓取 ChatGPT 生成

论文：https://arxiv.org/abs/2301.07597

机构：万得资讯

许可：[cc-by-sa-4.0](https://huggingface.co/datasets?license=license:cc-by-sa-4.0)

### [MOSS-002-SFT|590k|MG-`text-davinci-003`](https://huggingface.co/datasets/fnlp/moss-002-sft-data)

简介：通过 Self-Instruct 构建的 59 万的 SFT 数据，主要用 `text-davinci-003` 接口生成

机构：复旦

许可：[cc-by-4.0](https://huggingface.co/datasets?license=license:cc-by-4.0)

### [shareGPT_cn|26k|TSL](https://huggingface.co/datasets/shareAI/shareGPT_cn)

简介：某热心网友对 shareGPT 的翻译数据

机构：shareAI

许可：[apache-2.0](https://huggingface.co/datasets?license=license:apache-2.0)

### [OASST1-zh|2k|HG](https://huggingface.co/datasets/OpenAssistant/oasst1)

简介：开源 Open Assistant 项目通过页面网友们标注的数据，有小部分中文数据

论文：https://arxiv.org/abs/2304.07327

机构：开源

许可：[apache-2.0](https://huggingface.co/datasets?license=license:apache-2.0)

