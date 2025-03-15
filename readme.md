<h1 align="center"><b>🚀 XNL DevOps Platform - AI Powered Multi-Cloud System</b></h1>


## Features:

- [x] 🛠 **Tech Stack:** Spring Boot, FastAPI, Next.js, Vue.js, PostgreSQL, Redis, Kafka, MinIO
- [x] ☁ **Multi-Cloud Deployment:** AWS, GCP, Azure with Kubernetes & Istio
- [x] ⚡ **High Performance:** Supports 500K+ RPS with AI-based scaling
- [x] 🔐 **Security:** OAuth 2.0 + OpenID Connect + JWT Authentication
- [x] 🔄 **CI/CD Pipelines:** GitHub Actions + Jenkins
- [x] 📊 **AI-Powered Monitoring:** Real-time anomaly detection & auto-healing
- [x] 🚀 **Microservices:** REST & GraphQL APIs with Event-Driven Architecture
- [x] 🏗️ **Infrastructure:** Terraform + Kubernetes + Istio + Envoy
- [x] 🛡️ **Chaos Engineering:** Fault tolerance testing with LitmusChaos

---

## 📜 **Tech Stack**
| Layer        | Technologies Used |
|-------------|-----------------|
| **Frontend** | Next.js, Vue.js, Tailwind CSS |
| **Backend**  | Spring Boot, FastAPI, NestJS |
| **Database** | PostgreSQL, Redis, Cassandra, ClickHouse |
| **Storage**  | MinIO, AWS S3 |
| **Messaging** | Kafka, RabbitMQ |
| **Search**   | Elasticsearch, OpenSearch |
| **Authentication** | OAuth 2.0, OpenID Connect, JWT |
| **Monitoring** | Prometheus, Grafana, Loki, AI-based anomaly detection |
| **CI/CD**   | GitHub Actions, Jenkins, Docker |
| **Infrastructure** | Kubernetes, Istio, Envoy, Terraform |

---

## 🏗️ **High-Level Architecture**
- **Frontend:** Next.js & Vue.js with SSR for optimal performance.
- **Backend:** FastAPI & Spring Boot handling high-throughput requests.
- **Database:** Scalable architecture with PostgreSQL, Redis, and Cassandra.
- **Message Queues:** Kafka & RabbitMQ for async event processing.
- **Storage:** MinIO & AWS S3 for efficient object storage.
- **Security:** Advanced authentication & role-based access control.
- **CI/CD:** Automated pipelines for seamless deployments.
- **Kubernetes:** Multi-cloud orchestration with Istio service mesh.

---



## ⚙️ **Setup and Installation**

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-repo/XNL-21BCE2311-DEV-2.git
cd XNL-21BCE2311-DEV-2
```
### 2️⃣ Setup Backend 
```sh
cd backend
mvn clean install
java -jar target/backend-service.jar
```
### 3️⃣ Setup Frontend 
```sh
cd frontend/nextjs-app
npm install
npm run dev
```
### 4️⃣ Setup Database (PostgreSQL)
```sh
docker-compose -f database/docker-compose.yml up -d
```
### 5️⃣ Deploy with Kubernetes
```sh
kubectl apply -f k8s-deployments/
```
## 🛠 Run the Full Stack
```sh
docker-compose up --build
```

## 📜 Contributors
<table> <tr align="center"> <td> Your Name <p align="center"> <img src="https://via.placeholder.com/150" width="150" height="150" alt="Your Name"> </p> <p align="center"> <a href="https://github.com/your-profile"> <img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height="36" alt="GitHub"/> </a> <a href="https://www.linkedin.com/in/your-profile/" target="_blank"> <img src="http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/> </a> <a href="mailto:your-email@gmail.com" target="_blank"> <img src="https://www.iconninja.com/files/312/807/734/share-send-email-chat-circle-message-mail-icon.svg" width="36" height="36" alt="Email"/> </a> </p> </td> </tr> </table>

