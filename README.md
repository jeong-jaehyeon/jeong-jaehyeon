# 안녕하세요, 정재현입니다 👋

**Backend Engineer @ NEXON (7년차)** — 여러 팀이 사용하는 사내 빌드·배포 자동화 플랫폼의 핵심 API 서버를 최다 기여자로 약 3년간 설계·개발·운영하고 있습니다.

비동기 작업 큐의 동시성 제어와 정합성 보정, WebSocket 실시간 상태 동기화, 품질 게이트 기반 CI/CD, PAT/RBAC 인증 설계를 다뤄왔습니다. 최근에는 **LLM 에이전트를 프로덕션 수준으로 통합하는 일을 주도**하고 있습니다 — 민감정보 마스킹, 프롬프트 인젝션 방어, LLM 출력의 서버측 스키마 재검증, 토큰 비용 추적까지, "붙이는 AI"가 아니라 **운영되는 AI**를 만드는 데 관심이 있습니다.

## 🔭 지금 하고 있는 것

- 🤖 빌드 실패를 자동 진단하는 에이전트 시스템 — 클라우드 에이전트 런타임에서 **에이전트를 데이터가 있는 머신으로 보내는 구조**로 재설계
- ☕ Java/Spring 전이 학습: 익숙한 도메인(작업 큐)을 새 기술로 재구현하며 설계 근거를 면접 언어로 정리 중 → [`job-orchestrator`](https://github.com/jeong-jaehyeon/job-orchestrator)
- ✍️ 운영 경험 글쓰기: DB 기반 영속 큐(CAS + reconciliation), 폴링 vs 이벤트 push 트레이드오프

## 🧰 Tech Stack

| 구분 | 스택 |
|---|---|
| **Main** | TypeScript · Node.js · Express · Socket.IO · Sequelize/MariaDB |
| **AI/LLM** | AWS Bedrock AgentCore · Claude · Python(pytest) · 프롬프트 인젝션 방어 · 출력 스키마 검증 |
| **DevOps** | GitLab CI/CD · Docker(DinD) · SonarQube 품질 게이트 · AWS(EC2·RDS·S3) · PM2 |
| **Learning** | Kotlin(JVM) · Spring Boot 3 · JPA · Redis · Testcontainers |

## 📌 대표 프로젝트

- [`agora`](https://github.com/jeong-jaehyeon/agora) — 멀티 AI 코드 리뷰 오케스트레이터. Claude·Gemini·Copilot을 하나의 파이프라인에서 조율
- [`job-orchestrator`](https://github.com/jeong-jaehyeon/job-orchestrator) — 분산 작업 오케스트레이터 (Spring Boot 3 · JPA 낙관적 락 · Redis 분산 락 · Testcontainers). 실무 큐 시스템 경험의 Spring 재현
- [`stock-server`](https://github.com/jeong-jaehyeon/stock-server) / [`stock-client`](https://github.com/jeong-jaehyeon/stock-client) — Express + Sequelize REST API & React 클라이언트

## 📫 Contact

[![Email](https://img.shields.io/badge/wolgus104@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:wolgus104@naver.com)

<!--
추가 예정:
- 기술 블로그 링크 (첫 포스팅 후)
- WebSocket vs ws / Redis Adapter 스케일아웃 데모 레포
-->
