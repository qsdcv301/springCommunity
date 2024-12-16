# 📚 웹 애플리케이션 개요

## 1. 🚀 프로젝트 이름

**Spring Community**  

---

## 2. 📖 프로젝트 개요

- **📌 목적**: 기업 요구사항에 맞춘 온라인 서점 시스템 개발 및 포트폴리오 활용
- **🎯 주요 목표**:
  - ✅ 참여기업 요구사항 지시에 맞춘 각 시스템별 기능 구현
  - ✅ 유저 / 관리자 SIDE별 기능 제공
  - ✅ **회원가입, 로그인, 내정보 수정 기능**  
    (Google, Naver, Kakao 등 Synchro 로그인)
  - ✅ 장바구니, 구매기록 기능
  - ✅ **배송비 시스템** (주문/교환/반품 - 무료 / 조건부 무료)
  - ✅ 결제 및 조회 기능 (PG사 연동)
  - ✅ 적립금 시스템
  - ✅ **상품 및 게시판 등록 및 관리** (리뷰, 공지사항 등)

---

## 3. 🔧 기술 스택

### 🛠️ 개발 도구

![VS Code](https://img.shields.io/badge/IDE-VS%20Code-blue?logo=visualstudiocode&logoColor=white) ![IntelliJ](https://img.shields.io/badge/IDE-IntelliJ%20IDEA-orange?logo=intellijidea&logoColor=white)

### 🎨 프론트엔드

![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white) ![Jquery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white)

### 🔙 백엔드

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?logo=springsecurity&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-6DB33F?logo=hibernate&logoColor=white) ![Json](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)

### 🗄️ 데이터베이스

