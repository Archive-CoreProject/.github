
![팀 아카이브-001 (1)](https://github.com/user-attachments/assets/c459ed32-f5bb-4459-93d6-6d07c9ad7622)
## 1. 프로젝트 개요
**주제 : 음주감지 헬멧 및 자동 잠금기능 보관함이 있는 공유 킥보드🛴**
- 킥보드를 대여하려는 사용자의 헬멧 착용 및 음주 여부를 파악하여 킥보드 동작 제어
- 헬멧 도난 방지를 위한 자동잠금장치 기능이 있는 헤드박스 제공
## 2. 주요기능
![image](https://github.com/user-attachments/assets/4c672891-2a4e-430a-a4be-e7a62494dab6)
## 3. 기술스택
|제목|내용|
|------|---|
|사용언어|HTML/CSS, JavaScript, cpp(Arduino)|
|라이브러리/프레임워크|React, Bootstrap, axios, mysql2, express, jwt, etc|
|개발도구|VSCode, ArduinoIDE, Postman, MySQL workbench(cli), etc|
|서버환경|Node.js|
|데이터베이스|MySQL|
|협력도구|Github, Slack|
## 4. 시스템 아키텍처

## 5. 유스케이스
## 6. 서비스 흐름도
## 7. ER 다이어그램
![ER_DIAGRAM](https://github.com/user-attachments/assets/9c3f91e6-6864-426a-84c0-d92c7f4da50c)

## 8 .화면구성
## 9. 팀원역할
|🧰문주원(팀장)|🎶배길준(부팀장)|🛠김문창|🎨안진영|🔎김태윤|
|-----|-----|-----|-----|-----|
|센서 및 액추에이터<br/>정상 동작 확인 및 배선|서버 설계|DB 모델링|서비스 소개 페이지 제작|시장 조사|
|센서 배치|보드 to 보드 통신 구현|킥보드 부품 조립|킥보드 동작 구현| - |
| - |클라이언트 - 서버 통신 구현|웹 서비스 화면 디자인|발표자료 제작| - | 


## 10. 트러블슈팅

# 🛴 음주감지 헬멧 및 자동 잠금기능 보관함이 있는 공유 킥보드 

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

## 소개
**스마트 킥보드 프로젝트** 여러 사용자 기능을 제공하는 IoT 기반의 스마트 킥보드 시스템입니다. 이 프로젝트는 Node.js 백엔드, React 프론트엔드, Arduino 마이크로컨트롤러 및 MySQL 데이터베이스를 사용하여 완성되었습니다.

## 주요 기능
- **스마트 헬멧박스**: 헬멧 도난 방지를 위한 헬멧박스. 사용 인증을 해야지만 잠금이 해제되어 대여 가능 
- **킥보드 제어**: 음주감지 및 착용감지 헬멧을 통한 킥보드 동작 제어
- **사용자 관리**: 음주측정 결과에 따른 사용자의 서비스 이용 제한 가능

## 서비스
- Frontend (React): 사용자 인터페이스와 관련된 모든 작업을 처리
- Backend (Node.js): API 제공 및 데이터 처리
- Arduino (ESP32): 센싱된 값과 사용자의 사용 여부에 따른 동작 처리
- Database (MySQL): 사용자, 킥보드, 주행 데이터 저장 및 관리

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
