# íº€ Task 4 â€“ Version-Controlled DevOps Project with Git

## í³Œ Overview
This project is part of the DevOps Internship tasks and focuses on **Git best practices**.  
We created a simple **Python application** that prints system information, containerized it with **Docker**, and managed the repository using a **Git branching workflow**.

---

## í»  Tech Stack
- **Python 3.9**
- **Docker**
- **Git & GitHub**

---

## í³‚ Project Structure
Task-4-DevOps-Git/
â”‚â”€â”€ app/
â”‚ â””â”€â”€ app.py # Python script
â”‚â”€â”€ Dockerfile # Docker configuration
â”‚â”€â”€ .gitignore # Ignored files
â”‚â”€â”€ README.md # Project documentation
â”‚â”€â”€ docs.md # Git workflow documentation
â”‚â”€â”€ screenshots/ # Git process screenshots

yaml
Copy
Edit

---

## í³œ Features
- Prints OS details using Pythonâ€™s `platform` module.
- Dockerized for easy execution anywhere.
- Git workflow:
  - **main** â€“ production-ready branch.
  - **dev** â€“ integration branch.
  - **feature/** â€“ development branch for changes.
  - Pull Requests for merging.
  - Tags for versioning.
  - `.gitignore` for excluding unnecessary files.

---

## âš™ï¸ Setup Instructions

### 1ï¸âƒ£ Clone the Repository
```bash
git clone https://github.com/<your-username>/Task-4-DevOps-Git.git
cd Task-4-DevOps-Git
2ï¸âƒ£ Run Locally
bash
Copy
Edit
python app/app.py
3ï¸âƒ£ Build & Run Docker Container
bash
Copy
Edit
docker build -t task4-app .
docker run --rm task4-app
í¿· Versioning
v1.0 â€“ Initial working app with Docker support.

í³š Learning Outcomes
Learned Git branching & merging.

Practiced Pull Requests.

Used .gitignore effectively.

Added Git tags for version control.

Documented workflow in Markdown.
