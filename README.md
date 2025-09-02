# 🚀 Flask Docker App

This is a simple **Flask application** containerized using **Docker**.  
The project demonstrates how to package a Python web app into a Docker image and run it as a container.  

---
```
## 📂 Project Structure
flask-docker-app/
│── app.py
│── requirements.txt
│── Dockerfile
│── README.md
```
yaml
Copy code

---

## ⚙️ Prerequisites
- [Python 3.11+](https://www.python.org/)
- [Docker](https://docs.docker.com/get-docker/) installed on your system

---

## 🛠️ Setup & Run Locally (without Docker)
1. Clone the repository:
   ```
   git clone https://github.com/Pradeeprawat-01/flask-docker-app.git
   cd flask-docker-app
Create a virtual environment & activate it:

```
python -m venv venv
source venv/bin/activate    # Linux / Mac
venv\Scripts\activate       # Windows
Install dependencies:
```
```
pip install -r requirements.txt
Run the app:
```
```
python app.py
Visit the app at:
👉 http://localhost:5000
```
```
🐳 Run with Docker
Build the Docker image:


docker build -t flask-docker-app .
```
Run the container:


docker run -p 5000:5000 flask-docker-app
Open in your browser:
👉 http://localhost:5000

📌 Example Output
When you open the app in your browser, you should see something like:

```
Hello from Flask inside Docker! 🚀
📖 Learnings
```
How to write a Dockerfile for a Python Flask app

How to build and run Docker containers

How to map ports between container and host

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📝 License
This project is licensed under the MIT License.


---


Would you like me to also **add GitHub Action CI/CD workflow** in the repo (so every push automatically builds & tests the Docker image)? That will make your repo look even more professional 🚀
