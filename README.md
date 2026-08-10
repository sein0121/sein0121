<p align="center">
  <img src="./images/icon.png" width="200" alt="Sein Lee" />
</p>

<p align="center">
  <img src="./images/title.svg" alt="Hi, I'm Sein Lee 👋" height="48" />
</p>
<!-- <h3 align="center">문제를 구조적으로 바라보는 백엔드 개발자</h3> -->

<p align="center">
  <a href="https://velog.io/@baby_potato"><img src="https://img.shields.io/badge/Velog-20C997?style=flat&logo=velog&logoColor=white" /></a>
  <a href="mailto:sseny0121@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

## 🙋 About Me

**문제를 구조적으로 바라보고, 안정적인 시스템을 만들어가는 백엔드 개발자입니다.**

API 설계부터 데이터 처리, 비동기 시스템, 문서 분석 및 시스템 연동까지 다양한 백엔드 개발을 경험했습니다.

기능 구현에 그치지 않고 **성능, 장애 대응, 재처리와 같은 운영 관점에서 문제를 바라보며** 실제 환경에서 안정적으로 동작하는 시스템을 만드는 것을 중요하게 생각합니다.

새로운 기술을 빠르게 익히는 것보다 **문제에 적합한 기술과 구조를 선택하고, 그 이유를 설명할 수 있는 개발자**가 되는 것을 목표로 하고 있습니다.

---

## 🛠 Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Distributed Processing**
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![Asyncio](https://img.shields.io/badge/Asyncio-3776AB?style=flat&logo=python&logoColor=white)

**Database & Infra**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

**Integration**
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)

---

## 💻 Projects

<details open>
<summary><b>🧭 DevPilot</b> — AI 기반 개발자 성장/취업 준비 플랫폼</summary>
<br/>

GitHub, 블로그, 학습 기록, 채용 공고, 이력서 등 흩어진 개발자 데이터를 한곳에 모아 **AI 기반 맞춤형 커리어 코칭**을 제공하는 서비스

- Layered Architecture(Controller → Service → Repository → Domain) 기반 백엔드 설계
- 공통 응답 포맷 및 글로벌 예외 처리를 적용한 RESTful API 구조 설계
- GitHub API / OpenAI API 연동, Docker 기반 로컬 인프라(MySQL, Redis) 구성

`Java 21` `Spring Boot` `Spring Security` `JPA` `MySQL` `Redis` `React` `TypeScript` `Docker`

🔗 [github.com/sein0121/devpilot](https://github.com/sein0121/devpilot)
</details>

<details>
<summary><b>💳 x402 결제 프로토콜 로컬 테스트</b></summary>
<br/>

HTTP 402 상태코드 기반 **x402 결제 프로토콜**을 로컬에서 구현하고, Solana devnet USDC로 실제 결제를 수행해보는 프로젝트

- 402 응답 → 결제 실행 → 서명 재요청 → 서버 검증까지 전체 결제 플로우 직접 구현
- 핵심 결제 로직을 `payment_module.py`로 분리해 LangGraph 등 워크플로우 환경에서 재사용 가능하도록 설계
- Solana RPC를 통한 트랜잭션 서명 검증 로직 구현
- Solana Foundation × Google Cloud 공동 주최 AI 에이전틱 커머스 해커톤을 앞두고 사전 학습용으로 진행

`Python` `Flask` `Solana`

🔗 [github.com/sein0121/x402-test](https://github.com/sein0121/x402-test)
</details>

<details>
<summary><b>💌 DearU</b> — 모바일 초대장 웹 서비스</summary>
<br/>

결혼식, 돌잔치 등 오프라인 이벤트를 위한 초대장 생성부터 참석 여부(RSVP) 응답, 일정 알림, 초대장 공유까지 지원하는 End-to-End 웹 서비스

- React + TypeScript 기반 SPA로 초대장 생성/일정 입력 등 핵심 기능 구현
- Spring Boot 기반 RESTful API 설계 및 CRUD 로직 구현
- JWT 기반 회원가입/로그인 및 토큰 발급·검증 인증 처리 구현

`Spring Boot` `Java` `MySQL` `JPA` `React` `TypeScript` `JWT`

🔗 [github.com/sein0121/dearU](https://github.com/sein0121/dearU)
</details>

<details>
<summary><b>📈 개인 투자자 트렌드 분석 서비스</b></summary>
<br/>

한국거래소(KRX)와 네이버 금융 데이터를 기반으로 개인 투자자의 종목 매매 동향과 관심 종목을 시각적으로 분석하는 RESTful 백엔드 서비스

- KRX OpenAPI 연동으로 개인/기관/외국인 투자자별 매매 정보 수집 및 JPA 기반 MySQL 적재 자동화
- Jsoup 기반 뉴스 크롤러로 종목별 뉴스 데이터 수집 및 제공 기능 구현
- 사용자 맞춤 관심 종목 저장/조회 API 설계 및 구현

`Spring Boot` `Java` `MySQL` `JPA` `Jsoup`

🔗 [github.com/sein0121/personal_investor_trend](https://github.com/sein0121/personal_investor_trend)
</details>

---

## 💼 Career

### 애자일소다 | 플랫폼컨설팅팀
**선임연구원 · Backend Developer**
2022.05 ~ Present

AIOCR 및 생성형 AI 기반 업무 자동화 시스템의 백엔드 개발과 고객사 시스템 연동을 담당했습니다.

**주요 업무**
- Spring Boot / FastAPI 기반 백엔드 API 개발
- OCR 및 LLM 기반 문서 분석 파이프라인 구축
- Redis + Celery 기반 비동기 처리 시스템 개발
- Docker / Kubernetes 기반 애플리케이션 배포 및 운영
- 고객사 환경에 따른 API / 파일 연동 시스템 개발
- 운영 환경에서 발생하는 성능 및 장애 이슈 분석·해결

**주요 프로젝트**
- 생명보험사 생성형 AI 기반 PF 업무 자동화
- 공공기관 AIOCR 구축
- 손해보험사 OCR 구축

---

<!-- <p align="center"><i>더 자세한 프로젝트 회고는 <a href="https://velog.io/@baby0121">Velog</a>에서 확인하실 수 있습니다.</i></p> -->