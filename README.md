### Hi, I'm Minyeong Ahn

Backend developer focused on Java and Spring Boot.
In a team project, I worked on asynchronous AI processing, message delivery across multiple servers, and a concurrency bug found in production.

- B.S. in Computer Science, Ewha Womans University (2026.02)
- Kakao Tech Bootcamp, 3rd cohort (2025.09 ~ 2026.03)

---

### Projects

**CommitMe — AI resume & mock interview service** · team of 6 · 2025.12 ~ 2026.03
Generates a developer resume from GitHub repositories with AI, and runs AI mock interviews. Deployed three times and used by real users.
- Integrated asynchronous AI callbacks for resume generation
- Prevented a race where a timeout overwrote successful results, using a pessimistic lock
- Routed mock-interview SSE messages across 3 servers with Redis Pub/Sub (targeted delivery)
- Built the React screens for my features (resume PDF, voice answer recording)

`Java` `Spring Boot` `MySQL` `MongoDB` `Redis` `AWS` `React`
→ [My contributions](https://github.com/100-hours-a-week/15-team-service-be/blob/dev/CONTRIBUTIONS-zero.md) · [Backend repo](https://github.com/100-hours-a-week/15-team-service-be)

**Flio — travel-tip community** · personal · 2024.09 ~ 2025.02, improved later
- JWT stateless auth, soft-delete account withdrawal
- Fixed an IDOR vulnerability by taking the writer ID from the JWT
- Removed N+1 queries on list APIs with fetch joins
- S3 image upload, Docker Compose deployment, unit tests

`Java` `Spring Boot` `JPA` `MySQL` `AWS S3` `Docker`
→ [Repository](https://github.com/minzer01/flio)

---

### Tech Stack

**Backend** — Java, Spring Boot, Spring Data JPA, Spring Security
**Data** — MySQL, MongoDB, Redis
**Infra** — AWS (EC2, S3), Docker
**Frontend** — React, JavaScript

---

### 안녕하세요, 백엔드 개발자 안민영입니다

Java와 Spring Boot로 백엔드를 개발합니다.
팀 프로젝트에서 AI 비동기 처리, 여러 서버 간 메시지 전달, 운영 중 발견한 동시성 문제를 맡아 해결했습니다.

- 이화여자대학교 컴퓨터공학과 졸업 (2026.02)
- 카카오테크 부트캠프 3기 수료 (2025.09 ~ 2026.03)

#### 프로젝트

**CommitMe — AI 이력서·모의면접 서비스** · 6인 팀 · 2025.12 ~ 2026.03
GitHub 레포지토리를 바탕으로 AI가 개발자 이력서를 생성하고 모의면접을 진행하는 서비스입니다. 세 차례 배포해 실제 사용자가 이용했습니다.
- 이력서 생성 AI 콜백 기반 비동기 연동
- 타임아웃 처리가 성공 결과를 덮어쓰던 경합 문제를 비관적 락으로 해결
- 서버 3대 환경에서 Redis Pub/Sub으로 모의면접 SSE 메시지를 연결된 서버에만 전달
- 담당 기능의 React 화면 구현 (이력서 PDF, 음성 답변 녹음)

→ [담당 구현 내역](https://github.com/100-hours-a-week/15-team-service-be/blob/dev/CONTRIBUTIONS-zero.md) · [백엔드 레포](https://github.com/100-hours-a-week/15-team-service-be)

**Flio — 여행 정보 커뮤니티** · 개인 · 2024.09 ~ 2025.02, 이후 보완
- JWT 기반 Stateless 인증, 회원 탈퇴 소프트 삭제
- 작성자 ID를 JWT에서 꺼내도록 바꿔 IDOR 취약점 수정
- 목록 조회 API의 N+1 문제를 Fetch Join으로 해결
- S3 이미지 업로드, Docker Compose 배포 구성, 단위 테스트

→ [레포지토리](https://github.com/minzer01/flio)
