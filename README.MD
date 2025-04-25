# 🗨️ Chat in real time with Spring Boot, WebSocket and Docker

This project is an **aplicattion chat in real time** developed with **Spring Boot** and **WebSocket**, allowed instantly comunication throw many users. This application is **Dockerizer** to simplify deployment on any environment.

---

## 🚀 Technologies used

- ✅ Java 17
- ✅ Spring Boot 3
- ✅ WebSocket (STOMP on SockJS)
- ✅ Maven
- ✅ Docker & Docker Compose
- ✅ Frontend basic with HTML, CSS and JavaScript (optional)

---

## 🛠️ Functionalities

- 🔄 Real-time two-way communication
- 🧑‍🤝‍🧑 Multiple users can join the chat
- 📬 Sending and receiving messages via WebSocket
- 📦 Production-ready Docker container
- 🧪 Test endpoints available (optional)

---

## 🧑‍💻 How run

### 1. Clone Repository

```bash
git clone https://github.com/tuusuario/chat-app.git
cd chat-app

./mvnw clean install

docker build -t "spring-web-socket"

docker-compose up 
```

### Endpoints and WebSocket

- **Endpoint:**  ws://localhost:8080/chat
- **Topics:** /topic/public

### Autor
Developed by **Breiner Parra (Brin29)** 

### License

- This project is under the MIT license.