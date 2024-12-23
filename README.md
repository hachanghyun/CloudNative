# CloudNative

## 클라우드 네이티브를 사용하는 이유
### 1. 속도
    소프트웨어를 더 신속하게 출시하는 것

### 2. 복원력
    가용성이 좋음

### 3. 확장성
    부하에 유연함, 로드밸런싱

### 4. 비용
    온디맨드 방식으로 진행

## 클라우드 네이티브 개발원칙: 12요소와 확장
### 1. 하나의 코드베이스, 하나의 애플리케이션
    애플리케이션과 코드베이스 사의 일대일 관계를 설정

### 2. API 우선
    API우선 접근 방식을 사용하면 분산 시스템에 적합하도록 시스템을 고려하고 서로 다른 팀 간의 업무를 분배 가능.

### 3. 의존성 관리 
    애플리케이션의 모든 의존 라이브러리는 명시적인 방식으로 선언되어야 하며 이를 통해 의존라이브러리 관리 툴이 중앙 저장소에서 다운로드할 수 있어야 한다.

### 4. 설계, 빌드, 릴리즈, 실행
    설계: 특정 애플리케이션 기능에 필요한 기술, 의존성 및 툴이 결정된다.
    빌드: 코드베이스를 컴파일하고 의존 라이브와 함께 패키지로 만들어 빌드라고 부르는 불가변 아티팩트를 생성한다.
    릴리즈: 배포하기 위해 빌드를 특정 설정과 결합한다.
    실행: 애플리케이션의 특정 릴리즈가 실행 환경에서 작동한다.

### 5. 설정, 크리덴셜 및 코드
    
