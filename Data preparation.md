## ***Data Labeling mainly Weak Supervision***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[A Survey on Programmatic Weak Supervision](https://arxiv.org/abs/2202.05433)|arXiv|阐述了LF，label model，end model，two-stage method等WS中的概念|
|[Snorkel: Rapid Training Data Creation with Weak Supervision](https://arxiv.org/abs/1711.10160)|VLDB 2017|使用output space相同的LF来进行概率标签的取得，并进一步训练下游模型|
|[Cost-Effective Data Annotation using Game-Based Crowdsourcing](https://gsai.ruc.edu.cn/uploads/20210522/b2c076a99178832c132eeda4cd34567b.pdf)|VLDB 2018|通过Rule Generator 和 Rule Refuter 得到一系列高质量的rule，使用rule在crowdsourcing中完成标注|
|[End-to-End Weak Supervision](https://arxiv.org/abs/2107.02233)|NeurIPS 2021|结合下游模型的训练和probabilistic labels的产生，训练完直接获得下游模型的参数|
|[SIMVLM: SIMPLE VISUAL LANGUAGE MODEL PRETRAINING WITH WEAK SUPERVISION](https://arxiv.org/abs/2108.10904)|ICLR 2022|通过WS和language modeling loss降低训练复杂度|
|[FlexMatch: Boosting Semi-Supervised Learning with Curriculum Pseudo Labeling](https://arxiv.org/abs/2110.08263)|NeurIPS 2021|combines Consistency regularization with pseudo labeling to SSL，using a flexible threshold|
|[CREATING TRAINING SETS VIA WEAK INDIRECT SUPERVISION](https://openreview.net/pdf?id=m8uJvVgwRci)|ICLR 2022|使用output space不同的LF来进行概率标签的取得，并进一步训练下游模型|

## ***Controllable Text Generation Based on PLM***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[PLUG AND PLAY LANGUAGE MODEL: A SIMPLE BASELINE FOR CONTROLLED LANGUAGE GENERATION](https://openreview.net/pdf?id=H1edEyBKDS)|ICLR 2020|conditional language generation that combines one or more simple attribute models|
|[A Survey of Controllable Text Generation using Transformer-based Pre-trained Language Models](https://arxiv.org/abs/2201.05337)|arXiv|一篇关于基于预训练模型的可控文本生成的survey|

## ***Data Augmentation Based on PLM***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[Generating Datasets with Pretrained Language Models](https://aclanthology.org/2021.emnlp-main.555)|EMNLP 2021|运用prompt结合下面的的self-debias得到句向量作为训练数据|
|[Generating Training Data with Language Models: Towards Zero-Shot Language Understanding](https://openreview.net/forum?id=4G1Sfp_1sz7)|NeurIPS 2022|用单项PLM给双向PLM生成训练数据，并进行fine-tune|
|[Large Language Model as Attributed Training Data Generator: A Tale of Diversity and Bias](https://arxiv.org/abs/2306.15895)|arXiv|使用diversely attributed prompts来生成数据，保证生成的diversity，并分析了diversity的作用|
|[GPT3Mix: Leveraging Large-scale Language Models for Text Augmentation](https://aclanthology.org/2021.findings-emnlp.192)|EMNLP 2021|结合prompt和quality example引导PLM生成文本|
|[Is GPT-3 a Good Data Annotator?](https://aclanthology.org/2023.acl-long.626/)|ACL 2023|探索了三种利用GPT的数据标注方法的效果|
|[Is a prompt and a few samples all you need?Using GPT-4 for data augmentation in low-resource classification tasks](https://arxiv.org/abs/2304.13861)|arXiv|探索了GPT用来文本增强，在3个社科领域任务的效果|

## ***Guide PLM***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[Self-Diagnosis and Self-Debiasing: A Proposal for Reducing Corpus-Based Bias in NLP](https://arxiv.org/abs/2103.00453)|TACL 2021|diagnose并debias 生成的文本中的有害信息|
|[SIMPLE SYNTHETIC DATA REDUCES SYCOPHANCY IN LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2308.03958)|arXiv|用合成数据干预解决大模型的“迎合”现象|
|[Making Pre-trained Language Models Better Few-shot Learners](https://aclanthology.org/2021.acl-long.295)|ACL 2021|利用prompt优化bert式的双向预训练模型|

## ***Data Preparation***
| Paper | Conference | Remark |
| :---:| :---:| :---:|
|[Demystifying Artificial Intelligence for Data Preparation](http://iir.ruc.edu.cn/~fanj/papers/sigmod2023-dataprep-tutorial.pdf)|SIGMOD 2023|关于data preparation的一篇综述，包括foundation model，PLM，Pipeline|
