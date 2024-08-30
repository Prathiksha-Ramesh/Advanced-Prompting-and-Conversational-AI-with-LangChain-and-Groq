# Advanced Prompting and Conversational AI with LangChain and Groq

This project demonstrates the use of LangChain and Groq to build an advanced prompting and conversational AI system. The project utilizes Neo4j for graph databases, integrates with various APIs, and uses Python notebooks for interactive development.

## Project Structure

project-directory/
 │ ├── prompting.ipynb 
 ├── notebook.ipynb 
 ├── requirements.txt 
 ├── .env ├── README.md 
 ├── LICENSE 
 └── .gitignore

 
## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- Pip (Python package installer)
- Neo4j database

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/langchain-groq-neo4j-prompting.git
cd langchain-groq-neo4j-prompting
```

2. Install the required Python packages:
```bash 
pip install -r requirements.txt
```

3. Set up your environment variables in the `.env` file:

```bash
NEO4J_URI=your_neo4j_uri
NEO4J_USER=your_neo4j_username
NEO4J_PASSWORD=your_neo4j_password
GROQ_API_KEY=your_groq_api_key
```

Replace the placeholders with your actual Neo4j credentials and Groq API key.

## Running the Jupyter Notebooks
- Ensure your .env file is properly configured with your Neo4j credentials and Groq API key.

- Run Jupyter Notebook:

```bash
jupyter notebook
```
- Open `prompting.ipynb` or `notebook.ipynb` to interact with the project.

## Integration Details

- `LangChain`: Used for building advanced language models and managing conversation flows.
- `Groq API`: Provides high-performance AI capabilities, which are used for generating and handling complex prompts.
- `Neo4j`: A graph database used for storing and querying relationships, which enhances the contextual understanding in conversational AI.
- `Streamlit`: An interactive front-end for running the AI system and visualizing results.

## Files

- `prompting.ipynb`: A Jupyter Notebook that contains the main workflow and demonstration of the prompting and conversational AI system.

- `notebook.ipynb`: Additional notebook with further exploration and testing of the system.

- `requirements.txt`: Lists all the Python dependencies needed to run the application.

- `.env`: Contains the API keys and database credentials. This file should not be included in version control.

- `README.md`: This file, providing an overview of the project.

- `LICENSE`: The project's license, specifying how others may use the code.

- `.gitignore`: Specifies files and directories that should be ignored by Git, such as the .env file and any other sensitive information.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## .gitignore
The following files are ignored in version control:

```bash
.env
__pycache__/
*.pyc
*.pyo
*.pyd
```
## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments
- Thanks to LangChain for providing robust tools for language model development.
- Thanks to Groq for offering cutting-edge AI capabilities.
- Thanks to Neo4j for enabling efficient graph database management.
- Thanks to Streamlit for providing an easy-to-use platform for interactive applications.
