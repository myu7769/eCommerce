# eCommerce
eCommerce basic project

Use : Spring, Jpa , Mysql , Redis, Docekr, AWS

Goal : 판매자와 구매자 사이를 중개해주는 커머스 서버 구축


## 회원
### 공통

  - [ ] 이메일을 통해 인증 번호를 통한 회원 가입

### 고객

  - [ ] 회원 가입
  - [ ] 인증(이메일)
  - [ ] 로그인 토큰 발행
  - [ ] 로그인 토큰을 통한 제어 확인(JMT, FILTER를 사용해서 간략하게 구현)
  - [ ] 예치금 관리 

### 판매자

  - [ ] 회원 가입
  
## 주문 서버

### 판매자

  - [ ] 상픔 등록, 수정
  - [ ] 상품 삭제

### 구매자

  - [ ] 장바구니를 위한 Redis 연동
  - [ ] 상품 검색 & 상세 페이지
  - [ ] 장바구니에 물건 추가
  - [ ] 장바구니 확인
  - [ ] 주문하기
  - [ ] 주문내역 이메일로 발송하기
