# 미들웨어

## 미들웨어의 개념
미들웨어는 Middle과 Software의 합성어이다
- 분산 컴퓨팅 환경에서 서로 다른 기종 간의 하드웨어나 프로토콜, 통신 환경 등을 연결하여 운영체제와 응용 프로그램, 또는 서버와 클라이언트 사이에엇 원만한 통신이 이루어지도록 함
- 표준화된 인터페이스를 제공함으로써 시스템 간의 데이터 교환에 일관성을 보장
- 위치 투명성 제공
- DB
  - DB를 사용하여 시스템을 구축하는 경우 보통 2-Tier 아키텍처라고 함
  - ODBC, IDAPI, Glue
- RPC(Remote Procedure Call)
  - 원격 프로시저 호출은 응용 프로그램의 프로시저를 사용하여 원격 프로시저를 마치 로컬 프로시저처럼 호출 하는 방식
  - Entera, ONC/RPC
- MOM(Message Oriented Middleware)
  - 메시지 지향 미들웨어는 메시지 기반의 비동기형 메시지를 전달하는 방식
  - 온라인 업무 보다 이기종 분산 데이터 시스템의 데이터 동기를 위해 많이 사용
  - MQ, Message Q, JMS
- TP-Mnitor(Transaction Processing Monitor)
  - 트랜잭션 처리 모니터는 항공기나 철도 예약 업무 등과 같은 온라인 트랜잭션 업무에서 트랜잭션을 처리 및 감시하는 미들웨어
  - 사용자 수가 증가해도 빠른 응답 속도를 유지해야 하는 업무에 주로 사용
  - tuxedo, tmax
- ORB(Object Request Broker)
  - 객체 요청 브로커는 객체 지향 미들웨어로 코바 표준 스펙을 구현
  - 최근에는 TP-Monitor의 장점인 트랜잭션 처리와 모니터링 등을 추가로 구현
  - Orbix, CORBA
- WAS(Web Application Server)
  - 클라이언트/서버 환경보다는 웹 환경을 구현하기 위한 미들웨어
  - HTTP 세션 처리를 위한 웹 서버 기능뿐만 아니라 미션-크리티컬한 기업 업무까지 JAVA, EJB 컴포넌트 기반으로 구현
  - WebLogic, WebSphere
