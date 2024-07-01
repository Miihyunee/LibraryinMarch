# 📚 3월 도서관 (2nd Team Project)

국비지원 훈련과정 두번째 팀프로젝트입니다.

둘 이상의 사용자를 가정하고 각 환경에 맞는 통합 웹 환경, 이용 권한이 구분되는 케이스 라는 조건에 만족하는
가상의 도서관 & 도서 통합관리 시스템을 구현하였습니다.
<br><br>

## 🔖 목차
[1. 프로젝트 개요](#-1.-프로젝트-개요)
   - [개발 기간](#-개발-기간)
   - [사용 기술 및 개발 환경](#-사용-기술-및-개발-환경)
   - [팀원 소개](#-팀원-소개)   

[2. 프로그램 구조](#-2.-프로그램-구조)
   - [ER Diagram](#-ER-Diagram)
   - [View](#-View)
   - [Usecase Diagram](#-Usecase-Diagram)
   - [Flow Chart](#-Flow-Chart)

[3. 페이지 기능 안내](#-3.-페이지-기능-안내)
   - [관리자 화면 <통합관리시스템>](#-관리자-화면-<통합관리시스템>)
   - [사용자 화면 <도서관 홈페이지>](#-사용자-화면-<도서관-홈페이지>)

[4. 개선사항 및 후기](#-4.-후기-및-개선점)
   - [후기](#-후기)
   - [개선점](#-개선점)

[5. 참고 URL](#-5.-참고-URL)

<br><br>

## 1. 프로젝트 개요
### 🗓 개발 기간
* 2024.02.08 ~ 2024.03.11
* 1주차 : 프로젝트 기획 및 DB 구축 회의, 화면 설계(파트별 레이아웃 및 핵심 기능 설계)
* 2주차 : 파트별 DB 설계 및 구축, 개인별 화면 및 모델 개발 작업 진행
* 3주차 : 1차 기능테스트 및 작업현황 공유, 오류 수정
* 4주차 : 2차 기능테스트, 사이트 오픈 및 최종시연, 프레젠테이션 준비

<br>

### 🖥 사용 기술 및 개발 환경
* OS : <img src="https://img.shields.io/badge/windows 11-0078D4?style=for-the-badge&logo=windows11&logoColor=white">
* Front-end : <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
* Back-end : <img src="https://img.shields.io/badge/Java-34567C?style=for-the-badge&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white"> <img src="https://img.shields.io/badge/OpenJDK-000000?style=for-the-badge&logo=OpenJDK&logoColor=white">
* Tools : <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=for-the-badge&logo=EclipseIDE&logoColor=white">
* Library : <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=white"> <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=for-the-badge&logo=ApacheTomcat&logoColor=black"> <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=Chart.js&logoColor=white"> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white"> <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=JSON&logoColor=white">

<br>

### 👩‍💻 팀원 소개
* [도경민](https://github.com/mindyhere)
* 박미현🙋‍♀️
* [양미영](https://github.com/didaldud)
* [조연우](https://github.com/yunuyununu)
* [홍재희](https://github.com/jh91019)

![member](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/85ed98a1-3da0-481a-9fdc-317824ecd381)

<br><br>

## 2. 프로그램 구조
### 🔹 ER Diagram
![erDiagram](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/4ce6cca0-29a9-4622-9053-7c1650431234)

<br>

### 🔹 View
![view](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/a5d8b2cf-63eb-4e81-b617-1d63277b5ef6)

<br>

### 🔹 Usecase Diagram
![usecase](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/231b4dd7-0193-42ab-857f-9368f744c1dd)

<br>

### 🔹 Flow Chart
 - 관리자 
![flow_admin](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/6850b5c1-19c7-42dc-a5aa-039ad6ceb444)

<br>

 - 사용자(회원/비회원)
![flow-user](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/8c42ac33-d93d-418c-9c4a-ea3b85f6611e)

<br><br>

## 3. 페이지 기능 안내
#### 관리자 화면 <통합관리시스템>
   - 관리자 메인
     ![관리자 메인](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/ba758fd9-9bbf-4312-8018-72ac8eb237b1)
     ![관리자메인상세](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/5cf81a9e-5eb7-4eea-8123-22ce78910f50)

<br>

   - 도서목록/수정
     ![도서수정](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/2b260718-05e8-469d-ac7f-d50f0ab87301)

<br>

   - 도서 등록
     ![도서등록](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/18693b1e-85a0-4d88-948f-a18814271eeb)

<br>

   - 도서 대출/반납 목록
     ![대출반납목록](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/583178a9-b1a3-4530-a40a-02d2c3c31a8a)

<br>

   - 예약 도서 목록
     ![예약도서목록](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/2066c1d6-7f3c-450b-95c0-9996bea81517)

<br>

   - 도서 이용 통계
   ![도서 통계](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/3b72d358-5239-4355-ae84-62ff7dba883b)

<br><br>

#### 사용자 화면 <도서관 홈페이지>
   - 추천 도서(관리자 기능)
     ![홈-추천도서](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/b36326fa-cc59-4f86-8818-9c97e147c129)

<br>

   - 도서 검색

     <br>
     
   - 회원가입
     ![회원가입](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/6d207e05-4032-4e43-91f8-fa302f24cb55)

<br>

   - 로그인
     ![로그인](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/64ffedd7-eca1-4656-99b2-a4d5aeb85453)

<br>

   - 비밀번호 찾기 (아이디 찾기도 동일)
     ![비밀번호찾기](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/7f0f1064-1c11-4945-b3d4-571cb4a636a1)

<br>

   - 회원정보 수정
     ![회원정보수정](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/211d1ef3-1a66-45cb-a6b8-d9c48095e3c3)

<br>

   - 대출 신청
   ![대출신청](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/ff5d8a87-b5c2-48f0-bfcf-e6297228985e)

<br>

   - 도서 연장 신청
     ![대출중인도서-연장](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/677a7160-1cbb-4ea8-9c59-b8a7471f87d3)

<br>

   - 도서 리뷰 작성
     ![리뷰작성](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/71a1754d-43d8-4c31-849d-71552561d934)

<br>

   - 도서 정보 프린트
   ![인쇄](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/8c4b0806-112b-40fc-b583-40ea31d7469f)

<br>

   - 나의 서재
     ![나의서재](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/651fc006-9b71-4ede-8b69-636f351557df)

<br>

   - 예약 도서 취소
   ![예약취소](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/f482ded6-8c36-4931-a99f-57bed27beeac)

<br>

   - 도서관 오는길
   ![도서관오는길](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/38f83cb3-d124-4979-a2ea-9673641773f6)

<br><br>

## 4. 후기 및 개선점
### 📝 후기
- DB구축 과정에서 기획부터 다양한 테이블 관계 형성과 프로시저, 뷰를 적극 활용할 수 있도록 노력했고 그 결과 많은 공부가 되었다.
- 협업툴로써  SVN을 활용하여 1차 프로젝트보다 의사소통 및 버전 관리를 더 효율적으로 진행할 수 있었다.
- 팀 프로젝트를 통해 서로 부족한 부분을 채울 수 있는 계기가 되었다.

<br>

### 🛠 개선점
- 데이터가 바뀔 때마다 화면 깜빡이는 현상 개선
- 검색어 자동완성 기능 업그레이드
- 온라인 중고 서적 사이트나 도서관이용 모바일 앱 등으로의 발전
- 도서정보 오픈API 활용해보기
- 현업에서 많이 사용하는 Git을 활용해 볼 것을 고려

<br><br>

## 5. 참고 URL
| No. | Site | URL |
|---|:---:|---:|
| 1 | 노원구 구립도서관 | https://www.nowonlib.kr |
| 2 | 인창도서관 | https://www.gurilib.go.kr/inlib/index.do |
| 3 | 국립중앙도서관 | https://www.nl.go.kr |
| 4 | 알라딘 | https://www.aladin.co.kr/home/welcome.aspx |
| 5 | 교보문고 | https://www.kyobobook.co.kr |
