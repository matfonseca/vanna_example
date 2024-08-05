# Vanna Example Proof of Concept (POC)

This project is a basic Proof of Concept (POC) using the Vanna framework to demonstrate how to integrate a simple machine learning model with a vector store and execute SQL queries. The example shows how to define a custom class by combining `Ollama` and `ChromaDB_VectorStore`, interact with a DuckDB database, and use Vanna's capabilities to answer questions related to the data.

## Project Structure

- **MyVanna Class**: Inherits from both `ChromaDB_VectorStore` and `Ollama`.
- **DuckDB Connection**: Creates an in-memory DuckDB database.
- **SQL Execution**: Demonstrates creating a table, inserting data, and querying the database.
- **LLM Integration**: Trains the model to understand the context and answer questions based on the data.

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Poetry for dependency management

### Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd vanna-example
