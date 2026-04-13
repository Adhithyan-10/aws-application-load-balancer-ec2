## 🏗️ Architecture Diagram

This diagram represents a highly available web application architecture using an Application Load Balancer (ALB) and multiple EC2 instances deployed across different Availability Zones.

🖼️ **View Architecture:**
![Architecture](./architecture/architecture.png)

---

### 📌 Architecture Flow

1. **User Request** enters through the internet
2. Traffic is received by the **Application Load Balancer (ALB)**
3. ALB forwards requests to the **Target Group**
4. Target Group distributes traffic across multiple **EC2 instances**
5. Instances are deployed in **multiple Availability Zones (AZ-1, AZ-2)**

---

### ⚙️ Key Components

* **Application Load Balancer (ALB)** – Distributes incoming traffic
* **Target Group** – Routes traffic to healthy EC2 instances
* **Amazon EC2** – Hosts the web application
* **VPC** – Provides network isolation
* **Public Subnets** – Allow internet-facing access

---

### 💡 Key Highlights

* Ensures **high availability** using multi-AZ deployment
* Enables **load distribution** across multiple instances
* Improves **fault tolerance** by avoiding single point of failure

---

### 🔥 Interview Insight

> “The Application Load Balancer distributes incoming traffic across EC2 instances in multiple Availability Zones, ensuring high availability and fault tolerance.”
