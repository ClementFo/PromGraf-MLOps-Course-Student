# MLOps Course: Prometheus & Grafana - Student

This repository serves as a starting point for the hands-on exercise of the DataScientest MLOps course. Its goal is to guide you through setting up a **monitoring** infrastructure for a machine learning application using **Prometheus** and **Grafana**.

---

### The Goal

In the files of this repository, you will find the basic structure needed to get started. Your task will be to complete the files to:

* **Containerize** the API and the evaluation service.
* **Define** and **orchestrate** all services (the API, Prometheus, Grafana, etc.) in `docker-compose.yml`.
* **Automate** common tasks with a `Makefile`.
* **Add the necessary configurations** so that Prometheus can collect metrics from the application and Grafana can visualize them.

---

### Project Structure

The repository's structure is intentionally simple to allow you to build it step by step during the course.

```
├── deployment
│   ├── prometheus/
│   │   └── prometheus.yml
├── src/
│   ├── api/
│   │   ├── Dockerfile
│   │   ├── main.py
│   │   └── requirements.txt
│   ├── evaluation/
│   │   ├── data/
│   │   │   └── News_Category_Dataset_v3.json
│   │   ├── Dockerfile
│   │   ├── requirements.txt
│   │   └── run_evaluation.py
├── docker-compose.yml
└── Makefile
```

* `deployment/` : This folder will host the configuration files for your monitoring tools.
* `src/` : This folder contains the source code for the API and the evaluation service that you will need to use.
* `docker-compose.yml` : This file is to be completed to define all your services.
* `Makefile` : This file is to be completed to include your automation commands.

This repository is your workspace. Follow the course instructions to complete it and build your own MLOps infrastructure.
