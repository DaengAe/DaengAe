<h1 align="center">안녕하세요, 임은택입니다 👋</h1>
<p align="center">MSA 장애 격리와 분산 동시성 문제를 <b>이벤트·락</b>으로 해결하는 서버/백엔드 개발자입니다.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Java%20%7C%20Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Architecture-MSA-informational?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Reliability%20%26%20Concurrency-orange?style=flat-square" />
</p>
<p align="center">
  <a href="https://velog.io/@dmsxor434/posts"><img src="https://img.shields.io/badge/Blog-Velog-20C997?style=flat-square&logo=velog&logoColor=white" /></a>
</p>

---

### 📌 핵심 성과

- **Transactional Outbox**로 결과 불확실 케이스를 격리해 이벤트 유실 가능성을 `5% → 0%`로 없앴습니다.
- 외부 LLM 호출에 **재시도 캡·타임아웃·서킷브레이커**를 걸어 스레드 점유를 `300s → 30s` (90%↓) 줄였습니다.
- **Redis 분산락·pg_advisory_lock**으로 중복 승인·중복 호출을 직렬화해 동시성 결함을 `0건`으로 차단했습니다.
- Feign 호출을 트랜잭션 밖으로 분리해 커넥션 점유를 90%↓, 데드락 테스트 2건을 `0건`으로 없앴습니다.

> 기능이 동작하는 것과, 실제 서비스 환경에서 안정적으로 동작하는 것은 다릅니다. 눈에 잘 띄지 않지만 실제 서비스에서는 치명적인 문제(이벤트 유실, 동시성 결함, 외부 장애 전파)를 직접 찾아 근본 원인부터 고치는 걸 지향합니다.

---

### 🚀 대표 프로젝트

**[매삼코 (Maesamco)](https://github.com/maesamco/maesamco-backend)** — AI 기반 Java 마이크로러닝 플랫폼 `2026.08~`
Java 학습자가 문제를 풀고 AI에게 코드를 설명하며 이해도를 점검하는 MSA 학습 서비스. Coaching Service 도메인을 전담해 Outbox 이벤트 유실 방지, LLM 서킷브레이커, Redis 분산락, Gateway 인증 설계를 담당했습니다.

**[Sparta Logistics Platform](https://github.com/develop-9/delivery-project)** — 허브 기반 B2B 물류·배송 MSA `2026.07~08`
API Gateway JWT 인증, 분산 환경 동시성 제어(`pg_advisory_xact_lock`, `@Version`), Redis 장애 대응 Outbox+RabbitMQ 전환을 담당했습니다.

**[민생회복쿠폰 사용처 지도 서비스](https://github.com/livelihoodCoupon/Server-Backend)** — 위치 기반 검색 서비스 `2025.09~10`
카카오 API·Elasticsearch·PostGIS 기반 대규모 데이터 수집·검색. 반경 검색 응답 시간 `800ms → 120ms`(85%↓), 검색 응답 `300ms → 90ms`(70%↓) 개선.

**[Sparki](https://github.com/Team-Okebari/Server-Backend)** — 디자이너 영감·레퍼런스 관리 플랫폼 `2025.10~11`
Toss Payments 연동 결제/구독 시스템 설계. 비동기 결제 승인 무결성 문제를 상태 세분화와 복구 스케줄러로 해결했습니다.

---

### 🛠 기술 스택

<p align="left">
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Cloud%20Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/QueryDSL-4479A1?style=flat-square" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
</p>

<!--
---

### 📊 GitHub Stats
github-readme-stats.vercel.app 공용 인스턴스가 (2026-09-13 기준) 다운돼 있어 일단 주석 처리함.
서비스 복구되면 아래 두 줄 주석 해제하면 됨.

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=DaengAe&show_icons=true&theme=default&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DaengAe&layout=compact&hide_border=true" height="165" />
</p>
-->

---

### 📫 Contact

<p align="left">
  <a href="mailto:dladmsxor434@naver.com"><img src="https://img.shields.io/badge/Naver%20Mail-03C75A?style=flat-square&logo=naver&logoColor=white" /></a>
  <a href="https://velog.io/@dmsxor434/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white" /></a>
</p>
