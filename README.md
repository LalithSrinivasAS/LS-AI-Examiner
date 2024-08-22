
# LS AI Examiner

This repository contains a Streamlit application designed for administering and taking exams with AI evaluation. The app includes functionalities for both admins and students, with features to create exams, submit responses, and evaluate answers using the Gemini API.


## Features
### Admin Console:

#### Secure login system
Create and manage exam questions and answers
Save questions and answers to session state for use during student exams

#### Student Portal:

Submit personal details and exam responses
Receive AI-evaluated relevance scores and explanations for each answer
Display and save exam results including scores and explanations to an Excel file

#### AI Evaluation:

Utilize the Gemini API to assess the relevance of student answers against correct answers
Generate a cumulative score and detailed explanations for each question
Data Handling:

Save student data, scores, and explanations to an Excel file
Handle new entries and append to existing records
## API Reference
Gemini API

The Gemini API is used to evaluate the relevance of student answers against correct answers. Below is the information on how the API is utilized within the Streamlit application.
#### Configuration

```http
import google.generativeai as genai

# Securely configure the Gemini API with your API key
genai.configure(api_key='YOUR_API_KEY')
```
Replace 'YOUR_API_KEY' with your actual Gemini API key.



## Authors

- Aithepalli Suresh Lalith Srinivas


## Feedback

If you have any feedback, please reach out to us at as.lalithsrinivas@gmail.com

