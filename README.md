# FactBot: Interactive Chatbot for Sharing Interesting Facts

FactBot is an interactive chatbot designed to share interesting facts on various topics using the TF-IDF (Term Frequency-Inverse Document Frequency) technique and cosine similarity. This project aims to enhance user engagement by providing relevant and informative responses based on user queries.

## Features

- **TF-IDF and Cosine Similarity**: Utilizes TF-IDF to analyze the relevance of words in user input and cosine similarity to find the most similar facts from a dataset.
  
- **Interactive Responses**: Capable of responding to greetings, expressions of gratitude, and farewells, enhancing user interaction and experience.

## Subjects Familiar to FactBot

- General Knowledge
- Science and Technology
- History and Politics
- Arts and Entertainment
- Sports and Recreation
- Health and Wellness
- Social and Environmental Issues

## Setup and Usage

### Dependencies

- `nltk`: Natural Language Toolkit
- `scikit-learn`: Machine Learning Library for Python

Install dependencies using:

```bash
pip install nltk scikit-learn
```

### GKFacts Dataset

The GKFacts dataset comprises approximately 1200 facts covering various topics such as history, science, geography, arts, and more.

#### Dataset Description

- **Total Facts**: ~1200
- **Topics Covered**:
  - General Knowledge
  - Science and Technology
  - History and Politics
  - Arts and Entertainment
  - Sports and Recreation
  - Health and Wellness
  - Social and Environmental Issues

### Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AbbiJay/FactBot.git
   cd FactBot
   ```

2. **Install Dependencies and Setup NLTK:**

   ```bash
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

3. **Run the Chatbot:**

   Execute the `factbot.py` script to start the chatbot. Follow the prompts to interact with FactBot and ask for interesting facts.

   ```bash
   python factbot.py
   ```

## Example Interactions

```plaintext
Bot: Welcome to the Fact Bot! I'm here to provide you with interesting facts. Ask me anything, and I'll share a fascinating fact with you.
For ending convo type bye

User: Hey there
Bot: Hi! What can I do for you?

User: Who are you?
Bot: I'm an AI-powered Fact Bot designed to share fascinating facts with you.

User: Can you tell me a fact on the French Revolution?
Bot: The French Revolution took place from 1789 to 1799, leading to the overthrow of the monarchy and the rise of Napoleon Bonaparte.

User: Explain the theory of relativity.
Bot: The theory of general relativity, also by Einstein, provides a framework for understanding gravity as the curvature of spacetime.

User: Thank you
Bot: You're welcome!
```

