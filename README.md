# psycopg2
This repository provides psycopg2 Python 3.9 Library support for AWS Lambda with ssl.
It is derived from https://github.com/jkehler/awslambda-psycopg2

Copy both the folders psycopg2 and psycopg2_binary.libs to your lambda function zip file.
So overall your lambda function structure should look like:
Your-lambda-funcion --
   --psycopg2
   --psycopg2_binary.libs
   --lambda_function.py
