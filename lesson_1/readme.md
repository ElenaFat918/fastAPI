python -m pip install --upgrade pip
pip install fastapi
pip install "uvicorn[standard]"
uvicorn main:app --reload
http://127.0.0.1:8000/

