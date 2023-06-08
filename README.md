# 💻 커머스 프로젝트
구매자와 판매자 사이를 중계해주는 서버 구축

# ⚙ 기술 스택
- Language : `Java 11`
- Framework : `Spring Boot 2.7.12`
- Database
  - RDB : `MySQL`
  - Non-Relation DBMS : `Redis`
- Test : `JUnit5`
- Build : `Gradle`
- Login Token : `JWT`
- Test UI : `Swagger`

# 🔎 요구 사항
- 회원
  - 공통
    - 이메일 등록시 인증번호를 통한 회원가입
  - 구매자
    - 회원가입
    - 인증 (이메일)
    - 로그인 토큰 발행
    - 로그인 토큰을 통한 제어 확인 (JWT, Filter 사용)
    - 예치금 관리
  - 판매자
    - 회원가입
- 주문 서버
  - 구매자
    - 장바구니를 위한 Redis 연동
    - 상품 검색 및 상세 페이지
    - 장바구니에 물건 추가
    - 장바구니 확인
    - 주문하기
    - 주문내역을 이메일로 발송
  - 판매자
    - 상품 등록/수정/삭제
