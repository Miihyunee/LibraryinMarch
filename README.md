# 📚3월 도서관
도서관 및 도서 통합관리 웹
<br><br>
## 🖥 프로젝트 소개
둘 이상의 사용자를 가정하고 각 환경에 맞는 통합 웹 환경 구현
이용 권한이 구분되는 케이스를 레퍼런스로 활용
<br><br>
## 📅 개발 기간
* 2024.02.08 ~ 2024.03.11
<br><br>
### 🧑‍🤝‍🧑 팀원 소개
 - 박미현 : (사용자)로그인 페이지, 아이디/비밀번호 찾기 페이지, 나의서재 페이지, 대출현황 페이지, 연장신청, 대출이력페이지, 대출/예약/반납 안내페이지, 도서관 오는길 페이지, 주소검색 API, 카카오맵API<br>
 - 도경민 : (사용자)메인페이지, 인기도서/사용자 지정 추천도서, 도서통합검색/상세검색, 도서 상세정보 및 리뷰, 대출신청, 사이트맵 페이지<br>
 - 양미영 : (사용자)회원가입 페이지, 예약목록 페이지, 예약신청, 취소 및 대출<br>
 - 조연우 : (관리자)로그인 페이지, 메인페이지, 회원목록 페이지, 예약현황 페이지, 월간 분류별 대출량 통계<br>
 - 홍재희 : (관리자)도서목록 페이지, 도서 등록/수정/삭제, 도서 대출/반납 목록 페이지, 대출도서관리 페이지, 주간 도서 대출량 통계, 모달 구현
<br><br>
### ⚙️ 개발 환경
- `Java`
- **os** : Windows11
- **Tools** : Eclipse, SQL Developer, SVN
- **Front-end** : HTML, CSS, Javascript
- **Back-end** : JDK21, Oracle DB
- **Library** : Lombok 1.18.30, MyBatis 3.5.15, Json, Jquery 3.7.1, JSTL, Ajax, Bootstrap 5.3, Sweetalert2, Chart.js 4.4.0, Apache Tomcat 10.1.19
<br><br>
## 📌 주요 기능
#### 로그인 - <a href="주소" >상세보기 - WIKI 이동</a>
- DB값 검증
- ID찾기, PW찾기
- 로그인 시 쿠키(Cookie) 및 세션(Session) 생성
#### 회원가입 - <a href="주소" >상세보기 - WIKI 이동</a>
- 주소 API 연동
- ID 중복 체크
#### 마이 페이지 - <a href="주소" >상세보기 - WIKI 이동</a>
- 주소 API 연동
- 회원정보 변경

#### 영화 예매 - <a href="주소" >상세보기 - WIKI 이동</a>
- 영화 선택(날짜 지정)
- 영화관 선택(대분류/소분류 선택) 및 시간 선택
- 좌석 선택
- 결제 페이지
- 예매 완료
#### 메인 페이지 - <a href="주소" >상세보기 - WIKI 이동</a>
- YouTube API 연동
- 메인 포스터(영화) 이미지 슬라이드(CSS)
#### 1대1문의 및 공지사항 - <a href="" >상세보기 - WIKI 이동</a> 
- 글 작성, 읽기, 수정, 삭제(CRUD)

#### 관리자 페이지 
- 영화관 추가(대분류, 소분류)
- 영화 추가(상영시간 및 상영관 설정)
