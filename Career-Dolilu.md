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


# 예시
## 이름
이정수
## KYS 작성
### Key Strength
- Java/Kotlin Backend
- Spring/JPA
- AWS
- B2B SaaS, B2C
- K8S

### Read.me 작성
- Java/Kotlin 기반의 Spring Back-End 개발을 하고 있습니다.
- AWS 기반의 B2B SaaS 플랫폼, 제품을 개발 하고 있습니다.
- 저 포함 5명의 Back-End Part를 리딩하고 있습니다.
- B2C 투표 앱을 개발, 운영하며 짧은 기간 동안 많은 트래픽이 몰리는 서비스의 Back-End 시스템을 개발/운영 해본 경험이 있습니다.
- 좀 더 좋은 인프라 환경을 끊임 없이 고민 하는 회사에서 다양한 인프라 변화 경험을 통하여 K8S 전환을 일부 경험 했습니다.  

### Goal 설정
- 단기 목표
  - SaaS 기반의 플랫폼에 다양한 제품을 연동하면서 안정적으로 연동/개발 할 수 있는 개발자.
  - 개발 효율성 및 안정성을 위하여 아키텍처를 설계하고 테스트 커버리지를 높이고 빠른 속도로 테스트 할 수 있는 코드를 만드는 개발자. 
  - K8S 기반의 운영 환경을 구축하여 더 빠른 속도로 테넌트가 배포되고, 운영비용이 더 적게 발생하는 아키텍처로 개발/운영할 수 있는 개발자.
- 장기 목표
  - 많은 사람들이 사용하는 서비스를 안정적으로 운영/개발 할 수 있는 아키텍처 설계 및 개발을 할 수있는 개발자. 
  - 내가 정말 좋아하고 잘하는 도메인을 하나 이상 갖고 있는 개발자

## Gap 분석
### Goal
- 많은 사람들이 사용하는 서비스를 안정적으로 운영/개발 할 수 있는 아키텍처 설계 및 개발을 할 수있는 개발자.

### 필요 역량
- Java/Kotlin 개발 역량
- Spring Boot 역량
- JPA 역량
- AWS 및 다양한 Cloud Platform(Azure, GCP ..) 구축/운영 할 수 있는 역량
  - AWS 역량
  - AWS가 아닌 다른 Cloud Platform이 필요 할 경우 빠른 학습을 통하여 해당 Platform에서 성과를 낼 수 있는 역량
- 대용량 Transaction 및 Traffic을 처리 할 수 있는 역량
  - DB Transaction 역량 : isolation, mysql, mariaDB, 보상 Transcation
  - 비동기 처리 - Reactive / Coroutine
  - 이벤트 기반 아키텍쳐 구현 
    - Kafka를 비롯한 다양한 이벤트 기반 아키텍쳐 설계 능력
  - 인프라 환경 구성 능력
    - Auto Scale, Network, Security 관리
  - DB 관리 및 설계 능력
    - Partisioning, Sharding, 이중화
  - 부하테스트 및 결과를 기반으로 한 적정한 아키텍쳐 설계
    - nGrinder, pinpoint 
- 시스템 안정성이 높은 아키택쳐 구성
    - SPOF 방지를 위한 아키택쳐 : MSA, DDD, 핵사고날, 시스템 이중화
    - 안전한 배포를 위한 기술 : Blue/green deploy, canary deploy, staging 환경 설정
    - 모니터링 기술 : Grafana, datadog, cloudwatch
- 비용 절감 및 빠른 배포
  - K8S 기반의 아키텍쳐 설계

### 나의 상태
- Java/Kotin 개발 역량
- Spring Boot 역량
- JPA 역량
- 대용량 Transaction 및 Traffic을 처리 할 수 있는 역량
    - DB Transaction 역량 : isolation, mysql, mariaDB, 보상 Transcation
    - 인프라 환경 구성 능력
        - Auto Scale, Network, Security 관리
    - 부하테스트 및 결과를 기반으로 한 적정한 아키텍쳐 설계
        - pinpoint
- 시스템 안정성이 높은 아키택쳐 구성
    - SPOF 방지를 위한 아키택쳐 : 시스템 이중화
    - 안전한 배포를 위한 기술 : Blue/green deploy, canary deploy, staging 환경 설정
    - 모니터링 기술 : Grafana, datadog, cloudwatch

### Gap 분석
- Kotlin 학습 심화 : 개발에는 문제가 없으나 좀 더 Kotlin을 잘 사용 하도록 학습
- 대용량 Transaction 및 Traffic을 처리 할 수 있는 역량
  - DB Transaction 역량: 
    - DB Isolation Level을 환경 및 상황에 맞게 설정 할 수 있는 능력
    - 보상 Trasaction 관련 아키텍쳐 설계 및 개발 능력
  - 비동기 처리 - Reactive / Coroutine과 같은 비동기 처리 관련 스터디
  - 이벤트 기반 아키텍쳐 구현
      - Kafka를 비롯한 다양한 이벤트 기반 아키텍쳐 능력 향상
  - DB 관리 및 설계 능력
      - Partisioning, Sharding, 이중화 중 이중화 경험만 존재 
  - 부하테스트 및 결과를 기반으로 한 적정한 아키텍쳐 설계
      - nGrinder를 통한 부하테스트 및 pinpoint를 활용한 모니터링 까지는 경험이 있으나, 해당 결과를 토대로 적정한 아키텍쳐 설계 능력 향상 필요
- 시스템 안정성이 높은 아키택쳐 구성
    - SPOF 방지를 위한 아키택쳐 : MSA, DDD, 핵사고날과 같은 다양한 아키텍쳐 설계 능력 
    - 모니터링 기술 : Grafana, datadog, cloudwatch 같은 모니터링 툴을 사용하는 능력 향상
- 비용 절감 및 빠른 배포
    - K8S 관련 다양한 경험 및 관련 지식 습득

### To-Do List
- Kotlin 학습 심화
  - Kotlin 디자인 패턴 학습
  - 함수형 프로그래밍 학습
  - 코루틴 학습
- 대용량 Transaction 및 Traffic을 처리 할 수 있는 역량
    - DB Transaction 역량:
        - DB Isolation Level을 실무에 맞게 적용할 수 있는 능력 향상
        - 보상 Trasaction 관련 아키텍쳐 설계 및 개발 능력 향상
    - 비동기 처리 - Reactive Programing, r2dbc, noSql 스터디
    - 이벤트 기반 아키텍쳐 구현
        - Kafka를 비롯한 다양한 이벤트 기반 아키텍쳐 스터디
      - DB 관리 및 설계 능력
          - Partisioning, Sharding등 다양한 DB 설계 방법 스터디
      - 부하테스트 및 결과를 기반으로 한 적정한 아키텍쳐 설계
        - 성능테스트 분석 능력 향상
- 시스템 안정성이 높은 아키택쳐 구성
    - SPOF 방지를 위한 아키택쳐 : MSA, DDD, 핵사고날과 같은 다양한 아키텍쳐 스터디
    - 모니터링 기술 : Grafana, datadog, cloudwatch 같은 모니터링 툴을 사용하는 환경 구축 능력 스터디
- 비용 절감 및 빠른 배포
    - K8S 스터디