![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![AWS RDS](https://img.shields.io/badge/AWS%20RDS-232F3E?logo=amazonaws&logoColor=white)

### 🤝 협업 도구

![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) ![figma](https://img.shields.io/badge/figma-F24E1E?logo=figma&logoColor=black) ![googlesheets](https://img.shields.io/badge/googlesheets-34A853?logo=googlesheets&logoColor=white) ![googlecloud](https://img.shields.io/badge/googlecloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

### ⚙️ 기타 도구

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![PostMan](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white) ![kakao](https://img.shields.io/badge/kakao%20API-FFCD00?style=flat-square&logo=kakao&logoColor=black) ![naver](https://img.shields.io/badge/naver%20API-03C75A?style=flat-square&logo=naver&logoColor=white) ![google](https://img.shields.io/badge/google%20API-4285F4?style=flat-square&logo=google&logoColor=white) ![dotenv](https://img.shields.io/badge/dotenv-ECD53F?logo=dotenv&logoColor=black)

---

## 5. 📜 주요 기능 설명

### 💻 사용자 페이지

- 🔑 **회원가입 및 로그인**
  - 일반 회원가입 및 소셜 로그인 지원 (Google, Naver, Kakao)
- 👩‍🦲 **마이 페이지**
  - 나의 정보, 주문 내역, 문의 내역으로 효율적인 정보 관리 가능
- 🛒 **장바구니**
  - 상품의 구매와 찜 기능을 한 페이지로 효율적으로 관리
- 📜 **카테고리 분류**
  - 헤더의 navigation기능으로 효율적인 상품 조회 가능
- 🔍 **검색 기능**
  - 통합,제목,작가,ISBN,출판사 검색을 통해 세분화된 검색과 다시 결과내 재검색을 통해 효율적인 검색 기능 구현
- ✋ **고객센터**
  - 공지사항, FAQ, 문의하기, 이용약관을 고객센터 탭을 통해 상세한 내용 확인가능
- 💰 **적립금 시스템**
  - 상품 구매 및 이벤트 참여 시 적립금 지급
  - 일정 적립금 이상 시 구매에 사용 가능

### 🛠 관리자 페이지

- 📊 **관리자 페이지 대쉬보드**
  - 주문, 회원, 매출, 문의, Todolist, 실적, 현황 그래프를 통해 전반적인 정보 확인 가능
- 🧑 **회원 관리**
  - 회원 등급별 조회 시스템, 검색기능, 일괄 등급 변경기능, 회원 삭제기능으로 효율적인 관리 제공
- 📦 **도서 등록 및 관리**
  - 도서 조회 및 관리, 카테고리 관리를 분리하여 효율적인 도서 및 카테고리 관리 기능 제공
- 💳 **주문 관리(주문, 결제, 배송)**
  - 상세 필터를 통해 효율적 검색가능, 선택된 상품을 일괄적으로 상태 변경 가능
- 📝 **게시판 관리**
  - 공지사항 ,이벤트, 리뷰, Q&A를 통해 게시물의 추가 삭제를 관리함

---

## 8. 📊 ERD

| ERD | 이미지                            |
| --- | --------------------------------- |
| ERD | ![ERD](./read.me.image/00erd.png) |

---

## 9. 🖼️ 화면 예시

| 화면 설명                         | 이미지                                                                  | 설명                                                                        |
| --------------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 메인 페이지                       | ![메인 페이지](./read.me.image/00main.png)                              | 메인 페이지는 사용자가 사이트에 처음 접속했을 때 표시되는 기본 화면입니다.  |
| 상품 메인 페이지                  | ![상품 메인 페이지](./read.me.image/01bookproduct.png)                  | 상품 목록과 각 상품의 상세 정보를 확인할 수 있는 페이지입니다.              |
| 상품 디테일 페이지                | ![상품 디테일 페이지](./read.me.image/01bookdetail.png)                 | 상품 클릭시 상품의 상세정보를 볼 수 있는 상품 디테일 페이지입니다.          |
| 회원가입1 페이지                  | ![회원가입1 페이지](./read.me.image/02signup1.PNG)                      | 회원가입을 할 수 있는 페이지입니다.                                         |
| 회원가입2 페이지                  | ![회원가입2 페이지](./read.me.image/02signup2.PNG)                      | 회원가입을 할 수 있는 페이지입니다.                                         |
| 로그인 페이지                     | ![로그인 페이지](./read.me.image/03login.PNG)                           | 회원가입 후 로그인 또는 간편 소셜로그인을 할 수 있는 페이지입니다.          |
| 마이페이지 - 나의정보             | ![마이페이지 - 나의정보](./read.me.image/04mypage_profile.png)          | 가입한 정보를 확인하고 수정할 수 있는 페이지입니다.                         |
| 장바구니 페이지                   | ![장바구니 페이지](./read.me.image/05Cart.png)                          | 사용자가 선택한 상품들을 확인하고 결제를 진행할 수 있는 페이지입니다.       |
| 주문 확인 모달                    | ![주문 확인 모달](./read.me.image/05order.PNG)                          | 주문하기 전 정보를 확인하고 구매할 수 있는 모달창입니다.                    |
| PG연동 모달                       | ![PG연동 모달](./read.me.image/05PG_Pay.PNG)                            | 결제시 PG사 연동하여 결제할 수 있는 모달창입니다.                           |
| 마이페이지 - 주문내역             | ![마이페이지 - 나의정보](./read.me.image/06mypage_orderlist.PNG)        | 주문한 정보를 확인할 수 있는 페이지입니다.                                  |
| 주문내역 상세 모달                | ![주문내역 상세 모달](./read.me.image/07orderlist_check.PNG)            | 주문내역을 상세하게 확인할 수 있는 페이지입니다.                            |
| 관리자페이지 - 대시보드           | ![관리자페이지 - 대시보드](./read.me.image/8Admin_Dashboard.png)        | 관리자페이지에 처음 접속하면 한 눈에 확인하고 관리할 수 있는 페이지입니다.  |
| 관리자페이지 - 상품관리페이지     | ![관리자페이지 - 상품관리페이지](./read.me.image/9Admin_Product.png)    | 상품을 등록하고 조회, 관리할 수 있는 페이지입니다.                          |
| 관리자페이지 - 이벤트 관리 페이지 | ![관리자페이지 - 이벤트 관리 페이지](./read.me.image/10Admin_Event.png) | 이벤트를 등록하거나 관리할 수 있는 페이지입니다.                            |
| 이벤트 추가 모달                  | ![이벤트 추가 모달](./read.me.image/10Event_add.PNG)                    | 이벤트를 추가할 수 있는 모달창입니다.                                       |
| 최근 본 도서 확인                 | ![최근 본 도서 확인](./read.me.image/booklist.PNG)                      | 최근 본 도서 목록을 볼 수 있는 창입니다.                                    |
| 페이지 네비게이션 버튼            | ![관리자페이지 - 대시보드](./read.me.image/Detail_Buttun.PNG)           | 홈으로 돌아가기 / 상단으로 이동 / 관리자모드 / 최근 본 상품목록 버튼입니다. |

---
