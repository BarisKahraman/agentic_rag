# Agentic RAG for Medical Device Manuals

This repository implements an **Agentic Retrieval-Augmented Generation (RAG)** system designed to intelligently query and retrieve information from medical device manuals. By leveraging an agentic approach, the system can autonomously formulate queries and synthesize answers based on the provided datasets.

## 📂 Repository Structure

- **`agentic RAG.ipynb`**: The core Jupyter Notebook containing the implementation of the RAG pipeline, agent logic, and interaction flow.
- **`chroma_db/`**: Stores the persistent vector database (ChromaDB) used for efficient similarity search and retrieval of document embeddings.
- **`medical_device_manuals_dataset.csv`**: The primary dataset containing the text and metadata of various medical device manuals used as the knowledge base.
- **`train.csv`**: Additional dataset likely used for training, fine-tuning, or evaluating the model's performance.

## 🚀 Features

- **Agentic Workflow**: Goes beyond simple semantic search by using an agent to reason about the user's query and retrieve the most relevant context.
- **Vector Storage**: Utilizes **ChromaDB** for high-performance vector storage and retrieval.
- **Domain Specific**: Tailored for the medical domain, specifically handling technical documentation for devices.

## 🛠️ Getting Started

### Prerequisites

Ensure you have Python installed. You will likely need the following libraries (based on common RAG stacks):

- `langchain` / `langgraph` (or similar agent framework)
- `chromadb`
- `pandas`
- `notebook` or `jupyterlab`
- OpenAI API key (or another LLM provider)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/BarisKahraman/agentic_rag.git](https://github.com/BarisKahraman/agentic_rag.git)
   cd agentic_rag

Install dependencies: (Note: A requirements.txt is not yet provided, but you can install the essentials below)

Bash:
pip install pandas chromadb notebook langchain openai

Run the Application: Launch the Jupyter Notebook to explore the code and run the agent:

Bash:
jupyter notebook "agentic RAG.ipynb"

📊 Data
The system relies on structured CSV data (medical_device_manuals_dataset.csv) to build its knowledge base. Ensure this file is present in the root directory before running the notebook to populate the vector database.

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
