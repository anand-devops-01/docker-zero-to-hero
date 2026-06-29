# Docker Images vs Containers

## 🧱 What is a Docker Image?
- A Docker image is a blueprint/template
- It contains application code + dependencies
- It is read-only

Example:
nginx image, ubuntu image

---

## 🚀 What is a Container?
- A running instance of an image
- Lightweight and isolated environment

Example:
docker run nginx → container starts

---

## 🔄 Difference

| Image | Container |
|------|----------|
| Blueprint | Running instance |
| Static | Dynamic |
| Cannot run | Runs application |

---

## 🧪 Commands

docker images        # list images
docker ps            # running containers
docker ps -a         # all containers
docker run nginx     # run container
docker stop <id>     # stop container