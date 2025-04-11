# ■ 데이콘 대회 준비 
![image](https://github.com/user-attachments/assets/e3871e40-c4c8-4fc7-a0e9-8bf736c7bf20)

- 제목 : 부동산 허위매물 분류 해커톤: 가짜를 색출하라!
- 기간 : 2025.01.06 ~ 2025.02.28 09:59
- 출처 관련 링크 : https://dacon.io/competitions/official/236439/overview/description
- 데이터  : <br> 1) Dataset Info / train.csv [파일]
           ID : 샘플별 고유 ID, 매물확인방식, 보증금, 월세, 전용면적, 해당층, 총층, 방향, 방수, 욕실수
           주차가능여부, 총주차대수, 관리비, 중개사무소, 제공플랫폼, 게재일, 허위매물여부 <br>
          2) test.csv [파일]
           ID : 샘플별 고유 ID, 매물확인방식, 보증금, 월세, 전용면적, 해당층, 총층, 방향, 방수, 욕실수
           주차가능여부, 총주차대수, 관리비, 중개사무소, 제공플랫폼, 게재일

- 제출 로그 :

  ![image](https://github.com/user-attachments/assets/812fff4f-4b70-41ef-ac26-4c5de03c735f)
  
<br>

  - 최종 결과 :
  ![image](https://github.com/user-attachments/assets/0d6f73f9-c328-4ea4-b2b3-9bd68e1e4168)

    ※ 총 1065명 참여, 75등 달성, 상위 7.5% 달성

    <br>

-  데이터에 대한 이해도가 결과에 있어 큰 영향을 준다는 것을 깨달았고, 현실적 기준을 담은 파생 변수들이 실제 허위 매물을
   판단함에 있어 중요한 부분인 점을 다시 한번 알게된 기회였습니다. XGBoost라는 모델도 처음엔 단순히 성능이 좋다는 이유로 선택했지만,
   결과적으로 해석 가능성과 실전 활용성 측면에서 용이했고, 혼합형 데이터 처리에 효과적인 것을 확인했습니다.
   이후, 더 많은 대회에 참가하고 싶고 문제점에 대해 항상 본질적인 내용과 데이터의 특성을 정확하게 파악하고 논리적인 해결책을 설계하는 과정을
   더욱 더 경험하여 성장해 나가고 싶습니다. 
  


