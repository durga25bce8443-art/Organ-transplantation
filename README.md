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

Key Highlights from the Specification:
Layered System Architecture:
Detailed Mermaid flowcharts and sequence diagrams mapping interactions between the Next.js 15 / React 19 frontend, FastAPI / SQLAlchemy REST gateway, and persistence tiers.
Quantum vs. Classical Engine:
QUBO Hamiltonian mappings, 
𝑝
p-layer QAOA parameterized ansatz circuits on IBM Qiskit Aer, and baseline comparisons against SciPy Hungarian/MILP solvers.
Deterministic Clinical Rule Engine:
Algorithmic evaluation of ABO compatibility, virtual CDC, DSA screening, and organ-specific cold ischemia decay limits.
Security & Compliance Architecture:
6-role RBAC matrix, RFC 7519 JWT session security, and SHA-256 chained tamper-evident audit trails.
Deployment Topologies:
Cloud CDN architecture on Firebase Hosting (quantaorgan.web.app
) and local standalone execution from your OT QUANTA.zip package.
