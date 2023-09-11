# Evaluation_of_LLMs_on_NLG
Evaluation of LLMs on NLG benchmarks.

## What is NLG?

Natural Language Generation (NLG) is the process of producing a natural language text to meet specified communicative goals. The texts that are generated may range from a single phrase given in answer to a question, through multi-sentence remarks and questions within a dialog, to full-page explanations.

## Tasks and Datasets

### Text Summarization

| Language | Dataset                      | Test Input         | Test Output     | Train Input       | Train Output  | Paper                                          | Download                                                     |      |
| -------- | ---------------------------- | ------------------ | --------------- | ----------------- | ------------- | ---------------------------------------------- | ------------------------------------------------------------ | ---- |
| English  | CNN/DailyMail                | 3628; 175; 1088.84 | 1101; 12; 84.47 |                   |               | [Link](https://arxiv.org/pdf/1602.06023v5.pdf) | [Link](https://github.com/abisee/cnn-dailymail)              |      |
|          | XSum (Extreme summarization) | 18962; 95; 661.01  | 107; 4; 31.63   | 23397; 95; 656.37 | 120; 2; 31.68 | [Link](https://arxiv.org/pdf/1808.08745v1.pdf) | [Link](https://github.com/EdinburghNLP/XSum/tree/master/XSum-Dataset) |      |
| Chances  | LCSTS                        | 786; 191; 329.88   | 72; 6; 32.20    | 2736; 171; 329.37 | 107; 4; 32.23 | --                                             | [原始数据](https://www.jianshu.com/p/8f52352f0748?tdsourcetag=s_pcqq_aiomsg) [处理后数据](https://pan.baidu.com/share/init?surl=80aTaZe-5jopVBBJhBrTWg) 提取码：duba |      |



### Open-domain Dialogue System

| Language | Dataset              | Test Input                      | Test Output                  | Train Input                      | Train Output                 | Paper                                          | Download                                                     |
| -------- | -------------------- | ------------------------------- | ---------------------------- | -------------------------------- | ---------------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | DailyDialog          | max: 663, min: 129, avg: 246.57 | max:246, min: 3, avg: 16.55  | max: 1099, min: 128, avg: 247.60 | max: 313, min: 2, avg: 16.19 | [Link](https://arxiv.org/pdf/1710.03957v1.pdf) | [Link](http://yanran.li/dailydialog)                         |
|          | PersonaChat          | max: 529, min: 273, avg: 372.28 | max: 32, min: 5, avg: 13.53  |                                  |                              | [Link](https://arxiv.org/abs/1801.07243)       | [Link](https://www.kaggle.com/datasets/atharvjairath/personachat) |
|          | Empathatic Dialogues | max: 380, min: 148, avg: 201.64 | max: 110, min: 2, avg: 17.85 | max: 400, min: 146, avg: 193.13  | max: 135 min: 2, avg: 16.80  | [Link](https://arxiv.org/abs/1811.00207)       | [Link](https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai) |
| Chinese  | 清华LCCC             | max: 848, min: 214, avg: 264.73 | max: 347, min: 3, avg: 28.27 | max: 1666, min: 213, avg: 278.59 | max: 314, min: 2, avg: 26.98 | [Link](https://arxiv.org/abs/2008.03946)       | [Link](https://github.com/thu-coai/CDial-GPT)                |



### Controllable Story Generation

| Language | Dataset        | Test Input       | Test Output       | Train Input      | Train Output      | Paper                                                        | Download                                                     |
| -------- | -------------- | ---------------- | ----------------- | ---------------- | ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| English  | ROCStories     | 203; 115; 140.44 | 34; 4; 12.76      | 182; 115; 140.56 | 29; 4; 12.74      | [Link](https://aclanthology.org/N16-1098.pdf)                | [Link](https://cs.rochester.edu/nlp/rocstories/)             |
|          | WritingPrompts | 179; 95; 125.64  | 2912; 132; 793.14 | 208; 95; 126.23  | 8308; 115; 789.08 | [Link](https://arxiv.org/pdf/1805.04833v1.pdf)               | [Link](https://www.kaggle.com/ratthachat/writing-prompts)    |
| Chinese  | LOT            | 329; 215; 254.73 | 568; 112; 275.07  | 324; 207; 253.90 | 624; 113; 273.10  | [Link](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00469/110537/LOT-A-Story-Centric-Benchmark-for-Evaluating) | [Link](https://cloud.tsinghua.edu.cn/d/0cf033b0c7c049be855d/) |



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
- [ChatGLM-6B](https://huggingface.co/THUDM/chatglm-6b) $\checkmark$ 
- [ChatGLM2-6B](https://huggingface.co/THUDM/chatglm2-6b)  $\checkmark$ 
- [Flan-T5-XXL](https://huggingface.co/google/flan-t5-xxl) $\checkmark$ 
- [FastChat-T5-3B](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0) $\checkmark$ 
- [Open-LLaMA](https://github.com/openlm-research/open_llama) 
- [LLaMA2-7b-chat](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)
- [Vicuna-13B](https://github.com/lm-sys/FastChat) $\checkmark$ 
- [Chinese-Vicuna-13B](https://huggingface.co/Chinese-Vicuna/Chinese-Vicuna-lora-13b-belle-and-guanaco) 
- [Alpaca-lora-7B](https://github.com/tatsu-lab/stanford_alpaca)
- [Chinese-Alpaca-13b](https://github.com/ymcui/Chinese-LLaMA-Alpaca/wiki) 
- [GPT4ALL ](https://huggingface.co/nomic-ai/gpt4all-13b-snoozy?text=My+name+is+Julien+and+I+like+to)
- [Qwen-7b-chat](https://huggingface.co/Qwen/Qwen-7B-Chat)$\checkmark$ 
- [Baichuan2-13b-chat](https://huggingface.co/baichuan-inc/Baichuan-13B-Chat)$\checkmark$ 
-  [Dolly-12B](https://huggingface.co/databricks/dolly-v2-12b)
- [Oasst-Pythia-12B ](https://huggingface.co/OpenAssistant)



scp -o 'ProxyJump nuaanlp@18.tcp.cpolar.top:12174' xfni@172.18.101.151:/data/xfni/code/Evaluation_of_LLMs/data/dialogue.tar.gz  /Users/nixuanfan/

