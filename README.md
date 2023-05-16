# Evaluation_of_LLMs_on_NLG
Evaluation of LLMs on NLG benchmarks.

## What is NLG?

Natural Language Generation (NLG) is the process of producing a natural language text to meet specified communicative goals. The texts that are generated may range from a single phrase given in answer to a question, through multi-sentence remarks and questions within a dialog, to full-page explanations.

## Tasks and Datasets

### Text Summarization

| Language | Dataset                                                      | Paper                                          | Download                                                     |
| -------- | ------------------------------------------------------------ | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | CNN/DailyMail                                                | [Link](https://arxiv.org/pdf/1602.06023v5.pdf) | [Link](https://github.com/abisee/cnn-dailymail)              |
|          | NYT (New York Times)                                         | --                                             | [Link](https://catalog.ldc.upenn.edu/LDC2008T19)             |
|          | XSum (Extreme summarization)                                 | [Link](https://arxiv.org/pdf/1808.08745v1.pdf) | [Link](https://github.com/EdinburghNLP/XSum/tree/master/XSum-Dataset) |
|          | Gigaword                                                     | --                                             | [Link](https://huggingface.co/datasets/gigaword)             |
| Chinese  | 清华新闻                                                     | --                                             | [原始数据](http://thuctc.thunlp.org/) [处理后数据](https://pan.baidu.com/share/init?surl=a-CUtTc5xQFB9_EJaxDklA) 取码：vhol |
|          | 微博摘要                                                     | --                                             | [原始数据](https://www.jianshu.com/p/8f52352f0748?tdsourcetag=s_pcqq_aiomsg) [处理后数据](https://pan.baidu.com/share/init?surl=80aTaZe-5jopVBBJhBrTWg) 提取码：duba |
|          | [中文摘要数据集汇总](https://zhuanlan.zhihu.com/p/341398288) |                                                |                                                              |

### Question Answering

| Language | Dataset                                            | Paper                                                        | Download                                                     |
| -------- | -------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| English  | SQuAD (StanfordQuestion Answering Dataset)         | [Link](https://arxiv.org/abs/1606.05250)                     | [Link](https://rajpurkar.github.io/SQuAD-explorer/)          |
|          | MS MARCO (Microsoft Machine Reading Comprehension) | [Link](https://arxiv.org/abs/1611.09268)                     | [Link](https://microsoft.github.io/msmarco/)                 |
|          | WikiQA Corpus                                      | [Link](https://aclanthology.org/D15-1237/)                   | [Link](https://www.microsoft.com/en-us/download/confirmation.aspx?id=52419) |
|          | WebQuestions                                       | [Link](https://aclanthology.org/D13-1160/)                   | [Link](https://worksheets.codalab.org/worksheets/0xba659fe363cb46e7a505c5b6a774dc8a) |
| Chinese  | CMRC2018                                           | [Link](https://aclanthology.org/D19-1600/)                   | [Link](https://github.com/ymcui/cmrc2018)                    |
|          | DuReader Dataset                                   | [Document](https://link.zhihu.com/?target=https%3A//ai.baidu.com/broad/subordinate%3Fdataset%3Ddureader) | [Link](https://github.com/baidu/DuRead)                      |
|          | WebQA                                              | [Document](https://kexue.fm/archives/4338)                   | [Link](https://link.zhihu.com/?target=https%3A//pan.baidu.com/s/1pLXEYtd) 提取码6fbf |
|          | KdConv                                             | [Link](https://arxiv.org/abs/2004.04100)                     | [Link](https://github.com/thu-coai/KdConv)                   |

### Open-domain Dialogue System
| Language | Dataset              | Paper                                          | Download                                                     |
| -------- | -------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | DailyDialog          | [Link](https://arxiv.org/pdf/1710.03957v1.pdf) | [Link](http://yanran.li/dailydialog)                         |
|          | PersonaChat          | [Link](https://arxiv.org/abs/1801.07243)       | [Link](https://www.kaggle.com/datasets/atharvjairath/personachat) |
|          | Empathatic Dialogues | [Link](https://arxiv.org/abs/1811.00207)       | [Link](https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai) |
|          | Blended Skill Talk   | [Link](https://parl.ai/projects/bst/)          | [Link](https://arxiv.org/pdf/2004.08449v1.pdf)               |
| Chinese  | 清华LCCC             | [Link](https://arxiv.org/abs/2008.03946)       | [Link](https://github.com/thu-coai/CDial-GPT)                |
|          | 微博对话语料         | --                                             | [Link](https://github.com/codemayq/chinese_chatbot_corpus)   |
|          | CrossWoz             | [Link](https://arxiv.org/abs/2002.11893)       | [Link](https://github.com/thu-coai/CrossWoz)                 |

### Story Generation

| Language | Dataset                             | Paper                                          | Download                                                     |
| -------- | ----------------------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | ROCStories                          | [Link](https://aclanthology.org/N16-1098.pdf)  | [Link](https://cs.rochester.edu/nlp/rocstories/)             |
|          | WritingPrompts                      | [Link](https://arxiv.org/pdf/1805.04833v1.pdf) | [Link](https://www.kaggle.com/ratthachat/writing-prompts)    |
|          | Scifi_TV_Shows                      | [Link](https://arxiv.org/pdf/1909.03480v2.pdf) | [Link](https://huggingface.co/datasets/lara-martin/Scifi_TV_Shows) |
|          | HANNA                               | [Link](https://arxiv.org/pdf/2208.11646v4.pdf) | [Link](https://github.com/dig-team/hanna-benchmark-asg)      |
|          | TVRecap                             | [Link](https://arxiv.org/pdf/2109.08833v2.pdf) | [Link](https://github.com/mingdachen/TVRecap)                |
| Chinese  | Demi-Gods and Semi-Devils(天龙八部) |                                                |                                                              |

### Data-to-Text

| Language | Dataset  | Paper                                          | Download                                                  |
| -------- | -------- | ---------------------------------------------- | --------------------------------------------------------- |
| English  | WebNLG   | [Link](https://aclanthology.org/P17-1017.pdf)  | [Link](https://webnlg-challenge.loria.fr/)                |
|          | Rotowire | [Link](https://arxiv.org/pdf/1707.08052v1.pdf) | [Link]()                                                  |
|          | ToTTo    | [Link](https://arxiv.org/pdf/2004.14373v3.pdf) | [Link](https://github.com/google-research-datasets/totto) |
|          | XAlign   | [Link](https://arxiv.org/pdf/2202.00291v2.pdf) | [Link](https://github.com/tushar117/XAlign)               |
|          | E2E      | [Link](https://arxiv.org/pdf/1706.09254v2.pdf) | [Link](http://www.macs.hw.ac.uk/InteractionLab/E2E/)      |

#### Machine Translation

#### Text-to-SQL

| Language | Dataset                   | Paper                                          | Download                                                     |
| -------- | ------------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| English  | WikiSQL                   | [Link](http://arxiv.org/abs/1709.00103)        | [Link](https://github.com/salesforce/WikiSQL)                |
|          | Spider                    | [Link](https://arxiv.org/abs/1809.08887)       | [Link](https://github.com/taoyds/spider)                     |
|          | SEDE                      | [Link](https://arxiv.org/pdf/2106.05006v1.pdf) | [Link](https://github.com/hirupert/sede)                     |
|          | SParC                     | [Link](https://arxiv.org/pdf/1906.02285v1.pdf) | [Link](https://github.com/taoyds/sparc)                      |
|          | SPLASH                    | [Link](https://arxiv.org/pdf/2005.02539v2.pdf) | [Link](https://github.com/MSR-LIT/Splash)                    |
| Chinese  | CSpider                   | --                                             | [Link](https://github.com/taolusi/chisp)                     |
|          | 百度飞浆Text2SQL BASELINE | --                                             | [Link](https://github.com/PaddlePaddle/Research/tree/master/NLP/Text2SQL-BASELINE) |
