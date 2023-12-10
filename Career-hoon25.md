## 이름
최창훈
## KYS 작성
### Key Strength
> 개발자로서 본인을 대표할 수 있는 keyword를 3~5개 정도 작성하여 본다. 
  - Java Backend(SpringBoot)
  - Typescript Backend(NestJS)
  - Python Backend(Django)
  - Database(MySQL, PostgreSQL)
  - DevOps(Docker, EKS)
### Read.me 작성
> Key Strength로 표현된 keyword를 가지고 본인을 소개하는 3~5줄 정도의 Read.me를 작성해 본다.

- 다양한 언어를 기반으로 만든 서비스를 개발부터 운영까지 다수 경험하였습니다.
  - KT 대리점 AI 서비스 개발 및 배포
    - Django API 서비스
    - ResponseTime 개선를 위한 Redis 배치 작업
    - 로그 적재 및 분석을 위해 Kafka 및 Hive 사용한 백오피스 개발
  - 스타트업 드론 이미지제공 웹서비스 인하우스 BE개발 
    - NestJS API 서비스
    - EKS 전환 개발
    - MSA 기반 개발
  - MySQL DBA 업무
    - MySQL 쿼리 튜닝
    - DDL 및 migration 작업
- 시스템 아키텍처에 관심이 많아서 직접 서버를 구축하여 회사와 동일한 아키텍처 구축
  - Docker기반 CI/CD 구축 하루내로 가능
  - EKS기반 서비스는 GitOps를 기반으로 ArgoCD로 CI/CD 구축 1주내로 가능


### Goal 설정
> 작성된 read.me로 현재의 자신을 객관적으로 살펴 보고 현실적으로 본인이 되고자하는 개발자로서의 목표를 2~3개 잡아본다.
- 대용량 서비스의 시스템 아키텍처를 설계하고, 현재 시스템의 문제점을 찾아낼 수 있는 개발자
- 새로운 서비스를 초기 기술부채 없이 개발할 수 있고, 주변의 업무(FE, 기획)를 이해하여 조율할 수 있는 사람

## Gap 분석
### Goal
- 대용량 서비스의 시스템 아키텍처를 설계하고, 현재 시스템의 문제점을 찾아낼 수 있는 개발자
### 필요역량
- Spring Boot, JPA 역량
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
    - bulk transaction 처리
    - 비동기 처리이후 데이터 최종적 일관성 처리
    - DB Transaction 역량 : isolation, mySQL
- 시스템 안정성이 높은 아키택쳐 구성
    - 높은 테스트 커버리지: Junit, Cucumber
    - SPOF 방지를 위한 아키택쳐 : MSA, 시스템 이중화
    - 유연한 어플리케이션 구조 : 헥사고날, 클린 아키텍처
    - 오류 탐지율 개선을 위한 모니터링 및 로그 적재 : Prometheus, ELK
    - Traffic 처리 : Circuit break, A/B Test, Traffic control
### 나의 상태
- Java 개발역량
  - 객체 설계 후 OOP기반 TDD 개발 및 ATDD가능
- Spring Boot, JPA 역량
  - 주니어 개발 수준
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - bulk transaction이라고 부를 수 있는 데이터 처리 경험 X
    - (bulk transaction의 범위는 어느정도일까요?)
  - 비동기 처리는 경험하였으니(Node, Kafka 기반 메시지큐) 그에 대한 최종적 일관성 처리 경험 부족
  - RDB의 isolation 4단계 별 문제점을 인지하고 있고, DB의 내부 동작들을 어느정도 이해하고있음
    - ex)
      - PK가 기본적으로 클러스터링 키이고, 이를 더 잘 사용하는 방법
      - InnoDB의 버퍼풀과 리두로그의 동작방식을 이해
- 시스템 안정성이 높은 아키택쳐 구성
  - Junit기반 테스트 작성 가능, Cucumber는 실무 사용경험 X
  - MSA 개발 초기단계 실무 진행 중
  - 헥사고날 아키텍처, 클린아키텍처 책 열심히 읽고 있는중..
  - Prometheus, ELK 의 존재만 알고 있고, 사용경험 없음
  - Circuit break, Traffic control  개념은 알고 있으나 실무 사용경험 X

### Gap 분석
- Java 개발역량
  - DDD도 적용할 수 있어야한다.
- Spring Boot, JPA 역량
  - 프레임워크 내부 동작에 대해 깊게 알지 못한다.
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - bulk transaction이라고 부를 수 있는 데이터 처리 경험 X
  - 비동기 처리 경험 필요
  - RDB관련 깊게 공부한지 시간이 지나서 재정리 필요
- 시스템 안정성이 높은 아키텍처 구성
  - cucumber 실무 사용
  - MSA 개발 고도화 
  - 헥사고날 아키텍처 실무 사용
  - Prometheus, ELK 실무 사용
  - Circuit break, Traffic control 실무 사용



### To-Do List
- java 개발역량
  - OOP 관련 책 및 DDD 개발 스터디
- Spring Boot, JPA 역량
  - 이전 F-lab에서 학습했던 SpringBoot 내부 코드 학습했던 거 다시 정리
  - NextStep 학습테스트기반 학습 듣기
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - RealMySQL 기반 학습했던 내용 재정리 및 중요 내용 추출 정리
  - 비동기 처리 관련 책 학습
- 시스템 안정성이 높은 아키텍처 구성
  - 아래의 기술들을 묶은 토이프로젝트 개발
