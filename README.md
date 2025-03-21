# FastAPI Tutorial

## Setup
Set up your virtual environment
```bash
python -m venv env
.\env\Scripts\activate
pip install -r requirements.txt
```
If you're running Linux or MacOS you'll instead run
```bash
python -m venv env
source ./env/bin/activate
pip install -r requirements.txt
```

## Running the app
`uvicorn main:app --reload`
`OR`
`python -m uvicorn main:app --host 0.0.0.0 --port 8000 --reload`