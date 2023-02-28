# HuggingFace
Tutorial on Hugging Face based on the [official Hugging Face course, 2022](https://huggingface.co/course
). Online accessed February 2023 under Apache 2 license.

This course will teach you about some of the ingredients of the Hugging Face ecosystem, Datasets, Tokenizers and Transformers, through a set of hands-on Jupyter notebooks. These notebooks assume that you are familiar with Python, Pytorch, ML, NLP and Transformer models. I also assume that you are familiar with Clab, otherwise you can take a look at <a href="https://colab.research.google.com/github/probml/probml-notebooks/blob/main/notebooks/colab_intro.ipynb">Kevin Murphy's intro to Colab</a>.

<ol>
<li> <a href="02-Transformers.ipynb">Intro to HuggingFace using the pipeline function</a>: This notebook provides a high-level approach to HuggingFace using the concept of pipeline to tackle a set of NLP tasks. It proposes an exercise to show how easy is to use a state-of-the-art pretrained ASR system.</li>
<li> <a href="03-Pipeline.ipynb">Looking into the pipeline function</a>: It shows the three basic elements of a pipeline function still on a high-level overview. These three elements are Tokenizer (preprocessing), the Model (pre-trained models) and the Pos-processing exemplified on a simple sentiment-analysis (sentences classification) tasks.</li>
<li> <a href="04-Models.ipynb">Overview of working with Models</a>: Short notebook that shows how to load and save models.
</li>
<li> <a href="05-Tokenizers.ipynb">Going into the details of Tokenizers</a>: Explaining the components of Tokenizers in HuggingFace. An exercise is also proposed to apply SentencePiece preprocessing and Encoding.
</li>
<li> <a href="06-Finetuning-T5.ipynb">Finetuning a pretrained MT model</a>: This is a lengthy notebook that includes how to work with Datasets in HuggingFace and how to use them to fine-tune and evaluate a pre-trained model. It is based on a MT task for English into German using the Europarl-ST dataset and the pre-trained T5 model. As exercise, it is proposed to adapt this notebook to fine-tune the mT5 model for the task of English into Spanish MT.
</li>
<li> <a href="07-Finetuning-ImageClassification.ipynb">Finetuning a pretrained image classification model</a>: This notebook includes how to prepare images  to fine-tune and evaluate a pre-trained image classification model. It is based on the fashion MNIST classification task and the pre-trained DeiT model pre-trained and fine-tuned on ImageNet-1k. As exercise, it is proposed to adapt this notebook to fine-tune the same model on the CIFAR-10 dataset.
</li>
</ol>



