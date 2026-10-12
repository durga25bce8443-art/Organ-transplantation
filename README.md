 * Backend:
```bash
cd QuantaOrgan\backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
```

* Frontend:
```bash
cd QuantaOrgan\frontend
npm install
npm run dev
```

Access at http://localhost:3000

Also access through live that I have deployed globally:
https://quantaorgan.web.app
