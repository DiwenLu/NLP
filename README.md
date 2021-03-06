# NLP
DS-GA 1011 course labs + assigments + materials

## Syllabus

#### Course Logistics, 09/04/2019, week 1
Preparation
Python, PyTorch, Jupyter Lab.

#### Machine Learning, 09/11/2019, week 2
Multi-class classification in PyTorch
- NLLLoss in PyTorch
- Autodiff in PyTorch
- Optimization in PyTorch
- Embedding layer in PyTorch
- One-hot vector vs. Indexing

#### Language modeling (1), 09/18/2019, week 3
Count-based N-gram language models
- Using a trie structure for n-gram modeling
- Add-one smoothing
- If time permits, back-off
- How to use kenlm
- Sampling from count-based n-gram models

#### Language modeling (2), 09/25/2019, week 4
Introduction to Google Colab
Recurrent neural networks in PyTorch
- How to properly handle sequence data
- RNNCell vs. RNN
- How to compute the loss function properly
RNN Language modeling in PyTorch
- Computing perplexity
- Comparison to FF-LM and count-based n-gram LM

#### Backpropagation through time and residual networks, 10/02/2019, week 5
Demonstration of learning difficulties in PyTorch
- A deep feedforward network vs. a deep highway network
- A recurrent network vs. a LSTM network

#### Undirected language modelling + attention, 10/09/2019, week 6
Demonstration of BERT-like training of language models
- Explain the BERT objective
- Sampling from the BERT language model


## Assignments
There will be five programming assignments. These assignments are designed to be done by a team of 3-4 students and will be graded by the section leader and/or graders “in person”.

#### Document classification
Dataset: SNLI, MNLI <br>
Models: BoW Neural Networks <br>
Evaluation criteria: Accuracy, Analysis
#### Language models
Dataset: WikiText-2 or WikiText-103 <br>
Models: count-based n-gram LM, neural n-gram LM, recurrent LM <br>
Evaluation criteria: Perplexity, Analysis <br>
#### Transfer learning
Target dataset: MNLI (5%, 10%, 20%, 40% training set) <br>
Source dataset: WikiText-103 <br>
Models: BoW, recurrent nets <br>
Evaluation criteria: Accuracy improvement, Analysis 
#### Neural dialogue models
Dataset: PersonaChat <br>
Models: attention-based sequence-to-sequence using either recurrent nets or transformers <br>
Evaluation criteria: interactive demo of a chit-chat bot <br>
#### Machine reading
Dataset: SQuAD 1.0 <br>
Model: Attention sum reader or later models <br>
Evaluation criteria: build an interactive demo of a machine reading system

