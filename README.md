<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=250&color=0:F9A8D4,100:86EFAC&section=header&text=Hi%21%20It%27s%20HyeonSu%20Kim🍥%21&fontSize=48&fontColor=14532D&fontAlignY=40&desc=Welcome%20to%20My%20Github🍀&descSize=20&descAlignY=60)

</div>

# 👋 Introduce

**측정 가능한 근거로 병목을 찾고, 안정적인 구조로 개선하는 백엔드 개발자입니다.**

- Java·Spring Boot를 중심으로 인증·인가와 백엔드 서비스를 설계합니다.
- k6·Prometheus·Grafana로 병목을 관찰하고 개선 결과를 수치로 검증합니다.
- 데이터 파이프라인부터 임베딩 서버와 벡터 검색까지 연결해 구현한 경험이 있습니다.
- 새롭게 배운 기술과 문제 해결 과정을 문서화해 팀과 공유하는 것을 좋아합니다.

---

# 🛠 Tech Stack

### Core

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
</p>

### Data & AI

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
</p>

### Infra & Observability

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/OCI-F80000?style=flat-square&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white">
  <img src="https://img.shields.io/badge/Loki-F5A623?style=flat-square&logo=grafana&logoColor=white">
</p>

### Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
</p>

---

# 🚀 Featured Projects

## start.ai.io

> **레이어별 병목을 제거해 응답 시간을 9.3배 단축하고 RPS를 5.5배 향상**

GitHub 데이터를 임베딩·벡터 검색으로 분석해 개발자 맞춤형 `SKILL.md`를 추천하고 생성하는 AI 백엔드 서비스입니다.

- OCI Object Storage의 데이터를 정제·청킹·임베딩해 pgvector에 적재하는 파이프라인을 구축했습니다.
- bge-m3 기반 FastAPI 임베딩 서버와 단일·배치 임베딩 API를 개발했습니다.
- 타임아웃, HTTP 연결 풀, 배치 호출, 벡터 인덱스 등 6가지 병목을 순차적으로 개선해 응답 시간을 **29.77초에서 3.21초로 단축**했습니다.
- pgvector `ivfflat` 인덱스를 적용해 벡터 검색 쿼리를 **1~3초에서 약 20ms로 단축**했습니다.

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/OCI-F80000?style=flat-square&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white">
</p>

---

## 고구마 마켓

> **부하 테스트와 쿼리 최적화로 주요 API의 p99 응답 시간을 최대 96% 개선**

중고 거래와 실시간 경매를 함께 제공하는 Spring Boot 기반 플랫폼입니다.

- Spring Security 기반 JWT 인증·인가와 로그인 잠금, Rate Limiting 정책을 구현했습니다.
- N+1 제거, `Page`에서 `Slice`로의 전환, 인덱스 적용 등으로 경매 조회 API의 p99를 **약 5초대에서 856ms로 단축**했습니다.
- MySQL FullText Index, DTO Projection, Cursor 기반 페이징을 적용해 검색 API의 p95를 **13초에서 2.36초로 단축**했습니다.
- k6·Prometheus·Grafana 기반 부하 테스트 환경을 구축하고 개선 전후 결과를 검증했습니다.

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Bucket4j-6C757D?style=flat-square">
  <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white">
</p>

---

## AI Office

> **Workspace 중심의 권한·초대·접속 상태 관리로 멀티 사용자 협업 기반 구현**

AI Agent를 Workspace 단위로 관리하고 Slack과 대시보드에서 작업 상태를 추적하는 AI 협업 오피스 플랫폼입니다.

- Workspace 멤버십과 `ADMIN`·`MEMBER` 권한 정책을 서비스 계층에 구현했습니다.
- 초대 이메일을 비동기로 분리하고 `afterCommit()` 이후 실행해 커밋 전 조회 Race Condition을 방지했습니다.
- `JOIN FETCH`와 bulk 조회로 Workspace 목록 조회 쿼리를 **2회로 고정**했습니다.
- SSE와 REST를 조합해 접속자 입장·퇴장·위치 변경 이벤트를 전달했습니다.

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white">
  <img src="https://img.shields.io/badge/SSE-6DB33F?style=flat-square">
  <img src="https://img.shields.io/badge/JavaMail-007396?style=flat-square&logo=openjdk&logoColor=white">
</p>

---

## for-me

> **셀프 기프팅으로 목표 달성을 돕는 습관 관리 애플리케이션**

월별 투두리스트 달성률에 따라 미리 결제한 금액을 환급하는 대학 심화 캡스톤 프로젝트입니다. JWT 기반 로그인·인증·인가와 투두리스트 CRUD를 구현했으며, 설계 과정을 담은 논문과 프로젝트로 각각 은상을 수상했습니다.

<p>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white">
  <img src="https://img.shields.io/badge/REST_API-005571?style=flat-square">
</p>

---

# 🏆 Awards & Certifications

### Awards

- Programmers DevCourse 최종 프로젝트 **최우수상** (2026.04)
- Programmers DevCourse 팀 프로젝트 4회 중 **최우수팀 2회·우수팀 1회**
- 경기대학교 캡스톤디자인 산학협력 프로젝트 경진대회 **은상** (2024.06)
- 한국정보기술학회 우수논문상 **은상** (2024.05)
- 경기대학교 학업우수 장학금 **2회**

### Certifications

- 정보처리기사 (2024.09)
- SQLD (2024.09)
- 리눅스마스터 2급 (2025.07)
- 정보보안기사 필기 합격 (2025.03) · 실기 준비 중

---

# 🎓 Experience

<!-- 아래 표에서 '확인 필요'로 표시한 내용은 reference의 값을 임시로 복사했습니다. -->

| 소속                                      | 기간                                                  | 주요 활동                                                                            |
|-----------------------------------------|-----------------------------------------------------|----------------------------------------------------------------------------------|
| **경기대학교**                               | 2021.03 ~ 2025.08                                   | 컴퓨터공학전공                                       |
| **K.KNOCK (정보보안 동아리)**                  | 2023.03 ~ 2023.10  | C 언어·네트워크·웹 보안 스터디 및 PHP 웹페이지 기반 모의 해킹                                           |
| **Programmers DevCourse (백엔드 부트캠프)**    | 2025.10 ~ 2026.04  | Spring Boot 기반 백엔드 개발, 코드 리뷰 및 4회의 팀 프로젝트 수행                                     |
| **Programmers 체험형 인턴십 (그렙)**  | 2026.04 ~ 2026.05  | AI 협업 플랫폼 백엔드 개발                     |

---

# 📫 Contact

<p>
  <a href="mailto:kimhss@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white">
  </a>
  <a href="https://velog.io/@kimhss/posts">
    <img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white">
  </a>
  <a href="https://github.com/kimhss">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
  </a>
  <a href="https://www.notion.so/s-Archive-12beb96328cd81fb9c22e1cb2c7e7066">
    <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white">
  </a>
</p>
