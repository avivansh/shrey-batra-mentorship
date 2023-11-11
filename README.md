# Shrey-Batra-Mentorship

## Task - 1
- Steps
  - Start learning FastAPI - https://fastapi.tiangolo.com/
  - 2 min read of features (we are going to use Async Python and gonna beat Go performance) - https://fastapi.tiangolo.com/features/
  - Refresher on Concurrency and Async Await (very noob to pro) - https://fastapi.tiangolo.com/async/
  - What are Python Type Hints - https://fastapi.tiangolo.com/python-types/
  - Complete the First Steps under Tutorial to build a Hello World API - https://fastapi.tiangolo.com/tutorial/
- Code
  - Set up virtual environment
  ```python
    python3 -m venv env
  ```
  - install fastapi and uvicorn
  ```python
    source env/bin/activate
    python3 -m pip install "fastapi[all]"
  ```
  - Run
    - Run the server
    ```python
    python3 -m uvicorn task_1.main:app --reload
    ```
    - Go to http://127.0.0.1:8000/




