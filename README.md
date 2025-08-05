# Hello-Devops

A simple Dockerized Python Flask web application with Redis integration, designed for DevOps practice and learning Docker Compose basics.

## Usage

### 1. Clone the repository

```bash
git clone https://github.com/YourUsername/Hello-Devops.git
cd Hello-Devops
```

### 2. Run with Docker Compose

Make sure you have Docker and Docker Compose installed. Then run:

```bash
docker compose up --build
```

This command will build the Flask app and start both the Flask and Redis containers.

### 3. Access the app

Open your browser and go to:

```
http://localhost:5000
```
If running on a server, replace `localhost` with your server's IP address.

### 4. Stop the application

To stop the application and remove the containers:

```bash
docker compose down
```

---

**That’s it! Enjoy practicing DevOps with Docker and Flask.**


