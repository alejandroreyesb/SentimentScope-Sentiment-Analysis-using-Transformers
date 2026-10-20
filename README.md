# SentimentScope-Sentiment-Analysis-using-Transformers
In this notebook, you will train a transformer model from scratch to perform sentiment analysis on the IMDB dataset. 

Project code for Udacity's AI Programming with Python Nanodegree program. In this project, you are a Machine Learning Engineer at Cinescope, a growing entertainment company working to enhance its recommendation system. Your task is to fine-tune a transformer-based model for sentiment analysis using the IMDB dataset. By classifying reviews as positive or negative, you will help the company better understand user sentiment and deliver more personalized experiences.

# Run in your own computer

To run in my own laptop was a little tricky.
To create the enviroment in your computer with CUDA I use this command:

pip install torch torchvision torchaudio transformers --index-url https://download.pytorch.org/whl/nightly/cu130

Also you need:
pip install pandas, matplotlib

In `datasets` 3.0.1, an iterable stream was converted to a `DataFrame` without attempting to cast complex columns (such as lists of structs). However, as of `datasets` 3.6.0, a change was introduced in how features and PyArrow are handled. So you can use:
pip install datasets==3.0.1
conda install jupyter notebook
