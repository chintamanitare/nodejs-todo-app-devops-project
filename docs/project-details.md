
---

## ⚙️ Step-by-Step Implementation

### 🔹 Step 1: EC2 Setup

- Launch Ubuntu EC2
  
![EC2 Instance](../screenshots/ec2.png)

- Clone Github Code

![Git Repo](../screenshots/git.png)

![Git Clone](../screenshots/git%20clone.png)

- Install Docker & AWS CLI

![docker install](../screenshots/docker%20install.png)

- Create AWS USER & Credentials

![aws USER](../screenshots/aws%20user.png)

![aws Aceess key](../screenshots/access%20key.png)

- Configure AWS

![aws configurationl](../screenshots/aws%20configuration.png)


---

### 🔹 Step 2: ECR Setup

- Create ECR repository

![ECR Repository](../screenshots/ecr%20repo.png)

![ECR Repository](../screenshots/img%20pub%20gallery.png)


- Login & push Docker image

---

### 🔹 Step 3: ECS Configuration

- Create ECS Cluster (Fargate)

![ECS Cluster](../screenshots/cluster.png)

- Create Task Definition

![ECS Cluster](../screenshots/task%20defination.png)

---

### 🔹 Step 4: Running Task

- Run task in ECS

![ECS Running Task](../screenshots/task.png)


- Assign public IP

![ECS Cluster](../screenshots/ip.png)

---

### 🔹 Step 5: Application Output

- Access app via browser
- `http://<public-ip>:8000`

![App Output](../screenshots/output.png)

---

### 🔹 Step 6: CloudWatch Logs

- Monitor logs in CloudWatch  
- Log group: `/ecs/node-app`

![CloudWatch Logs](../screenshots/cloudwatch.png)

![CloudWatch Logs](../screenshots/cloudwatch%20logs.png)


---

## 🎯 Outcome

- Successfully deployed a containerized Node.js app
- Implemented serverless deployment using ECS Fargate
- Monitored logs using CloudWatch

---

