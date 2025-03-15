# News-Summarization-and-Search-Application

This Python-based command-line application allows users to:

 Search for news articles on specific topics using NewsAPI
 
 Generate brief & detailed summaries using LangChain + Groq API
 
 Perform semantic search using vector embeddings (ChromaDB)
 
 Save search history (last 10 searches)
 
 Manage favorite topics

# Team Members
Ahmed Mohamed Dawood  ID/21100820    

Amr Khaled Gaber    ID/21100834


# Features

Semantic Search: Uses vector embeddings instead of keyword search

 Multi-Level Summarization: Brief (1-2 sentences) & Detailed (paragraph)
 
 AI-Powered Summarization: Uses Groq API (Llama 3) via LangChain
 
 User Preference Management: Saves favorite topics & search history
 
 Efficient Vector Storage: Uses ChromaDB for fast retrieval
 
 Command-Line Interface: Simple and easy to use

# Prerequisites

Python 3.8+

API keys for:

NewsAPI

Groq API


# Installation
Clone this repository:

git clone https://github.com/Ahmed230460/News-Summarization-and-Search-Application.git

# Install Dependencies

Ensure you have Python 3.8+ installed, then run:

pip install -r requirements.txt

# Set Up API Keys

Register for a News API key from NewsAPI.

Get an AI summarization API key from Groq or any preferred service.


# Example Usage

Menu Options:

1️ Search for News – Enter a topic and retrieve news articles with summaries.

2️ View Search History – Check previous topics with saved summaries.

3️ View Favorite Topics – See all favorited topics.

4️ Clear Search History – Remove all saved searches.

5️ Exit – Quit the application.


Select an option: 1  

Enter a topic: AI  

Fetching news...  

🔹 Article 1: Google AI Breakthrough  

Brief Summary: Google introduces a new AI system improving automation.  

Detailed Summary: The article discusses...  

🔹 Article 2: OpenAI's GPT-5 Preview  

Brief Summary: OpenAI announces upcoming AI model with enhanced capabilities.  

Detailed Summary: The article highlights...  

Do you want to add this topic to favorites? (yes/no): yes  

Topic added to favorites.  

