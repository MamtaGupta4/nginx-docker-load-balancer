# Nginx Docker Load Balancer 🚀

A simple load balancing system using Nginx reverse proxy and Docker Compose to distribute traffic across backend services.

---

## 📌 Technologies Used
- Docker
- Docker Compose
- Nginx
- HTTP Echo Backend

---

## 📂 Project Structure

```bash
LB-project/
│
├── nginx.conf
└── docker-compose.yaml
```

---

## ⚙️ How It Works

- Nginx acts as a reverse proxy and load balancer
- Backend service runs using `hashicorp/http-echo` image
- Docker Compose manages both services
- Traffic is distributed to backend instances via Nginx upstream

---

## 🚀 Run the Project

### Step 1: Build & Start Containers

```bash
docker compose up -d
```

### Step 2: Access Application

Open browser:

```text
http://localhost
```

---

## 🧠 Learning Outcome

This project helped in understanding:
- Load balancing concept
- Nginx reverse proxy
- Docker networking
- Docker Compose multi-container setup
- Microservices communication

---

## 🌐 Output
Open in browser: http://localhost

## 👩‍💻 Author
Mamta Gupta
