## 👩‍💻 Team

- <a href="https://github.com/multicampusiot3project/iot"> IOT </a>

  - **[김진우](https://github.com/jinu12)** 
    - 전체 조장 및 iot 팀장   
    - iot
  - **[강기범](https://github.com/paramore0)**
    - 팀원
- <a href="https://github.com/multicampusiot3project/ai"> AI </a>

  - **[김인후](https://github.com/InhuKim)**
    - ai 팀장
  - **[정민수](https://github.com/yourms)**
    - ai 팀원
  - **[심혜주](https://github.com/hjst0223)**
    - ai 팀원
  - **[서지연](https://github.com/Yeony54)**
    - ai 팀원

- <a href="https://github.com/multicampusiot3project/bigdata"> BigData </a>
  - **[정승희](https://github.com/SeungheeJeong)**
    - 부조장 및 bigData 조장
    - 빅데이터  
  - **[김주영](https://github.com/jyakler)**
    - 빅데이터
 
 ## 📚 목차
 
 1. 💡 브레인스토밍  
 2. ✨ 주제 추출 
 3. 🗒️ 요구사항
 4. 📋 아키텍처 및 플로우 차트
 5. 🖊️ 피드백
 6. 🧪 피드백을 바탕으로 테스트 시나리오 수정

`프로젝트 진행 기간 2022.05.20 13:00 ~ 2022.06.27 18:00`

## 💡 브레인스토밍

### 스마트팜(정승희)
  - 식물별 파종시기, 성장속도, 양육환경 조사 및 조성 등으로 수확시기 예측, 시세파악 및 예측하여 작물선정하여 적합한 환경에서 파종-수확까지 관리, 스마트영농인등록 및 관리 
  
### 계절날씨를 고려한 코디시스템(정승희)
  - 사용자 취향조사, 날씨별 추천 아이템 20~25도: 반팔티셔츠 / 반바지 / 샌들 등, 15~20도: 트렌치 코트 등등,,, - 추천시스템 만들고 공유옷장 서비스 제공
  
### 드론을 통한 약 배달(김진우)
  - 드론을 이용해서 안드로이드로 드론을 이동하고 iot 드론에 있는 파이 카메라를 통해 ai 시스템으로 무슨 약인지 판단(머신러닝 학습)해서 지정된 장소에 놓으면 센서에서 인식해서 웹에서 데이터를 전달
  
### 시각장애인을 위한 쇼핑서비스(서지연)
  - 시각장애인이 카트를 끌고 마트에서 자유롭게 쇼핑할 수 있도록 도와주는 서비스. 물건을 인식하고 가격정보를 알려준다. 사고싶은 물건의 위치를 음성서비스로 알려준다.
  
### 시각장애인 / 청각장애닝을 위한 글자 / 점자 서비스(서지연)
  - 활용 가능한 방안
  - (글자to점자)(음성to점자) 시각장애인 교육
  - (음성to글자) 청각장애인 교육 
  
### 화재대비 소방차 경로 설정 장애물 지능자동차(서지연)
  - 저희동네는 앰뷸런스가 신호에 막혀서 못가고 서있는경우가 아주 많습니다. 그래서 앰뷸런스 전용경로나, 앰뷸런스가 필요할 때 신호 개편 등,,, 이런게 있으면 좋을것같아서 생각해 본 아이디어입니다.
  
### 수어 영상 이용한 자연어 출력 서비스(김인후)
  - 핸드폰으로 수어를 촬영하여 인식하고 해당 데이터를 자연어로 변환하여 스피커로 출력. 수어를 못하는 일반인과 대화를 위한 번역시스템. 
  - 마이크를 통해서 음성을 인식하고 수어로 변환하여 화면에 출력
  
### 길, 사물, 명령을 인식하는 4족보행 로보트(배민배달로봇 + 보스턴다이나믹스 로봇)(정민수)
  - 길과 사물을 인식
  
### 식품 구입 시 성분 파악 후 사용자가 알레르기로 인해 섭취가 불가능한 식품인지 판단하여 알려주는 서비스(+ 섭취 가능한 식품 추천)(심혜주)
  - 식품을 구입할 때 식품 이미지를 인식해서 성분 분석 후 사용자가 사전에 등록해놓은 알레르기와 대조 - 사용자가 알레르기로 인해 섭취 불가능한 식품일 경우 알려주는 서비스 
  - 사전에 필요한 데이터 : 식품군별 성분표, 식품 이미지 데이터, 성분별 반응하는 알레르기 종류, 사용자의 알레르기 반응 정보 등 (식품 종류가 방대하여 학습에 한계가 있을 것 같음 - 식품군 제한 필요)
  
### 탄소중립과 관련한 생활 서비스(웹이나 앱 서비스) (이지희) 
  - iot를 활용한 기계 제어로 에너지 절약
  
### 홈 어시스턴트(강기범)
  -  날씨 파악해서 빔 프로젝트나 디스플레이에 정보 표시 및 지정된 영상 표시
  
### 재미로 보는 호들갑 로봇(강기범)
  - 일정시간 이상 로봇을 작동시키지 않으면 자주 검색한 차트에 대해 자동으로 데이터를 수집하고 지금 이 차트 이렇게되는데! 라는 의미의 호들갑을 떨게 한다
  
### 다이어트 영양, 칼로리 계산(김주영)
  - 카메라를 이용해 어떤 음식인지 파악후 영양과 칼로리들을 계산하여 알려주는 시스템 구축
  
### 외출전 확인시스템(김주영)
  - 마스크나 우산을 쓰고 외출할지 판단하기 위해 기상청 데이터 가져와 외출전 대기질 상태, 기상상태를 알려주는 시스템구축

## ✨ 주제 추출 

### 시각장애인 이마트 쇼핑 서비스

- 기대효과 
  - 쇼핑할 때 도우미가 필요한 시각장애인을 위한 쇼핑도우미 서비스로 다른사람의 도움없이 혼자 쇼핑을 할 수 있도록 도와줄 수 있다.
- 테스트 시나리오 
  0. 어플로 서비스를 하고 있는 마트 검색
  1. 시각장애인 마트 입장, 도우미 카트 등록, 어플에 쇼핑 리스트 등록
  2. 시각장애인 카트를 매장 카메라로 인식, 추적하여 현재 위치 저장
  3. 쇼핑리스트 목록을 정렬, 최적 쇼핑 경로 알고리즘을 도출
  4. 객체 추적으로 도출해낸 고객의 현재위치에서 쇼핑리스트 경로 알고리즘으로 도출해낸 위치로 이동하기 위한 경로 음성안내 ( 카트 스피커)
  5. 쇼핑리스트 코너에 도착 (카트스피커 안내)
  6. 고객이 원하는 물건을 핸드폰 어플 카메라로 인식, 물건의 정보를 알려준다. (이름, 가격, 다른 추천상품 등)
  7. 쇼핑바구니에 담기면 예상 금액 계산 (미정)
  8. 쇼핑을 마치면 계산대로 안내

## 🗒️ 요구사항

### 시각장애인 이마트 쇼핑 서비스
- 빅데이터
  - 음성인식방식의 제품입력
  - 모바일웹서비스제작 - 쇼핑상품입력, 쇼핑순서 소팅, 카메라로 상품찍기 
- AI
  - 상품 촬영 시 이미지 인식으로 상품에 대한 상세 정보 출력하는 기능, 상세 정보 출력 후 유사한 상품과의 가격 등을 비교하는 기능
- IOT
  - 카트 : 상품이 어디에 있는지 알려 줄 수 있는 음성 인식 시스템 필요
  - 마트 카메라 : 사용자의 위치를 파악하기 위한 카메라(1층,2층 - 층나눌건지 미정)
  - 개인 디바이스 : 서비스를 제공하는 마트 정보, 사용자가 물건을 (카메라)촬영해서 정보를 얻고자 할때  
- 클라우드
  - 클라우드에 mqtt 서버를 만듬
  - aws s3 버킷 파일 데이터를 저장 

## 🖊️ 피드백

### 빅데이터

- 최인호 멘토님
  - 각 기능별 ( 위치안내, 등) 별로 카테고리화 하여 구체적으로 기획 구성해보는 것이 좋을 것 같음.
  - 서빙로봇의 개념을 사용해보는 것은 어떨지? 벤치마킹이 중요할것 같다.
  - 매장내 코스를 스튜디오를 제작하여 위치정보를 입력할 것임
  - 카메라를 매장 상단에 위치를 시켜서 평면도처럼 사용할 수 있지 않을까?(카트의 위치를 찾기기 위함)
  - 코너가 어디에 위치 해 있는지 - 마트의 매대는 거의 정해져있기 때문에 위치정보는
  - 카트에 버튼을 만들어 사용자가 어디쯤 와있는지 음성으로 안내함
  - 상품리스트만 크롤링하여 작성하는 것은 빅데이터라고 할 수는 없다. 기술 항목마다의 강점을 가지고 가는 것이 중요할 것 같다.
  - 다음 멘토링에서는 상품과 카트를 나눠서 카테고리별로 정확한 유형을 만들어서 만났으면 좋겠다.

- 남영우 멘토님
  - 기술요소들을 다양하게 넣기는 했지만 구현가능한 요소들과 환경을 잘 꾸며줬으면 좋겠다.
  - 상품이미지를 하는 것은 크게 어려움은 없을 것
  - 위치 트래킹이 어려울 것이라고 생각하지만 멘토님들 의견을 응용해보면 좋을 것 같다.

### AI
- 심형광 멘토님
  - 택배로봇 - 로봇의 카메라는 충돌이나 사고방지용.
### IOT
- 오태양 멘토님
  - 각장애인이 무딫히지 않고 이동해야하는 니즈, 원하는 상품을 입력해야하는 니즈(로케이션정보), 특정 위치에 도달했을 때 스탑을 해야하는 위치 매칭, 매대에서 결제하는 프로세스와 같은 정보가 취합이 되어야할것 같은데 어떻게 할것인지?
  - 매장의 전체 상품을 카메라 등으로 스캔을 하는 것은 어떨지? 위치 정보를 캡처를 받는 것은 어떨지? 맵의 형태로. 맵에서는 공간 좌표를 알려줌. 전체적인 과정이 수월할 것
  - 최종 데모를 구현을 해보고 구현을 확장하는 방법을 사용하는 것도 좋을 것 같다.
- 신동호 멘토님
  - 매대에 제품 위치가 변화되는데 나중에는 실시간 제품의 좌표를 매장을 통해서 받는 것을 고려해보는 것도 좋을 것 같음.
  - 시간이 5주밖에 없는데 그 시간안에 프로젝트를 완성을 시키기 위해서는 벤치마킹이 필요하다
  - 현대 - 지게차를 자율주행하던 케이스 -1차에 창고내 맵을 미리 작성하는 것과 물류의 위치를 미리 정해놓는다. 그러면 지게차가 다닐 수 있는 공간이 한정되어있었고 카메라가 정면, 좌우 3개만 있었고 가까이에 누군가 왔을때 멈추면 됐다. 카메라를 사용하고 싶다면 카트에 카메라를 장착하여 충돌방지용으로 사용하는게 좋다.
  - 위치를 보정하려면 입체적으로 카메라를 배치해야한다. 평면으로했을 때는 위치가 정확도가 떨어질 수 있다.
  - 여의도 현대백화점 가보는 것도 좋겠다. - 물건을 들고 나오면 자동결재되는 시스템

### 🧪 피드백을 바탕으로 테스트 시나리오 수정

#### 시나리오 배경

- 맵 : 강의실을 마트처럼 조성
- 상품 정보 : 상품 5개로 test / 실제로는 상품 섹션별 2~3개
    - 이미지, 상품명, 가격, 카테고리별 분류
    - AI : 이미지(많이 필요), 상품명
- 코너 정보 : (IoT 예산에 따라서)
    - BigData : 데이터는 충분히 모아오면 그중에서 선택해서 쓰면 된다.
    - 코너 종류 : 위치정보(매대 구분) + 사진 (전제 : 해당 매대에서 상품을 촬영한다.)
        - 신선식품 : 과일식품, 채소식품, 생선,
        - 공장(?)식품 : 과자(봉지, 박스), 음료, 유제품, 냉동식품, 라면, 커피,
        - 가전제품
        - 완구…
- 고객 정보 : 마트 사용 빈도수에 따라 각각 3, 4 케이스로 구성해서 테스트

#### 전제 조건

- 해당 마트에서 제공하는 서비스(마트가 가진 재고상황과 같은 데이터베이스가 존재한다 가정)

1. 이용자 안드로이드 앱 기동
2. 안드로이드 앱에서 카트 예약
3. 안드로이드 앱을 통해서 음성으로 쇼핑 원하는 품목 입력.
4. 해당 마트의 재고 상황에 맞추어 상품 안내 및 경로 안내.
5. 이용자 마트 도착 -> 카트 수령 (3,5번 항목은 시간 순서 상관 없음)
    1. 장바구니 내역 카트 연동
    2. 장바구니 내역에 따른 쇼핑 경로 생성
6. 카트가 상품이 있는 구역으로 안내 시작.
    - 네비게이션 기능에서 경로 설정 알고리즘과 같은 기능은 누가 만들 것인가?
7. 목표 구역으로 이동. 
8. 이동 과정에서 장애물(지나가는 사람, 길을 막는 물체)을 회피.
9. 목표 구역 도착
10. 목표 구역에서 해당 상품이 있는 진열대로 이동.
11. 해당 진열대에 있는 상품들의 간략한 소개
12. 이용자가 특정 상품을 선택하여 안드로이드 앱으로 촬영하면 어떤 상품인지 정확한 정보 제공
13. 안드로이드 앱에서 제스쳐를 통해서 상품의 구매 여부 결정.
    1. 예시로 촬영후 설명을 듣는 와중에 3초간 꾹 누르면 해당 상품을 구매하는 것으로 결정하여 경로안내에서 제거하고 장바구니에 추가.
    2. 설명을 듣는 와중에 스와이프를 하여 취소하면 안내를 끄고 해당 상품에 대한 경로안내가 유지.
14. 쇼핑리스트가 모두 제거되고 장바구니에 물건이 존재하면 계산대로 카트 경로 안내.
15. 결제후 카트 반납하면 서비스 종료

### 🗒️ 피드백을 바탕으로 요구사항 수정

#### 빅데이터

- 사용자의 쇼핑리스트 만들기
- 상품별  품목 정렬하기(식품, 가전, 신선식품, 생활용품 등)
- 마트 층별 상품 코너 정보
- 매장 내 위치정보 만들기 : 상품코너에 있는 상품 정보 (상품들의 마트 내 위치정보)
- 앱으로 인식한 상품의 세부정보 
(이름, 가격, 브랜드, 제품상세정보-(칼로리,성분 등), 유사제품)
- 제품 추천 시스템
    - 사용자 이용로그 기록 - 사용자 쇼핑 데이터를 활용한 상품추천 서비스 제공
    - 사용자 이용데이터를 활용하여 추천시스템 추가
- **미정**
    - 쇼핑 순서 정하기 (쇼핑경로)
- **보류**
    - 사용자 위치 인식 (GPS 말씀하시는건가요?)
    - 서비스를 제공해주는 마트 정보

#### AI

- 카트에 설치된 탐지된 장애물 카메라로 촬영하여 판별 (사람만 인식하여 알려줌)
- 앱 카메라로 상품을 인식하여 상품에 대한 상세정보를 검색, 출력해주는 기능
- 네이버/구글 API를 사용해서 STT(speech-to-text), TTS(text-to-speech) 활용
- **미정**
    - 쇼핑경로
    

#### IoT

- APP : 카트 예약
- APP : 사용자위치 기반 도착 예정시간 마트에 전송
- 웹 : 수신받은 사용자의 위치와 마트 사이의 직선거리 시간으로 도착시간 예상
- APP : 사용자 계정 로그인 - 쇼핑리스트생성 - 쇼핑- 쇼핑완료
- 카트 : 비콘을 사용하여 위치 파악, 쇼핑 경로 안내
- 카트 : 쇼핑경로 도달 시 알림
- 카트 : 거리감지 센서로 근거리의 장애물이 사람이면 안내해줌(AI의 사람 인식 모델과 같이 작동)
- APP : 사용자가 물건을 (카메라)촬영해서 정보를 얻을 수 있는 기능
- APP : 계산대에서 장바구니의 정보와 일치한지 확인
- APP : 카트 이용 완료

#### 클라우드

- 클라우드에 mqtt 서버를 만듬
- aws s3 버킷 파일 데이터를 저장
- 데이터베이스 구축
- AWS 환경 구축

## 📋 아키텍처

### iot 플로우 차트

![iot 플로우차트](https://user-images.githubusercontent.com/99372065/171769590-070f758a-f712-425c-bc76-2dcbff60eb6a.png)


### 안드로이드 와이어 프레임

## 🛒 1. 전체 시나리오
### 1. 장바구니 내역 생성
- 빅데이터 : 상품 카테고리 데이터 저장 후 장바구니 내역 상품의 카테고리 분류 진행
- 고려 사항 : 테스트 데이터 설정
![image](https://user-images.githubusercontent.com/52309288/171770105-18c850b5-04ab-4775-92ab-fe9899787df9.PNG)
### 2. 장바구니 내역에 따른 쇼핑 경로 생성
- 빅데이터 : 매장 지도 정보 수집
-  고려 사항: 상품 픽업 우선순위 / 최단 경로
### 3. 상품이 위치한 구역으로 카트 안내 시작
- 빅데이터 : 매장 정보 구축
- AI : 최적 쇼핑 경로 생성, 장애물 회피
- IoT : 위치 추적 - 3점측량법, 장애물 회피
- 음성 안내 (TTS) : 경로 안내, 도착 후 해당 상품 소개
![image](https://user-images.githubusercontent.com/52309288/171770108-36ac6b52-1b9a-458a-89e7-dc109f42653b.PNG)
![image](https://user-images.githubusercontent.com/52309288/171770270-26ac4188-fade-4d25-ac15-360984267a0d.PNG)
### 4. 상품 촬영 ▪ 정보 제공
![image](https://user-images.githubusercontent.com/52309288/171770110-4150bfa5-529f-48c0-a055-b01770971c8e.PNG)
![image](https://user-images.githubusercontent.com/52309288/171770111-d2030e13-69cd-499f-ac04-f87751f7b603.PNG)
### 5. 앱 내에서 제스쳐로 구매 여부 결정
- 고려 사항 :  음성 안내 + 제스쳐
### 6. 장바구니 내역 상품 모두 픽업 시 계산대 경로 안내
### 7. 결제 후 카트 반납
## 🛍 2. 장바구니 작성 시나리오
- TTS, STT : 구글/네이버 API(CLOVA Speech Recognition, CLOVA Voice)
- 안드로이드 내장 TTS
- UI 구성
마트 지정
### 2-1. 장바구니
- 기능 : 설명 듣기, 뒤로 가기, 장바구니 추가, 장바구니 삭제, 카트에 정보 전송 등
- 고려 사항 : 음성 안내 + 제스쳐
## 📸 3. 상품 인식 시나리오
1. 상품 검색 클릭 
2. 상품 촬영 클릭 
3. 상품 상세 설명 (+ 유사 상품 추천) 
4. 상세 설명 종료 
5. 구매 결정 / 선택 취소

## 클라우드 아키텍처

![iotdataflow drawio](https://user-images.githubusercontent.com/73889507/171769213-5b158682-9834-4327-8aad-dbf9b377a3c9.png)

## ai 플로우 차트

![product_classification](https://user-images.githubusercontent.com/46711633/171769597-1bb3e348-5ed1-4f8f-94f7-6c332aaa56c6.jpg)

![classification_training_process](https://user-images.githubusercontent.com/46711633/171769606-c01405e2-5074-4859-b3f5-d205937ebd2e.jpg)

![object_detector](https://user-images.githubusercontent.com/34851766/171771776-183e221c-c2a9-465b-a7b3-ce5076d30172.png)

## 빅데이터 플로우 차트 

![빅데이터 플로우차트](https://user-images.githubusercontent.com/49812691/171805300-643f4274-6199-4de5-8f16-7ec840d19670.PNG)

## mqtt subscirbe 테스트

![mosquitto 확인](https://user-images.githubusercontent.com/73889507/171589056-b20856d9-6c76-49b8-9f30-cb3c174f4c92.PNG)

* 안드로이드 tts 테스트도 


### 문서 보기

<a href="https://docs.google.com/spreadsheets/d/1DY_rrN_rtfK2Bv8FmD04xFgqk4KdGOCzxC6TvhPFQII/edit#gid=66557486"> 3조 docs 문서 </a>
<br>
<a href="https://docs.google.com/spreadsheets/d/1rW45_AzOEOq-xhR0rkEWkgi-3Wvp15g9/edit#gid=1447991798"> 시각장애인 쇼핑서비스 문서 </a>
<br>
<a href="https://legendary-open-e74.notion.site/0a5ca489b2f7497a975fe8f15a6c310d"> 3조 노션 </a>
<br>
<a href="https://drive.google.com/drive/folders/1Ujl_JuMMgoPF_HWqt6JJlGG1bybrlwM7"> 삼성 드라이브 폴더 가기 </a>

