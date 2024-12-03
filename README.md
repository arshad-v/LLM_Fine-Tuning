<div align="center">
  <img src="https://raw.githubusercontent.com/AxelStrange/HealChat/main/Assets/HealChat.png" width="300"/>
</div>

# HealChat - Heal your Soul <br>
A mental health chatbot, which specialises in working with individuals who have experienced trauma, depression, anxiety and other mental illnesses. Share your thoughts and concerns & it will try it's best
to heal you.

<!-- ABOUT THE PROJECT -->
## About The Project

Our aim was to create a mental health chatbot, for answering queries related to preserving mental health.
<br><br>
A pre-trained Large Language Model called TinyLlama was used as the base model for our chatbot.
<div align="center">
  <img src="https://raw.githubusercontent.com/jzhang38/TinyLlama/main/.github/TinyLlama_logo.png" width="300"/>
</div>
<br>
For that the path we journeyed are:
<ul>
  <li>
    Created a dataset that contains over 350 questions and answers that relate to mental health.
  </li>
  <li>
    Loaded the base model for the purpose of fine tuning.
  </li>
  <li>
    The model was fine tuned using the above mention dataset, for 30 epochs
  </li>
</ul>

### Retrieval-Augmented Generation (RAG)
RAG, an AI framework for retrieving facts from an external knowledge base to ground large language models (LLMs) on the most accurate, up-to-date information and to give users insight into LLMs' generative process. Used for improving the quality of LLM-generated responses by grounding the model on external sources of knowledge to supplement the LLM’s internal representation of information.





<!-- ABOUT THE PROJECT -->
## Built  With

![Javascript](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Javascript](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![Javascript](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&labelColor=black&logo=google-colab&logoColor=white)
![Javascript](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&labelColor=black&logo=google-sheets&logoColor=white)

## Getting Started

The chatbot was developed using transfer learning techniques by fine-tuning a pre-trained model. The fine-tuning was performed on Google Colab utilizing a T4 GPU for accelerated training.


The links for the model are provided below:<br><br>
The pre-trained model - https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0 <br>
Dataset - https://github.com/AxelStrange/HealChat/blob/main/Dataset/Mental%20Health%20ChatBot.xlsx<br>
HealChat bot model link: https://drive.google.com/file/d/1JaNZHf2BzFOJ-I1cL8DcDxyYo5pVNMXr/view?usp=sharing

## Features
* Customized Responses: Tailored responses based on a dataset designed to address a wide range of mental health topics. 
* Supportive Interactions: Engages users in a supportive and non-judgmental manner.
* Resource Recommendations: Provides users with relevant resources and coping strategies.

## Limitations
* Resource Limitations: Limited computational resources and low dataset volume.
* Data Handling: Ensuring the dataset was comprehensive and representative of diverse mental health issues while maintaining data privacy and ethical standards.
* Recurring response: Due to limited data and inability to fine-tune the model with a large number of epochs, leads to a never ending response
* Improper response: A rare chance to receive an incorrect response from the bot.

## Solutions
* Increase the size of the dataset
* Fine tune the model with a large number of epochs
* By using RAG, we were able to get better responses from the model.
  
## Deployed Model
* hugging face - https://huggingface.co/Jeganz/Healchat-mental_health_chatbot
