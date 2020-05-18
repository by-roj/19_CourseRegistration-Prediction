# CourseRegistration-Prediction

사용자가 Web 상에서 입력한 데이터로 해당 과목의 수강 신청 성공 여부를 예측하는 프로젝트입니다

<br>

### 🚩 *Goal*

- 수강 신청 데이터가 적재된 DB server와 연동된 Web 상에서 직접 강의를 선택하고 데이터 입력

  → 데이터에 따라 예측된 수강 신청 성공 여부가 출력되도록 구현

  <br>
  
  #### 💡 *Step*
  
  1. 마일리지 우선순위 정보에 따른 예측 모델링 구현
  
   	2. pymysql과 flask를 통해 DB server와 연동된 Web 구현
   	3. 사용자가 Web 상에 입력하는 정보에 따른 수강 신청 성공 여부 출력

<br>

### 📁 *Data Used*

- https://portal.yonsei.ac.kr/main/
  - Yonsei portal의 수강신청 정보

<br>

### 🔑 *Tech/Framework Used*

​			(참여한 과정 : ✔)

- Crawling
  - BeautifulSoup ✔
- Database
  - MySQL ✔
  - pyMySQL ✔
- Model
  - XGBoost
  - GridSearchCV
- Web
  - Flask ✔
  - HTML
  - CSS
  - JavaScript
