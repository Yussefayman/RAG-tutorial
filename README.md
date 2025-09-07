# RAG Tutorial

This is a minimal rag implementation for QA

to be updated.

## Installation

### Install the required packages

```bash
$ pip install -r requirement.txt
```


## Setup the env variables
```bash
$ cp .env.example .env
```

Set your environment variables in the '.env' file. like API keys.

### Run the FastAPI server
```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

### POSTMAN collection availble under assets
RAG app.postman_collection