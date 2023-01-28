# Is-it-Toxic
An app to check for comment toxicity using LSTMs.

An app for jigsaw toxic comment classification challenge.

Challenge link: https://www.kaggle.com/datasets/julian3833/jigsaw-toxic-comment-classification-challenge

We Vectorize the text sentences and Create a model consisting of an embedding, an LSTM and 4 Dense layers. 

The model is trained on vectorized text for 10 epochs and the model achieves precision and recall scores of 92.95% and 92.73% respectively.

Then we create a web application using Gradio to analyze a comment provided by the user using our trained toxicity model.
