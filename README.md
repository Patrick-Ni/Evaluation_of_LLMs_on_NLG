# Evaluation_of_LLMs_on_NLG
Evaluation of LLMs on NLG benchmarks.

## What is NLG?

Natural Language Generation (NLG) is the process of producing a natural language text to meet specified communicative goals. The texts that are generated may range from a single phrase given in answer to a question, through multi-sentence remarks and questions within a dialog, to full-page explanations.

## Tasks and Datasets

### Text Summarization

| Language | Dataset                                                      | Paper                                          | Download                                                     |
| -------- | ------------------------------------------------------------ | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | CNN/DailyMail                                                | [Link](https://arxiv.org/pdf/1602.06023v5.pdf) | [Link](https://github.com/abisee/cnn-dailymail)              |
|          | XSum (Extreme summarization)                                 | [Link](https://arxiv.org/pdf/1808.08745v1.pdf) | [Linvhok](https://github.com/EdinburghNLP/XSum/tree/master/XSum-Dataset) |
| Chinese  | 清华新闻                                                     | --                                             | [原始数据](http://thuctc.thunlp.org/) [处理后数据](https://pan.baidu.com/share/init?surl=a-CUtTc5xQFB9_EJaxDklA) 取码：vhol |
|          | 微博摘要                                                     | --                                             | [原始数据](https://www.jianshu.com/p/8f52352f0748?tdsourcetag=s_pcqq_aiomsg) [处理后数据](https://pan.baidu.com/share/init?surl=80aTaZe-5jopVBBJhBrTWg) 提取码：duba |
|          | [中文摘要数据集汇总](https://zhuanlan.zhihu.com/p/341398288) |                                                |                                                              |



### Open-domain Dialogue System

| Language | Dataset              | Paper                                          | Download                                                     |
| -------- | -------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | DailyDialog          | [Link](https://arxiv.org/pdf/1710.03957v1.pdf) | [Link](http://yanran.li/dailydialog)                         |
|          | PersonaChat          | [Link](https://arxiv.org/abs/1801.07243)       | [Link](https://www.kaggle.com/datasets/atharvjairath/personachat) |
|          | Empathatic Dialogues | [Link](https://arxiv.org/abs/1811.00207)       | [Link](https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai) |
| Chinese  | 清华LCCC             | [Link](https://arxiv.org/abs/2008.03946)       | [Link](https://github.com/thu-coai/CDial-GPT)                |
|          | 微博对话语料         | --                                             | [Link](https://github.com/codemayq/chinese_chatbot_corpus)   |
|          | CrossWoz             | [Link](https://arxiv.org/abs/2002.11893)       | [Link](https://github.com/thu-coai/CrossWoz)                 |



### Story Generation

| Language | Dataset        | Paper                                                        | Download                                                     |
| -------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| English  | ROCStories     | [Link](https://aclanthology.org/N16-1098.pdf)                | [Link](https://cs.rochester.edu/nlp/rocstories/)             |
|          | WritingPrompts | [Link](https://arxiv.org/pdf/1805.04833v1.pdf)               | [Link](https://www.kaggle.com/ratthachat/writing-prompts)    |
| Chinese  | LOT            | [Link](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00469/110537/LOT-A-Story-Centric-Benchmark-for-Evaluating) | [Link](https://cloud.tsinghua.edu.cn/d/0cf033b0c7c049be855d/) |



### Data-to-Text

| Language | Dataset  | Paper                                          | Download                                                  |
| -------- | -------- | ---------------------------------------------- | --------------------------------------------------------- |
| English  | WebNLG   | [Link](https://aclanthology.org/P17-1017.pdf)  | [Link](https://webnlg-challenge.loria.fr/)                |
|          | ToTTo    | [Link](https://arxiv.org/pdf/2004.14373v3.pdf) | [Link](https://github.com/google-research-datasets/totto) |
|          | Rotowire | [Link](https://arxiv.org/pdf/1707.08052v1.pdf) | [Link](https://github.com/harvardnlp/boxscore-data)       |



### Text-to-SQL

| Language | Dataset | Paper                                               | Download                                                     |
| -------- | ------- | --------------------------------------------------- | ------------------------------------------------------------ |
| English  | WikiSQL | [Link](http://arxiv.org/abs/1709.00103)             | [Link](https://github.com/salesforce/WikiSQL)                |
|          | Spider  | [Link](https://arxiv.org/abs/1809.08887)            | [Link](https://github.com/taoyds/spider)                     |
|          | SEDE    | [Link](https://arxiv.org/pdf/2106.05006v1.pdf)      | [Link](https://github.com/hirupert/sede)                     |
| Chinese  | CSpider | --                                                  | [Link](https://github.com/taolusi/chisp)                     |
|          | Chase   | [Link](https://aclanthology.org/2021.acl-long.180/) | [Link](https://github.com/xjtu-intsoft/chase/tree/page/data) |



### LLMs

- [ChatGPT](https://chat.openai.com/auth/login) through APIs
- [Vicuna-13B](https://github.com/lm-sys/FastChat)
- [LLaMa-13B](https://github.com/facebookresearch/llama)
- [FastChat-T5-3B](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0)
- [Alpaca-13B](https://github.com/tatsu-lab/stanford_alpaca)
- [Dolly-12B](https://huggingface.co/databricks/dolly-v2-12b)
- [ChatGLM-6B](https://huggingface.co/THUDM/chatglm-6b)
- [Oasst-Pythia-12B](https://huggingface.co/OpenAssistant)
- GPT4ALL
- Open-LLaMA
