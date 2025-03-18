1 : python -m venv env to install
2 : create file requirements.txt to library need install
3: pip install -r requirements.txt
use command uvicorn main:app to run project or  python -m uvicorn main:app --host 0.0.0.0 --port 8000
python -m uvicorn main:app --host 0.0.0.0 --port 8000 --reload