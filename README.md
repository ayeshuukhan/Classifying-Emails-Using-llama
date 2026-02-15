## *Project Overview*

This project is an AI-powered email classifier that uses a local Large Language Model (LLM) via llama.cpp to categorize emails into predefined categories based on their content.

The model reads the subject and body of an email and classifies it into one of the following categories:

Priority → Urgent or important emails requiring immediate attention
Updates → Informational emails such as reminders or notifications
Promotions → Marketing or sales emails
This project demonstrates how local LLMs can be used for text classification tasks without relying on cloud APIs.

**Objective**

Build an email classification system using a local LLM

Demonstrate prompt engineering techniques

Process dataset emails and classify them automatically

Allow custom user input for real-time testing

Showcase practical NLP application

## **Technologies Used**

Python

pandas

llama-cpp-python

Local Llama / GGUF model

CSV dataset

Install dependencies pip install pandas llama-cpp-python

## **Download Model**

Download a GGUF Llama or Mistral model and place it inside the model folder.

Example models:

Llama 2

Mistral Instruct

TinyLlama

Dataset

The dataset contains emails with expected categories.

