# jpashop
Spring Boot / JPA를 이용한 쇼핑몰 웹 구현

### 사용기술
- Spring Boot
- JPA
- RDBMS (H2)

### 메인 화면
![image](https://user-images.githubusercontent.com/41888956/153837246-cabdf98b-5d7b-4f3a-9b54-8e9c1872e32b.png)

### 회원 가입
![image](https://user-images.githubusercontent.com/41888956/153837492-612e86e5-47c9-420e-92c3-8dd2c75ac99d.png)

#### 회원 목록
![image](https://user-images.githubusercontent.com/41888956/153837283-f6f7bc74-22bc-49ad-8358-d245030997ef.png)

### 상품 등록
![image](https://user-images.githubusercontent.com/41888956/153837524-a623a68b-6fd0-4b03-ad50-8c29990002a8.png)

#### 상품 목록
![image](https://user-images.githubusercontent.com/41888956/153837339-af820d73-f484-43cc-b8ac-a7a4a349b7c1.png)

### 상품 주문
![image](https://user-images.githubusercontent.com/41888956/153837649-af2248ad-dbc6-4abc-90eb-9439eeb4e756.png)

#### 주문 목록
![image](https://user-images.githubusercontent.com/41888956/153837392-17b326ec-0a6e-46d8-8466-15827ce4894a.png)


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
