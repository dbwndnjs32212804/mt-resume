# 이력서 

---
<table>
  <tr>
    <td valign="top">
      <h2>1. 기본 인적 사항</h2>
      <ul>
        <li>이름 : 유주원 / 柳柱元 / JUWON YOO</li>
        <li>연락처 : 010-3285-9598</li>
        <li>E-mail : dbwndnjs321@naver.com</li>
        <li>병역 : 병역필 (만기제대)</li>
      </ul>
    </td>
    <td align="right" valign="top">
      <img src="https://github.com/user-attachments/assets/178fe636-82e7-4f7e-8d0d-99e3241b370d" width="150">
    </td>
  </tr>
</table>
<br>



---

##  목차
- [About Me](#about-me)
- [학력 사항](#학력-사항)
- [기술 스택](#기술-스택)
- [주요 이수 과목](#주요-이수-과목)
- [프로젝트 경험](#프로젝트-경험)
- [교내외 활동](#교내외-활동)
- [대회 참가](#대회-참가)
- [학습 목표](#학습-목표)
- [Contact](#contact)

---

##  About Me

안정적인 금융 IT 시스템 구축과 데이터 일관성을 중요하게 생각하는 개발자입니다.  
문제 해결 과정을 체계적으로 기록하고 공유하며, 꾸준한 학습을 통해 성장하고 있습니다.

**"꾸준한 학습과 기록을 통해 성장하는 개발자"**

---

##  학력 사항

### 학력
- **대학교명:** 단국대학교
- **전공:** 소프트웨어학과
- **재학 기간:** [2021.03 ~ ]
- **상태:** 재학중 

### 어학 능력
- **토익:** 750점 이상

---

##  기술 스택

### Backend & Database
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

### Algorithm & Language
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)

### Tools & Others
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

##  주요 이수 과목

| 과목명 | 주요 학습 내용 |
|--------|---------------|
| **금융경제학** | 자산 가치 평가, 투자 결정론, 금융 시장 분석 등 경제학적 모델링 기법 |
| **고급데이터베이스** | 최신 데이터베이스 도구(HDFS, Spark, NiFi, Kudu)의 특징, 아키텍처 및 실제 업무 활용 사례 |
| **데이터사이언스** | R을 활용한 데이터 수집, 전처리, 분석 및 머신러닝 모델링 |
| **운영체제보안** | OS 취약점 분석, 접근 제어, 암호화, 커널 레벨 보안 등 시스템 보호 기술 |
| **자료구조** | 배열, 리스트, 스택, 큐, 트리, 그래프 등 핵심 자료구조 학습 및 시간/공간 복잡도 분석 |
| **알고리즘** | 정렬, 탐색, 동적 계획법(DP), 그래프 알고리즘 등 주요 알고리즘 설계 및 효율성 분석 |

---

##  프로젝트 경험



###  AI 기반 모바일 구인·구직 플랫폼 아키텍처 설계
**팀 프로젝트 (총괄 설계 및 기술 리서치)** [![Notion](https://img.shields.io/badge/Notion-설계/기획-000000?style=flat&logo=notion)](https://www.notion.so/1c91f99e010b80ea9abdf21d2b6467a2)

**프로젝트 개요:** AI 기반 자동 상담, 위치 기반 추천, 인앱 결제 등을 통합한 모바일 구직 매칭 서비스의 전체 아키텍처를 설계했습니다.

**주요 역할 (기술 스택 선정 및 시스템 설계):**
아이디어 구상 단계부터 참여하여, 플랫폼 구현에 필요한 6개 핵심 분야(프론트엔드, 백엔드, AI, 결제, GPS, 보안)의 기술 스택을 조사하고 비교 분석하는 역할을 담당했습니다.
-   성능, 사용자 경험, 개발 속도, 비용, 확장성 등을 기준으로 각 기능에 최적화된 도구를 선정하고 전체 시스템 아키텍처를 구상했습니다.
-   단순 개발 참여를 넘어, 전체적인 앱 구조를 파악하고 기술 선택이 운영 효율성과 비즈니스에 미치는 영향을 분석했습니다.

**주요 설계 내용:**
-   **프론트엔드:** `React Native` 채택. iOS/Android 동시 개발 및 웹 기술 재사용성, 풍부한 라이브러리.
-   **백엔드:** `Firebase 서버리스 아키텍처` 적용. Firebase Auth, Firestore, Cloud Functions를 조합하여 서버 유지보수 비용을 절감하고 개발 속도 향상.
-   **AI 시스템:** `Dialogflow + GPT API 혼합 구조` 설계. Dialogflow로 사용자의 요청을 구조적으로 분류하고, GPT API로 자연스러운 응답을 생성하여 역할 분담.
-   **결제:** `공식 인앱 결제 (IAP)` 채택. `react-native-iap`를 활용하고, Firebase Functions로 서버 측 영수증을 검증하여 플랫폼 정책 준수 및 보안성 확보.
-   **GPS 추천:** `Haversine 공식` 활용. 시각적 지도 API 없이 GPS 좌표와 Haversine 공식을 이용해 거리 기반 필터링을 구현.
-   **보안:** `Firebase 중심 설계`. Firebase Security Rules로 DB 접근을 제어하고, GPT 호출 및 결제 등 민감 로직은 Cloud Functions로 이전하여 API 키 노출 방지.
---

###  금융 P2P 송금 시스템
**개인 프로젝트 (백엔드 학습)**  
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style-flat&logo=github)](https://github.com/dbwndnjs32212804/personal-finance-dashboard)

**사용 기술:** Java, Spring Boot, Spring Security, Spring Data JPA, MySQL, Maven

**프로젝트 개요:** Spring Boot, JPA, Security를 기반으로 금융 IT 시스템의 안정성과 데이터 일관성을 목표로 개발한 P2P 송금 시스템

**주요 성과:**
- **REST API 설계 및 유효성 검증:**
    - `AccountController`를 구현하여 `POST /api/v1/accounts` 등 RESTful 엔드포인트를 설계했습니다.
    - `AccountDto` (DTO 패턴)를 적용하여 Entity와 API 요청/응답 데이터를 명확히 분리하여 보안 및 유연성을 확보했습니다.
    - DTO에 `@Valid`, `@NotBlank`, `@Min` 등 Validation 어노테이션을 적용, 컨트롤러 계층에서 데이터 유효성을 선제적으로 검증하여 시스템 안정성을 높였습니다.

- **Spring Security 기반 API 보안 적용:**
    - `SecurityConfig`를 정의하여 API 보안 체계를 구축했습니다.
    - Stateless한 REST API 환경을 고려하여 `csrf.disable()`을 설정했습니다.
    - `authorizeHttpRequests`를 통해 '계좌 생성' API(`POST /api/v1/accounts`)는 `permitAll()`로 허용하고, 그 외 모든 요청은 `authenticated()`로 설정하여 API를 안전하게 보호했습니다.

- **JPA 및 데이터 무결성 중심 설계:**
    - `Account` Entity 설계 시, 금융 데이터의 정확성을 위해 잔액(balance) 필드에 `BigDecimal` 타입을 사용했습니다.
    - `@Column(unique = true)` 속성을 `accountNumber`에 적용하여 DB 수준에서 데이터 고유성을 보장했습니다.
    - `AccountRepository` (Spring Data JPA)를 구현하고, `Optional<T>`을 활용한 쿼리 메서드(`findByAccountNumber`)를 정의하여 NPE(NullPointerException)를 방지했습니다.

- **트랜잭션 및 비즈니스 로직 구현:**
    - `AccountService` (서비스 계층)에서 `@Transactional` 어노테이션을 사용하여 '계좌 생성' 로직의 원자성을 보장, 데이터 일관성을 확보했습니다.
    - `UUID`를 활용하여 고유한 계좌번호를 생성하고, DTO와 Entity 간의 변환 로직을 서비스 계층에서 처리했습니다.

- **개발 환경 설정 및 디버깅:**
    - `application.yml`에서 `local` 프로필을 분리하여 환경별(개발, 운영) 설정을 체계적으로 관리했습니다.
    - Hibernate SQL 로깅(`logging.level.org.hibernate.SQL: debug`)을 활성화하여 JPA가 생성하는 쿼리를 실시간으로 모니터링하며 개발 및 디버깅 효율을 높였습니다.


---

###  개인 금융 대시보드 (Personal Finance Dashboard)
**개인 프로젝트 (시스템 학습)**  
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/dbwndnjs32212804/personal-finance-dashboard)

**사용 기술:** Java 17, Spring Boot 3, Spring Security, Spring Data JPA, JWT, MySQL, Redis, Docker, Nginx, Prometheus, Swagger, Maven

**프로젝트 개요:** 계좌 관리, 입출금, 이체, 예산 설정 등 개인 자산 관리를 위한 웹 애플리케이션입니다. 금융 서비스의 핵심 요소인 데이터 정합성과 동시성 제어에 중점을 두고 개발했습니다.

**주요 성과 및 구현 기능:**
-   **동시성 및 데드락 제어:**
    -   금융 거래의 동시성 문제를 해결하기 위해 `AccountRepository`에 비관적 락(Pessimistic Lock) (`@Lock(LockModeType.PESSIMISTIC_WRITE)`)을 적용했습니다.
    -   `TransactionService`의 '이체' 기능 구현 시, 두 계좌의 ID를 정렬하여 `findByIdWithLock`을 순차적으로 호출함으로써 Deadlock(교착 상태)을 방지했습니다.
    -   `@Transactional(isolation = Isolation.SERIALIZABLE)` 격리 수준을 이체 로직에 적용하여 최고 수준의 데이터 정합성을 보장했습니다.
-   **인증 및 인가 (Spring Security):**
    -   `Spring Security 6`와 **JWT (Access/Refresh Token)**를 통합하여 Stateless 인증 시스템을 구현했습니다.
    -   `SecurityConfig`에서 `SessionCreationPolicy.STATELESS`를 설정하고, `JwtAuthenticationFilter`를 커스텀하여 매 요청 시 토큰을 검증했습니다.
    -   `@PreAuthorize`와 커스텀 보안 표현식(`@accountSecurity.isOwner`)을 연동하여, 사용자가 본인의 계좌 정보에만 접근할 수 있도록 리소스 소유권을 검증했습니다.

-   **성능 최적화 (Redis Caching):**
    -   `AccountService`의 계좌 통계 및 상세 조회 메서드에 `@Cacheable`, `@CacheEvict`를 적용했습니다.
    -   `docker-compose.yml`을 통해 **Redis**를 캐시 저장소로 구성하여 자주 조회되는 데이터의 응답 속도를 최적화했습니다.
-   **인프라 구축 (Docker & Nginx):**
    -   `docker-compose.yml`을 사용하여 Spring Boot(app), MySQL(db), Redis, Nginx, Prometheus를 포함하는 멀티 컨테이너 아키텍처를 구축했습니다.
    -   `Nginx`를 리버스 프록시로 구성하여 API 엔드포인트별 **Rate Limiting(요청 제한)**을 적용하고, 보안 헤더(CSP, X-Frame-Options)를 설정했습니다.
    -   Multi-stage `Dockerfile`을 작성하여 빌드 환경과 런타임 환경을 분리하고, non-root 유저로 애플리케이션을 실행하여 보안을 강화했습니다.
-   **API 설계 및 예외 처리:**
    -   `Swagger(OpenAPI)`를 도입하여 API 문서를 자동화하고, `GlobalExceptionHandler`(`@RestControllerAdvice`)를 통해 `BusinessException`(커스텀 예외), `ValidationException` 등을 일관되게 처리했습니다.

-   **고급 기능 구현:**
    -   `Transaction` Entity 설계 시, 금융 데이터의 정확성을 위해 `BigDecimal` 타입을 사용하고 입출금액(음수/양수)을 명확히 구분했습니다.
    -   `BudgetService`에서 `@Scheduled` 어노테이션을 사용한 스케줄링 작업 으로 매일 예산 임계치를 자동 검사하는 '예산 관리' 기능을 구현했습니다.

-   **테스트:**
    -   `TransactionIntegrationTest`에서 `ExecutorService`와 `CountDownLatch`를 사용한 동시성 테스트 케이스(`testConcurrentWithdraw`)를 작성하여 비관적 락의 정상 동작을 검증했습니다.

---

###  금융 IT 블로그 운영
**개인 활동** [![Blog](https://img.shields.io/badge/Naver-Blog-03C75A?style=flat&logo=naver)](https://blog.naver.com/dbwndnjs321)

**운영 목적:** '금융 전문 개발자'라는 목표를 가지고, 기술 역량(SW)과 금융 도메인 지식(Finance)을 균형 있게 학습하고 기록하는 지식 베이스로 블로그를 운영해왔습니다. (총 102개 포스트)

**주요 카테고리:**
- **SW 역량 강화 및 문제 해결 기록:** '개인 금융 대시보드' 프로젝트를 진행하며 마주친 `validation` 의존성 누락, MySQL `Connection Refused` 디버깅, `Spring Security` 401(인증)/403(인가) 에러 해결 과정을 논리적 추론을 통해 기록했습니다. 또한 백준 알고리즘 풀이 시 시간 초과를 2중 for문에서 1중 for문으로 최적화한 과정, C언어 `uthash`를 활용한 해시 테이블, '운영체제 보안'의 샌드박싱 등 CS 기본기를 심화하고 공유했습니다.

- **금융 도메인 지식 및 IT 아키텍처 분석:** IT와 금융의 접점을 깊이 있게 탐구했습니다. 실시간 결제 처리 기술, 초고속 메시징 큐(MQ), 트랜잭션 일관성(ACID), MSA, API 게이트웨이 등 금융 시스템의 핵심 아키텍처를 분석했습니다. 나아가 「국내 금융권 클라우드 보안 위협」, 「전자금융거래시스템의 클라우드 도입 요인」 등 최신 학술 논문을 요약하며 금융권의 클라우드 전환과 보안 요구사항을 학습했습니다.

- **금융 산업 동향 리서치:** 'KDB 소식', '한국은행 금융안정 보고서' 등 정기 간행물과 '금융경제학' 전공 수업 내용을 정리하며, 은행의 3대 시스템(계정계, 정보계, 대외계), KYC, NPL 등 현업 용어와 금융 산업 동향을 꾸준히 추적하고 있습니다.


---

##  교내외 활동

###  코딩테스트동아리
**활동 기간:** 2025.03 ~ 2025.08

- 알고리즘 및 자료구조 핵심 개념 공동 학습 및 토론
- 백준(Baekjoon) 온라인 저지 문제 풀이 및 코드 리뷰를 통한 솔루션 공유
- 실전 대비 모의 코딩 테스트 훈련을 통한 문제 해결 능력 강화
- 서울대 SCSC Computer Programming Contest 참가

###  코딩동아리
**활동 기간:** 2021.03 ~ 2022.08

- C언어 및 Java 프로그래밍 언어 멘토링 참여 및 팀 스터디 (2021.03~2021.12)
- Linux 시스템 및 보안 기초 개념 스터디 및 실습 진행 (2022.03~2022.08)
- 정기적인 코드 리뷰 참여를 통한 협업 능력 및 코드 품질 개선 경험

###  봉사동아리
**활동 기간:** 2021.03 ~ 2022.02

- 교내외 봉사 활동 프로그램 정기 참여
- 부원들 간 원활한 소통을 통해 대인관계 기술 및 사회성 증진

###  피겨동아리
**활동 기간:** 2021.03 ~ 2022.02

- 주 1회 정기 훈련 참여
- 꾸준한 연습을 통한 성실함 및 목표 달성 역량 배양

---

##  대회 참가

  - SCSC Computer Programming Contest 참가 (2025)

  

---

##  학습 목표

현재 다음 기술들을 학습하고 있습니다:

- **Spring Boot 심화학습** : Spring Security, OAuth2를 활용한 인증/인가 구현 및 JPA N+1 문제 해결, 쿼리 최적화 등 심층 학습

- **DevOps 기초 및 배포 경험** : Docker, Jenkins/GitLab CI를 활용하여 개인 프로젝트의 CI/CD 파이프라인을 구축하고 AWS 등 클라우드 환경에 배포하는 경험

- **금융 도메인 지식 및 트렌드 학습** : 안정적인 금융 시스템 구축을 위한 금융 공학 기초 지식을 학습하고, 핀테크, 결제 시스템 등 IT와 연관된 최신 금융 트렌드를 꾸준히 분석

- **테스트 코드 작성 역량** : JUnit, Mockito 등을 활용한 단위 테스트(Unit Test) 및 통합 테스트(Integration Test) 코드 작성 습관화

- **CS 기본기 및 코딩 테스트** : 자료구조, 알고리즘, 네트워크, 운영체제 등 핵심 전공 지식을 복습하고 꾸준한 코딩 테스트 문제 풀이


---

##  Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-dbwndnjs321@naver.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dbwndnjs321@naver.com)
[![Blog](https://img.shields.io/badge/Blog-blog.naver.com/dbwndnjs321-03C75A?style=for-the-badge&logo=naver&logoColor=white)](https://blog.naver.com/dbwndnjs321)
[![GitHub](https://img.shields.io/badge/GitHub-dbwndnjs32212804-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dbwndnjs32212804)

**Phone:** 010-3285-9598

</div>


<div align="center">


</div>
