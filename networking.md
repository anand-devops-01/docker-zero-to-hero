# Docker Networking Basics

## What is Docker Networking?
Docker networking allows containers to communicate with each other and with the outside world.

---

## Types of Docker Networks

### 1. Bridge Network (Default)
- Default network in Docker
- Containers communicate using internal IP

### 2. Host Network
- Container uses host machine network directly
- No isolation

### 3. None Network
- No network access
- Fully isolated container

---

## Common Commands

### List networks
docker network ls

### Inspect network
docker network inspect bridge

### Run container with port mapping
docker run -d -p 8080:80 nginx

---

## Port Mapping
- Host Port → Container Port

Example:
8080:80  
👉 8080 = your system  
👉 80 = container (nginx)

---

## Why Networking is important in DevOps?
- Microservices communication
- Kubernetes networking
- Load balancing
- Service discovery