# Docker Volumes

## 💾 What is a Volume?
A volume is used to store data permanently in Docker.

---

## ❗ Problem Without Volume
- Data lost when container stops

---

## ✅ Solution: Volume

- Keeps data safe
- Shared between host and container

---

## 🧪 Command Example

docker run -d -p 8080:80 -v mydata:/data nginx

---

## 📂 Types of Storage

### 1. Named Volume
docker volume create myvolume

### 2. Bind Mount
docker run -v /host/path:/container/path nginx

---

## 💡 Why Volumes?
- Data persistence
- Database storage
- Logs storage