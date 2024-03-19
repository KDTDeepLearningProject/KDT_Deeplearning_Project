# KDT_Deeplearning_Project
Pytorch를 활용한 딥러닝을 수행한 결과를 취합한 저장소입니다.


|                |이름                          |한일                         |
|----------------|-------------------------------|-----------------------------|
|KMS|`'Isn't this fun?'`            |'Isn't this fun?'            |
|GUS|`"Isn't this fun?"`            |"Isn't this fun?"            |
|GHW|`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|

# 1. 프로젝트 회의
## 1.1 뭐하지?
- PEPE 이미지를 기반으로 한 분석
- op.gg 를 기반으로 롤, 발로란트 티어 예측하기
- 캐글에서 주최하는 Home credit risk model 예측하기 
  * https://www.kaggle.com/competitions/home-credit-credit-risk-model-stability/data
- 의료쪽 데이터 분석
- 음주 관련 데이터 셋?
- 술과 이와 맞는 음식 추천 모델
## 1.2 최종 선택
**LeagueofLegend** 게임에서 리더보드의 각종 데이터를 기반으로 순위 예측 모델을 만들어보자


# 2. 프로젝트 진행
## 2.1 크롤링
- https://www.op.gg 웹사이트 사용
  * 해당 웹사이트의 Leaderboard의 경우 표를 json 파일을 받은 후 이를 프런트엔드에서 처리하여 표시
  * 따라서 해당 웹사이트 자체를 다운 받는 것이 아닌 json 파일을 다운 받는 것이 보다 효율적
  * 해당 웹사이트에서 적용되는 ratelimit를 알 수 없기 때문에 사람의 최고반응속도보다 약 2배정도 높은 0.5초 단위로 다운
  * Json 파일에는 단순 순위 정보 뿐만 아니라 해당 플레이어가 최근 어떤 플레이를 하였는지 내용이 존재

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.
