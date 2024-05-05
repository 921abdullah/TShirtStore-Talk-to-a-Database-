# TShirtStore-Talk-to-a-Database-

This is an end to end LLM project based on Google Palm and Langchain. I built a system that can talk to MySQL database. User asks questions in a natural language and the system generates answers by converting those questions to an SQL query and then executing that query on MySQL database.

# Installation and Usage
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies using pip
4. Acquire an api key through makersuite.google.com and put it in .env file
5. Setup your database
6. Run the Streamlit app by executing:
   streamlit run main.py
7. The web app will open in your browser where you can ask questions
