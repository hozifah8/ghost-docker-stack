# Ghost CMS Deployment with Docker

Professional Ghost CMS setup using Docker Compose and MySQL 8.0.

## 🚀 Features
* **Full Stack:** Ghost CMS + MySQL 8.0 database.
* **Persistent:** Data stays safe in Docker Volumes.
* **Secure:** Environment variables handled via `.env`.

## 🛠️ How to Run

1. **Clone the project:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/ghost-docker-stack.git](https://github.com/YOUR_USERNAME/ghost-docker-stack.git)
   cd ghost-docker-stack
2-Create .env file: Add your database credentials inside it.
3-start the containers:
<pre>
 docker compose up -d

## Access
Website: http://localhost:8080
Admin: http://localhost:8080/ghost
