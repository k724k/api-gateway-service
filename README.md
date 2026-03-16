# 🏷️ api-gateway-service

MSA 환경에서 클라이언트 요청을 각 서비스로 라우팅하고  
JWT 기반 인증을 처리하는 API Gateway 서비스입니다.

---

# 📌 Overview

API Gateway는 클라이언트의 **단일 진입점(Single Entry Point)** 역할을 하며  
요청을 user-service와 board-service로 전달합니다.

또한 JWT 인증 필터를 통해 사용자 인증을 수행합니다.

---

# 🔧 Key Features

### 1️⃣ 서비스 라우팅

Spring Cloud Gateway를 사용하여

- `/users/**` → user-service
- `/boards/**` → board-service

경로 기반 라우팅을 구성했습니다.

---

### 2️⃣ JWT 인증 필터

`JwtAuthenticationFilter`를 구현하여

- Authorization 헤더 검증
- JWT 토큰 파싱
- 사용자 인증 처리

를 수행하도록 구성했습니다.

---

# 🏗 Architecture

<img width="786" height="393" alt="Image" src="https://github.com/user-attachments/assets/76ae3e03-0a2f-43d1-a86b-ddf25f562708" />

---

# 🔗 Related Services

- https://github.com/k724k/user-service
- https://github.com/k724k/board-service
- https://github.com/k724k/point-serivce

---

# ⚙️ Tech Stack

Java  
Spring Cloud Gateway  
Docker  
AWS


