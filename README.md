# NLP-SQL
Natural language query system for end users
The system gives accurate results for certain class of queries including relational queries, queries involving simple join conditions etc.. using mappings, tokenizing and retrieving information form the enlish-like queries.

Quick Setup

1. Create and activate virtual Environment 
   vitualenv nlpSql
   source nlpSql/bin/activate
 
2. Download required packages 
   pip install -r requirements.txt 
  
3. Download NLTK packages 
   run python interpreter
   import nltk
   nltk.download()
  
4. Run Server 
   python nlp-sql.py

References: 
[1] Garima Singh, Arun Solanki 2016. An algorithm to transform natural language into SQL queries for relational databases. Gautam Buddha University, Greater Noida, India
