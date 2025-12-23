# 🚀 Backend Developer Portfolio

### 안정적인 운영, 보안, 성능을 함께 고민하는 개발자
### 🎯 실무에서 해결한 문제들

| 문제 상황 | 해결 방법 | 결과 |
|---------|---------|------|
| 처리 속도가 느림 | 중복 구조 제거 | 성능 77% 개선 |
| 토큰 탈취 위험 | RTR 구현 | 재사용 공격 차단 |
| 사용자 인증 필요 | OAuth2.0 적용 | 안전한 인증 체계 |
| 수동 배포의 리스크 | GitHub Actions | 자동 빌드 및 배포 파이프라인 |

## 🛠️ TECH STACK

### Framework & Language
- Spring Boot / Spring Security / JPA
- Java
- RESTful API

### Database
- PostgreSQL
- Redis (캐싱 & 분산 락)

### DevOps
- Docker / Docker Compose
- GitHub Actions 자동 배포

### Authentication
- OAuth2.0
- JWT (Refresh Token Rotation)

### Monitoring
- Prometheus
- Grafana
- Loki & Promtail
- MDC Logging

## 🔬 개인 프로젝트를 통해 적용해본 기술

### 선착순 100명 이벤트 시스템 구축

#### 동시성 제어 및 성능 최적화

| 문제 상황 | 해결 방법 | 결과 |
|---------|---------|------|
| 동시성 제어 필요 | Redis + 분산 락 | 정확한 선착순 처리 |
| 성능 검증 필요 | k6 부하 테스트 | 동시 접속자 처리 성능 측정 |
| 이메일 발송 지연 | RabbitMQ | 비동기 메시지 큐로 분산 처리 |

#### 장애 대응 및 모니터링

| 문제 상황 | 해결 방법 | 결과 |
|---------|---------|------|
| 장애 원인 파악 | MDC Logging | 요청별 추적 ID로 디버깅 |
| 시스템 모니터링 | Grafana & Loki & Promtail | 실시간 로그 수집 및 시각화 |
| 리소스 모니터링 | Prometheus | CPU, 메모리, 디스크 사용량 추적 |

## 🔧 운영성 강화

### 🔍 장애 대응
- **MDC Logging**: 요청별 추적 ID로 빠른 디버깅
- **GlobalExceptionHandler**: 통합 예외 처리로 일관된 응답

### ✅ 품질 보증
- **테스트 코드**: HTTP 상태 코드별 테스트로 예상치 못한 버그 방지
- **Validation**: 잘못된 요청 사전 차단

### 📊 모니터링
- **Grafana & Loki**: 로그 수집 및 시각화
- **Prometheus**: CPU, 메모리, 디스크 리소스 추적
- **Promtail**: 로그 자동 수집 및 전송

## 💡 WHAT MAKES ME DIFFERENT

### 보안, 운영성, 성능까지 고민하는 개발자

단순히 기능을 구현하는 것을 넘어, **왜 이 코드가 필요한가?** **어떻게 더 안정적으로 만들 수 있는가?** 를 고민합니다.

### 장애를 경험하고, 예방하는 마인드셋
B2B 고객이 에러를 발견해서 연락할 때까지 우리가 몰랐던 경험을 하며,
<br>**에러를 고객이 발견하기 전에 개발자가 먼저 감지해야 한다**는 중요성을 배웠습니다.

고객 신고를 받고 나서 대응하는 것과, 문제가 발생하는 순간 감지해서 대응하는 것은 
<br>신뢰도와 대응 속도에서 완전히 다릅니다.

다음에 같은 문제가 생기지 않도록 MDC Logging과 Prometheus & Grafana & Loki를 활용해
<br>**실시간으로 문제를 감지하고 고객이 알기 전에 대응**할 수 있는 모니터링 시스템을 구현했습니다.
