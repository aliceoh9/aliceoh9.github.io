# CS492 ML for NLP Fall 2019

## Teaching Staff

- Alice Oh, alice.oh@kaist.edu
- Dongkwan Kim, dongkwan.kim@kaist.ac.kr
- Changmin Lee, changmin.lee@kaist.ac.kr
- **When you send emails, please email to all TAs and prof. Oh. and put "CS492" to the title. (e.g., [CS492] Do we have a class on thanksgiving day?)**

## Important Notes about Registering for this Course

- If you are lucky enough to be registered and selected for this class, PLEASE make sure you will not drop this class after it starts. If you are thinking of just "shopping around" to see what this course is like, please DROP IT NOW, so that students who really want to take this course can register. There were more than 90 students signed up for 40 slots, and dozens of students emailed me that they could not register because they have taken CS492 before. So please give up your seat if you are not serious about this course.
- If you have emailed me about not being able to register for this class because you have taken another CS492 before, you will be entered into a lottery and randomly picked (about 5 students) to be added into this class. You will receive email whether you have been selected this way by July 12. If you are selected, you must come to the first class to get your form signed.
- If you registered for this class but did not get selected, I cannot add you. There are too many students asking to be added. Hopefully some students will be dropping, so you can check frequently to see if there is an available slot.
- This course will be offered again in Fall 2020, probably as a regular course. At that time, we hope to be able to accommodate more students (current limit is 40). So please be patient if you really want to take this course.

## Course Description

This course will cover important problems and concepts in natural language processing and the machine learning models used in those problems.

## Prerequisites  

