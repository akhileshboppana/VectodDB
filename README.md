# Sentence Embeddings with VectorDB

This project demonstrates how to generate, store, and query sentence embeddings using [Milvus](https://milvus.io/), an open-source vector database, and [SentenceTransformers](https://www.sbert.net/), a library for generating dense vector representations of sentences.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
  - [Generating Embeddings](#generating-embeddings)
  - [Storing Embeddings in Milvus](#storing-embeddings-in-milvus)
  - [Querying Embeddings](#querying-embeddings)
- [Performance Comparison](#performance-comparison)
- [Acknowledgements](#acknowledgements)

## Introduction

This project showcases the integration of SentenceTransformers with Milvus to perform efficient similarity searches on sentence embeddings. The code includes steps to:
1. Generate sentence embeddings using various models.
2. Store these embeddings in Milvus collections.
3. Query the stored embeddings and compare their performance.

## Features

- Generate embeddings using different SentenceTransformers models.
- Store embeddings in Milvus for efficient similarity search.
- Compare search performance between different collections.

## Setup

To set up the project, follow these steps:

### Prerequisites

- Python 3.6 or higher
- Milvus (installed and running)
- Git (optional, for cloning the repository)

### Install Dependencies

1. Clone the repository:
2. Install necessary python dependencies

## Usage
### Generating Embeddings
Import necessary libraries and initialize models.

Generate embeddings for a list of sentences.

### Storing Embeddings in Milvus
Start the Milvus server and connect to it.

Define the schema and create collections.

Insert embeddings into collections.

### Querying Embeddings
Create and load indices for efficient search.

Perform searches and measure performance.

Print search results.

## Performance Comparison
The code measures and prints the time taken for performing searches in different collections as required. This helps in comparing the efficiency and performance of similarity searches using different models and embeddings.

## Acknowledgements
[Milvus](https://milvus.io/)

[SentenceTransformers](https://www.sbert.net/)

[pymilvus](https://github.com/milvus-io/pymilvus)

This project showcases the powerful capabilities of Vector Databases and SentenceTransformers in handling large-scale vector similarity searches efficiently.
