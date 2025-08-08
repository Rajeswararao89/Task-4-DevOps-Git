# � Task 4 – Version-Controlled DevOps Project with Git

## � Overview
This project is part of the DevOps Internship tasks and focuses on **Git best practices**.  
We created a simple **Python application** that prints system information, containerized it with **Docker**, and managed the repository using a **Git branching workflow**.

---

## � Tech Stack
- **Python 3.9**
- **Docker**
- **Git & GitHub**

---

## � Project Structure
Task-4-DevOps-Git/
│── app/
│ └── app.py # Python script
│── Dockerfile # Docker configuration
│── .gitignore # Ignored files
│── README.md # Project documentation
│── docs.md # Git workflow documentation
│── screenshots/ # Git process screenshots

yaml
Copy
Edit

---

## � Features
- Prints OS details using Python’s `platform` module.
- Dockerized for easy execution anywhere.
- Git workflow:
  - **main** – production-ready branch.
  - **dev** – integration branch.
  - **feature/** – development branch for changes.
  - Pull Requests for merging.
  - Tags for versioning.
  - `.gitignore` for excluding unnecessary files.

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Task-4-DevOps-Git.git
cd Task-4-DevOps-Git
2️⃣ Run Locally
bash
Copy
Edit
python app/app.py
3️⃣ Build & Run Docker Container
bash
Copy
Edit
docker build -t task4-app .
docker run --rm task4-app
� Versioning
v1.0 – Initial working app with Docker support.

� Learning Outcomes
Learned Git branching & merging.

Practiced Pull Requests.

Used .gitignore effectively.

Added Git tags for version control.

Documented workflow in Markdown.
