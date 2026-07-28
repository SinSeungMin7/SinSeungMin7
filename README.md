
# 신승민 | Sin Seung Min

### Backend Developer

**Java · Spring Boot 기반 백엔드 개발자를 준비하고 있습니다.**

데이터베이스 설계부터 백엔드 로직, REST API,  
실시간 통신과 AI 연동까지 직접 구현하며 개발 경험을 쌓고 있습니다.

---

##  About Me

- Java / Spring Boot 기반 백엔드 개발
- Oracle 기반 DB 설계 및 데이터 처리 경험
- REST API 기반 서버·클라이언트 데이터 통신 구현
- WebSocket(STOMP) 기반 실시간 채팅 구현
- Gemini API를 활용한 AI 회의 요약 기능 구현
- Git / GitHub 기반 팀 프로젝트 협업 경험

---
## 🛠 Tech Stack
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
---

# 🚀 Main Projects

## 🐙 WorkTopus

### 실시간 협업 및 AI 회의록 자동화 플랫폼

> **담당 : 실시간 채팅 시스템 · AI 회의록 자동화**

### 주요 구현

- WebSocket(STOMP) 기반 실시간 메시지 송수신
- 프로젝트별 단체 채팅 및 프로젝트 멤버 간 1:1 개인 채팅
- 채팅 메시지 DB 저장·조회 및 읽음 처리
- USERS / PROJECT_MEMBER / PROJECTS 기반 사용자·프로젝트 데이터 연동
- Gemini 기반 프로젝트 채팅 내용 AI 요약
- AI 회의록 저장·조회 및 게시판 작성 기능 연동

### Tech

`Java` `Spring Boot` `JPA` `Oracle` `JavaScript`  
`Thymeleaf` `WebSocket` `STOMP` `SockJS` `Gemini` `Git/GitHub`

### 🔗 Repository

👉 [WorkTopus GitHub Repository](https://github.com/worktopus/WorkTopus)

---

## 🎨 AI Palette

### 다양한 AI 서비스를 검색하고 추천받을 수 있는 플랫폼

> **담당 : Database · Backend**

### 주요 구현

- Oracle 기반 데이터베이스 구조 설계
- AI 서비스 목록 조회 및 키워드 검색
- 카테고리별 AI 서비스 필터링
- 사용자 즐겨찾기 등록·해제 및 상태 유지
- 인기 AI TOP3 추천 기능
- Spring Boot + MyBatis 기반 데이터 조회 및 처리 로직 구현

### Tech

`Java` `Spring Boot` `MyBatis` `Oracle`  
`JSP` `JavaScript` `AJAX` `Git/GitHub`

### 🔗 Repository

👉 [AI Palette GitHub Repository](https://github.com/ai-palette-project/Ai_Pmt)

---

# 🌿 Git & GitHub Collaboration

팀 프로젝트에서 **기능별 브랜치를 활용하여 개발하고 GitHub 공유 Repository를 통해 팀원들과 코드를 통합**했습니다.

### WorkTopus Branch Workflow

```mermaid
flowchart TB
    A["feature/chat<br/>채팅 · AI 기능 개발"]
    B["Commit"]
    C["Push"]
    D["develop Merge"]
    E["팀 코드 통합"]

    A --> B
    B --> C
    C --> D
    D --> E
