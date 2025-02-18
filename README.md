# Customer-Support-Agent
This **Customer Support Query Classification &amp; Response Generation Model** first classifies user queries into three categories: **Order Issue, Payment Problem, and General Inquiry** using a trained classifier. Based on the classification, it then generates a professional, natural-sounding response using LLaMA 2.
The model ensures concise, helpful, and human-like replies while avoiding chatbot-like phrasing, making it ideal for automating customer support interactions.

This pipeline follows these steps:

1️⃣ Query Classification:

Trained a model on a small dataset consisting of two features:
Query: The user's question or input.
Category: The classification label with three possible classes:
Order Issue
Payment Problem
General Inquiry
Used Logistic Regression to classify the category of the query.
2️⃣ Response Generation:

Used LLaMA 2 to generate a response based on the classified category.
Ensured responses are professional, natural, and helpful for customer support automation.
This model efficiently automates customer service interactions by combining classification and text generation.
