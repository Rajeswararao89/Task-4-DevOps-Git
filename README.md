# 🚀 Task 4 – Git Workflow Practice with a Simple Python App

## 📌 About This Project
This is my submission for Task 4 of the DevOps Internship.  
For this task, I created a small Python program that prints basic system information, and I also wrote a Dockerfile to containerize it.  
The main goal was to practice **Git best practices** — working with different branches, using pull requests, tagging versions, ignoring unnecessary files, and keeping proper documentation.

---

## 🛠 Tools & Technologies Used
- **Python 3.9**
- **Docker**
- **Git & GitHub**

---

## 📂 Project Structure
Task-4-DevOps-Git/
│── app/
│ └── app.py # Python script that prints system info
│── Dockerfile # To build the Docker image
│── .gitignore # To ignore unnecessary files in Git
│── README.md # This documentation
│── docs.md # Step-by-step Git workflow followed
│── screenshots/ # Screenshots of Git workflow and outputs


---

## 🏗 How I Worked on This Task
1. Created a new Git repository and connected it to GitHub.
2. Made `main`, `dev`, and `feature` branches.
3. Wrote the Python code and Dockerfile.
4. Added a `.gitignore` file to keep the repo clean.
5. Worked on a feature branch and merged it into `dev` via a Pull Request.
6. Merged `dev` into `main` after review.
7. Added a Git tag `v1.0` for the first version.
8. Documented all steps in `docs.md`.
9. Added screenshots to show the workflow.

---

## ⚙️ How to Run the App

### Run with Python
```bash
python app/app.py
Build and Run with Docker

docker build -t task4-app .
docker run --rm task4-app

🏷 Version
v1.0 – Initial version with Python app and Docker support.

✍️ Author
Rajeswara Rao
DevOps Internship – Task 4 Submission
