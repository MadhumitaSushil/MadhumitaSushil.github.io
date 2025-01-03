---
layout: default
---

# About me

I am an Assistant Professor in the [Division of Clinical Informatics and Digital Transformation (DoC-IT) - Department of Medicine](https://docit.ucsf.edu/), [Department of Neurological Surgery](https://neurosurgery.ucsf.edu/), and the [Bakar Computational Health Sciences Institute (BCHSI)](https://bakarinstitute.ucsf.edu/) at University of California, San Francisco. I have previously worked as a postdoctoral researcher with [Prof. Atul Butte](https://profiles.ucsf.edu/atul.butte) at BCHSI. I have obtained a PhD in clinical Natural Language Processing at the [Computational Linguistics and Psycholinguistics (CLiPS) Research Center](https://www.uantwerpen.be/en/research-groups/clips/), University of Antwerp, Belgium, under [Prof. Dr. Walter Daelemans](https://www.clips.uantwerpen.be/~walter/) and [Dr. Simon Šuster](http://simonsuster.github.io/). My research interest is to develop foundation models to understand the nuances in electronic health record data, and to use these insights for answering clinical research questions. I am particularly interested in developing strategies for inferring causal patterns from observational textual data, improving generalization for low frequency data samples, and developing multi-modal and interpretable foundation models to improve the understanding of patients' disease and treatment trajectory. I have extensive experience with the development of methodology for deep learning model interpretability and retrieval-augmented classification, and in creating benchmarking datasets for advanced oncology-specific information extraction from clinical notes.

During my PhD, I have worked as a research intern at the Google Brain Applied team in Zurich, where I investigated linguistic reasoning skills of BERT representations. I have additionally been involved in several academic service positions throughout. I hold a Master of Science in Language Science and Technology (spec. Language Technology) from Saarland University, Germany, and a Bachelor of Technology in Computer Science and Engineering from VIT University, Vellore, India. I have additionally worked on clinical text understanding as a Junior Research Developer at the Antwerp University Hospital, Belgium, and contributed towards recognizing textual entailment for the EU-funded [Excitement](https://sites.google.com/site/excitementproject/) project as a Research Assistant at the German Research Center for Artifical Intelligence (DFKI), Saarbrücken, Germany.

# Research Grants
* Principal Investigator, <b>National AI Research Resource (NAIRR) Pilot </b> on _Pre-training a generative selective state space model, the Mamba model, on UCSF-specific deidentified clinical data_ (17,250 GPU hours).
* Principal Investigator, <b>Computational Cancer Award, Helen Diller Family Comprehensive Cancer Center</b> on _Explainable vision-language models for pancreatic cancer radiology imaging analysis_ ($50,000).
* Technical Leader, <b>NIH-NCI supplement award to the Helen Diller Family Comprehensive Cancer Center</b> on _Large language models for treatment and pathology data extraction_ ($300,000).

# Selected Publications

* [CORAL: Expert-Curated Oncology Reports to Advance Language Model Inference](https://ai.nejm.org/doi/10.1056/AIdbp2300110) <br/>
<b>Madhumita Sushil</b>, Vanessa E. Kennedy<sup>#</sup>, Divneet Mandair<sup>#</sup>, Brenda Miao, Travis Zack<sup>\*</sup>, Atul J. Butte<sup>\*</sup> <br/>
*New England Journal of Medicine (NEJM)-AI*, 2024 <br/>
[bibtex](papers/bibtex/coral.bib) | [preprint](https://arxiv.org/abs/2308.03853) | [Dataset](https://physionet.org/content/curated-oncology-reports/1.0/)

* [A comparative study of large language model-based zero-shot inference and task-specific supervised classification of breast cancer pathology reports](https://academic.oup.com/jamia/advance-article/doi/10.1093/jamia/ocae146/7696538) <br/>
<b>Madhumita Sushil<sup>\*</sup></b>, Travis Zack<sup>\*</sup>, Divneet Mandair<sup>\*</sup>, Zhiwei Zheng<sup>\#</sup>, Ahmed Wali<sup>\#</sup>, Yan-Ning Yu<sup>\#</sup>, Yuwei Quan<sup>\#</sup>, Dmytro Lituiev, Atul J. Butte <br/>
*Journal of American Medical Informatics Association (JAMIA)*, 2024 <br/>
[bibtex](papers/bibtex/jamia24-breastca-path.bibtex) | Dataset

* [Cross-institution natural language processing for reliable clinical association studies: a methodological exploration](https://doi.org/10.1016/j.jclinepi.2024.111258) <br/>
<b>Madhumita Sushil</b>, Atul J. Butte, Ewoud Schuit, Maarten van Smeden, Artuur M. Leeuwenberg <br/>
*Journal of Clinical Epidemiology*, 2024 <br/>
[bibtex](papers/bibtex/JCE_SDOH_associations.bib)

* [Algorithmic identification of treatment-emergent adverse events from clinical notes using large language models: a pilot study in inflammatory bowel disease](https://ascpt.onlinelibrary.wiley.com/doi/10.1002/cpt.3226) <br/>
Anna L Silverman<sup>\*</sup>, <b>Madhumita Sushil<sup>\*</sup></b>, Balu Bhasuran<sup>\*</sup>, Dana Ludwig, James Buchanan, Rebecca Racz, Mahalakshmi Parakala, Samer El-Kamary, Ohenewaa Ahima, Artur Belov, Lauren Choi, Monisha Billings, Yan Li, Nadia Habal, Qi Liu, Jawahar Tiwari, Atul J. Butte, and Vivek A. Rudrapatna. <br/>
*Journal of Clinical Pharmacology and Therapeutics*, 2024. <br/>
[bibtex](papers/bibtex/fda_ae_ibd.bib) | [preprint](https://www.medrxiv.org/content/10.1101/2023.09.06.23295149v1)

* [Topic modeling on clinical social work notes for exploring social determinants of health factors](https://academic.oup.com/jamiaopen/article/7/1/ooad112/7536094) <br/>
Shenghuan Sun, Travis Zack, Christopher Y. K. Williams, <b>Madhumita Sushil\*</b>, Atul J. Butte\* <br/>
*JAMIA Open*, 2024 <br/>
[bibtex](papers/bibtex/topicmodeling_jamiao.bibtex)

* [Are we there yet? Exploring clinical domain knowledge of BERT models](https://aclanthology.org/2021.bionlp-1.5) <br/>
<b>Madhumita Sushil</b>, Simon Šuster, Walter Daelemans <br/>
*BioNLP* Workshop, NAACL 2021 <br/>
[bibtex](papers/bibtex/bionlp21-1.bib) | [slides](talks/NAACL_knowledge_integration.pdf)

* [Contextual explanation rules for neural clinical classifiers](https://aclanthology.org/2021.bionlp-1.22/) <br/>
<b>Madhumita Sushil</b>, Simon Šuster, Walter Daelemans <br/>
*BioNLP* Workshop, NAACL 2021 <br/>
[bibtex](papers/bibtex/bionlp21-2.bib) | [code](https://github.com/clips/rnn_expl_rules) | [poster](posters/bionlp_interpretability.pdf)

* [Rule induction for global explanation of trained models](https://aclweb.org/anthology/W18-5411) <br/>
<b>Madhumita Sushil</b>, Simon Šuster, Walter Daelemans <br/>
Workshop on *Analyzing and interpreting neural networks for NLP (BlackboxNLP)*, EMNLP 2018 <br/>
[bibtex](papers/bibtex/blackboxnlp18.bib) | [code](https://github.com/clips/interpret_with_rules) | [poster](posters/blackboxnlp_poster.pdf)

* [Revisiting neural relation classification in clinical notes with external information](https://aclweb.org/anthology/W18-5603) <br/>
Simon Šuster, <b>Madhumita Sushil</b>, Walter Daelemans <br/>
Workshop on *Health Text Mining and Information Analysis (LOUHI)*, EMNLP 2018 <br/>
[bibtex](papers/bibtex/louhi18.bib) |
[code](https://github.com/SimonSuster/seg_cnn) | [poster](posters/LOUHI2018relextrposter_final.pdf)

* [Patient representation learning and interpretable evaluation using clinical notes](https://www.sciencedirect.com/science/article/pii/S1532046418301266) <br/>
<b>Madhumita Sushil</b>, Simon Šuster, Kim Luyckx, Walter Daelemans <br/>
Journal of Biomedical Informatics, 2018 <br/>
[bibtex](papers/bibtex/jbi_rep_learning.bib) | [code](https://github.com/clips/PatientRep) | [arXiv preprint](https://arxiv.org/abs/1807.01395)

<!--- * [Unsupervised patient representations from clinical notes with interpretable classification decisions](https://arxiv.org/abs/1711.05198) <br/> --->
<!--- <b>Madhumita Sushil</b>, Simon Šuster, Kim Luyckx, Walter Daelemans <br/> --->
<!--- Workshop on *Machine Learning for Health*, NeurIPS 2017 <br/> --->
<!--- [bibtex](papers/bibtex/patientrep_ml4h.bib) | [poster](posters/ml4h2017.pdf) --->

* [Counting trees in Random Forests: Predicting symptom severity in psychiatric intake reports](https://www.sciencedirect.com/science/article/pii/S1532046417301302) <br/>
Elyne Scheurwegs, <b>Madhumita Sushil</b>, Stéphan Tulkens, Walter Daelemans, Kim Luyckx <br/>
Journal of Biomedical Informatics, 2017 <br/>
[bibtex](papers/bibtex/rdoc_jbi.bib) | [code](https://github.com/Elyne/rdocChallenge)

<!--- * [Integration of Safety and Smartness Using Cloud --->
<!--- Services- An insight to future](https://link.springer.com/chapter/10.1007%2F978-1-4614-3535-8_25) <br/> --->
<!--- #Neha Tekriwal, <b>Madhumita</b>, P. Venkata Krishna <br/> --->
<!--- #Part of Lecture Notes in Electrical Engineering, 2012 --->

# Mentoring
* <b>MEng Capstone project, UC Berkeley, 2022-2023</b>: Breast cancer pathology extraction from pathology reports.
 <br/> Mentees: Ahmed Wali, Yan-Ning Yu, Yuwei Quan, Zhiwei Zheng
* <b>Biomedical Informatics PhD student, UCSF</b>: Social determinants of health exploration from social work notes.
  <br/> Mentee: Shenghuan Sun
* <b>Google Summer of Code, 2019</b>: [Bias identification in machine learning models](https://github.com/clips/gsoc2019_bias)
  <br/> Mentee: Panagiotis Lantavos, Artistotle University of Thessaloniki
  
# Service
* <b>Reviewer/Program Committee Member: </b>Journal of American Medical Informatics Association 2024; Journal of Biomedical Informatics 2023; Biomedical Natural Language Processing (BioNLP) workshop at ACL 2022, 2023; BMC Medical Informatics 2021; AMIA Informatics Summit ’23, AMIA Annual Symposium ’22, ’23; International Conference on Information Management and Big Data (SIMBig) ’21, ’23; Workshop on Machine Learning for Health at NeurIPS 2017, 2018, 2019; Student Research Workshop and Widening NLP Workshop at ACL 2019.
* <b>Session chair: clinical NLP</b>; AMIA 2021
* <b>Student Board</b>: EACL 2019&ndash;20.
* <b>Co-chair</b>: Student Research Workshop at EACL 2021.

# Talks
* [Natural language processing for inferences from electronic health record notes](talks/FDA_CERSI_lecture.pdf) <br/>
Clinical Informatics Data Science Pathway lecture series, UCSF, 2023. <br/>
UCSF-Stanford Center of Excellence in Regulatory Science and Innovation (CERSI) EHR training series to the FDA, 2023.

* [Lessons learned from clinical language processing](talks/UCSF_seminar.pdf) <br/>
Seminar at Butte lab, University of California-San Francisco, July 2020

* [Synthetic dataset for explaining and evaluating rules learned by RNNs](talks/Blackbox@NL.pdf) <br/>
[Blackbox@NL Workshop](https://blackbox-nl.github.io/), May 2019

* [Understanding Machine Learning models for healthcare: Why, and how?](talks/Accumulate_22ndMar2019.pdf) <br/>
Project [Accumulate](https://www.accumulate.be/index.html) Industry Meeting, March 2019

* [Identifying Patients with Major Diabetes-related Complications](talks/major-diab-comp.pdf) <br/>
CLiPS Lab Meeting, May 2018

* [Model Agnostic Interpretability Techniques](talks/Model Agnostic Interpretability Techniques.pdf) <br/>
CLiPS Lab Meeting, March 2018

* [Unsupervised patient representations with interpretable classification decisions](talks/CLIN28 - Unsupervised patient representations with interpretable classification decisions.pdf) <br/>
Computational Linguistics in the Netherlands 28 (CLIN28), January 2018 <br/>

* [Clinical Data Characteristics and Processing Challenges](talks/Clinical data characteristics and processing challenges.pdf) <br/>
Project [Accumulate](https://www.accumulate.be/index.html) Technical Meeting, December 2016

* [Psychiatric symptom severity identification, and experiences with cTakes](talks/Accumulate-25thAug2016.pdf) <br/>
Project [Accumulate](https://www.accumulate.be/index.html) Technical Meeting, August 2016

# Posters

* [Large Language Models are Zero-shot Oncology Information Extractors](posters/GptExtract.pdf) <br/>
AMIA Annual Symposium, 2023

* [Training a transferrable clinical language model from 75 million notes](posters/UCSF-BERT.pdf) <br/>
AMIA Annual Symposium, 2022

* [Rule induction for global explanation of recurrent neural classifiers](posters/Google NLP summit.pdf) <br/>
3rd Google NLP Summit, Zurich, June 2019

* [Symptom Severity Identification from Psychiatric Evaluation Notes](posters/atila2017.pdf) <br/>
ATILA Workshop, Nijmegen, October 2016

* [Evolution of Language from an Information Theoretic Point of View](posters/info_theory.pdf) <br/>
Saarland University, May 2015

# Thesis
* [Exploring and Understanding Neural Models for Clinical Tasks](https://repository.uantwerpen.be/docman/irua/45481a/madhumita_sushil_phd_thesis.pdf) <br/>
Ph.D. Thesis, March 2021 <br/>
[slides](talks/PhD_defense.pdf)

* Recognizing Textual Entailment <!-- [Recognizing Textual Entailment](thesis/MSc_Thesis.pdf) --> <br/>
M.Sc. Thesis, February 2016 <br/>
[slides](talks/rte.pdf)

<!-- # Technical Reports
* [Automatic Question Generation for Literature Review Writing Support - A Brief Survey](articles/termPaper.pdf) <br/>
Saarland University, September 2014 -->
