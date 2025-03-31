# Komofunding

Komofunding은 사용자의 프로젝트를 홍보하고 다른 사용자로부터 후원을 받을 수 있도록 지원하는 크라우드 펀딩 플랫폼입니다.

## Komofunding 프로젝트 발표

[![Komofunding 발표 미리보기](https://raw.githubusercontent.com/KeumKyuHwan/portfolio/main/komofunding/assets/presentation/presentation.gif)](https://github.com/KeumKyuHwan/portfolio/blob/main/komofunding/presentation/KOMOFUNDING__.pdf)

📄 [전체 PDF 보기](https://github.com/KeumKyuHwan/portfolio/blob/main/komofunding/presentation/KOMOFUNDING__.pdf)
## 기간

- 2024.11.04 ~ 2024.12.18

## 인원

- 8명

## 기술스택

- **Frontend**: JavaScript, React.js, HTML, CSS
- **Backend**: Java, Spring Boot, JPA
- **Database**: MariaDB
- **Design**: Figma
- **Diagram**: draw.io, PlantUML

## 기여부분

1. 사용자(User) 관리 기능 개발
- 회원가입, 로그인, 프로필 수정, 이메일 인증 로직 구현
- Spring Security를 활용한 보안 적용

2. 결제(Payment) 시스템 개발
- 백엔드 결제 로직 설계 및 구현
- 결제 서비스와의 연동 (포트원API(토스페이먼츠))

3. API 개발 및 문서화
- 프론트엔드와의 원활한 연동을 위한 RESTful API 설계 및 구현

4. 테스트 및 데이터 관리
- 테스트를 위한 더미 데이터 정보 수집 및 생성

5. 상태 관리 및 프론트엔드 연동
- 노리덕스(Noridux) 패턴을 활용한 상태 관리
- React와 Spring Boot 간 원활한 데이터 흐름을 위한 API 연동

#### Github 주소 : https://github.com/coding-ji/komofunding.git

## 소개
>### 메인
#### 메인 화면
- ###### 메인 화면은 프로젝트의 달성률과 대표 이미지를 중심으로 간결하게 구성하였습니다. Framer motion을 활용하여 다양한 애니메이션을 적용하여 동적인 사용자 경험을 제공합니다.

![komofunding main](https://github.com/user-attachments/assets/8980fef9-761b-40d1-9b40-73925e2ba01f)

---

## 🏠 **홈 화면**
- 전체 프로젝트를 카테고리별로 확인할 수 있도록 구성
- 후원하는 품목에 집중할 수 있도록 이미지를 중심으로 한 레이아웃 제공
    - **Home**: 운영자의 승인을 받은 모든 프로젝트
    - **Upcoming**: 아직 후원이 시작되지 않은 프로젝트
    - **Active**: 현재 후원이 진행 중인 프로젝트

---

## 👤 **유저**
### 마이페이지
- 사용자의 활동과 정보를 한 곳에서 관리 가능
- **프로필 편집**: 사용자의 정보를 수정할 수 있음
- **제작자 전환 신청**: 프로젝트 생성 전 운영자 승인이 필요
- **나의 후원**: 사용자가 후원한 프로젝트 조회 및 환불 가능
- **나의 문의**: 1:1 문의 기능 제공
- **프로젝트 문의 댓글**: 답글이 없을 경우에만 수정 가능, 프로젝트 작성자만 답변 가능

---

## 📌 **프로젝트**
### 프로젝트 관리
- 제작자 전환 후 프로젝트 생성 가능
- 마이페이지에서 본인의 프로젝트 생성, 수정, 삭제 가능
- **프로젝트 생성**: 제목, 소개 글, 카테고리, 상품 작성 후 운영자 승인 필요
- **프로젝트 확인**: 마이페이지에서 프로젝트 제목 클릭 시 상세 페이지 확인 가능
- **프로젝트 수정**: 제목, 소개 글, 카테고리만 수정 가능
- **프로젝트 삭제**: 프로젝트가 시작되지 않은 경우에만 가능

---

## 💳 **결제**
- 결제는 **포트원 API(토스페이먼츠)**를 통해 연동
