# Natural Language to SQL Query Generator  

## Description  
This project converts natural language queries into SQL statements using the GPT-Neo 2.7B model. It simplifies database querying by allowing users to input plain text and receive valid SQL code, making data retrieval accessible to non-technical users.  

## Features  
- Converts natural language input to SQL queries.  
- Utilizes GPT-Neo 2.7B for accurate text-to-SQL transformation.  
- Easy-to-use interface for quick results.  

## Technologies Used  
- Python  
- Hugging Face Transformers  
- GPT-Neo 2.7B  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Mrnobody2004/natural-language-to-sql.git
   cd natural-language-to-sql
Install the required Python packages:
bash
Copy
Edit
pip install torch transformers
Usage
Run the script:
bash
Copy
Edit
python txt_to_query.py
Input your natural language query when prompted.
The generated SQL query will be displayed.
Example
Input:

bash
Copy
Edit
List all employees who joined after 2020.  
Output:

sql
Copy
Edit
SELECT * FROM employees WHERE join_date > '2020-01-01';
License
This project is licensed under the MIT License.

Author
Mrnobody2004

vbnet
Copy
Edit

Let me know if you'd like to add or adjust anything!
