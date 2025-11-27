# 🏷️ api-gateway-service

## ✅ Overview
- Apache Kafka를 이용한 이벤트 발행 및 소비(컨슈머) 패턴 적용
- user-service, point-service와 Kafka 토픽을 통해 비동기 이벤트 방식으로 연동
- 서비스 간 결합도를 낮추고 확장성을 고려한 이벤트 기반 마이크로 서비스 설계
- API Gateway와 통신하여 클라이언트 요청을 받아 내부 서비스로 라우팅하며, 서비스 간 통신을 효율적으로 관리

## ✅ Features
- 사용자 서비스 및 보드 서비스 라우팅 처리
- 포인트 서비스는 내부 호출만 사용하여 별도 라우팅은 없음
- JwtAuthenticationFilter를 통한 JWT 토큰 검증 및 사용자 인증 기능 구현

## ✅ Tech Stack
<div align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />&nbsp
</div>

## ✅ etc
<img width="786" height="393" alt="Image" src="https://github.com/user-attachments/assets/76ae3e03-0a2f-43d1-a86b-ddf25f562708" />
