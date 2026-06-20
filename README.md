# RealityShield_AI_Generated_Content_Detector
RealityShield: An advanced deep-learning web application designed to counter digital misinformation by detecting deepfakes and manipulated multimedia using Python , ML algorithm like CNN .
# RealityShield: AI-Generated Content & Deepfake Detector

RealityShield is an advanced, end-to-end deep learning web application designed to counter digital misinformation by detecting deepfakes and manipulated multimedia. The system processes video frames/images to identify pixel-level inconsistencies and AI-generated artifacts.

## 🚀 Key Features
* **Full-Stack Architecture:** Features a robust backend API synced with a modern, interactive frontend interface.
* **Deep Learning Core:** Implements a custom trained Convolutional Neural Network (CNN) optimized for deepfake classification.
* **Automated Data Pipeline:** Includes dedicated scripts for synthetic data generation and full multimodal processing pipelines.
* **Production-Ready & Containerized:** Fully dockerized setup using `Dockerfile` and `docker-compose.yml` for seamless microservices management.
* **Testing & Evaluation:** Includes robust testing scripts to evaluate deep learning model accuracy and performance matrices.

## 🛠️ Tech Stack
* **Frontend:** React / Vite (HTML5, CSS3, Modern JavaScript)
* **Backend:** Python, Flask
* **Machine Learning & CV:** TensorFlow / Keras (CNN), OpenCV, NumPy
* **DevOps:** Docker, Docker Compose

## 📁 Repository Structure
```text
├── backend/                  # Flask backend server & API logic
├── frontend/                 # Vite/React configuration and package settings
├── src/                      # Source code for the frontend components
├── memory/                   # Directory tracking states or session metrics
├── reports/                  # Generated assessment and evaluation reports
├── tests/                    # Testing modules for structural evaluation
├── Dockerfile                # Docker image setup instructions
├── docker-compose.yml        # Multi-container orchestrator configuration
├── train_models.py           # Deep Learning CNN architecture and training script
├── complete_pipeline.py      # End-to-end processing and modeling automation workflow
└── requirements.txt          # Python environment dependencies
