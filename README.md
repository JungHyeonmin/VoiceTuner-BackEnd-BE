# 📖VoiceTuner
메타버스와 AI를 결합한 비대면 보컬 트레이닝 프로그램

## 📜 1. 프로젝트 소개
<div align="center">
  <img width="800" alt="image" src="https://github.com/user-attachments/assets/9a7d9149-ccb3-4641-a876-ef88952f05b4">
</div>

실시간으로 사용자의 음정을 시각적으로 체크하고, 노래가 끝난 후 AI 가 맞춤형 솔루션을 제공하는 혁신적인 보컬 학습 경험을 목표로 합니다. 게임화된 학습을 통해사용자는 몰입감 있게 학습할 수 있으며, 초보자부터 전문가까지 쉽게 접근할 수 있는 현대적인 보컬 트레이닝 솔루션을 제공합니다.

### 📺 1-1. VoiceTuner 소개 영상(이미지 클릭!)
<div align="center">
  <a href="https://youtu.be/vKhWGwFSEa4?t=4722">
    <img src="https://github.com/user-attachments/assets/94557f8f-5b41-4f23-b555-b5704fad74b6" alt="VoiceTuner 썸네일" width="700"/>
  </a>
</div>

## 👥 2. Back-End 팀원 소개
<div align="center">

  |                                               김도현                                               |                                               김재협                                               |                                              정현민                                                |
  |:-------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------:|
| <img src = "https://avatars.githubusercontent.com/u/94904427?v=4" width = "100" height = "100"> | <img src = "https://avatars.githubusercontent.com/u/73402982?v=4" width = "100" height = "100"> | <img src = "https://avatars.githubusercontent.com/u/148692050?v=4" width = "100" height = "100"> |
|                             [@syamcat](https://github.com/syamcat)                              |                           [@YachaTree](https://github.com/YachaTree)                            |                             [@JungHyeonmin](https://github.com/JungHyeonmin)                             |

</div>

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

## 🎯 4. 담당 역할

### 김도현
- Unreal Engine과 AI 서버 간 음성 및 텍스트 데이터를 효율적으로 전송할 수 있는 파이프라인 구축
- REST API 설계를 통해 사용자의 피드백 조회 기능 구현
- DataBase 구축

### 김재협
- Unreal Engine과 AI 서버 간 음성 및 텍스트 데이터를 효율적으로 전송할 수 있는 파이프라인 구축
- REST API 설계를 통해 사용자의 피드백 조회 기능 구현
- JWT 로그인 구현

### 정현민
- Unreal Engine과 AI 서버 간 음성 및 텍스트 데이터를 효율적으로 전송할 수 있는 파이프라인 구축
- REST API 설계를 통해 모바일 및 PC에서 사용자의 피드백 조회 기능 구현
- 사용자가 피드백을 프로그램 밖에서도 조회할 수 있도록 모바일, 웹페이지에 맞도록 React 기반 웹페이지 개발
- YouTube Data API를 활용해 사용자의 AI 피드백에 기반한 맞춤형 연습 영상 추천 기능 구현


## 🌐 5. 프로젝트 아키텍처
### 🏗️ 5-1. Service Architecture
<div align="center">
  <img src="https://github.com/user-attachments/assets/3afb8349-3fad-4333-a387-4d868bc77d3c" alt="전체 아키텍처" width="900"/>
</div>

## ✨ 6. 기능 소개
### 🔑 6-1. 회원가입, 로그인
- 선생님, 학생을 선택한 뒤 학교, 학년, 반, 학생 번호, 이름, 비밀번호로 회원가입한다.
- 이름, 비밀번호로 로그인한다.
### 📚 6-2. 온작품읽기 자료 제작, 수정, 삭제
- 선생님이 책 제목, 저자, `pdf`를 등록하면 `pdf`를 AI서버로 전송한다. 내용을 기반으로 AI가 열린 질문 2개, 퀴즈 8개, 등장인물 4명, 단체사진 배경 1개를 생성한다.
  - 선생님은 생성된 온작품읽기 자료를 확인하고 열린 질문 2개, 퀴즈 2개를 선택하고 수정한 뒤, 저장한다.
  - 수정한 수업자료를 저장하면 백그라운드에서 배경 이미지를 생성한다.
- 선생님은 기존에 생성한 온작품읽기 자료를 수정, 삭제할 수 있다.
### 🏫 6-3. 수업 생성
- 저장된 온작품읽기 자료를 이용해서 온작품읽기 월드를 생성한다.
### 👩‍🎨 6-4. 아바타 생성
- 학생이 그린 아바타를 AI 서버로 전송하고 아바타에 맞는 애니메이션 2개와 크기가 수정된 아바타 이미지를 받는다.
  - 서버에서 `zip`파일 저장 후 압축 해제한 뒤 이미지와 애니메이션을 하나의 폴더로 저장한다.
  - 하나의 서버에 두개의 서버로 아바타 생성 요청을 보내도록 함.
- 수업에 참가한 다른 학생의 아바타 이미지와 애니메이션을 다운받는다.
### ❓ 6-5. 온작품읽기 활동 1 : 열린 질문
- 열린 질문에 답변을 저장한다.
### 🎭 6-6. 온작품읽기 활동 2 : 핫시팅
- 각 역할 몰입하여 자기소개를 작성한 뒤 저장한다.
- 자기소개를 바탕으로 학생들의 질의응답을 진행한다.
  - 각 질의응답을 `wav`파일로 AI서버로 전송하면 `STT`을 이용하여 서버에서 자기소개에 맞는 질의응답 저장
### 📷 6-7. 온작품읽기 활동 3 : 단체사진
- 단체사진을 저장한다.
### 🖼️ 6-8. 학생 단체사진 조회
- 참가한 수업을 조회하고 수업에서 찍은 단체사진을 최신순으로 확인한다.
### 🗃️ 6-9. 선생님 수업 기록 조회
- 참가한 수업을 조회하고 수업에 참가한 학생들의 활동 기록을 최신순으로 조회한다.
