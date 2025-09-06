# LLM vs EOS Thermodynamics

🧪🧠📊🌡️This project compares classical thermodynamic models with AI-driven predictions.

🧪 – Thermodynamic systems and EOS modeling
🧠 – AI/LLM intelligence
📊 – Data analysis, predictions, visualization
🌡️ – Key thermodynamic variables (T, P, etc.)

## 📌 Features
- Vapor–liquid equilibrium (VLE) calculations
- Cubic Equations of State (EOS): Peng–Robinson (PR), Soave–Redlich–Kwong (SRK)
- Activity coefficient models: NRTL, UNIQUAC, Wilson, UNIFAC
- Antoine equation Psat tools
- AI/ML predictions via NeuraGPT-mini (Mistral-7B with LoRA adapter)
- Comparisons across:
  - **K-values and K-value ranges**
  - **Vapor fraction (ϕV)**
  - **Bubble/dew temperatures and pressures**
  - **T-x-y / P-x-y diagrams**
  - **Psat(T)** vs experimental

## 🚀 Run
```bash
python -m venv .venv && . .venv/Scripts/activate
pip install -r requirements.txt
streamlit run app/streamlit_app.py
