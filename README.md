# Talk to Your Database: Natural Language Meets SQL Queries

## Overview
The **Talk to Your Database** project enables seamless interaction with databases through natural language. By leveraging advanced AI models, this application translates user queries in plain English into SQL commands, simplifying data retrieval and manipulation.

## Features
- **Natural Language Processing:** Converts plain language queries into SQL statements.
- **Database Integration:** Executes SQL queries on connected databases and retrieves results.
- **User-Friendly Interface:** Provides an easy-to-use platform for inputting queries and viewing results.
- **Extensible Design:** Supports multiple database systems with minimal configuration.

## Getting Started

### Prerequisites
- Python 3.7 or higher
- Pip (Python package manager)
- Access to a SQL database (e.g., SQLite, MySQL, PostgreSQL)
- OpenAI API key (if using OpenAI's models)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PujaAmmineni/Talk-to-Your-Database-Natural-Language-Meets-SQL-Queries.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Talk-to-Your-Database-Natural-Language-Meets-SQL-Queries
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Configure environment variables:
   Create a `.env` file in the project root and add your API keys and database configurations:
   ```
   OPENAI_API_KEY=your_openai_api_key
   DATABASE_URL=your_database_connection_string
   ```

### Running the Application
1. Execute the main script:
   ```bash
   python main.py
   ```
2. Follow the on-screen instructions to input natural language queries and view results.

## Usage
1. **Input Query:** Enter a question in natural language (e.g., "List all customers who made purchases over $1000 last month").
2. **SQL Translation:** The application translates your input into SQL.
3. **View Results:** The generated SQL is executed, and the results are displayed.

## Technology Stack
- **Python:** Core programming language for application logic.
- **OpenAI API:** Powers the natural language processing capabilities.
- **LangChain:** Framework for integrating and managing language models.
- **SQL Databases:** Compatible with SQLite, MySQL, PostgreSQL, and others.

## Acknowledgments
This project is inspired by the need to make database interactions more accessible through natural language and AI.
