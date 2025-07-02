✅ Title : 

"AI-Powered Natural Language SQL Assistant for Employee Database"


💼 Business Use Case :

#### 1. Problem:
* Non-technical stakeholders often need access to data but don't know how to write SQL. Manual reporting or involving technical teams creates delays.

#### 2. Solution:
* This tool allows users to ask natural language questions about employee data (e.g., salaries, roles, counts) and instantly get results and explanations—powered by Google Gemini LLM and SQLite.

#### 3. Impact:
* Speeds up data access
* Reduces dependency on data/tech teams
* Empowers HR, Finance, and Operations to self-serve analytics
-------------------------------------------------------------------------  


🧾 Project Description :

This is a web-based application built with Streamlit that allows users to:
* Ask natural language questions about a local SQLite employee database
* Automatically generate SQL queries using Google's Gemini API
* Execute those queries on a local database
* Display results in a clean, interactive UI
* Optionally explain the SQL logic using Gemini for educational or verification purposes
The underlying database (SB_it_employee1.db) includes a table SB_it_employee1 with the following columns:
* employee_name (text)
* employee_role (text)
* employee_salary (float)


🎯 Key Responsibilities / Features : 

1.Natural Language Input Interface
* Text input for asking questions in plain English

2.Prompt Engineering with Gemini API
* Custom prompt structure to ensure accurate SQL generation

3.SQL Query Execution
* Queries are run safely on the SQLite database
* Error handling included

4.Result Visualization
* Displays tabular results with pandas DataFrame
* Clean layout with Streamlit

5.Explainability
* Gemini explains the SQL logic in natural language for transparency and learning

6.Security & Environment
* Uses .env for API key management
* SQLite ensures lightweight, local data storage


📦 Technologies & Packages Used : 
## Package/Tool<------------------------------------->Purpose
-------------------------------------------------------------
1.streamlit                                 	Web UI for user interaction

2.sqlite3                                     Local database connection & execution

3.pandas	                                    Tabular data handling

4.google.generativeai                       	Access to Gemini LLM for NLP to SQL

5.dotenv	                                    Load API key from .env file

6.os	                                        Environment variable management




























