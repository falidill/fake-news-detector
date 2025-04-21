# fake-news-detector
A scalable machine‑learning system for real‑time misinformation detection, combining transformer‑based NLP models with a fully automated MLOps pipeline.
## About

Misinformation on social media and news sites can sway public opinion, influence elections, and erode trust. **Fake News Detector** tackles this by:

- **Aggregating diverse data**: pulls from both established datasets (LIAR, FakeNewsNet, Kaggle) and real‑time news feeds.  
- **Leveraging state‑of‑the‑art NLP**: fine‑tunes BERT, RoBERTa and DistilBERT models to distinguish factual reporting from misleading content.  
- **Automating everything**: uses DVC for data versioning, MLflow for experiment tracking, and GitHub Actions + Airflow for CI/CD and scheduled retraining.  
- **Serving via API**: exposes a FastAPI endpoint so any client can submit an article and get an “real vs. fake” verdict in milliseconds.  
- **Monitoring & A/B testing**: integrates Prometheus/EvidentlyAI to detect performance drift and continuously improve model accuracy.

By the end of this project you’ll have a **production‑ready**, containerized service (Docker/Kubernetes) that flags fake news in real time—and the MLOps machinery to keep it sharp as misinformation evolves. :contentReference[oaicite:2]{index=2}&#8203;:contentReference[oaicite:3]{index=3}
