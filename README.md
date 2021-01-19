# NLP Chatbot

This is a chatbot created using NLP over StackOverflow questions data. The bot runs on Telegram and can guide the user to the StackOverflow solutions for the question asked. </br>
To make the bot user friendly, I've used a pre-trained neural network from Chatterbot. The chatterbot is able to simulate dialogue on all non-programming related questions.</br>

The dataset contains tags for each question. The intent of the user is detected from the question and then search for the answer is done among
questions with tag related to the question. Only one tag per question is allowed.

Dataset: https://www.kaggle.com/zethione/stack-overflow-bot-dataset?select=tagged_posts.tsv </br>
 &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;    https://drive.google.com/drive/folders/17YTZMRMpkLx9kR4KvoZ3c4BEovujHZbd
