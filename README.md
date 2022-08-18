# football

대회 - [링크](https://www.kaggle.com/datasets/omkargowda/football-players-stats-premier-league-20212022)

참고한 notebook - [링크](https://www.kaggle.com/code/jus9298/cristiano-ronaldo-goals-eda-analy-ac3af6/edit)

___

## Football Players Stats (EPL 2021-2022)

# 컬럼 & 데이터

 * Player : 플레이어 이름
 
 * Team : 2020-2021시즌 소속 클럽
 
 * Nation : 국적
 
 * Pos : 포지션
 
 * Age : 나이
 
 * MP : 플레이한 경기수
 
 * Starts : 시작한 경기수
 
 * Min : 플레이한 시간(분)
 
 * 90s : min을 90으로 나눈 것
 
 * GLs : 유효득점 골 수
 
 * Ast : 어시스트
 
 * G-PK : 패널티 골을 제외한 골 수
 
 * PK : 패널티 킥 수
 
 * PKatt : 패널티 킥 참가 수
 
 * CrdY : 옐로카드 
 
 * CrdR : 레드카드
 
 * Gls.1 : 각 90분간의 골 수
 
 * Ast.1 : 각 90분간의 어시스트 수
 
 * G+A : Gls와 Ast의 합
 
 * G-PK.1 : 패널티 골을 제외한 각 90분간의 골 수
 
 * G+A-PK : 패널티 골을 제외한 각 90분간의 골과 어시스트 수
 
 * xG : 예상 골 수
 
 * npxG : 패널티 골을 제외한 예상 골 수
 
 * xA : 예상 어시스트 수
 
 * npxG+xA : 패널티 골을 제외한 예상 골과 어시스트 수
 
 * xG.1 : 각 90분간의 예상 골 수
 
 * xA.1 : 각 90분간의 예상 어시스트 수
 
 * xG+xA : 각 90분간의 예상 골과 어시스트 수
 
 * npxG.1 : 패널티 골을 제외한 각 90분간의 예상 골 수
 
 * npxG+xA.1 : 패널티 골을 제외한 각 90분간의 예상 골과 어시스트 수

___

### !chardetect football_data/Football-players-Stats.csv

football_data/Football-players-Stats.csv: Windows-1252 with confidence 0.7294248518046071

인코딩 방식 = Windows-1252

### football.head()
 <img width="985" alt="스크린샷 2022-08-18 오전 11 47 11" src="https://user-images.githubusercontent.com/58887561/185282391-eca25bbc-5f94-42ca-bac5-4758dcd9629a.png">

 ### football.info()
 <img width="405" alt="스크린샷 2022-08-18 오전 11 47 20" src="https://user-images.githubusercontent.com/58887561/185282516-307cb66b-7d88-457d-92a4-bff583c6ad55.png">
 
 ### 시각화
 
 * 히스토그램 

 <img width="984" alt="스크린샷 2022-08-18 오후 12 34 38" src="https://user-images.githubusercontent.com/58887561/185287558-2ac54747-faee-4f55-907c-e32e945d1a61.png">
 <img width="990" alt="스크린샷 2022-08-18 오후 12 34 49" src="https://user-images.githubusercontent.com/58887561/185287577-2fac89e4-9eed-40b3-bcbb-b2d549015c16.png">

 <img width="631" alt="스크린샷 2022-08-18 오후 12 43 24" src="https://user-images.githubusercontent.com/58887561/185288533-23578aac-aabd-4702-a1b3-e900ee9b5587.png">


 * 산점도
 
 #### 나이에 따른 골 결과
 
 <img width="586" alt="스크린샷 2022-08-18 오후 12 47 22" src="https://user-images.githubusercontent.com/58887561/185289118-39868906-965a-42dc-9ac9-3d393475fbee.png">

 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
