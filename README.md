LLM Agentic Legal Retrieval
This project implements an LLM-based system for legal document retrieval, combining large language models with information retrieval techniques to efficiently locate relevant legal content.

*Requirements

1. To run this project, you will need to download the following GGUF model from Hugging Face: (we are not able to upload the model gguf file to GitHub as it is too)
mistral-7b-instruct-q4-k-m-gguf
Example model path used in the project:
mistral-7b-instruct-q4-k-m-gguf/gguf/default/1
a.Go to the model repository for the GGUF version of Mistral‑7B‑Instruct.
b.Find the file: mistral-7b-instruct.Q4_K_M.gguf
c.Click Download and place it in your project folder.
3. Setup Instructions
4. Clone the repository.
5. Install the requirements in the requirements.txt file.
6. Download the file court_considerations.csv and laws_de.csv from https://www.kaggle.com/competitions/llm-agentic-legal-information-retrieval/data and add them to your repository in the data.
7. Update all data paths in the code to match the locations of your downloaded files and datasets.
8. Ready to run your file.

Notes
-Ensure the model path in the code matches the location where you stored the GGUF model.
-Verify that all dataset and resource paths are correctly configured before execution.
