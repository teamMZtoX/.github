# <img src="img/ico_clbg.png" width="30" height="30"> Project MZtoX 

<div style="text-align: center;">
    <a href="http://mztox.aikopo.net/">
        <img src="img/MZTOX.png" />
    </a>
</div>

## 1. 프로젝트 소개

MZtoX 프로젝트는 신조어로 인한 언어 소통 문제를 해결하기 위한 프로젝트입니다. <br>한국어 LLM 모델을 이용하여 신조어를 평문으로 번역해, 신조어의 의미를 이해할 수 있도록 돕고 있습니다. <br>웹 사이트를 통해 서비스를 제공하여 사용자의 접근성을 높였고, 단순한 UI를 채택하여 사용성을 향상시켰습니다.
<br>
[사용방법](#6-데모-사이트)
## 2. 팀원 소개 (한국 폴리텍 대학교 서울 정수 캠퍼스 인공지능 소프트웨어과)

| 이름     | 역할                  | 기술 스택                                                                                                                                       | 소개                                           | 
|:---------|:---------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------|
| 강병준   | 지도교수             |                                                                                                                                                 | 든든한 지도교수님                           |
| 유승호   | 팀 리더              | ![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white) <br> ![Flask](https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white) <br> ![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) <br> ![Naver Cloud](https://img.shields.io/badge/Naver%20Cloud-00A859?style=flat-square&logo=naver&logoColor=white) | 프로젝트 관리를 담당 <br> 인공지능 서버 구축 <br> 네이버 클라우드 기반 서버 구축 |
| 변서진   | 프론트엔드 개발자    | ![Vue.js](https://img.shields.io/badge/vuejs-4FC08D?style=flat-square&logo=vue.js&logoColor=white) <br> ![Node.js](https://img.shields.io/badge/Node.js-8CC84B?style=flat-square&logo=node.js&logoColor=white) <br> ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) | 웹 애플리케이션 개발 <br> 웹 서버 구축      |
| 오상현   | 학습 데이터 구축 담당 | ![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white) <br> ![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) <br> ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | 인공지능 학습 데이터 라벨링 자료 수집 및 가공 <br> 학습 데이터 라벨링   |
| 이석호   | 백엔드 개발자        | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white) <br> ![Apache Tomcat](https://img.shields.io/badge/Apache%20Tomcat-F8DB2D?style=flat-square&logo=apachetomcat&logoColor=black) <br> ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) <br> ![Spring Boot](https://img.shields.io/badge/spring_boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) | Spring security를 이용한 로그인 구현 <br> RestAPI 서버 구현              |


## 3. 개요
- **프로젝트 이름**: MZtoX
- **프로젝트 지속 기간**: 2024.07.01 ~ 2024.08.22
- **서버 제공**: ![Naver Cloud](https://img.shields.io/badge/Naver%20Cloud-00A859?style=flat-square&logo=naver&logoColor=white)
- **OS**: ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
- **개발 언어**: ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white) ![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
- **개발 프레임워크**: ![Spring Boot](https://img.shields.io/badge/spring_boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Flask](https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white) ![Vue.js](https://img.shields.io/badge/vuejs-4FC08D?style=flat-square&logo=vue.js&logoColor=white) ![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
- **서버**: ![Apache Tomcat](https://img.shields.io/badge/Apache%20Tomcat-F8DB2D?style=flat-square&logo=apachetomcat&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

## 4. 구현 일정

| 구분   | 추진 내용                      | 추진 <br>일정                      | 1주 | 2주 | 3주 | 4주 | 5주 | 6주 | 7주 | 8주 |
|--------|-------------------------------|----------------------------------|-----|-----|-----|-----|-----|-----|-----|-----|
| 도입   | 프로젝트 검토 및 예산안 설정 |                                  | ■   |     |     |     |     |     |     |     |
| 계획   | 역할 분담 및 단계 설정       |                                  | ■   | ■   |     |     |     |     |     |     |
| 실행   | AI 알고리즘 프로그래밍 <br> (Python) |                              |     |     | ■   | ■   |     |     |     |     |
| 실행   | 백엔드 프로그래밍 <br> (Spring Boot) |                              |     |     | ■   | ■   |     |     |     |     |
| 실행   | 프론트엔드 프로그래밍 <br> (Vue.js) |                              |     |     | ■   | ■   |     |     |     |     |
| 테스트 | 웹 호스팅 및 디버깅         |                                  |     |     |     |     | ■   | ■   | ■   | ■   |
|        | 오프라인 미팅 계획           |                                  | ■   | ■   | ■   | ■   | ■   | ■   | ■   | ■   |

## 5. 구현 핵심 기술
### AI 서버
- kobart를 이용한 translate 모델 제작
- TCP/IP 통신을 이용한 Model 포팅
- Flask를 이용한 Router 서버 제작


### Spring Boot 백엔드 서버
-   Spring boot 사용하여 RESTful API 서버 개발
-   SpringSecurity를 사용하여 사용자 인증 및 권한 관리
-   Jwt 토큰을 이용한 보안 및 유효성검사
-   로그인, 회원가입, 회원탈퇴, 번역서비스, 최근번역기록 기능 구현  
-   MariaDB 사용하여 회원관리 및 번역내용 저장   

### Vue.js Web 어플리케이션
- Vue.js: 사용자 인터페이스를 구축하기 위한 프레임워크. 컴포넌트 기반 아키텍처로 코드 재사용성 향상
- Vue Router: 라우팅 관리. 페이지 간 탐색 시 적절한 컴포넌트 로드
- Axios: HTTP 요청 관리 라이브러리. 서버와의 비동기 통신으로 데이터 송수신 처리
- CSS: 미디어 쿼리를 활용한 반응형 웹 디자인. 다양한 화면 크기에 최적화된 사용자 경험 제공

### 학습 데이터 구축 및 가공

- 국립국어원 우리말샘 사전 및 AI-Hub 연령대별 특징적 발화(은어·속어) 음성데이터의 사전 데이터, 2023~2024년 신조어 수집으로 학습데이터 구축

- Python, Pandas를 이용한 데이터 전처리

- PySide를 이용한 라벨링 프로그램 AnnoText 제작

- AnnoText를 이용한 학습데이터 라벨링
## 6. 데모 사이트
우리가 만든 애플리케이션을 직접 체험해 보세요!

[**데모 사이트 방문하기**](http://mztox.aikopo.net/) (2024.08.22 까지 운영 예정)


[**로그인 없이 사용시**]

![데모 사이트](img/demo_unlogin.gif)



[**로그인 후 사용시**]

![데모 사이트](img/demo_login.gif)

## 7. 업데이트 내역
- **07-31** 
    1. 중복 회원가입 문제 해결
    2. 인공지능 서버 null 값 들어가는 문제 해결
 
- **08-01**
    1. 최근 번역목록 업데이트
    2. 회원 탈퇴 기능 추가
    3. 회원 약관 추가
    4. 번역 중 UI 개선
    5. 디자인 개선
    6. 모델 추론 GPU로 변경 (레이턴시 개선)

- **08-02**
    1. SSL 인증서 등록
    2. HTTPS 자동 리다이렉트

- **08-07**
    1. 토큰 만료시 자동 로그아웃 추가
       
- **08-19**
    1. 새로운 문장 추가 학습
    2. 초성 관련 번역 추가

## 8. 후기
- 추후 작성 예정

## 9. Reference
- [KoBART](https://github.com/SKT-AI/KoBART)
- [Kobart-translation](https://github.com/seujung/KobART-translation)
- [AI-hub 연령대별 특징적 발화(은어·속어 등) 음성 데이터](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71320)
