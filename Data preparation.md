## ***weak supervision***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[A Survey on Programmatic Weak Supervision ](https://gsai.ruc.edu.cn/uploads/20210522/b4fdaf3782d52b96782c52967a0790f4.pdf)|arXiv|阐述了LF，label model，end model，two-stage method等WS中的概念|
|[Snorkel: Rapid Training Data Creation with Weak Supervision](https://ojs.aaai.org/index.php/AAAI/article/view/11513)|VLDB 2017|使用output space相同的LF来进行概率标签的取得，并进一步训练下游模型|
|[Cost-Effective Data Annotation using Game-Based Crowdsourcing](https://arxiv.org/abs/2004.03473)|VLDB 2018|通过Rule Generator 和 Rule Refuter 得到一系列高质量的rule，使用rule在crowdsourcing中完成标注|
|[End-to-End Weak Supervision](https://proceedings.neurips.cc/paper/2021/file/0e674a918ebca3f78bfe02e2f387689d-Paper.pdf)|NeurIPS 2021|结合下游模型的训练和probabilistic labels的产生，训练完直接获得下游模型的参数|
|[SIMVLM: SIMPLE VISUAL LANGUAGE MODEL PRETRAINING WITH WEAK SUPERVISION](https://www.vldb.org/pvldb/vol12/p223-varma.pdf)|ICLR 2022|通过WS和language modeling loss降低训练复杂度|
|[FlexMatch: Boosting Semi-Supervised Learning with Curriculum Pseudo Labeling](https://proceedings.neurips.cc/paper/2021/file/0e674a918ebca3f78bfe02e2f387689d-Paper.pdf)|NeurIPS 2021|combines Consistency regularization with pseudo labeling to SSL，using a flexible threshold|
|[CREATING TRAINING SETS VIA WEAK INDIRECT SUPERVISION](https://www.vldb.org/pvldb/vol12/p223-varma.pdf)|ICLR 2022|使用output space不同的LF来进行概率标签的取得，并进一步训练下游模型|

## ***Generation with PLM***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[Self-Diagnosis and Self-Debiasing: A Proposal for Reducing Corpus-Based Bias in NLP](https://gsai.ruc.edu.cn/uploads/20210522/b4fdaf3782d52b96782c52967a0790f4.pdf)|arXiv|diagnose并debias 生成的文本中的有害信息|
|[Generating Datasets with Pretrained Language Models](https://gsai.ruc.edu.cn/uploads/20210522/b4fdaf3782d52b96782c52967a0790f4.pdf)|arXiv|运用prompt结合上面的debias得到句向量作为训练数据|
|[Generating Training Data with Language Models: Towards Zero-Shot Language Understanding](https://ojs.aaai.org/index.php/AAAI/article/view/11513)|NeurIPS 2022|用单项PLM给双向PLM生成训练数据，并进行fine-tune|
|[Large Language Model as Attributed Training Data Generator: A Tale of Diversity and Bias](https://arxiv.org/abs/2004.03473)|arXiv|使用diversely attributed prompts来生成数据，保证生成的diversity，并分析了diversity的作用|
|[GPT3Mix: Leveraging Large-scale Language Models for Text Augmentation](https://proceedings.neurips.cc/paper/2021/file/0e674a918ebca3f78bfe02e2f387689d-Paper.pdf)|EMNLP 2021|结合prompt和quality example引导PLM生成文本|
|[PLUG AND PLAY LANGUAGE MODEL: A SIMPLE BASELINE FOR CONTROLLED LANGUAGE GENERATION](https://www.vldb.org/pvldb/vol12/p223-varma.pdf)|ICLR 2020|conditional language generation that combines one or more simple attribute models|

## ***Data Preparation***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[Demystifying Artificial Intelligence for Data Preparation](https://gsai.ruc.edu.cn/uploads/20210522/b4fdaf3782d52b96782c52967a0790f4.pdf)|SIGMOD 2023|关于data preparation的一篇综述，包括foundation model，PLM，Pipeline|
