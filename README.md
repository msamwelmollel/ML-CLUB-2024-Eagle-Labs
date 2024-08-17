# ML Club 2024 - Eagle Labs

This repository contains the code developed for the Presentation at ML Club 2024 at Eagle Labs. The primary focus of this project is to evaluate different chunking strategies used in retrieval-augmented generation (RAG) models, with a specific emphasis on visualizing the RAGAS Score.

## Features

- **Chunking Strategy Evaluation**: The script is designed to evaluate various chunking strategies used in RAG models. It provides insights into how different strategies impact the performance and accuracy of generated answers.
- **RAGAS Visualization**: The script includes a function to create a custom plot that visualizes the components of the RAGAS Score, which measures the quality and relevance of the generated content.
- **Dependencies**: The script installs several required Python libraries, including `langchain`, `pymongo`, `tqdm`, and `matplotlib`, which are essential for conducting the analysis and creating visual outputs.
- **Jupyter Notebook Integration**: Initially developed as a Jupyter notebook, the script can be integrated into Colab for interactive exploration and execution.

## Installation

To run the script, ensure you have Python installed. You can install the required packages using:

```bash
pip install langchain langchain-openai langchain-experimental ragas pymongo tqdm chromadb
```

## Usage

- The script can be run directly in a Python environment or imported into a Jupyter notebook for further customization and experimentation.
- Use the `create_ragas_plot` function to generate a visual representation of the RAGAS score components, including Context Precision, and Context Recall.
- Experiment with different chunking strategies and observe their impact on the RAGAS scores to determine the most effective approach.

## Contributing

Feel free to fork this repository and submit pull requests if you have improvements or new features to add.

## License

This project is licensed under the MIT License.

