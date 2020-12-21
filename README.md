# RNN-text_generation
A simple RNN model for text generation.
The model can be trained on any text corpus and used to generate text by giving an input of 3 words.
The first 3 words are taken as an input seed and the output from the generator is fed back as an input to generate text sentence.
Model was trained in colab with 50000 epochs and an accuracy of ~80%.
The training text used was fairly small with just 112 unique words and took nearly 24 mins on CPU.
Further training on a larger text corpus with significantly more training time will yield better results in text generation.
Model can be simply copy pasted in colab notebook for training and text generation
