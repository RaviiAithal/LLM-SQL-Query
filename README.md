# LLM-SQL-Query

This project demonstrates how to use Large Language Models (LLMs) to generate and execute SQL queries from natural language inputs.

## 🚀 Features
- Convert natural language questions into SQL queries.
- Execute queries on a connected database.
- Supports customization for different schemas and databases.

## 📂 Project Structure
- `main.py` – Entry point for running the application.
- `llm_model/` – Contains logic for connecting and prompting the LLM.
- `db/` – Database connection and query execution utilities.
- `examples/` – Sample natural language queries and expected SQL outputs.

## ⚡ Installation
```bash
git clone https://github.com/RaviiAithal/LLM-SQL-Query.git
cd LLM-SQL-Query
pip install -r requirements.txt
```

## ▶️ Usage
```bash
python sql.py
```

Then, enter a natural language question (e.g., *"Get all employees with salary greater than 50000"*), and the system will generate and execute the corresponding SQL query.

## 🛠 Requirements
- Python 3.8+
- OpenAI / HuggingFace LLM API access
- SQL database (MySQL / PostgreSQL / SQLite)

## 📌 Future Improvements
- Support for multiple databases.
- More robust query optimization.
- Integration with a Streamlit web app for interactive querying.

## 👨‍💻 Author
Developed by [RaviiAithal](https://github.com/RaviiAithal) and the Tutorial from Krish Naik
