<h1 align="center">Hi, I'm Sein Lee 👋</h1>
<h3 align="center">문제를 구조적으로 바라보는 백엔드 개발자</h3>

<p align="center">
업무 자동화 · 문서 분석(AIOCR) · LLM 파이프라인 · 시스템 연동 프로젝트를 수행하며<br/>
"동작하는 코드"를 넘어 "운영 가능한 시스템"을 고민합니다.
</p>

<p align="center">
  <a href="https://velog.io/@baby0121"><img src="https://img.shields.io/badge/Velog-20C997?style=flat&logo=velog&logoColor=white" /></a>
  <a href="mailto:sseny0121@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

### 🛠 Tech Stack

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

### 💼 Key Projects

<details>
<summary><b>🧠 신한라이프 생성형AI 활용 PF시스템 자동화 (AIPF)</b> — 애자일소다 · 2025.07 ~ 2025.12</summary>
<br/>

수기 기반 보기/납기 업무를 자동화하는 **3단계 AI 파이프라인**(HWP 구조화 → LLM 추출 → 코드맵핑) 설계·구현

- Redis/Celery 기반 비동기 처리 + Worker 동시성 제어로 대량 문서 처리 환경의 OOM·timeout 이슈 완화
- 단계별(PARSE/EXTRACT/MAPPING) 상태 관리 및 실패 문서만 재처리하는 구조 설계
- AI 기반 문서 구조화 관련 특허 공동 출원, 언론 보도

`Python` `FastAPI` `Redis` `Celery` `MariaDB` `Docker`
</details>

<details>
<summary><b>📄 국민연금 / AXA손해보험 / 한국장학재단 등 AIOCR 구축</b> — 애자일소다 · 2022 ~ 2025</summary>
<br/>

차세대 문서 심사 시스템에 AIOCR 솔루션을 적용해 데이터 자동 추출·가공 및 실시간·비동기 연동 시스템 구현

- 고객사 맞춤형 JSON 스키마 설계 및 RESTful API / 폴링 기반 파일 연동 시스템 구현
- Kubernetes 기반 배포 및 운영, HTTPS 전환 및 콜백 이슈 해결
- 정답지 자동 비교 프로그램 개발로 **검증 시간 80% 이상 단축**

`Spring Boot` `Java` `MySQL` `JavaScript` `ShellScript` `Kubernetes`
</details>

<details>
<summary><b>🏭 세아제강 제조가부 AI 시스템 구축</b> — 애자일소다 · 2025.03 ~ 2025.04</summary>
<br/>

BoM·표준 스펙 문서 기반, LLM과 DLA(Document Layout Analysis)를 활용한 스펙 적합성 자동 판단 AI 분석 파이프라인

- asyncio + Semaphore 기반 병렬 LLM 호출 구조 구현
- 키워드 기반 2단계 검증(Title Prompt → Extract Prompt) 및 결과 정형화 로직 개발

`Python` `OpenAI API` `JSON`
</details>

<details>
<summary><b>📚 EduSoDA 백엔드 개발</b> — 2022.12 ~ 2023.02</summary>
<br/>

학생/기관 사용자를 위한 학습 관리 웹 서비스 백엔드 개발 — Spring Boot 기반 REST API, 역할별 권한 분리, JPA 기반 도메인 모델링

`Spring Boot` `Java` `MySQL` `JPA`
</details>

---

### 🧩 Problem Solving Highlights

- **대용량 트래픽 안정성 개선** — Redis 비동기 큐 재정비 + Worker 동시성 제어 + 장애 격리 구조로 LLM OOM/timeout 발생 빈도 감소
- **Nexacro 환경 Multipart 업로드 처리** — 표준 방식이 동작하지 않는 환경에서 HttpServletRequest 스트림 직접 처리로 우회 해결
- **HTTPS 전환 & 콜백 오류 해결** — SSL/TLS 인증서 적용, Ingress 라우팅 재설계로 포트 분기 및 콜백 이슈 해결

---

### 🎓 Education & Certification

- 한양여자대학교 빅데이터학과 학사 (2023.03 ~ 2024.01)
- 한양여자대학교 컴퓨터정보과 전문학사 (2019.03 ~ 2022.01)
- SQL 개발자(SQLD) 자격증 (2022.12)

---

<p align="center"><i>더 자세한 프로젝트 회고는 <a href="https://velog.io/@baby0121">Velog</a>에서 확인하실 수 있습니다.</i></p>