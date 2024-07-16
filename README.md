# Advanced NLP Research Assistant

This project implements an advanced Natural Language Processing (NLP) research assistant using LangChain, Google's Generative AI, and various APIs including Wikipedia and arXiv. It combines web content processing, embeddings, and a conversational AI agent to provide informative responses about NLP topics, particularly focusing on Word2Vec.

## Features

- Web content loading and processing
- Text splitting for efficient processing
- Embedding generation using Google's Generative AI
- Vector store creation and similarity search
- Integration with Wikipedia and arXiv APIs
- Custom retriever tool for Word2Vec information
- Conversational AI agent with memory

## Prerequisites

- Python 3.7+
- Pip package manager
- Google API key

## Installation

1. Clone this repository:
2. Install the required packages:


## Usage

1. Set up your Google API key as an environment variable when prompted.

2. Run the main script:

3. Interact with the AI agent by asking questions about Word2Vec or related NLP topics.

## Configuration

- Adjust the `chunk_size` and `chunk_overlap` in the `RecursiveCharacterTextSplitter` for different text splitting behavior.
- Modify the `top_k_results` and `doc_content_chars_max` in the API wrappers to change the amount of retrieved information.
- Customize the agent's behavior by adjusting the `max_iterations` and `max_execution_time` in the `AgentExecutor`.