- You need to have good programming skills in Python.
- You need to have basic understanding of ML concepts. You do not need to have taken CS376 or any other undergraduate ML course, but you need to know concepts such as train vs test data, clustering vs classification, accuracy/precision/recall, overfitting, and basic classification models such as SVM, random forest, etc. You can learn these concepts as we go along, but you may find some lectures and papers difficult to understand if you do not put in extra time to learn these concepts.
- We will use [NumPy](https://numpy.org/)/[TensorFlow](https://tensorflow.org) in in-class exercises. You may start with little prior experience and learn these libraries during this semester, but that will require extra time and effort. Note that we do not provide any lectures about learning libraries.
- The topic of the in-class exercise in week 10 is Korean NLP. You do not need to be fluent in Korean, but you need to know what the Korean alphabet (Hangeul) is and how they combine to form syllables and words.

## Materials
1. [Jacob Eisenstein, Natural Language Processing](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
1. Recent papers from [ACL, EMNLP, NAACL, TACL, etc.](https://aclweb.org/anthology/)
1. (Optional Reference) [Jurafsky an Martin, Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition](https://web.stanford.edu/~jurafsky/slp3/ed3book.pdf)

## Course Goals

By the end of the course, you will be able to

1. Understand important concepts in NLP
1. Read current research papers in NLP 
1. Implement some of the basic ML models for NLP
1. Conduct replication studies based on a recent NLP+ML paper
1. Communicate in written and spoken English about NLP+ML research

## Schedule (Subject to Change)

**Course Dates:** Tuesday, Sept 3 – Thursday, Dec 19, 2019 

**Class Times:** Tuesday and Thursday at 13:00 - 14:15 

| Week |          Dates         |                 Topics                  |             Activity           |
|:-----:|:----------------------:|:---------------------------------------:|:------------------------------:|
|  1 |   Tue/Thurs Sept 3/5                         | Introduction / Math Review | Discussions |
|  2 |   Tue/Thurs Sept 10/12                    | Word Vectors & Distributed Semantics / No Class on Sept 12 (Holiday) | Discussions |
|  3 |   Tue/Thurs Sept 17/19                        | Word Vectors / Text Classification | word2vec (Tues) |
|  4 |   Tue/Thurs Sept 24/26                     | Text Classification | BOW & Logistic Regression (Tues) |
|  5 |   Tue/Thurs Oct 1/3                      | Text Classification / No Class on Oct 3 (Holiday)| Naive Bayes (Tues) |
|  6 |   Tue/Thurs Oct 8/10                     | Project Proposal Presentations | Proposal Evaluation |
|  7 |   Tue/Thurs Oct 15/17                         | Language Models | N-grams (Thurs) |
| 8 |   Tue/Thurs Oct 22/24                        | Midterm Exam |
| 9 |   Tue/Thurs Oct 29/31                          | Sequence Models | RNN (Thurs) | 
| 10 |   Tue/Thurs Nov 5/7                      | Machine Translation & Multilinguality | Korean NLP |
| 11 |   Tue/Thurs Nov 12/14                     | Neural Language Models (ELMo, BERT, XLNet) | Discussions |
| 12 |   Tue/Thurs Nov 19/21                     | NLP Applications (QA, Dialogue, Information Extraction, etc) | Discussions |
| 13 |   Tue/Thurs Nov 26/28                     | Project Paper Presentations  | Presentation Evaluation |
| 14 |   Tue/Thurs Dec 3/5                     | Project Paper Presentations  | Presentation Evaluation |
| 15 |   Tue/Thurs Dec 10/12                     | Project Presentations  | Presentation Evaluation |
| 16 |   Tue/Thurs Dec 17/19                    | Project Report Due | None |


## Team Projects

You will form teams of three, and as a team, pick one paper from ACL, EMNLP, NAACL, or TACL, published in 2016 to 2019, and replicate it. You will be required to change at least one thing -- dataset, model, or research question. More details will be given out during the first week of class.

## Evaluation
Your grade will be a combination of the following:

- Participation and attendance 10%
- Midterm exam 25%
- In-class exercises 15%
- Team Project 50% 
  - Proposal 5%
  - Paper presentation 10%
  - Final presentation 20%
  - Written report 10%
  - Teamwork 5% (Note that any team may get up to -25% if there is a serious problem with teamwork)
  
## Paper List for Team Projects (Can be revised during the first two weeks)

Document Classification

- Convolutional Neural Networks for Sentence Classification (EMNLP 2014)
- Character-level Convolutional Networks for Text Classification (NIPS 2015)
- Hierarchical Attention Networks for Document Classification (NAACL 2016) 

Language Modeling & Transfer Learning

- Character-Aware Neural Language Models (AAAI 2016)
- Regularizing and Optimizing LSTM Language Models (ICLR 2018)
- Deep Contextualized Word Representations (NAACL 2018)
- Universal Language Model Fine-tuning for Text Classification (ACL 2018)
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (NAACL 2019)

Word, Sentence, and Document Embedding

- Enriching Word Vectors with Subword Information (TACL 2017)
- Subword-level Word Vector Representations for Korean (ACL 2018)

Machine Translation / Multilinguality

- Convolutional Sequence to Sequence Learning (ICML 2017)
- Attention Is All You Need (NIPS 2017)
- Word Translation Without Parallel Data (ICLR 2018)
- Unpaired Sentiment-to-Sentiment Translation: A Cycled Reinforcement Learning Approach (ACL 2018)
- Adversarial Deep Averaging Networks for Cross-Lingual Sentiment Classification (EMNLP 2018)
- Non-Autoregressive Neural Machine Translation (ICLR 2018)
- The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation (ACL 2018)
- Depth Growing for Neural Machine Translation (ACL 2019)
- Pay Less Attention with Lightweight and Dynamic Convolutions (ICLR 2019)
- Improving Neural Language Modeling via Adversarial Training (ICML 2019)
- Synchronous Bidirectional Neural Machine Translation (TACL 2019)
- Self-Attention with Relative Position Representations (NAACL 2018)

Conversation Modeling / Response Generation

- Building End-To-End Dialogue Systems Using Generative Hierarchical Neural Network Models (AAAI 2016)
- A Hierarchical Latent Variable Encoder-Decoder Model for Generating Dialogues (AAAI 2017)
- A Hierarchical Latent Structure for Variational Conversation Modeling (NAACL 2018)
- DialogWAE: Multimodal Response Generation with Conditional Wasserstein Auto-Encoder (ICLR 2019) 
- Learning from Dialogue after Deployment: Feed Yourself, Chatbot! (ACL 2019)
- Coherent Comments Generation for Chinese Articles with a Graph-to-Sequence Model (ACL 2019)
- ReCoSa: Detecting the Relevant Contexts with Self-Attention for Multi-turn Dialogue Generation (ACL 2019)
- Retrieval-Enhanced Adversarial Training for Neural Response Generation (ACL 2019)
- Proactive Human-Machine Conversation with Explicit Conversation Goal (ACL 2019)
- Learning to Abstract for Memory-augmented Conversational Response Generation (ACL 2019)
- One Time of Interaction May Not Be Enough: Go Deep with an Interaction-over-Interaction Network for Response Selection in Dialogues (ACL 2019)
- Know More about Each Other: Evolving Dialogue Strategy via Compound Assessment
- Neural Response Generation with Meta-words (ACL 2019)
- Improving Neural Conversational Models with Entropy-Based Data Filtering (ACL 2019)
- Domain Adaptive Dialog Generation via Meta Learning (ACL 2019)
- Self-Supervised Dialogue Learning (ACL 2019)

Question & Answering / Summarization

- Get To The Point: Summarization with Pointer-Generator Networks (ACL 2017)
- Inferential Machine Comprehension: Answering Questions by Recursively Deducing the Evidence Chain from Text (ACL 2019)
- Unsupervised Question Answering by Cloze Translation (ACL 2019)
- Entity-Relation Extraction as Multi-Turn Question Answering (ACL 2019)
- RankQA: Neural Question Answering with Answer Re-Ranking (ACL 2019)
- Efficient and Robust Question Answering from Minimal Context over Documents (ACL 2018)
- CNN for Text-Based Multiple Choice Question Answering (ACL 2018)
- An End-to-End model for Question Answering over Knowledge Base with Cross-Attention Combining Global Knowledge (ACL 2017)
- Textbook Question Answering with Multi-modal Context Graph Understanding and Self-supervised Open-set Comprehension (ACL 2019)
- Multi-Hop Paragraph Retrieval for Open-Domain Question Answering (ACL 2019)
- Generating Question-Answer Hierarchies (ACL 2019)
- Answering while Summarizing: Multi-task Learning for Multi-hop QA with Evidence Extraction (ACL 2019)
- Episodic Memory Reader: Learning What to Remember for Question Answering from Streaming Data (ACL 2019)
- Improving the Robustness of Question Answering Systems to Question Paraphrasing (ACL 2019)
- Latent Retrieval for Weakly Supervised Open Domain Question Answering (ACL 2019)
- Careful Selection of Knowledge to solve Open Book Question Answering (ACL 2019)
- Learning Representation Mapping for Relation Detection in Knowledge Base Question Answering (ACL 2019)
- Interpretable Question Answering on Knowledge Bases and Text (ACL 2019)
- NLProlog: Reasoning with Weak Unification for Question Answering in Natural Language (ACL 2019)
- Open-Domain Why-Question Answering with Adversarial Learning to Encode Answer Texts (ACL 2019)

Computational Social Science

- Conversation Model Fine-Tuning for Classifying Client Utterances in Counseling Dialogues (NAACL 2019)
- Conversational Decision Making Model for Predicting King’s Decision in the Annals of the Joseon Dynasty (EMNLP 2018)
- Using millions of emoji occurrences to learn any-domain representations for detecting sentiment, emotion, and sarcasm (EMNLP 2017)
- Conversations Gone Awry: Detecting Early Signs of Conversational Failure (ACL 2018)
- Detecting Incongruity Between News Headline and Body Text via a Deep Hierarchical Encoder (AAAI 2019)
- Word embeddings quantify 100 years of gender and ethnic stereotypes (PNAS 2018)
- Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change (ACL 2016)
- Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints (EMNLP 2017)
- DeClarE: Debunking Fake News and False Claims using Evidence-Aware Deep Learning (EMNLP 2018)
- Multi-agent cooperation and the emergence of (natural) language (ICLR 2017)
- Rumor Detection on Twitter with Tree-structured Recursive Neural Networks (ACL 2018)
- Document-level Sentiment Inference with Social, Faction, and Discourse Context (ACL 2016)

Language Generation

- A Context-aware Convolutional Natural Language Generation model for Dialogue Systems (SIGDIAL 2018)
- Toward Controlled Generation of Text (ICML 2017)
- Semantically Conditioned Dialog Response Generation via Hierarchical Disentangled Self-Attention (ACL 2019)
- Retrieval-Enhanced Adversarial Training for Neural Response Generation (ACL 2019)
- A Conditional Variational Framework for Dialog Generation (ACL 2017)
- Interconnected Question Generation with Coreference Alignment and Conversation Flow Modeling (ACL 2019)
- Cross-Lingual Training for Automatic Question Generation (ACL 2019)
- Syntax-Infused Variational Autoencoder for Text Generation (ACL 2019)
- Towards Generating Long and Coherent Text with Multi-Level Latent Variable Models (ACL 2019)
- Reinforced Dynamic Reasoning for Conversational Question Generation (ACL 2019)
- Generating Sentences from Disentangled Syntactic and Semantic Spaces (ACL 2019)
