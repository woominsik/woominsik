# 우민식
## Junior Back-end Developer.

## **Contact.**

---

**Age: 25**

**Github : [github.com/woominsik](https://github.com/woominsik)**

**Email : 9737638@naver.com**

## Introduce.

---

제가 항상 **타인과 함께 하고 싶은** 개발자입니다.

이를 위해 **다양한 사람들**이 **유용하게 사용**할 수 있는 서비스를 만드는 것이 제 목표입니다.
또한 사용자들이 제 서비스를 **원할히 사용**할 수 있도록 항상 빠르고 성능이 좋게 만들고 싶습니다.

이러한 목표를 위해 항상 열정을 갖고 노력하고 있습니다.

## What I’ve Done

---

### 백엔드 프로젝트

- **콘서트 및 스포츠 직관 동행 서비스 (Play With Me)**
    - [x]  2022.08~2022.09 (진행중)
    - 소스코드 (현재 Private Repository로 링크 X)
    - 스프링 및 자바, MySQL, ThymeLeaf를 통해 뷰 구현
    - 이벤트(콘서트, 연극, 야구, 축구, 농구) 일정 저장 구현
        - JSoup을 통해 해당 사이트의 일정을 가져와 DB에 저장
        (JSoup, MySQL, JPA, Spring)
    - 사용자 편의성을 위해 저장된 이벤트 검색 기능 구현
        - JPA를 통해 이벤트의 이름과 장소를 검색하는 기능 구현
        (JPA, MySQL)
    - 로그인 후 동행 일정에 대해 알람 기능 구현
        - JPA를 통해 동행 일정을 가져와 해당 일정을 D-day를 통해 보여줌
            
            (JPA, MySQL)
            
    
- **쇼핑몰 상품 리뷰 분석 및 추천 서비스**
    - [x]  2022.03~2022.06
    - 소스코드 (현재 Private Repository로 링크 X)
    - [소스코드 (AI 모델 서버)](https://github.com/woominsik/sinsahelper-ai_server)
    - [소개영상](https://youtu.be/w6WLZEoQJkk)
    - [**논문작성 후 논문지(데이타베이스연구)에 게재**](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002871168) 
    ([사용자의 구매만족도 향상을 위한 BERT 기반의 리뷰 분석 방법](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002871168))
    - 스프링 및 자바, Django 및 파이썬(Ai 모델 서버), MySQL 사용
    - 쇼핑몰 상품 추가 기능 및 상품 검색 기능 구현
        - URL 입력시 크롤링을 통해 상품 추가 후 데이터베이스에 저장
        (Java, Spring, MySQL)
        - JPA를 통해 사용자가 선택한 카테고리에 맞는 상품 리스트 보여줌
        (Java, Spring, MySQL)
    - AI 모델 서버에게 HTTP요청 전송하는 기능 구현 (웹 백엔드)
        - 상품 추가 및 매일 오전 5시에 AI 모델을 돌리기 위해 AI 서버에게 HTTP 요청 전송
        (Java, Spring)
    - 사용자 상품 추천을 위해 웹 백엔드로부터 HTTP 요청 받아 상품 추가 및 상품 점수 최신화 기능 구현 (AI 모델 서버)
        - 백엔드로부터 URL 전송 받은 후 해당 URL의 상품을 크롤링 후 AI 모델을 통한 상품 점수 저장
        (Python, Django, DRF, MySQL)
    - AI 모델 서버 EC2를 통해 배포 (현재는 진행 X)
    
- **자신만의 앨범 만들기 및 공유**
    - [x]  2021.06~2021.08
    - [소스코드](https://github.com/woominsik/image_classifier)
    - 파이썬 및 Django 사용
    - 사용자 개인 앨범을 위한 사진 추가 및 삭제 기능 구현
    - 다양한 사람들의 앨범을 볼 수 있도록 사용자 앨범을 공유하여 다양한 사람들의 앨범 공유 기능 구현
    - 부트스트랩을 통한 정적 웹사이트 구현
    
- **레시피 검색 어플**
    - [x]  2021.03~2021.06
    - [소스코드](https://github.com/woominsik/recipe_search_server/tree/master)
    - [시연 영상](https://www.youtube.com/shorts/ytoNz89gsw4)
    - 파이썬 및 Django 사용
    - 사용자에게 레시피 정보를 보여주기 위해 크롤링하여 레시피 데이터 수집 기능 구현
        - Python 외장 라이브러리인 BeautifulSoup4을 통해 구현
    - AI 모델을 통해 인식된 재료들 리스트를 넘겨 받아 검색하는 기능 구현
        - Python 백엔드 프레임워크인 Django를 통해 검색 기능 구현

- **사용자 편의를 위한 도서관리책장**
    - [x]  2017.09~2017.12
    - [시연 영상](https://www.youtube.com/shorts/EfaWzDeHhMA)
    - 사용자 편의를 위해 블루투스 책장 관리 기능 개발
        - c언어 및 아두이노 사용하여 책장 관리 기능 구현

### 데이터 분석

- **NBA.com 데이터를 이용한 선수 분류 및 연봉 예측 모델**
    - [x]  2022.05~2022.06
    - [소스코드](https://github.com/woominsik/NBA_Player_Analysis)
    - NBA 데이터 수집
        - 동적 웹사이트 크롤링을 위한 Selenium과 파이썬 크롤링을 위한 BeautifulSoup4를 통해 NBA.com 선수 데이터 수집
    - NBA 선수 그룹화
        - KMeans 클러스터링을 통해 NBA 선수 분류 및 실루엣 분석
        - Elbow 기법으로 각 분류 비교, 가장 효율적인 분류 생성
    - NBA 선수 연봉 예측
        - Linear Regression을 통한 NBA 선수 연봉 예측 모델 생성
        - 해당 모델들 rmse순으로 각 모델 비교

## Skills.

---

- 언어 : Python, C, Java, Kotlin
- 기술 : Spring, Django
- MySQL과 같은 RDBMS
- AWS 서버(EC2, RDS) 배포
