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


## 이름
정요한
## KYS 작성
### Key Strength
  - Java / Spring / Spring Boot / JPA / Spring Security / Spring Batch
  - AWS / Jenkins / Kubernetes / Docker
  - ElasticSearch / BigQuery
  - 영어 의사소통
### Read.me 작성
  - Java와 Spring Boot를 기반으로 하여 JPA , Spring Batch, Spring Security 들을 사용하여
    출퇴근 시간의 데이터들을 바탕으로 급여를 계산하고 급여 송금 및 세금 납부를 운영하는 핀테크 서비스를 개발하였습니다
  - 모바일 보안 소프트웨어 회사에서 글로벌 팀원들과 함께 일 1억건 이상의 모바일 앱 구동 데이터들을 활용하여
    해킹 시도를 탐지하고 방어하기 위한 백엔드 시스템 설계 및 해킹 데이터들을 통계화 하는 일을 하고 있습니다
  - ElasticSearch / Google BigQuery 등을 활용하여 대용량의 데이터들을 안정적으로 처리하고 통계 작업을 담당하고 있습니다
  - Jenkins, Kubernetes, Docker 등을 통해 On-Premise 환경에서의 보안 모듈 시스템을 설계 할 수 있도록 시스템을 구축하는 일을 하고 있습니다
### Goal 설정
  - 일 10억건 이상의 데이터들을 안정적으로 관리하고 실시간으로 해킹 데이터들을 통계화
  - On-Premise 환경에서 구축 시 JPA를 활용하여 빠르게 설치하고 ElasticSearch RollUp Job등의 직접 확인해야 하는 부분들 자동화
  - 코어, 백엔드 등의 연동되어 있는 로그들을 통합하여 디버깅이 원활할 수 있는 시스템 구축
  - Global 팀원들간의 원활한 의사소통
## Gap 분석
### Goal
  - 코어와 백엔드 개발자간 불필요한 병목 현상을 막고 일 10억건 이상의 데이터들을 안정적으로 운영 관리 할 수 있는 시스템 운영 및 On-Premise 안정 배포 능력
### 필요역량
- Java 개발 역량 / Spring Boot 역량 / JPA 역량
- Docker On-Premise 용 이미지 생성 역량
- Kubernetes 기반 배포 및 운영 역량
- 효율적이고 간단하게 지속적 배포가 가능한 배포 파이프라인에 대한 이해 
- 시스템 상태 모니터링 구축 역량
- 대용량 데이터들을 처리하고 관리할 수 있는 역량
  - Elasticsearch 
  - BigQuery
- MSA 환경에서 통합해서 로그들을 처리할 수 있는 역량
  - DataDog / Grafana / cloudwatch
- 코어에서 백엔드 API를 호출하는 아키텍처에 대한 이해 필요
### 나의 상태
- Java 개발 역량 / Spring Boot 역량 / JPA 역량
- On-Premise 용 Docker 이미지 생성 부분에 대한 범위에 방법 등에 대한 지식 부족
- Kubernetes 구축을 해보지 않았음
- 효율적이고 간단하게 지속적 배포가 가능한 배포 파이프라인에 대한 이해
  - Jenkins나 Code Deploy등을 통해 배포 파이프라인 구축은 가능하나 code Push 바로 바로 배포가 등의 최적화된 배포 파이프라인에 대한 개념 부족
- 시스템 상태 모니터링 구축 역량
  - cloudwatch 또는 grafana를 통해 모니터링 구축 능력이 있으나 적당한 구축 범위에 대한 이해 부족
- 대용량 데이터들을 처리하고 관리할 수 있는 역량
  - Elasticsearch
  - BigQuery 안써봄
- MSA 환경에서 통합해서 로그들을 처리할 수 있는 역량
  - MSA 환경에서 로그 통합을 위한 어떤 식으로 아키텍처를 구성해야 하는지를 모름
- 코어에서 백엔드 API를 호출하는 부분에 대한 이해 부족
### Gap 분석
- MSA 환경에서 로그를 통합하여 버그 트래킹을 하기 쉽도록 할 수 있는 아키텍쳐에 대한 학습
- On-Premise 배포 시 점검해야 할 모든 사항에 대한 문서화
- On-Premise 배포를 위해 Docker 이미지를 생성할 대상들이나 범위 정리
- Kubernetes DEV계 배포
- BigQuery 샘플용으로 비슷한 아키텍처로 구축
- 최적화된 배포 파이프라인데 대한 학습
- 시스템 모니터링 항목 리스트를 정리
### To-Do List
- Kubernetes로 On-Premise를 직접 구축을 해본다
- On-Premise 환경을 위한 Docker 이미지를 직접 생성해본다
- 시스템 모니터링을 위한 항목 리스트를 정리한다
- MSA 통합 로그들을 어떤 식으로 구성하는지 리서치 및 구축
- BigQuery에 대한 이해를 위해 test용 쿼리를 생성하고 데이터를 전송해본다
- 코어에서 백엔드 API를 호출하는 프로세스에 대한 이해 및 플로우 정리