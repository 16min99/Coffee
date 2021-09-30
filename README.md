# Coffee 주문관리 Web App


## 프로젝트 목표

1. 상품을 판매할 제품 관리 페이지를 구현
2. 상품을 주문할 온라인 웹사이트 구현


## 사용 기술
- Spring Boot / JAVA 11
- MySQL 
- Jdbc Template
- React.js / Thymeleaf


## 시스템 구성도
![image](https://user-images.githubusercontent.com/65473604/135153787-2c5f5c89-8403-4592-998e-1aa472c6f35e.png)

관리자는 Thymeleaf로 작성한 관리자 페이지에서 상품 등록을 합니다.  
고객은 React로 구현된 페이지에서 상품을 주문합니다.  
Spring으로 구현된 WAS에서 Rest API를 통해 주문 페이지와 요청, 응답을 합니다.  
WaS는 Jdbc Template을 통해 RDB에 데이터를 저장 및 관리합니다.

## ERD
![image](https://user-images.githubusercontent.com/65473604/135250463-23996553-400f-4f29-9ef0-661bfb8dc5d4.png)


## 추후 과제
관리자 페이지 기능추가 (상품 수정, 삭제, 주문 목록 조회)
고객 페이지 기능추가 (배송 상태, 주문 수정)



