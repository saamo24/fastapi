# fastapi
The small FastAPI project
You can run this with the following commands

Open your terminal
```
1. git clone git@github.com:saamo24/fastapi.git
2. python -m venv venv
3. source venv/bin/activate
4. pip install -r requirements.txt
```
Create Database
open your terminal
```
1. psql -U postgres
2. CREATE DATABASE fastapi_db;
3. CREATE USER student WITH PASSWORD 'student';
4. ALTER DATABASE fastapi_db OWNER TO student;
5. GRANT ALL PRIVILEGES ON fastapi_db TO student;
6. \q
```
Run the server
```
1. uvicorn main:app --reload
```
Open browser
Go to `localhost:8000/docs`

Enjoy!