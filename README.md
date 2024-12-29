# 🎵 VoiceTuner
**메타버스와 AI를 결합한 비대면 보컬 트레이닝 프로그램**

---

## 📜 1. 프로젝트 소개
<div align="center">
  <img width="800" alt="VoiceTuner 메인 이미지" src="https://github.com/user-attachments/assets/9a7d9149-ccb3-4641-a876-ef88952f05b4">
</div>

VoiceTuner는 **실시간 음정 체크**와 **맞춤형 AI 피드백**을 제공하여 사용자의 보컬 학습을 혁신적으로 향상시키는 프로그램입니다. 게임화된 학습 경험을 통해 몰입감 높은 환경을 제공하며, 초보자부터 전문가까지 누구나 쉽게 접근할 수 있는 현대적인 보컬 트레이닝 솔루션을 목표로 합니다.

### 📺 1-1. VoiceTuner 소개 영상 (이미지 클릭)
<div align="center">
  <a href="https://youtu.be/vKhWGwFSEa4?t=4722">
    <img src="https://github.com/user-attachments/assets/94557f8f-5b41-4f23-b555-b5704fad74b6" alt="VoiceTuner 소개 영상 썸네일" width="700"/>
  </a>
</div>

---

## 👥 2. Back-End 팀원 소개
<div align="center">

|                                               김도현                                               |                                               김재협                                               |                                              정현민                                                |
|:-------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------:|
| <img src = "https://avatars.githubusercontent.com/u/94904427?v=4" width = "100" height = "100"> | <img src = "https://avatars.githubusercontent.com/u/73402982?v=4" width = "100" height = "100"> | <img src = "https://avatars.githubusercontent.com/u/148692050?v=4" width = "100" height = "100"> |
|                             [@syamcat](https://github.com/syamcat)                              |                           [@YachaTree](https://github.com/YachaTree)                            |                             [@JungHyeonmin](https://github.com/JungHyeonmin)                             |

</div>

---

## 👨‍💻 3. 프로젝트 환경

### 🛠️ 3-1. 기술 스택
<div align=center> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/jpa-59666C?style=for-the-badge&logo=hibernate&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
</div>

### 🤝 3-2. 협업 툴
<div align=center> 
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
</div>

---

## 🎯 4. 담당 역할

### 김도현
- Unreal Engine과 AI 서버 간 음성 및 텍스트 데이터 전송 파이프라인 구축
- REST API 설계를 통해 사용자 피드백 조회 기능 구현
- 데이터베이스 설계 및 구축

### 김재협
- Unreal Engine과 AI 서버 간 음성 및 텍스트 데이터 전송 파이프라인 구축
- REST API 설계를 통해 사용자 피드백 조회 기능 구현
- JWT 로그인 기능 구현

### 정현민
- Unreal Engine과 AI 서버 간 음성 및 텍스트 데이터 전송 파이프라인 구축
- REST API 설계를 통해 모바일 및 PC에서 사용자 피드백 조회 기능 구현
- React 기반 웹페이지 개발로 프로그램 외부에서도 피드백 확인 가능 ([프런트 프로젝트 보기](https://github.com/MTVS-VoiceTuner/VoiceTuner-BackEnd-FE))
- YouTube Data API를 활용한 맞춤형 연습 영상 추천 기능 구현

---

## 🌐 5. 프로젝트 아키텍처

### 🏗️ 5-1. Service Architecture
<div align="center">
  <img src="https://github.com/user-attachments/assets/a1e23439-5a05-4620-a69c-92021c710da5" alt="Service Architecture" width="900"/>
</div>

### 🧱 5-2. 음성파일 전달 아키텍처
<div align="center">
  <img src="https://github.com/user-attachments/assets/eb2c8cfc-d9c7-44e4-88b9-e7d5cffb08bf" alt="Audio File Delivery Architecture" width="900"/>
</div>

---

## ✨ 6. 백엔드 기능 소개

### 🔑 6-1. 회원가입 및 로그인
- **JWT 기반 로그인**을 통해 사용자의 보안 및 인증 처리

### 📚 6-2. Unreal과 AI 데이터 통신
- **RestTemplate**을 활용하여 AI 서버와 데이터 전송

### 📂 6-3. 피드백 관련 기능
- **피드백 조회**: 사용자가 받은 AI 피드백 정보를 REST API를 통해 조회
- **음성 데이터 전송**: 사용자의 음성 데이터를 Unreal Engine에서 AI 서버로 전달
- **피드백 텍스트 반환**: AI 서버에서 처리된 맞춤형 피드백 텍스트를 사용자에게 반환
