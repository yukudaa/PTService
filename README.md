**사용자 (member)**

```json
**Member**
id : Long
userName : String
passWord : String
gender : String
ticket: Ticket
Study : study
role : Role
createdAt : LocalDateTime
endedAt : LocalDateTime
```

```json
Teacher
id : Long
teacherName : String
role : Role
```

```json
**MemberShip**
id : Long
type : String
duration : LocalDateTime
createdAt : LocalDateTime
endedAt : LocalDateTime
```

```json
**Study**
id : Long
teacher : Teacher
member : Member

```

사용자 이용권 조회 페이지(수업예약, 출석, 이용권 횟수) 

로그인(소셜) 페이지 (Oauth2.0) ⇒ naver, google

메인 페이지 index.html

PT수업 예약 페이지

```json

```

이용권 구매 페이지 

```json
Request

GET /ticket/purchase
```

```json
Response

```

이용권 관리 페이지 Get(ticket/manage)

```jsx
Request

GET /ticket/manage
```

**관리자 (admin)**

관리자 이용권 등록 페이지 

관리자 통계 조회 페이지

https://app.eraser.io/workspace/ShvsRrbJqYDbrVY4i5HM
