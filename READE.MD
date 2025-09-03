# mini-rag-app

This is a minimal implementation of the RAG model for question answering.


## Requirements 
python 3.8 or later 

#### Install Python using MiniConda 

1) Download and install miniconda from [here](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions)

2) Create a new environment using the following command :
```bash
$ conda create -n mini-rag-app python=3.8
```
3) Actiate the environment:
```bash
$ conda activate -n mini-rag-app 
```
### (Optional) Setup you command line interface for better readabily

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation 

### Install the required packages 

```bash
$ pip insall -r requirements.txt
```

### Setup the environment variables 

```bash
$ cp .env.example .env 
```

Set your environememt variables  in the `.env` file like `OPEN_API_KEY` value.

## Run the FastAPI derver 

```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

## POSTMAN Collection 

Download the POSTMAN collection from  # mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirements

- Python 3.8 or later

#### Install Python using MiniConda

1) Download and install MiniConda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)
2) Create a new environment using the following command:
```bash
$ conda create -n mini-rag python=3.8
```
3) Activate the environment:
```bash
$ conda activate mini-rag
```

### (Optional) Setup you command line interface for better readability

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.

## Run the FastAPI server

```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

## POSTMAN Collection

Download the POSTMAN collection from [/assets/mini-rag-app.postman_collection.json](/assets/mini-rag-collection.postman_collection.json)