# career-goal

# 요구사항

- [x] KYS(Known Your Self)를 작성한다.
    - [x] Key Strength 를 작성한다.
    - [x] Read.me 를 작성한다.
    - [x] Goal을 작성한다.
- [x] 되고싶은 개발자(Goal)가 되기 위한 gap 분석을 한다..
    - [x] Goal 작성 : 위에서 완성된 Goal중 원하는 하나를 선택한다.
    - [x] 필요역량 작성 : 되고싶은 개발자(Goal)가 되기 위해 필요 역량을 작성한다.
    - [x] 나의 상태 작성 : 지금 나는 어떤 역량을 가지고 있는지 작성한다.
    - [x] Gap 분석 : 되고싶은 개발자(Goal)가 되기 위해 가지고 있는 역량과 앞으로 습득해야할 역량을 작성한다.
    - [x] To-Do List : 되고싶은 개발자(Goal)가 되기 위해 어떤 것들이 필요할지 작성한다.

---

## 이름

유재영

## KYS 작성

### Key Strength

- Java Backend (Java 8 / 17)
- Spring Framework, Spring Batch
- Sql query (Mysql or Oracle)
- Game platform, In-game revenue statistics for settlement

### Read.me 작성

- Spring Framework 기반 DAU 20만 정도의 포커 게임 플랫폼 운영 및 개발 중이며, Game Server 와의 Integration 을 통해 발생되는 원천데이터를 타 시스템에 가공 및 전달하는 하고있습니다.
- Spring Batch 를 이용하여 GS에서 발생된 원천데이터를 aggregation 한 뒤 B2B, B2C 서버에 전달하여 정산을 하고 있습니다.
- In-Game 내에서 사용되는 Rank 시스템이나, 비슷한 실력의 사람과 같이 칠 수 있게 해주는 매칭 시스템등과 기타 기능들을같이 서비스 하고 있습니다.

### Goal 설정

- 단기 목표로는 현재 운영하고 있는 레거시 시스템을 헥사고날 아키텍처로 변경하는 스터디를 진행
- DAU 100만이 넘어가도 안정적 서비스로 운영할 수 있는 아키텍처로의 전환

## Gap 분석

### Goal

- 단기 목표로는 현재 운영하고 있는 레거시 시스템을 헥사고날 아키텍처로 변경하는 스터디를 진행
    - 회사 메인 프로젝트를 변경하는걸 목표로 하고 있지만, 규모도 크고 조직이 워낙 보수적이라 아마도 변경되는걸 원치않을 듯 하여 개인적으로 대규모 서비스를 변경해보고 싶음

### 필요역량

- Hexagonal architecture 에 대한 이해
    - Hexagonal architecture 를 설계, 구축할 수 있는 역량
- Multi Module 분리 에 대한 이해
- Java 및 Spring Boot 에 대한 역량
- Security / Oauth2
    - Spring security
    - Oauth2.0
    - JWT
- Message Queue 에 대한 역량
    - Kafka
    - RedisMq
- 이 기종간 RealTime 통신에 대한 Transaction 의 무결성 보장 (Game Server 나 타 Platform 통신에 대비해서 ..)
    - Two Phase Commit
    - Saga Pattern
- 테스트 주도 개발
    - Integration Test
    - End to End Test
    - Mocking

### 나의 상태

- Java 및 Spring Boot 에 대한 역량
- Message Queue 에 대한 역량
    - RedisMq
- 테스트 주도 개발
    - Integration Test
    - End to End Test

### Gap 분석

- Hexagonal architecture 에 대한 이해
    - 여러 Blog 와 책을 읽어 보았지만, 장점에 대한 이해도가 부족함.
    - 스터디 및 개인 프로젝트를 진행.
- Security / Oauth2
    - Spring security
        - 실무에서 써본 경험 있지만, 아직 이해도 부족.
    - Oauth2.0
        - 강의를 통해 스터디
- MQ 에 대한 역량
    - Kafka
        - Consumer 는 실무에서 구현 해봄.
- 이 기종간 RealTime 통신에 대한 Transaction 의 무결성 보장
    - Two Phase Commit
        - 이론만 알고있음.
    - Saga Pattern
        - 일종의 미들웨어가 필요하고, 이기종의 DB에서는 요 방법을 써야된다 정도로만 알고있음.

### To-Do List

- Hexagonal architecture 스터디
    - 레거시 시스템 중 규모가 작은 프로젝트를 헥사고날 아키텍처로 개발하는 사내 스터디를 진행 후, 메인 프로젝트에 대해 점진적으로 적용.
- Security / Oauth2 스터디
    - Oauth2에 대한 강의를 완강 한 뒤 개인 프로젝트를 진행 후, Oauth2 가 적용되 있는 레거시 프로젝트를 변경.
- Kafka 스터디
    - Producer 는 내년쯤 실무에 적용해볼 기회가 생길 듯 하여, 스터디를 진행하며 구현 대비.
- 이 기종간 RealTime 통신에 대한 Transaction 의 무결성 보장
    - 이건 어떻게 해야 하는지 감이 잡히질 않아, 셔플 런치를 통해 타 팀의 팀장님께 자문을 구한 뒤, 그에 맞춰 준비할 예정.
- 위 Goal 과 별개로 Webflux 를 이용한 리액티브 프로그래밍에 대한 스터디 예정.
