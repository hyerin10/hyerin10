"토큰 탈취를 막으려면?" → RTR 학습 및 구현
"선착순 이벤트의 동시성 문제는?" → k6 부하 테스트 + RabbitMQ 분산 처리
"장애가 발생했다면?" → MDC Logging + Grafana로 추적 및 시각화

🛠️ TECH STACK
Backend & Framework
Java Spring Boot Spring Security

Database & Storage
PostgreSQL

DevOps & Tools
Docker GitHub Actions

Authentication
JWT OAuth2.0

Monitoring & Performance
Grafana Loki Promtail Prometheus RabbitMQ

📊 REAL IMPACT
🎯 실무에서 해결한 문제들
문제 상황	해결 방법	결과
토큰 탈취 위험	RTR 구현	재사용 공격 차단
사용자 인증 필요	OAuth2.0 적용	Monday.com 확장앱 구축
수동 배포의 리스크	GitHub Actions	자동 빌드 및 배포 파이프라인
🔬 개인 프로젝트를 통해 적용해본 기술
선착순 100명 이벤트 시스템 구축

문제 상황	해결 방법	결과
동시성 제어 필요	Redis + 분산 락	정확한 선착순 처리
성능 검증 필요	k6 부하 테스트	동시 접속자 처리 성능 측정
이메일 발송 지연	RabbitMQ	비동기 메시지 큐로 분산 처리
장애 원인 파악	MDC Logging	요청별 추적 ID로 디버깅
시스템 모니터링	Grafana & Loki & Promtail	실시간 로그 수집 및 시각화
리소스 모니터링	Prometheus	CPU, 메모리, 디스크 사용량 추적
🔧 운영성 강화
🔍 장애 대응	✅ 품질 보증	📊 모니터링
MDC Logging
요청별 추적 ID로 빠른 디버깅	HTTP 상태 코드별 테스트
예상치 못한 버그 방지	Grafana & Loki
로그 수집 및 시각화
GlobalExceptionHandler
통합 예외 처리로 일관된 응답	안정적인 API 제공
테스트 코드로 품질 유지	Prometheus
CPU, 메모리, 디스크 리소스 추적
Validation
잘못된 요청 사전 차단		Promtail
로그 자동 수집 및 전송
💡 WHAT MAKES ME DIFFERENT
보안 / 운영성 / 성능까지 고민하는 개발자
단순히 기능을 구현하는 것을 넘어, 왜 이 코드가 필요한가? **어떻게 더 안정적으로 만들 수 있는가?**를 고민합니다.

토큰 탈취 방지를 위한 RTR, 선착순 이벤트의 동시성 제어, 비동기 메시지 처리를 통한 성능 최적화까지
모두 실무와 프로젝트에서 마주한 문제를 해결하기 위해 학습하고 적용한 결과입니다.

장애를 경험하고, 예방하는 방법을 고민합니다
실무에서 디스크 용량 부족으로 인한 장애를 겪은 후, "사후 대응"이 아닌 "사전 예방"의 중요성을 깨달았습니다.
이후 Prometheus를 학습하며 시스템 리소스를 모니터링하고, 문제가 발생하기 전에 미리 감지할 수 있는 환경을 구축했습니다.
