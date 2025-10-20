# 🐳 Docker Project - Flask App Deployment  

This project demonstrates how to **containerize a Flask web application** using Docker.

---

## 🧩 Steps Followed

### **Step 1:** Build the Docker Image  
```bash
docker build -t shafaqimage .
Step 2: Check Available Images
docker images

Step 3: Run the Container
docker run -d -p 5000:5000 --name shafaqcontainer1 shafaqimage

Step 4: Check Running Containers
docker ps

Step 5: View Logs
docker logs shafaqcontainer1

Step 6: Access Application

Open your browser and visit 👉 http://localhost:5000

🖼️ Screenshots

Below are the screenshots of each step:

1️⃣ Image build successful
2️⃣ Docker images list
3️⃣ Container running
4️⃣ Docker Desktop showing running container
5️⃣ Localhost page
6️⃣ Logs

🧠 Technologies Used

Python 3.9

Flask

Docker

Kubernetes (YAML deployment file)

✨ Author

Shafaq 💫

Cloud Computing Enthusiast | Learning DevOps | Future AI Engineer