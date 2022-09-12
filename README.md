### Hi there 👋
## 저는요
***
제가 속한 공동체와 함께 성장하고 싶은 개발자입니다.<br>
저를 위한 서비스가 아닌 일반 사람들도 유용하게 사용할 수 있는 서비스를 만드는 것이 제 목표입니다.<br>
그리고 제 서비스를 통해 모든 사용자가 좀 더 발전할 수 있었으면 <br>

## 제가 가진 기술은요 
***
- 언어 : Python, C, Java
- 기술 : Spring, Django
- MySQL과 같은 RDBMS 경험
- AWS 서버(EC2, RDS) 배포 경험


## 저는 이런걸 해왔어요
***
### 웹 프로젝트

- 2017.09~2017.12 ) 사용자 편의를 위한 도서관리책장
  - c언어 및 아두이노 사용
  - <a href="https://www.youtube.com/shorts/EfaWzDeHhMA">시연 영상</a>


- 2021.03~2021.06) <a href="./recipe_search_server">레시피 검색 어플</a>
  - [소스코드](https://github.com/woominsik/recipe_search_server/tree/master)
  - <a href="https://www.youtube.com/shorts/ytoNz89gsw4">시연 영상</a>
  - 파이썬 및 Django 사용
  - 레시피 크롤링 및 앱 백엔드 구현


- 2021.06~2021.08) <a href="https://github.com/woominsik/image_classifier">자신만의 앨범 만들기 및 공유</a>
  - [소스코드](https://github.com/woominsik/image_classifier)
  - 파이썬 및 Django 사용
  - 웹 백엔드 
  - 부트스트랩을 통한 정적 웹사이트 구현


- 2021.09~2021.12) <a href="https://github.com/woominsik/Eyes_On_You">실시간 cctv를 통한 피보호자 인식</a>
  - [소스코드](https://github.com/woominsik/Eyes_On_You)
  - 스프링 및 자바, MySQL 사용
  - 웹 백엔드 및 
  - Thymeleaf를 통한 정적 웹사이트 구현


- 2022.03~2022.06) <a href="https://github.com/woominsik/Eyes_On_You">쇼핑몰 상품 리뷰 분석 및 추천 서비스</a>
  - [소스코드](https://github.com/woominsik/Eyes_On_You)
  - [소스코드 (AI 모델 서버)](https://github.com/woominsik/sinsahelper-ai_server)
  - 스프링 및 자바, Django 및 파이썬(Ai 모델 서버), MySQL 사용
  - 쇼핑몰 상품 추가 기능 및 상품 검색 기능, AI 서버에게 HTTP 전송하는 기능 구현 (웹 백엔드)
  - 웹 백엔드로부터 HTTP 요청 받아 상품 추가 및 상품 점수 최신화 기능 구현 (AI 모델 서버)


- 2022.08~2022.09) <a href="https://github.com/likelion-backendschool/Play_With_Me">콘서트 및 스포츠 직관 동행 웹사이트 Play With Me</a>
  - [소스코드](https://github.com/likelion-backendschool/Play_With_Me)
  - 스프링 및 자바, MySQL, ThymeLeaf를 통해 뷰 구현
  - 이벤트(콘서트, 연극, 야구, 축구, 농구) 일정 JSoup을 통해 구현 및 데이터베이스에 저장 구현
  - 저장된 이벤트들의 이름이나 장소를 통해 검색하는 기능 구현
  - 선택된 날짜의 행사들을 뷰에게 전달해주는 기능 구현
  - 상단바, footer 등 레이아웃 구현
  
### 데이터 분석  
  
- 2022.05~2022.06) <a href="https://github.com/woominsik/NBA_Player_Analysis">NBA.com 데이터를 이용한 선수 분류 및 연봉 예측 모델</a>
  - [소스코드](https://github.com/woominsik/NBA_Player_Analysis)
  - NBA 선수들의 데이터를 통해 각 선수들을 분류 및 연봉을 예측하였다.
  - 동적 웹사이트 크롤링을 위한 Selenium과 파이썬 크롤링을 위한 BeautifulSoup4를 통해 NBA.com 선수 데이터 수집
  - KMeans 클러스터링을 통해 NBA 선수 분류 및 적절한 그룹 수를 찾기 위해 Elbow 기법 사용 및 실루엣 분석을 통해 각 군집간의 거리가 얼마나 효율적으로 분리돼 있는 지를 확인
  - 결론 : 총 2개의 선수 분류로 나누는 것이 가장 효율적으로 분리한 것이다. 
  - Linear Regression을 통한 NBA 선수 연봉 예측 모델 생성 및 해당 모델의 성능을 위한 각 컬럼들을 fs_score을 구한 뒤 상위 5개~27개를 구한 후 이 결과를 rmse순으로 두어 해당 값이 가장 작은 모델을 선정하여 모델을 완성함
  - 결론 : ['PTS', 'FGA', 'FGM', 'FP', 'TOV', 'FTM', 'FTA', 'MIN', 'AST', 'DREB', 'REB', '3PA', '3PM', 'DD2', 'STL', 'PF', 'GP', 'W', 'BLK', 'TD3', '+/-', 'FT%', 'L', 'OREB', '3P%', 'FG%', 'AGE'] 총 27개의 컬럼을 선택하여 연봉을 예측했을 때 가장 정확한 모델이 나왔다.


<!--
**woominsik/woominsik** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
