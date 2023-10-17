# Building-Generic-Code-Mixed-Chatbot-for-Banking-System

Bilingual NLP Chatbot for Banking System

## Introduction

Banking is a critical component of a well-functioning economy, yet it often comes with challenges, such as long wait times for simple queries like checking one's balance or blocking an ATM card. To address these issues, we have developed a Bilingual Natural Language Processing (NLP) Chatbot for the banking system.

The primary goal of this project is to create a user-friendly chatbot capable of understanding and responding to user queries in multiple languages. By doing so, we aim to reduce waiting times for customers and enhance the quality of customer service. Chatbots are computer programs designed to comprehend and respond to human queries in a conversational manner using natural language processing techniques. In our case, the chatbot provides answers based on data stored in a database, and it ranks responses using cosine similarity to ensure the most relevant information is delivered to the user.

## Background

In today's world, computers play a crucial role in our lives by running a wide variety of programs. One such program, a chatbot, is designed to simulate intelligent conversations with users through text-based interactions. While chatbots can use existing conversation data or data collected from human interactions and online resources to understand user questions, our application relies on a predefined knowledge base.

Our system uses a question-and-answer protocol, where the chatbot serves as a virtual assistant to answer user queries. The primary objective is to reduce wait times for users who have basic banking-related questions. Users can ask a variety of questions related to banking, saving them the time and hassle of visiting a bank in person.

## Functionality

The chatbot processes user queries by identifying significant keywords in sentences and searching for the most relevant answers in its knowledge base. If the most relevant answer is found, it is presented to the user; otherwise, similar answers are provided. For complex or unique questions not covered by the database, an expert is available to answer them. This personalized approach ensures that users can obtain specific information quickly and conveniently.

To determine the relevance of answers, the chatbot uses a keyword ranking and sentence similarity calculation method based on cosine similarity. We have developed a user-friendly app interface using the JAVA programming language and created an API using the FLASK framework for smooth communication between the chatbot and users.

## Conclusion

Our Bilingual NLP Chatbot for the banking system offers a convenient and efficient solution to common banking-related queries. By combining natural language processing, a well-structured knowledge base, and a user-friendly interface, we aim to improve customer service and reduce wait times for users seeking assistance. This project was presented at the 17th International Conference on Multimedia Information Technology and Applications (MITA) on July 2, 2021.

For more information and details about the project, please refer to the [MITA 2021 Conference Paper](link-to-your-paper).
