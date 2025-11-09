# Node App Deployment on EC2 with Docker

## 📦 Project Overview
This is a simple Node.js Express app deployed on an AWS EC2 instance using Docker.

## 🛠️ Steps to Recreate

### 1. Install Dependencies
```bash
npm install

#### 2. Run Locally
        npm start

#   Create Docker Image
    docker build -t nodeapp:v1 .

# Run Docker Container
   docker run -d -p 3000:3000 nodeapp:v1

#  Verify

# Open your browser and visit:

# http://<EC2_PUBLIC_IP>:3000


