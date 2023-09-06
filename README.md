# Evaluation_of_LLMs_on_NLG
Evaluation of LLMs on NLG benchmarks.

## What is NLG?

Natural Language Generation (NLG) is the process of producing a natural language text to meet specified communicative goals. The texts that are generated may range from a single phrase given in answer to a question, through multi-sentence remarks and questions within a dialog, to full-page explanations.

## Tasks and Datasets

### Text Summarization

| Language | Dataset                      | Paper                                          | Download                                                     |
| -------- | ---------------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | CNN/DailyMail                | [Link](https://arxiv.org/pdf/1602.06023v5.pdf) | [Link](https://github.com/abisee/cnn-dailymail)              |
|          | XSum (Extreme summarization) | [Link](https://arxiv.org/pdf/1808.08745v1.pdf) | [Link](https://github.com/EdinburghNLP/XSum/tree/master/XSum-Dataset) |
|          | LCSTS                        | --                                             | [原始数据](https://www.jianshu.com/p/8f52352f0748?tdsourcetag=s_pcqq_aiomsg) [处理后数据](https://pan.baidu.com/share/init?surl=80aTaZe-5jopVBBJhBrTWg) 提取码：duba |



### Open-domain Dialogue System

| Language | Dataset              | Paper                                          | Download                                                     |
| -------- | -------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | DailyDialog          | [Link](https://arxiv.org/pdf/1710.03957v1.pdf) | [Link](http://yanran.li/dailydialog)                         |
|          | PersonaChat          | [Link](https://arxiv.org/abs/1801.07243)       | [Link](https://www.kaggle.com/datasets/atharvjairath/personachat) |
|          | Empathatic Dialogues | [Link](https://arxiv.org/abs/1811.00207)       | [Link](https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai) |
| Chinese  | 清华LCCC             | [Link](https://arxiv.org/abs/2008.03946)       | [Link](https://github.com/thu-coai/CDial-GPT)                |



### Controllable Story Generation

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



### Style Transfer

| Language | Dataset | Paper                                                        | Download                                                     |
| -------- | ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| English  | Yelp    | [Link](https://arxiv.org/abs/1705.09655)                     | [Link](https://github.com/shentianxiao/language-style-transfer/tree/master) |
|          | Bible   | [Link](https://royalsocietypublishing.org/doi/full/10.1098/rsos.171920) | [Link](https://github.com/keithecarlson/StyleTransferBibleData) |



### LLMs

- [ChatGPT](https://chat.openai.com/auth/login)
- [ChatGLM-6B](https://huggingface.co/THUDM/chatglm-6b)
- [ChatGLM2-6B](https://huggingface.co/THUDM/chatglm2-6b)  $\checkmark$ 
- [Flan-T5-XXL](https://huggingface.co/google/flan-t5-xxl)
- [FastChat-T5-3B](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0)
- [Open-LLaMA](https://github.com/openlm-research/open_llama) 
- [LLaMA2-7b-chat](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)
- [Vicuna-13B](https://github.com/lm-sys/FastChat) 
- [Chinese-Vicuna-13B](https://huggingface.co/Chinese-Vicuna/Chinese-Vicuna-lora-13b-belle-and-guanaco) 
- [Alpaca-lora-7B](https://github.com/tatsu-lab/stanford_alpaca)
- [Chinese-Alpaca-13b](https://github.com/ymcui/Chinese-LLaMA-Alpaca/wiki) 
- [GPT4ALL ](https://huggingface.co/nomic-ai/gpt4all-13b-snoozy?text=My+name+is+Julien+and+I+like+to)
- [Qwen-7b-chat](https://huggingface.co/Qwen/Qwen-7B-Chat)
- [Baichuan-13b-chat](https://huggingface.co/baichuan-inc/Baichuan-13B-Chat)
-  [Dolly-12B](https://huggingface.co/databricks/dolly-v2-12b)
- [Oasst-Pythia-12B ](https://huggingface.co/OpenAssistant)



scp -o 'ProxyJump nuaanlp@18.tcp.cpolar.top:10491' xfni@172.18.101.151:/data/xfni/code/Evaluation_of_LLMs/data/Text_Summarization/XSum/* /Users/nixuanfan/Evaluation_of_LLMs/data/Text_Summarization/XSum/

