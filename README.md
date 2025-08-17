# GraphRagPrivacyPolicy

A demonstration notebook for applying Graph-based Retrieval-Augmented Generation (GraphRAG) techniques to privacy policy documents. This repository provides resources for constructing a knowledge graph from privacy text, performing queries, and generating compliance-aware answers via LLMs.

## Features

- **Entity & Relationship Extraction:** Converts privacy policy documents into a graph of entities (e.g., users, data types) and their relationships (e.g., data sharing, collection purposes).
- **Community Detection & Summarization:** Groups related entities for thematic exploration.
- **Question-Answering Pipeline:** Answers questions about privacy policy using the graph structure and LLMs.
- **Privacy-Aware Outputs:** Ensures responses highlight compliance and key concepts.

## Usage

1. **Clone Repository**
    ```
    git clone https://github.com/Himadri001/GraphRagPrivacyPolicy.git
    cd GraphRagPrivacyPolicy
    ```

2. **Install Requirements**
    - Python 3.8+, Jupyter Notebook.
    - Required libraries (e.g., pandas, networkx, transformers).
    ```
    pip install -r requirements.txt
    ```

3. **Run the Notebook**
    - Open `GraphRag.ipynb` and execute cells step-by-step.
    - Replace or add privacy policy text as needed.


## Applications

- Privacy compliance audits
- Policy analytics for GDPR, CCPA, etc.
- Automated regulatory QA

## Contributing

Suggestions, issues, and pull requests are welcome!

## License

MIT License


