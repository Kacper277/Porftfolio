## Projects

### ETL-pipeline
End-to-end weather data platform: a pandas-based batch ETL orchestrated by Apache Airflow, a Kafka streaming path with at-least-once delivery and DLQ, both landing in PostgreSQL through idempotent upserts — served by a Streamlit dashboard, tested (90+ tests) and shipped via Docker Compose, GitHub Actions CI/CD and a Terraform IaC scaffold.

- **Technologies**: Python, pandas, SQLAlchemy, PostgreSQL, Apache Kafka (confluent-kafka), Apache Airflow, Streamlit, Docker, GitHub Actions, Terraform, pytest, flake8, pyarrow
- **Repository**: [https://github.com/Kacper277/ETL-pipeline](https://github.com/Kacper277/ETL-pipeline)

### EV Charging Analytics
An end-to-end data platform for EV charging networks: synthetic-but-realistic data generation → medallion architecture in Databricks → SQL analytics → Power BI dashboard with tariff what-if scenarios. The platform processes data through three layers (Bronze/Silver/Gold) from 80.8k records and offers interactive "what-if" scenarios for charging cost optimization.

- **Technologies**: Databricks (PySpark, Delta Lake), SQL, Power BI, pandas, NumPy, pytest, mypy, ruff
- **Repository**: [Kacper277/ev-charging-analytics](https://github.com/Kacper277/ev-charging-analytics)

### Defect Detection API
A REST API for classifying surface defects on steel. The solution is built around a fine-tuned ResNet-18 model trained on the NEU-DET dataset. It provides classification outputs and Grad-CAM heatmaps for interpretability. The service is containerised with Docker and runs on Microsoft Azure.

- **Technologies**: PyTorch, Streamlit, Uvicorn, OpenCV, Docker, Azure
- **Repository**: [Kacper277/defect-detection-api](https://github.com/Kacper277/defect-detection-api)

### Neural Backtester
A backtesting framework for evaluating neural-network-driven trading strategies. It enables historical simulation, performance visualisation, and analysis of model predictions on financial time-series data.

- **Technologies**: PyTorch, Streamlit, Uvicorn
- **Repository**: [Kacper277/neural-backtester](https://github.com/Kacper277/neural-backtester)

## Core Stack

- **Languages**: Python, SQL
- **Data Engineering**: SQL, Databricks, Apache Spark, pandas, NumPy
- **Machine Learning**: PyTorch, ResNet, Scikit-learn
- **Cloud & DevOps**: Docker, Microsoft Azure, AWS, Kubernetes
- **Frameworks**: Flask/FastAPI (REST), Jupyter
- **Visualization**: Power BI, Matplotlib, Plotly
- **Web Serving**: Streamlit, Uvicorn
- **Image Processing**: OpenCV

