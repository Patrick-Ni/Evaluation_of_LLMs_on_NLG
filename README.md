# Evaluation_of_LLMs_on_NLG
Evaluation of LLMs on NLG benchmarks.

## What is NLG?

Natural Language Generation (NLG) is the process of producing a natural language text to meet specified communicative goals. The texts that are generated may range from a single phrase given in answer to a question, through multi-sentence remarks and questions within a dialog, to full-page explanations.

## Tasks and Datasets

### Text Summarization

| Language | Dataset                      | Test Input         | Test Output     | Train Input       | Train Output  | Data                                                         |
| -------- | ---------------------------- | ------------------ | --------------- | ----------------- | ------------- | ------------------------------------------------------------ |
| English  | CNN/DailyMail                | 3628; 175; 1088.84 | 1101; 12; 84.47 |                   |               | [Paper](https://arxiv.org/pdf/1602.06023v5.pdf) & [Data](https://github.com/abisee/cnn-dailymail) |
|          | XSum (Extreme summarization) | 18962; 95; 661.01  | 107; 4; 31.63   | 23397; 95; 656.37 | 120; 2; 31.68 | [Paper](https://arxiv.org/pdf/1808.08745v1.pdf) & [Data](https://github.com/EdinburghNLP/XSum/tree/master/XSum-Dataset) |
| Chances  | LCSTS                        | 786; 191; 329.88   | 72; 6; 32.20    | 2736; 171; 329.37 | 107; 4; 32.23 | --[原始数据](https://www.jianshu.com/p/8f52352f0748?tdsourcetag=s_pcqq_aiomsg) [处理后数据](https://pan.baidu.com/share/init?surl=80aTaZe-5jopVBBJhBrTWg) 提取码：duba |



### Open-domain Dialogue System

| Language | Dataset              | Test Input       | Test Output       | Train Input       | Train Output  | Data                                                         |
| -------- | -------------------- | ---------------- | ----------------- | ----------------- | ------------- | ------------------------------------------------------------ |
| English  | DailyDialog          | 663, 129, 246.57 | max:246, 3, 16.55 | 1099, 128, 247.60 | 313, 2, 16.19 | [Paper](https://arxiv.org/pdf/1710.03957v1.pdf) & [Data](http://yanran.li/dailydialog) |
|          | PersonaChat          | 529, 273, 372.28 | 32, 5, 13.53      |                   |               | [Paper](https://arxiv.org/abs/1801.07243) & [Data](https://www.kaggle.com/datasets/atharvjairath/personachat) |
|          | Empathatic Dialogues | 380, 148, 201.64 | 110, 2, 17.85     | 400, 146, 193.13  | 135 2, 16.80  | [Paper](https://arxiv.org/abs/1811.00207) & [Data](https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai) |
| Chinese  | 清华LCCC             | 848, 214, 264.73 | 347, 3, 28.27     | 1666, 213, 278.59 | 314, 2, 26.98 | [Paper](https://arxiv.org/abs/2008.03946) & [Data](https://github.com/thu-coai/CDial-GPT) |



### Controllable Story Generation

| Language | Dataset        | Test Input       | Test Output       | Train Input      | Train Output      | Paper                                                        |
| -------- | -------------- | ---------------- | ----------------- | ---------------- | ----------------- | ------------------------------------------------------------ |
| English  | ROCStories     | 203; 115; 140.44 | 34; 4; 12.76      | 182; 115; 140.56 | 29; 4; 12.74      | [Paper](https://aclanthology.org/N16-1098.pdf) & [Data](https://cs.rochester.edu/nlp/rocstories/) |
|          | WritingPrompts | 179; 95; 125.64  | 2912; 132; 793.14 | 208; 95; 126.23  | 8308; 115; 789.08 | [Paper](https://arxiv.org/pdf/1805.04833v1.pdf) & [Data](https://www.kaggle.com/ratthachat/writing-prompts) |
| Chinese  | LOT            | 329; 215; 254.73 | 568; 112; 275.07  | 324; 207; 253.90 | 624; 113; 273.10  | [Paper](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00469/110537/LOT-A-Story-Centric-Benchmark-for-Evaluating) & [Data](https://cloud.tsinghua.edu.cn/d/0cf033b0c7c049be855d/) |



### Data-to-Text

| Language | Dataset  | Test Input       | Test Output   | Train Input | Train Output | Paper                                                        |
| -------- | -------- | ---------------- | ------------- | ----------- | ------------ | ------------------------------------------------------------ |
| English  | WebNLG   | 324; 156; 201.68 | 158; 7; 38.55 |             |              | [Paper](https://aclanthology.org/P17-1017.pdf) & [Data](https://webnlg-challenge.loria.fr/) |
|          | ToTTo    |                  |               |             |              | [Paper](https://arxiv.org/pdf/2004.14373v3.pdf) & [Data](https://github.com/google-research-datasets/totto) |
|          | Rotowire |                  |               |             |              | [Paper](https://arxiv.org/pdf/1707.08052v1.pdf) & [Data](https://github.com/harvardnlp/boxscore-data) |



### Style Transfer (Paraphrasing & Simplification & formal-informal)

| Language                          | Dataset   | Paper                                                        |
| --------------------------------- | --------- | ------------------------------------------------------------ |
| English                           | Yelp      | [Paper](https://arxiv.org/abs/1705.09655) & [Data](https://github.com/shentianxiao/language-style-transfer/tree/master) |
| Chinese (Formal-Informal)         | CLSD      | [Paper](https://arxiv.org/abs/1909.11493) & [Data](https://drive.google.com/file/d/15TxvHgd_SEC-Wy47uI_CgDdiPf_yUw60/view?pli=1) |
| English (Paraphrasing)            | ParaNMT   | [Paper]([ParaNMT-50M: Pushing the Limits of Paraphrastic Sentence Embeddings with Millions of Machine Translations](https://paperswithcode.com/paper/paranmt-50m-pushing-the-limits-of)) & [Data](https://www.cs.cmu.edu/~jwieting/) |
| English (Sentence Simplification) | WikiLarge | [Paper](Sentence Simplification with Deep Reinforcement Learning) & [Data](https://github.com/XingxingZhang/dress) |



### LLMs

- [ChatGPT](https://chat.openai.com/auth/login)
- [ChatGLM2-6B](https://huggingface.co/THUDM/chatglm2-6b)  $\checkmark$ 
- [Flan-T5-XXL](https://huggingface.co/google/flan-t5-xxl) $\checkmark$ 
- [LLaMA2-7b-chat ](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)$\checkmark$ 
- [LLaMA2-13b-chat](https://huggingface.co/meta-llama/Llama-2-13b-chat-hf)$\checkmark$
- [Llama2-Chinese-13b-Chat](https://huggingface.co/FlagAlpha/Llama2-Chinese-13b-Chat) $\checkmark$
- [Vicuna-13B-v1.5-16k](https://github.com/lm-sys/FastChat)$\dots$
- [Chinese-Alpaca-2-13b](https://github.com/ymcui/Chinese-LLaMA-Alpaca/wiki) $\checkmark$
- [Qwen-7b-chat](https://huggingface.co/Qwen/Qwen-7B-Chat)$\checkmark$ 
- [Baichuan2-13b-chat](https://huggingface.co/baichuan-inc/Baichuan-13B-Chat)$\checkmark$ 
- [Oasst-Pythia-12B ](https://huggingface.co/OpenAssistant) 

实验设置：Chat模型

实验目的：

- 中英文模型对照 (llama2-7b-chat vs baichuan2 vs Qwen)
- 模型规模（llama2-7b-chat vs llama2-13b-chat）
- 模型架构不同 （chatglm2-6b vs llama2-7b-chat，llama2-13b-chat vs oasst-pythia-12b，flan-t5-xxl）
- 模型微调数据集不同 （Qwen, Baichuan2, chinsese-alpaca2, vicuna）

scp -o 'ProxyJump nuaanlp@8.tcp.cpolar.top:14989' xfni@172.18.101.150:/data/share/LLMs/llama2/llama-2-7b-chat/params.json  /Users/nixuanfan/

