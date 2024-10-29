# Langchain Server

## Overview

Langchain Server is a simple API server built using FastAPI and Langchain runnable interfaces. This server provides a chain of operations that can be accessed via API endpoints.

## Features

- FastAPI for creating the API server
- Langchain for creating and managing chains
- Easy to extend and customize

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the server:
    ```sh
    python serve.py
    ```

2. Access the API at `http://127.0.0.1:8000`

## API Endpoints

- **Chain Endpoint**: `/chain`
  - Description: Endpoint to interact with the chain created using Langchain.
