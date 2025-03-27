# Invoice Summarizer

Transform PDF invoices into structured JSON data using advanced language models and intelligent document processing.

## Overview
Our intelligent API offers:
- Automated extraction of structured data from PDF invoices
- Smart interpretation of invoice details including company, customer, and transaction information
- State-of-the-art AI technology for accurate data extraction
- Comprehensive validation and error reporting

## Structure
Built on Lamatic Studio's powerful framework:
- **API Request Node**: Handles incoming GraphQL requests with PDF URL
- **PDF Extraction Node**: Processes and extracts text from PDF documents
- **LLM Processing Node**: Converts extracted text into structured JSON using GPT-4 Turbo
- **Response Node**: Returns formatted JSON responses

## Prerequisites
To get started, you'll need:
- A registered account on [Lamatic Studio](https://studio.lamatic.ai)
- Valid API credentials for:
  - OpenAI (GPT-4 Turbo)
- Fundamental knowledge of GraphQL API concepts

## Setup Guide
1. Access your account at [Lamatic Studio](https://studio.lamatic.ai)
2. Initialize a new Flow project
3. Upload and integrate the YAML configuration file
4. Configure your LLM model in the respective node
5. Deploy your configured setup
6. Validate the functionality through endpoint testing

## Usage
Your deployed API enables you to:
- Submit PDF invoice URLs via GraphQL endpoint
- Automatically extract and structure invoice data
- Receive standardized JSON responses
- Get validation warnings for missing or inconsistent data
- Support various invoice formats and layouts

## API Integration
Access our versatile GraphQL API endpoint for:
- Dynamic invoice processing
- Structured data extraction
- Intelligent data validation
- Real-time JSON responses

For comprehensive guidance, visit our [documentation](https://lamatic.ai/docs)
