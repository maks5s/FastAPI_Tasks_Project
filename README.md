# FastAPI_Tasks_Project

## How to get started with the project

Run these commands in the terminal:

```bash
python -m venv venv
```
```bash
.\venv\Scripts\activate
```
```bash
pip install -r .\requirements.txt
```

Now project is ready to run

## How to run the project 

Run this command in the terminal:

```bash
uvicorn main:app --reload
```

"--reload" stands for auto reloading then at least one of the project`s files is changed
and changes are saved.

After these steps the project is running at http://127.0.0.1:8000.

To test the API go to http://127.0.0.1:8000/docs.