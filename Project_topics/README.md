**DEADLINES**
- Friday 24th, January 2025. CHOICE OF PROJECT TOPIC (7 available topics, first come first served: https://evento.renater.fr/survey/choice-of-mva-projects-7cgf1cb2 )
- Monday 27th, January, 2025. Groups formed (random assignment based on topics)
- Friday 14th, Februrary 2025. DEADLINE FOR SENDING 1 PAGE PROJECT PLAN (late submissions will be penalized by 1 point/20 every day): **specify what you want to do, the planning, and how you will collaborate within the group**
- Friday 28th March, 2025: DEADLINE FOR SENDING the 4 PAGE-PROJECT REPORT (late submissions will be penalised by 1 point/20 every day)
- Oral presentation (remote): 10-minute presentation + 5 minutes of questions. Slot TBA between Monday 31 March 2025 and Thursday April 10, 2025

**Criteria for the evaluation**

creativity, in-depth results analysis, critical thinking

Example: depending on the project, you can suggest a different approach/improvement to the task, or make the method applicable to a different task or data set,

**You will be evaluated individually on the basis of your engagement in the group work.**


**PROJECTS**

- Project 1:  [**BERT Has Uncommon Sense: Similarity Ranking for Word Sense BERTology**](https://aclanthology.org/2021.blackboxnlp-1.43/) (Gessler and Schneider, 2021) ([Code](https://github.com/lgessler/bert-has-uncommon-sense/tree/master))
  Project supervisor: Aina Garí Soler (aina.gari-soler@inria.fr)
  
  Words often have multiple meanings, and some are used more frequently than others (e.g., the noun _duck_ typically refers to an animal but it is also a cricket term). This paper introduces a simple method to investigate how well the BERT model captures less common word meanings. 

- Project 2 : [**Necessity and Sufficiency for Explaining Text Classifiers: A Case Study in Hate Speech Detection**](https://arxiv.org/abs/2205.03302) (Balkir et al., 2022) ([Code](https://github.com/esmab/necessity-sufficiency/tree/main))
  Project supervisor: Célia Nouri (celia.nouri@inria.fr)

  Hate speech classifiers often over-predict hate speech when identity terms (e.g., "women", "black", "muslim") are present, leading to the over-targeting of mentions of marginalized communities. This paper introduces a refined explainability framework, using generative models and necessity and sufficiency metrics, to analyze such errors in detection.

- Project 3 : Translation [**A Paradigm Shift In Machine Translation: Boosting Translation Performance of Large Language Models**](https://arxiv.org/pdf/2309.11674)
  Project supervisor: Armel Randy Zebaze (armel.zebaze-dongmo@inria.fr)

  Generative Large Language Models (LLMs) have achieved remarkable advancements in various NLP tasks. However, these advances have not been reflected in the translation task, especially those with moderate model sizes (i.e., 7B or 13B parameters), which still lag behind conventional supervised encoder-decoder translation models. This paper introduces a novel fine-tuning approach for LLMs that is specifically designed for the translation task, eliminating the need for the abundant parallel data that traditional translation models usually depend on. The approach consists of two fine-tuning stages: initial fine-tuning on monolingual data followed by subsequent fine-tuning on a small set of high-quality parallel data.

  The objective of this project is to familiarize with the Machine Translation task. It involves using language models to perform the Machine Translation task and evaluate the outputs using the relevant metrics (e.g. BLEU, chrF++, COMET and more). Moreover, fine-tuning language models and evaluating them is also expected (this should be possible for small enough LLMs with quantization and peft methods, using colab). The students are also invited to reflect on fine-tuning vs. In-Context Learning (Brown et al. 2020) in the context of MT and more importantly to think about the broader implications of this work for the field and its challenges.

  Relevant resources:
    - [Initial release](https://github.com/fe1ixxu/ALMA/tree/a3cc7877752779346312bb07798172eadc83d692)
    - [Updated release](https://github.com/fe1ixxu/ALMA)
    - [Fine-tuning a model on a 16GB GPU](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/2.Fine_Tune_Your_Own_Llama_2_Model_in_a_Colab_Notebook.ipynb)
  
- Project 4 :   [**When and Why Vision-Language Models Behave like Bags-Of-Words, and What to Do About It?**](https://openreview.net/pdf?id=KRLUvxh8uaX) (Yuksekgonul et al., 2023) ([Code](https://github.com/vinid/neg_clip)) Project supervisor: Matthieu Futeral (matthieu.futeral@inria.fr)

  Despite the success of large vision and language models (VLMs) in many downstream applications, it is unclear how well they encode the compositional relationships between objects and attributes. This paper introduces a simple training method to overcome the shortcomings of VLMs when it comes to embed this compositional relationship.

- Project 5 : [**ML-SUPERB: Multilingual Speech Universal PERformance Benchmark**](https://www.isca-archive.org/interspeech_2023/shi23g_interspeech.html) (Shi et al., 2023) ([Code](https://github.com/espnet/espnet/tree/master/egs2/ml_superb)) Project supervisor: Angelo Ortiz Tandazo (angelo.ortiz.tandazo@ens.psl.eu)

  Self-supervised speech representation learning (SSL) is the core component of modern speech processing systems. These models are trained on large quantities of unlabeled speech using a pretext task that enables them to learn contextualized representations. The use of such representations has led to significant improvements in downstream tasks, such as speech recognition, speaker diarization, or emotion recognition. Initially, these models were developed in English only. However, there has been a growing interest in the speech community in applying SSL to multilingual and low-resource settings. The project will consist of using a pretrained SSL model (HuBERT, wav2vec 2.0, etc.), freezing its parameters, and implementing speech recognition with a CTC loss using only 10 minutes / 1h of speech in a low-resource language, following the procedure outlined in ML-SUPERB.

  Some ideas for extensions: comparison with other monolingual or multilingual models, comparison of performance between finetuning languages, other tasks (phone recognition, language identification...), other training procedure (LoRA or other PEFT methods as in ML-SUPERB 2.0, etc.), multilingual finetuning vs monolingual finetuning.

- Project 6 : [**Augmentation Invariant Discrete Representation for Generative Spoken Language Modeling**](https://aclanthology.org/2023.iwslt-1.46) (Gat et al., 2023) Project supervisor: Maxime Poli (maxime.poli@ens.psl.eu)

  Generative Spoken Language Modeling research focuses on optimizing speech language models (LMs) using raw speech recordings without any textual supervision. Such speech LMs operate over discrete units obtained from quantizing internal representations of self-supervised models. This paper focuses on improving the robustness of discrete input representations for generative spoken language modeling. The project will consist in reproducing the evaluations of robustness from the paper on selected models and augmentations, implementing the pseudo-labeling algorithm, and training the robust quantizer. It will be evaluated using the ABX metric on the discrete units (not with the zero-shot language modeling tasks: too costly to train the LM).

  Useful codebase: [textlesslib](https://github.com/facebookresearch/textlesslib) for easy loading of pretrained speech encoders and quantizers.

  Some ideas for extensions: introduce new augmentations, evaluation of robustness across languages, comparison with newer speech encoders ([DinoSR](https://proceedings.neurips.cc/paper_files/paper/2023/hash/b6404bf461c3c3186bdf5f55756af908-Abstract-Conference.html), [HuBERT + Spin](https://www.isca-archive.org/interspeech_2023/chang23_interspeech.html), [mHuBERT-147](https://arxiv.org/abs/2406.06371), [XEUS](https://aclanthology.org/2024.emnlp-main.570/), etc.)

- Project 7: [**Anti-efficient encoding in emergent communication**](https://papers.nips.cc/paper/2019/file/31ca0ca71184bbdb3de7b20a51e88e90-Paper.pdf) (Chaabouni et al., 2019) & [**Lazimpa: Lazy and impatient agents learn to communicate efficiently**](https://www.aclweb.org/anthology/2020.conll-1.26/) (Rita et al., 2020) ([Code 1](https://github.com/facebookresearch/EGG), [Code 2](https://github.com/MathieuRita/Lazimpa)) Project supervisor: Jean-Baptiste Sevestre (jean-baptiste.sevestre@ens.psl.eu)
 	
  These papers aim to study how universal properties of human languages (here efficient coding of the transmitted information) can emerge (or not) in simple communicative agents depending on the architecture and inductive biases of these agents. The project aims to reproduce one experiment of one of these two papers and propose, motivate and test a new experiment.
