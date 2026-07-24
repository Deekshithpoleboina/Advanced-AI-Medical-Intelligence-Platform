Advanced AI Medical Intelligence Platform
Overview
End-to-end AI system for chest X-ray analysis using:

PyTorch (DenseNet121 transfer learning)
Grad-CAM explainability
Google Gemini API report generation
FastAPI backend
SQLite + SQLAlchemy history storage
Streamlit frontend
Dockerized setup
Disclaimer: This is AI-assisted output and not a medical diagnosis tool.

Repository
https://github.com/Deekshithpoleboina/Advanced-AI-Medical-Intelligence-Platform

API
GET /health
POST /predict
POST /explain
POST /generate-report
GET /history
GET /history/{id}
Swagger UI: http://localhost:8000/docs

Model
DenseNet121 pretrained on ImageNet, fine-tuned for binary classification:

NORMAL
PNEUMONIA
Run
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
streamlit run frontend/streamlit_app.py --server.port 8501
Deployment Status
Not deployed at submission time. Project is Dockerized and deployment-ready.
