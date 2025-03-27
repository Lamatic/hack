# Google Drive RAG Chatbot

Use Google Drive as External Knowledge and implement RAG and use in Chatbot using Lamatic.ai

## Overview
Our intelligent Chatbot offers:
- Sync the External Knowledge using Google Drive Files 
- Implement RAG using in build vector database
- Chatbot with RAG node
- Real-time document processing and indexing
- Automated knowledge base updates

## Structure
Built on Lamatic Studio's powerful framework:
- **Google Drive Node**: Sync files from Google Drive with configurable sync intervals
- **Chunking Node**: Process documents into manageable chunks for better context handling
- **Vectorization Node**: Convert text chunks into embeddings using OpenAI's text-embedding-3-small model
- **Indexing Node**: Store and manage vector embeddings in the built-in vector database
- **RAG Node**: Implement Retrieval Augmented Generation for context-aware responses
- **Chat Interface**: Interactive chat widget for user interactions

## Prerequisites
To get started, you'll need:
- A registered account on [Lamatic Studio](https://studio.lamatic.ai)
- Valid API credentials from OpenAI (for embeddings and chat)
- Google Drive OAuth credentials
- Fundamental knowledge of REST API concepts

## Setup Guide
1. Access your account at [Lamatic Studio](https://studio.lamatic.ai)
2. Initialize a new Flow project
3. Create two flows:
    1. Google Drive Sync Flow (`google-drive.yaml`)
        - Configure Google Drive folder URL
        - Set up sync schedule (default: every 3 hours)
        - Configure chunking parameters
        - Set up vector database indexing
    2. Chatbot Flow (`chatbot-rag.yaml`)
        - Configure RAG parameters
        - Set up embedding and generative models
        - Configure response handling
4. Upload and integrate the YAML configuration files
5. Set up your preferred LLM model, embedding model & Vector Database
6. Deploy your configured setup
7. Validate the functionality through endpoint testing

## Configuration Details
### Google Drive Sync Flow
- Sync Mode: Full refresh with append
- Chunk Size: 200 characters
- Overlap: 20 characters
- Vector Database: GoogleDriveDocs
- Embedding Model: text-embedding-3-small

### Chatbot Flow
- Context Limit: 5 relevant chunks
- Certainty Threshold: 0.5
- Embedding Model: text-embedding-3-small
- Generative Model: gpt-4-mini-2024-07-18
- System Prompt: Configured for direct, context-based responses

For comprehensive guidance, visit our [documentation](https://docs.lamatic.ai/)