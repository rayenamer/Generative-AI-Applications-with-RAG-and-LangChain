# Generative AI Applications with RAG and LangChain

## Overview

This repository contains a collection of tools and examples for building Generative AI applications using Retrieval-Augmented Generation (RAG) and LangChain. The project demonstrates various components of a RAG pipeline including document loading, text splitting, embedding generation, vector storage, and retrieval.

## Features

- **Document Processing Pipeline**:
  - Document loading from various sources
  - Text splitting/chunking strategies
  - Embedding generation with watsonx
  - Vector storage and retrieval

- **LangChain Integration**:
  - Ready-to-use LangChain components
  - Examples of document loaders, text splitters, retrievers
  - Vector store implementations

- **Demo Applications**:
  - Simple LLM interaction example
  - QA bot implementation
  - Gradio-based demo interface

## Notebook Examples

1. **Embedding Generation**: `embed_documents_with_watsonx_embedding.ipynb`  
   Demonstrates how to generate embeddings using watsonx's embedding models.

2. **Document Processing**:  
   - `LangChain_document_loader.ipynb` - Loading documents from various sources  
   - `LangChain_text-splitter.ipynb` - Text splitting/chunking techniques  
   - `LangChain_vector_store.ipynb` - Storing and querying embeddings in vector databases  
   - `LangChain_retriever.ipynb` - Implementing retrieval components

3. **Limitations**: `Full_document_retrieve_limitation.ipynb`  
   Explores the limitations of document retrieval in RAG systems.

## Python Modules

- `common_input_types.py`: Common data types and schemas used across the project
- `simple_llm.py`: Basic LLM interaction example
- `qabot.py`: Question-Answering bot implementation
- `gradio_demo.py`: Interactive Gradio interface for the QA system

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook (for running the example notebooks)
- Required Python packages (install via `pip install -r requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Generative-AI-Applications-with-RAG-and-LangChain.git
   cd Generative-AI-Applications-with-RAG-and-LangChain
   ```


### Running the Demos

1. For the Gradio interface:
   ```bash
   python gradio_demo.py
   ```

2. For the simple LLM example:
   ```bash
   python simple_llm.py
   ```

3. For the QA bot:
   ```bash
   python qabot.py
   ```

## Contributing

Contributions are welcome! Please open an issue to discuss your proposed changes before submitting a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- IBM watsonx team for the embedding models
- LangChain developers for their amazing framework
- The open-source AI community for continuous inspiration
