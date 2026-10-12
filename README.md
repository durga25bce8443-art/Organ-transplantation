* Backed :
cd QuantaOrgan\backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000


* Frontend : 
cd QuantaOrgan\frontend
npm install
npm run dev

Access at http://localhost:3000

also access through live that i have deployed  globally 
https://quantaorgan.web.app
