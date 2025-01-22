

- Project 1:  [**BERT Has Uncommon Sense: Similarity Ranking for Word Sense BERTology**](https://aclanthology.org/2021.blackboxnlp-1.43/) (Gessler and Schneider, 2021) ([Code](https://github.com/lgessler/bert-has-uncommon-sense/tree/master))
  Project supervisor: Aina Garí Soler (aina.gari-soler@inria.fr)
  
Words often have multiple meanings, and some are used more frequently than others (e.g., the noun _duck_ typically refers to an animal but it is also a cricket term). This paper introduces a simple method to investigate how well the BERT model captures less common word meanings. 

- Project 2 : [**Necessity and Sufficiency for Explaining Text Classifiers: A Case Study in Hate Speech Detection**](https://arxiv.org/abs/2205.03302) (Balkir et al., 2022) ([Code](https://github.com/esmab/necessity-sufficiency/tree/main))
  Project supervisor: Célia Nouri (celia.nouri@inria.fr)

Hate speech classifiers often over-predict hate speech when identity terms (e.g., "women", "black", "muslim") are present, leading to the over-targeting of mentions of marginalized communities. This paper introduces a refined explainability framework, using generative models and necessity and sufficiency metrics, to analyze such errors in detection.

- Project 3 : Translation 
- Project 4 :   [**When and Why Vision-Language Models Behave like Bags-Of-Words, and What to Do About It?**](https://openreview.net/pdf?id=KRLUvxh8uaX) (Yuksekgonul et al., 2023) ([Code](https://github.com/vinid/neg_clip)) Project supervisor: Matthieu Futeral (matthieu.futeral@inria.fr)

Despite the success of large vision and language models (VLMs) in many downstream applications, it is unclear how well they encode the compositional relationships between objects and attributes. This paper introduces a simple training method to overcome the shortcomings of VLMs when it comes to embed this compositional relationship.

- Project 5 : [**ML-SUPERB: Multilingual Speech Universal PERformance Benchmark**](https://www.isca-archive.org/interspeech_2023/shi23g_interspeech.html) (Shi et al., 2023) ([Code](https://github.com/espnet/espnet/tree/master/egs2/ml_superb)) Project supervisor: Angelo Ortiz Tandazo (angelo.ortiz.tandazo@ens.psl.eu)

Self-supervised speech representation learning (SSL) is the core component of modern speech processing systems. These models are trained on large quantities of unlabeled speech using a pretext task that enables them to learn contextualized representations. The use of such representations has led to significant improvements in downstream tasks, such as speech recognition, speaker diarization, or emotion recognition. Initially, these models were developed in English only. However, there has been a growing interest in the speech community in applying SSL to multilingual and low-resource settings. The project will consist of using a pretrained SSL model (HuBERT, wav2vec 2.0, etc.), freezing its parameters, and implementing speech recognition with a CTC loss using only 10 minutes / 1h of speech in a low-resource language, following the procedure outlined in ML-SUPERB.

Some ideas for extensions: comparison with other monolingual or multilingual models, comparison of performance between finetuning languages, other tasks (phone recognition, language identification...), other training procedure (LoRA or other PEFT methods as in ML-SUPERB 2.0, etc.), multilingual finetuning vs monolingual finetuning.

- Project 6 : Speech language models
- Project 7 : language emergence

