# Dockerfile Basics

## 📦 What is Dockerfile?
A Dockerfile is a script used to create Docker images.

---

## 🧱 Basic Example

FROM ubuntu:latest
RUN apt update
RUN apt install -y curl
CMD ["bash"]

---

## 🚀 Real Example (Nginx)

FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html

---

## 🧪 Build Image

docker build -t myimage .

## 🚀 Run Container

docker run -d -p 8080:80 myimage

---

## 💡 Why Dockerfile?
- Automates image creation
- Used in CI/CD pipelines
- Important for DevOps