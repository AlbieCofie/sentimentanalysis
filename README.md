# Sentiment Analysis with Finetuned Models

[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/AlbieCofie/sentimentanalysis.git)
[![Read Article](https://img.shields.io/badge/Read-Article-purple)](https://medium.com/@albiecofie2000/building-a-covid-19-vaccine-sentiment-analysis-app-using-pre-trained-huggingface-models-961c00bfc7c3)
[![Gradio App](https://img.shields.io/badge/Gradio-App-yellow)](https://huggingface.co/spaces/AlbieCofie/sentiment-classification-Gradio-App)

# Introduction

In the wake of the COVID-19 pandemic, our world has witnessed unprecedented challenges and changes in various aspects of life. Alongside the rapid spread of the virus, the internet and social media platforms have become critical sources of information and communication for people across the globe. These platforms have not only provided an avenue for disseminating vital updates but have also become a space for expressing emotions, opinions, and sentiments related to the pandemic.

The development and distribution of COVID-19 vaccines have been monumental milestones in our battle against the global pandemic. These vaccines have provided hope and a pathway to recovery, offering protection against the severe effects of the virus. As vaccination efforts continue to progress worldwide, it becomes increasingly important to gauge public sentiment and understand the prevailing attitudes towards COVID-19 vaccines.

**The objective of this challenge is to develop a machine learning model to assess if a Twitter post related to vaccinations is positive, neutral, or negative. This model will be deployed using streamlit on a Docker Container.**

# Dataset

Tweets have been classified as pro-vaccine (1), neutral (0) or anti-vaccine (-1). The tweets have had usernames and web addresses removed.

**Variable definition:**

**tweet_id:** Unique identifier of the tweet

**safe_tweet:** Text contained in the tweet. Some sensitive information has been removed like usernames and urls

**label:** Sentiment of the tweet (-1 for negative, 0 for neutral, 1 for positive)

**agreement:** The tweets were labeled by three people. Agreement indicates the percentage of the three reviewers that agreed on the given label. You may use this column in your training, but agreement data will not be shared for the test set.

Files available for download are:

**Train.csv** - Labeled tweets on which to train your model

**Test.csv** - Tweets that you must classify using your trained model

**SampleSubmission.csv** - is an example of what your submission file should look like. The order of the rows does not matter, but the names of the ID must be correct. Values in the 'label' column should range between -1 and 1.

**NLP_Primer_twitter_challenge.ipynb** - is a starter notebook to help you make your first submission on this challenge.

# Setup

Fork this repo and run the notebook on Google Colab. The Hugging face models are Deep Learning based, so will need a lot of computational GPU power to train them. Please use [Colab](https://colab.research.google.com/) to do it, or your other GPU cloud provider, or a local machine having NVIDIA GPU.

Note that Google Colab sessions have time limits and may disconnect after a period of inactivity. However, you can save your progress and re-establish the connection to the GPU when needed.

Hugging Face is an open-source and platform provider of machine learning technologies. You can use install their package to access some interesting pre-built models to use them directly or to fine-tune (retrain it on your dataset leveraging the prior knowledge coming with the first training), then host your trained models on the platform, so that you may use them later on other devices and apps.

Please, [go to the website and sign-in](https://huggingface.co/) to access all the features of the platform.

[Read more about Text classification with Hugging Face](https://huggingface.co/tasks/text-classification)

# Evaluation

The evaluation metric for this challenge is the **Root Mean Squared Error**.

## Screenshots

### Streamlit App

![ezgif com-optimize](https://huggingface.co/spaces/AlbieCofie/sentiment-analysis-app)


### Gradio App

![ezgif com-crop (1)](https://img.shields.io/badge/Gradio-App-yellow)](https://huggingface.co/spaces/AlbieCofie/sentiment-classification-Gradio-App)

## Resources

1. [Quick intro to NLP](https://www.youtube.com/watch?v=CMrHM8a3hqw)
1. [Getting Started With Hugging Face in 15 Minutes](https://www.youtube.com/watch?v=QEaBAZQCtwE)
1. [Fine-tuning a Neural Network explained](https://www.youtube.com/watch?v=5T-iXNNiwIs)
1. [Fine-Tuning-DistilBert - Hugging Face Transformer for Poem Sentiment Prediction | NLP](https://www.youtube.com/watch?v=zcW2HouIIQg)
1. [Introduction to NLP: Playlist](https://www.youtube.com/playlist?list=PLM8wYQRetTxCCURc1zaoxo9pTsoov3ipY)
<!-- 1. [](https://www.youtube.com/)
1. [](https://www.youtube.com/) -->

## 👏 Support

If you found this article helpful, please give it a clap or a star on GitHub!

## Author

- [Alberta Cofie](https://www.linkedin.com/in/alberta-cofie-32203881//)
