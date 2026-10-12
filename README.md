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


### Key Highlights from the Specification

1. **Layered System Architecture:**
   * Detailed **Mermaid flowcharts** and **sequence diagrams** mapping interactions
   * **Next.js 15 / React 19** frontend
   * **FastAPI / SQLAlchemy REST gateway**
   * **Persistence tiers**

2. **Quantum vs. Classical Engine:**
   * **QUBO Hamiltonian mappings**
   * **p-layer QAOA** parameterized ansatz circuits on **IBM Qiskit Aer**
   * Baseline comparisons against **SciPy Hungarian/MILP solvers**

3. **Deterministic Clinical Rule Engine:**
   * Algorithmic evaluation of **ABO compatibility**
   * **Virtual CDC**
   * **DSA screening**
   * Organ-specific **cold ischemia decay limits**

4. **Security & Compliance Architecture:**
   * **6-role RBAC matrix**
   * **RFC 7519 JWT** session security
   * **SHA-256 chained** tamper-evident audit trails

5. **Deployment Topologies:**
   * Cloud **CDN architecture** on **Firebase Hosting** (`quantaorgan.web.app`)
   * Local standalone execution from your `OT_QUANTA.zip` package




    # 🏥 QuantaOrgan Platform
> Real-time donor coordination, deterministic crossmatch, and quantum allocation research.

## 🖥️ Platform Preview

<p align="center">
  <img src=""C:\Users\SASI\Pictures\Screenshots\Screenshot 2026-10-12 164413.png"" alt="QuantaOrgan Clinical Transplant Dashboard Preview" width="100%">
</p>
