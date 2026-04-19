# mini-rag
This is aminimal implementation of the RAG model for 
question answering.

## Requirements
- Python 3.8 or later

#### Install Python using Miniconda
### (Optional) Setup you command line interface for better readability

## Installation 
### Install the required packages
 # $ pip install -r requirements.txt
 

### setup the environment variables
 
 # $cp .env.example.env
 Set your environment variables in the .env file like 'OPENAI_API_KEY' value.

## Run the FastAPI server
  $ uvicorn main:app --reload --host 0.0.0.0 --port 8001