# 도메인 주도 설계 핵심

## 나에게 도메인 주도 설계는

- 더 자세한 내용은 도메인 주도 설계 구현[IDDD]를 참고한다.
- DDD는 복잡하다.
- 스크럼은 설계에 대해 이야기하지 않는다.
- 기술에 대한 집착으로 도메인이 부실해진다.
- 클래스와 오퍼레이션 이름에 관심이 부족하다.
- 비즈니스 프로세스와 업무보다 데이터베이스 주변 솔루션에 관심이 많다.
- 작업 보드 셔플은 큰 진흙 덩어리다.
- 비즈니스 이해관계자는 개발자들이 일부만 보는 명세서 작성에 시간을 많이 보낸다.
- 개발자는 비즈니스 로직에 영속화 로직과 인터페이스 관련 코드를 작성한다.
- 개발자는 상상 속 미래를 가지고 과도한 일반화를 한다.
- 오퍼레이션을 수행하는 서비스가 다른 서비스를 직접 호출한다. 강한 결합이고 종종 데이터 불일치의 원인이된다.
- 설계는 필연적이다. (더글라스 마틴)
- 모델링을 인정하지 않아도 모델링을 한다.
- 설계는 어떻게 생겼는지가 아니고 어떻게 동작하는지다. (스티브 잡스)
- 전략적 설계의 시작은 바운디드 컨텍스트 안에 있는 보편언어
- 서브도메인으로 복잡성을 다룬다.
- 컨텍스트 매핑으로 여러개의 바운디드 컨텍스트를 통합한다.
- 컨텍스트 맵은 2개의 바운디드 컨텍스트를 통합하고 그사이의 관계/기술적 매커니즘을 정의한다.
- 전술적 설계에는 더 자세한 설계인데 그중 엔티티와 값 객체를 애그리게잇으로 묶는 패턴이 있다.
- 도메인 이벤트는 도메인에서 발생하는 내용을 시스템과 공유하는 것을 돕는다. 공유는 로컬 바운디드 컨텍스트이거나 원격 바운디드 컨텍스트일 수 있다.

## 바운디드 컨텍스트 및 보편언어와 전략적 설계

- DDD는 바운디드 컨텍스트 안에서 보편언어를 구현하는 것
- 바운디드 컨텍스트는 부서 또는 조직과 대응
- 바운디드 컨텍스트 안에 클래스로 구현
- 바운디드 컨텍스트가 핵심 전략적 계획으로 개발되고 있다면 이를 핵심 도메인이라고 부른다.
- 바운디드 컨텍스트는 언어의 경계와 비슷하다.
- 보편 언어는 소프트웨어 모델 소스 코드다.
- 바운디드 컨텍스트 별로 리포지토리가 있어야한다.
- 보편 언어는 컨텍스트 안에서 유효하다.
- 바운디드 컨텍스트 없이 수 많은 개념이 추가되면 진흙 덩어리 처럼 엉망진창이 된다.
- ...
