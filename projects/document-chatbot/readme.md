# Document Chatbot

A powerful chatbot solution that enables intelligent conversations with your PDF documents using Large Language Models (LLMs).

## Overview
This project implements a document-based chatbot that can:
- Process and understand PDF documents
- Engage in natural conversations about the document content
- Leverage advanced LLM capabilities for accurate responses

## Structure
The chatbot is built using the following Lamatic Studio nodes:
- **Chat Widget**: Provides the user interface for interactions
- **Extract From File Node**: Handles PDF document processing
- **Logic Node**: Manages the conversation flow
- **Text LLM Node**: Powers the intelligent responses

## Prerequisites
Before getting started, ensure you have:
- An active account on [Lamatic Studio](https://studio.lamatic.ai)
- A publicly accessible PDF file URL
- API credentials for your chosen LLM provider

## Setup Guide
1. Log in to [Lamatic Studio](https://studio.lamatic.ai)
2. Create a new Flow project
3. Import the provided YAML configuration
4. Set up your LLM credentials in the Text LLM node
5. Save and deploy your configuration
6. Test the endpoint to ensure everything works correctly

## Usage
After deployment, your chatbot will be ready to:
- Accept PDF documents through the configured endpoint
- Process document content automatically
- Engage in natural conversations about the document
- Provide accurate, context-aware responses

## API Integration
The chatbot exposes a REST API endpoint that accepts requests for:
- Document processing
- Question answering
- Conversation management

For detailed check out the [docs](https://lamatic.ai/docs)