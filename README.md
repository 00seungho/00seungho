# How To Use
```
python seungho.py --input coffice☕
```
기술 스택
----------

### 🧑‍💻 **프로그래밍 언어**
[![Python Badge](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)](https://www.python.org/)
[<img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>](https://developer.mozilla.org/ko/docs/Web/JavaScript)
[<img src="https://img.shields.io/badge/C Language-A8B9CC?style=flat-square&logo=C&logoColor=white"/>](https://learn.microsoft.com/ko-kr/cpp/c-language/?view=msvc-170)
<a href="https://www.r-project.org/">
    <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white" alt="R Language Badge"/>
</a>

---

### ⚙️ **프레임워크 & 라이브러리**
[<img src="https://img.shields.io/badge/tensorflow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>](https://www.tensorflow.org/?hl=ko)
[<img src="https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>](https://pytorch.org/)
[<img src="https://img.shields.io/badge/nodedotjs-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>](https://nodejs.org/en)
[<img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>](https://spring.io/projects/spring-boot)
[<img src="https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white"/>](https://flask.palletsprojects.com/en/3.0.x/)

---

### 🗄️ **데이터베이스**
[<img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"/>](https://www.mysql.com/)
[<img src="https://img.shields.io/badge/mariadb-003545?style=flat-square&logo=mariadb&logoColor=white"/>](https://mariadb.com/kb/ko/mariadb-korean/)

---

### 🔧 **버전 관리 및 협업**
[<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/>](https://github.com/)

---

### 💻 **운영체제**
[<img src="https://img.shields.io/badge/linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>](https://github.com/)
[<img src="https://img.shields.io/badge/ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white"/>](https://github.com/)
[<img src="https://img.shields.io/badge/windows-0078D4?style=flat-square&logo=windows10&logoColor=white"/>](https://github.com/)
[<img src="https://img.shields.io/badge/Raspbian-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>](https://github.com/)
[![CentOS](https://img.shields.io/badge/CentOS-CC0000?style=flat-square&logo=centos&logoColor=white)](https://www.centos.org/)

---



## 📚 **프로젝트**

---

### 👥 **팀 프로젝트**

#### 1. [RealGlow](https://github.com/TeamRealGlow)
> **화장품 효과 시각화 쇼핑 도우미 어플리케이션**
- **프로젝트 개요**
    -  생필품과 가전제품은 온라인으로 쉽게 구매할 수 있지만, 화장품은 그렇지 않다는 문제의식에서 시작된 프로젝트  
- **주요 기능**
    - RealGlow 어플리케이션을 통해 소비자는 화장품의 **실제 효과를 시각적으로 확인**할 수 있음  
    - 온라인에서도 **자신에게 적합한 제품을 선택**하여 구매할 수 있도록 돕고, **구매 링크를 제공함**
    
- **기여**
    - 팀장으로써 설계 및 개발 주도 
    - 딥러닝 Segmention 모델 제작
    - Python 기반 Segmention 모델 파이프라인 구축
    - Python 기반 가상화장 적용 알고리즘 개발
    - MariaDB 기반 아이템DB 구축
    - SpringBoot 기반 아이템DB 관리 웹 서비스 개발
    - Flask 기반 RestAPI 구축
    - AWS EC2 기반 서비스 구축
    - React기반 웹 서비스 제작
    - nginx 기반 웹 서비스 배포

- **결과**
    - 실제 서비스 과정에서 Segmention 부터 메이크업 적용까지 300ms의 레이턴시 제공(88.7KB 이미지 기준)
    - FaceSegmention 모델은 TestDataSet에 대해 IOU 평가지표에서 0.88의 성능 제공 
    - 현재까지도 안정적인 서비스 운영중 [(링크)](http://realglow.aikopo.net/)
    - 졸업작품 경진대회 은상 수상
      
---

#### 2. [MZtoX](https://github.com/teamMZtoX)
> **신조어 번역 플랫폼 (MZ 세대와 소통 문제 해결)**
- **프로젝트 개요**: 신조어로 인한 세대 간 **언어 소통 문제를 해결**하기 위한 프로젝트
  
- **주요 기능**: 
  - **한국어 LLM 모델**을 활용하여 신조어를 **평문으로 번역**  
  - 웹 사이트를 통해 사용자는 **간단한 UI로 신조어의 의미**를 쉽게 확인할 수 있음 
  - 사용자 접근성을 높이기 위해 **웹 기반의 서비스**로 제공됨
    
- **기여**
    - 팀장으로써 설계 및 개발 주도
    - 영수증 관리
    - Torch기반의 LLM 모델 Kobart Fine-Tuning 진행
    - 웹 스크랩핑을 통한 데이터 통계
    - PySide 기반 Text Data Labeling Tool 개발
    - Python 기반 LLM 모델 파이프라인 구축
    - Flask 기반의 RestAPI 제작 
    - 서비스 아키텍쳐 설계
    - 아키텍쳐 기반의 서비스 배포
    - 버그 트래킹 및 원인 분석
    
- **결과**
    - 1차 배포기간이였던 3주간 284명의 사용자 확보 (구글 애널리틱스 통계 기반)
    - 현재까지도 안정적인 서비스 운영중 [(링크)](http://mztox.aikopo.net/)
    
---

#### 3. [가온나들목](https://github.com/00seungho/GaonNadulmok)
> **교통약자를 위한 지하철 및 버스 교통 정보 플랫폼**

- **프로젝트 개요**: **교통약자를 위한 지하철 편의시설 조회**와 **저상버스 도착 정보**를 제공하기 위해 시작한 프로젝트 
- **주요 기능**: 
  - **서울 열린데이터 광장 API**와 **kakaoMap API**를 활용하여 교통 약자를 위한 **편의시설 정보 조회 서비스**를 제공  
  - **저상버스 도착 정보**를 실시간으로 조회
    
- **기여**
    - Express 기반의 백엔드 서버 제작
    - js기반의 프론트엔드 스크립트 작성

---

#### 4. [민원고](https://github.com/00seungho/figting)
> **길거리 보도 불편 민원을 쉽고 간편하게 신고하는 솔루션**

- **프로젝트 개요**: 길거리 보도 불편 민원을 사진 촬영만 하면 민원 게시판에 자동으로 신고되는 솔루션  
- **주요 기능**:  
  - **길거리 보도 불편 민원 사진촬영 어플리케이션** 제공 
  - AI 관제 서버에서 **RestAPI를 통해 서버 관리**
  - **Azure Custom Vision**을 활용한 **객체 탐지(Object Detection)**
  - **Spring Boot** 기반의 민원 게시판에 **민원 자동 등록** 기능
    
---

### 🧑‍💻 **개인 프로젝트**

#### 1. [Every Poly!](https://github.com/00seungho/PolyBoard)  
> **학교 커뮤니티 사이트**  
> <img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> 
> <img src="https://img.shields.io/badge/springsecurity-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/> 
> <img src="https://img.shields.io/badge/jpa-59666C?style=flat-square&logo=hibernate&logoColor=white"/> 
> <img src="https://img.shields.io/badge/oracle-F80000?style=flat-square&logo=oracle&logoColor=white"/>


- **프로젝트 개요**: **SpringBoot**를 이용한 커뮤니티형 웹 서비스 프로젝트  
- **주요 기능**: 
  - REST API를 활용한 동적 메인페이지 구현  
  - JPA 쿼리를 이용한 전체 게시글 조회 및 페이징 처리  
  - Spring Security를 이용한 권한 관리 (관리자, 매니저, 사용자)  
  - 카테고리별 게시글 및 공지사항 조회 기능  
  - 댓글 CRUD 및 좋아요/싫어요 기능 구현  

---

#### 2. [서울정수캠퍼스 학식 챗봇](https://github.com/00seungho/PolyLanchBot)
> **서울정수캠퍼스 학식 정보를 제공하는 웹 기반 챗봇**  
> <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/> 
> <img src="https://img.shields.io/badge/streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> 
> <img src="https://img.shields.io/badge/selenium-43B02A?style=flat-square&logo=selenium&logoColor=white"/> 
> <img src="https://img.shields.io/badge/langchain-00BFFF?style=flat-square&logo=langchain&logoColor=white"/>

- **프로젝트 개요**:  
  서울정수캠퍼스의 학식 정보를 크롤링하여 사용자가 실시간으로 학식 정보를 확인할 수 있도록 돕는 **웹 기반 챗봇**  
  자연어 처리, 웹 크롤링, 대화형 UI를 결합하여 사용성을 극대화했습니다.
  
- **주요 기능**: 
  - **학식 정보 크롤링** Selenium과 BeautifulSoup을 사용하여 서울정수캠퍼스 학식 정보를 크롤링
  - LangChain(ChatOllama 모델)을 활용하여 사용자가 입력한 질문을 분석하고 적절한 응답을 생성
  - 프롬포트 엔지니어링을 통해 예외사항과 할루시네이션을 통제
  - Streamlit 기반으로 구축된 대화형 UI를 통해 사용자가 손쉽게 챗봇과 상호작용 가능

---

#### 3. [문장 라벨링 툴](https://github.com/00seungho/Sentence_labeling_tool)

> TSV 기반의 문장을 라벨링을 도와주는 Windows 프로그램
- **프로젝트 개요**: **MZTOX 프로젝트** 중 팀원의 라벨링 작업을 지원하기 위해 제작된 툴
> <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/> 
> <img src="https://img.shields.io/badge/pyside-41CD52?style=flat-square&logo=qt&logoColor=white"/> 
> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
- **주요 기능**: 
    - **TSV 파일 로드** 원문과 번역문 데이터를 불러와 작업 가능.
    - **직관적인 라벨링** 원문은 읽기 전용, 번역문은 수정 가능.
    - **단축키 지원** 작업 속도를 높이는 단축키 제공 (복사, 삭제, 탐색).
    - **자동 저장** JSON 파일에 작업 위치를 자동으로 저장.
    - **탐색 기능** 전체 문장 개수와 현재 위치 표시, 버튼으로 문장 이동 가능.
      
---

#### 4. [빵먹는아이 봇](https://github.com/00seungho/discord-bbangbot)  
> **디스코드 봇 어플리케이션**  
> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/discord-5865F2?style=flat-square&logo=discord&logoColor=white"/>

- **프로젝트 개요**: **디스코드 API와 게임 사이트의 API**를 활용하여 만든 **디스코드 봇** 어플리케이션  
- **주요 기능**: 
  - 게임 사이트의 **API를 활용한 다양한 기능**을 디스코드 플랫폼에 제공  
  - 디스코드에서 **커뮤니티와의 소통 및 게임 정보 제공**에 활용  

---

#### 5. [밈생성기](https://github.com/00seungho/meme-generator/tree/main)  
> **MEME 생성 웹 어플리케이션**  
> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white"/>

- **프로젝트 개요**: **MEME 생성기**는 사용자가 입력한 텍스트와 이미지를 조합하여 **밈을 생성**할 수 있는 웹 어플리케이션 
- **주요 기능**: 
  - **PIL 모듈**을 사용하여 사용자가 입력한 텍스트를 이미지에 삽입
  - **Flask 웹 프레임워크**를 이용해 사용자와의 **인터랙션을 제공**하는 웹 어플리케이션  

---

#### 6. [지구근접물체 탐색기](https://github.com/00seungho/Close-Approaches-of-Near-Earth-Objects)  
> **CLI 기반의 지구근접물체 탐색기**  
> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>

- **프로젝트 개요**: **지구근접물체(NEO, Near-Earth Object) 탐색기**는 우주 물체의 궤도를 조회할 수 있는 **CLI(명령줄 인터페이스) 어플리케이션**
- **주요 기능**: 
  - 사용자는 **쿼리(검색 조건)를 입력**하여 특정 지구근접물체의 궤도를 조회
  - **파일 입출력 기능**을 통해 조회된 정보를 **저장하고 다시 불러올 수 있는 기능** 포함

---

#### 7. [Movie Story](https://github.com/00seungho/movie_story)  
> **HTML + JS 기반의 프론트엔드 실습 프로젝트**  
> <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>

- **프로젝트 개요**: **HTML과 자바스크립트를 활용한 웹 프론트엔드 실습 프로젝트**  
- **주요 기능**: 
  - **HTML과 JavaScript로 인터랙션을 구현**
  - 프론트엔드의 **기본적인 이벤트 처리 및 데이터 출력**

---

## 📚 **연구**
---
#### 1. 한국폴리텍I대학 산학협력단 AI Musculoskeletal Expert System 기초연구 수행

#### 2. [DQN 알고리즘을 이용한 강화학습](https://github.com/00seungho/DQNTensorflow)  
> **Python의 Tensorflow와 Unity를 활용한 강화학습 알고리즘 구현 및 연구**  



## 📜 **수상내역**  
---

#### 1. **교내 졸업작품 경진대회 은상 수상** 🥈  
> **한국폴리텍 1대학장상**  

#### 2. **2024 WORLD CREATIVE ROBOT CONTEST 은상 수상** 🥈  
> **한국폴리텍대학 이사장상**  

#### 3. **2024 마이크로소프트 클라우드 AI모델 경진대회 참가상 수상** 🎖  
> **마이크로소프트 글로벌 트레이닝 파트너 ㈜ 엘릭서**  

#### 4. **2학년 1학기 성적 우수 장학금** 🎖  
> **한국폴리텍 1대학**

## 🌐 **대외활동**

---

### 🧑‍💻 **1. Azure 클라우드 심화 과정**
> **Azure 심화 학습 과정**  
> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>  
> 클라우드 컴퓨팅의 핵심 기술을 학습하고, **Azure의 클라우드 인프라 서비스**에 대한 심층 지식을 쌓기 위해 참여한 과정
> <img src="imgs/azure.png" alt="Azure 인증서" height="500"/>

---

### 📘 **2. UDACITY Intermediate Python 과정**
> **UDACITY Intermediate Python 과정 수료**  
> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>  
> **중급 파이썬 프로그래밍 스킬**및 **고급 파이썬 문법 및 모듈 활용 능력**을 향상시키기 위해 참여한 과정
> 
> [<img src="imgs/UDACITY.jpg" alt="UDACITY 인증서" width="500"/>](https://confirm.udacity.com/e/6e0ca150-4d1a-11ee-abf8-572ee5ae121d)  
> **🔗 [인증서 보기](https://confirm.udacity.com/e/6e0ca150-4d1a-11ee-abf8-572ee5ae121d)**

---
