# ARF
Repository for the master's degree course "Aplicaciones de Reconocimiento de Formas"

Tutorial on text classification based on Keras with several example files:

<ol>
  <li> <a href="src/KerasTutorial_PreTrainedWordEmbedding.ipynb">Pre-trained English Word Embedding </a> </li>
  <li> <a href="src/KerasTutorial-TrainingWordEmbeddingPooling.ipynb">Spanish Word Embedding with global average 1D pooling </a>. In addition, examples of summary model and graph plotting.</li>
  <li> <a href="src/KerasTutorial-TrainingWordEmbeddingConv1D.ipynb">Adding a convolutional 1D layer to the second example</a>.</li>
  <li> <a href="src/KerasTutorial-TrainingWordEmbedding.ipynb">Replacing global average 1D pooling and convolutional 1D layers in previous two examples by a BLSTM layer</a>.</li>
  <li> <a href="src/KerasTutorial-TrainingBilingualModel.ipynb">Bilingual text classifier with independent word embedding and BLSTM layer per language, but common feed-forward layer and softmax output</a>.</li>
  <li> <a href="src/KerasTutorial-TrainingBilingualModelSharedLayer.ipynb">Bilingual text classifier with independent word embedding per language, but shared BLSTM layer</a>.</li>
<!--
  <li> <a href="src/KerasTutorial-NeuralMachineTranslationWithAttention.ipynb"> Neural Machine Translation model based on the attention mechanism</a>.</li>
-->
</ol>

Datasets:
<ol>
  <li> <a href="dat/traveler">Traveler dataset</a>. The Traveler dataset comes from a limited-domain Spanish-English machine translation application for human-to-human communication situations in the front-desk of a hotel. It was semi-automatically built from a small “seed” dataset of sentence pairs collected from traveler-oriented booklets by four persons; A, F,
J and P, in accordance with an independent subdomain assignment, that define 4 classes. The Traveler dataset contains 8.000 sentence pairs, with 2.000 pairs per class.</li>
  <li> <a href="dat/tweets"> Twitter US Airline Sentiment</a>. A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to classify into 3 classes: positive, negative, and neutral tweets. Data source: <a href="https://www.kaggle.com/crowdflower/twitter-airline-sentiment">https://www.kaggle.com/crowdflower/twitter-airline-sentiment</a></li>
</ol>

