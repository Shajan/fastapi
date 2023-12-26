# fastapi

A simple web server using fastapi

## Run locally on laptop

### One time dev setup
  conda activate py_3_11
  python -m venv .venv
  source .venv/bin/activate
  pip install -r requirements.txt

### Development env
  conda activate py_3_11
  source .venv/bin/activate

### Run server from development env
  uvicorn main:app --reload [--port 8000]
  open http://localhost:8000

## Run on cloud
