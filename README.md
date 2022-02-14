# jpashop
Spring Boot / JPA를 이용한 쇼핑몰 웹 구현

### 사용기술
- Spring Boot
- JPA
- RDBMS (H2)

### 메인 화면
<img src="https://user-images.githubusercontent.com/41888956/153838268-c2cd61b5-9cb5-4de2-bd4f-e6fcf2f66872.png"/>

### 회원 가입
![image](https://user-images.githubusercontent.com/41888956/153838506-b9d96274-de84-4855-a4eb-0bd6b99a2750.png)

#### 회원 목록
![image](https://user-images.githubusercontent.com/41888956/153838557-2c07d7e8-6b9c-4c1a-bedb-767f192b2d73.png)

### 상품 등록
![image](https://user-images.githubusercontent.com/41888956/153838578-8942e294-bb3e-47e4-9a1d-2b74642204d8.png)

#### 상품 목록
![image](https://user-images.githubusercontent.com/41888956/153838617-477fb37a-4018-45ae-ae9e-dfb670f746fa.png)

### 상품 주문
![image](https://user-images.githubusercontent.com/41888956/153838680-3d8fea9c-8964-40c6-9829-f4b7b9e568fa.png)


#### 주문 목록
![image](https://user-images.githubusercontent.com/41888956/153838722-94448947-daaa-45c3-b01b-94c67604ccad.png)


### 요구사항
- 회원 기능
  - 회원 등록
  - 회원 조회
- 상품 기능
  - 상품 등록
  - 상품 수정
  - 상품 조회
- 주문 기능
  - 상품 주문
  - 주문 내역 조회
  - 주문 취소
- 기타 요구사항
  - 상품은 재고 관리가 필요하다.
  - 상품의 종류는 도서, 음반, 영화가 있다.
  - 상품을 카테고리로 구분할 수 있다
  - 상품 주문시 배송 정보를 입력할 수 있다.

### 도메인 모델 및 테이블 설계
![image](https://user-images.githubusercontent.com/41888956/152853382-f468f2c2-66d1-4926-86ba-a3d99cfa455d.png)

### Entity 관계 정의
![image](https://user-images.githubusercontent.com/41888956/152853204-5115f9b5-da59-4a5b-8f78-5ffc4bd1a6bd.png)

### ERD
![image](https://user-images.githubusercontent.com/41888956/152853333-6b0d308d-4228-44c5-b961-18fc9b6ab1be.png)
