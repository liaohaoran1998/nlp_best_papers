# NLP Best/Outstanding Papers
best papers published on ACL, NAACL, EMNLP. [[ref-web](https://aclweb.org/aclwiki/Best_paper_awards)] (after 2017) 

extra resources: 
- CS224N: [[official](https://web.stanford.edu/class/cs224n/), [video](https://www.bilibili.com/video/BV1uL41137jN?from=search&seid=8973136216976968045&spm_id_from=333.337.0.0), zhihu, [code](https://github.com/DSKSD/DeepNLP-models-Pytorch)]
## ACL

### 2020 [[ref](https://acl2020.org/blog/ACL-2020-best-papers/)]  
1. Beyond Accuracy: Behavioral Testing of NLP Models with CheckList. [[paper](https://homes.cs.washington.edu/~marcotcr/acl20_checklist.pdf), [code](https://github.com/marcotcr/checklist)]  
Marco Tulio Ribeiro, Tongshuang Wu, Carlos Guestrin and Sameer Singh
    - core: new evaluation methodology (checklist) for NLP models.
1. Don’t Stop Pretraining: Adapt Language Models to Domains and Tasks. [[paper](https://aclanthology.org/2020.acl-main.740.pdf)]  
Suchin Gururangan, Ana Marasović, Swabha Swayamdipta, Kyle Lo, Iz Beltagy, Doug Downey, Noah A. Smith
    - core: task-specifical or multi-phase adaptive pretraining still helps.
### 2021
1. Vocabulary Learning via Optimal Transport for Neural Machine Translation. [[paper](https://aclanthology.org/2021.acl-long.571.pdf), [code](https://github.com/Jingjing-NLP/VOLT)]  
Jingjing Xu, Hao Zhou, Chun Gan, Zaixiang Zheng, Lei Li
    - core : transform token dictionary to discrete optimal transport with *Marginal Utility*. 
## NAACL
### 2018 
1. Deep contextualized word representations. [[paper](https://aclanthology.org/N18-1202.pdf), [code](https://github.com/flairNLP/flair), [blog](https://blog.csdn.net/Magical_Bubble/article/details/89160032)]  
Matthew E. Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, Luke Zettlemoyer
    - core: char CNN encoder + biLMs + scalar mixer
### 2019 
1. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, 2019. [[paper](https://aclanthology.org/N19-1423.pdf), code: [1](https://github.com/huggingface/transformers), [2](https://github.com/graykode/nlp-tutorial)]  
Jacob Devlin, Ming-Wei Chang, Kenton Lee and Kristina Toutanova  
    - core: bidirectional self-attention + mask + sentence prediction
### 2021 [[ref](https://2021.naacl.org/blog/best-paper-awards/)]
1. Video-aided Unsupervised Grammar Induction. [[paper](https://arxiv.org/pdf/2104.04369.pdf)]  
    Songyang Zhang, Linfeng Song, Lifeng Jin, Kun Xu, Dong Yuand and Jiebo Luo
    - core: leveraging video information for unsupervised grammar induction. 
1. Unifying Cross-Lingual Semantic Role Labeling with Heterogeneous Linguistic Resources [[paper](https://aclanthology.org/2021.naacl-main.31.pdf)]  
1. It's Not Just Size That Matters: Small Language Models Are Also Few-Shot Learners
1. Learning How to Ask: Querying LMs with Mixtures of Soft Prompts
1. How many data points is a prompt worth?
1. Preregistering NLP research

## EMNLP
### 2021 [[ref](https://2021.emnlp.org/blog/2021-10-29-best-paper-awards)]
1. Visually Grounded Reasoning across Languages and Cultures. [[paper](https://arxiv.org/vc/arxiv/papers/2109/2109.13238v1.pdf)]  
Fangyu Liu, Emanuele Bugliarello, Edoardo Maria Ponti, Siva Reddy, Nigel Collier and Desmond Elliott
     - core : multi-model, multicultural data.