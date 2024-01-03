# Average_temp_Seoul-Prophet-

시계열 데이터를 다뤄보기 위해 데이콘에서 진행하는 서울시 평균 기온예측 해커톤에 참여하였습니다.

모델선정 : AutoML 패키지는 사용이 불가능

![image](https://github.com/KOO-96/Average_temp_Seoul-Prophet-/assets/113090595/c285b258-bdf1-4347-bf75-2a21477fa64f)

# Prophet모델이란?
2017년 Facebook에서 공개한 시계열 예측을 위한 오픈 소스 라이브러리로 정확도가 높은 편이며 직관적인 파라미터로 모델 수정이 용이하다.

## 이론
Prophet모형은 구성요소로 Growth(트렌드), Seasonality(계절성), Holidays(휴일) 입니다.  

![image](https://github.com/KOO-96/Average_temp_Seoul-Prophet-/assets/113090595/fbc1f9de-698a-45b9-8627-d696508ca140)  
- g(t) : 주기적이지 않은 변화, 부분적으로 선형성, Logistic곡선으로 이루어져있다.
- s(t) : 주기적인 변화 ex_주간/연간
- h(t) : 불규칙한 이벤트 ex_휴일
- ϵt : 정규분포를 따르는 잔차

prophet모델은 시간에 종속적인 구조를 가지는 것이 아닌 curve-fitting방식으로 예측을 진행합니다.  

![image](https://github.com/KOO-96/Average_temp_Seoul-Prophet-/assets/113090595/52956593-9d03-43dd-8544-8224ebf6672d)  

모델의 특징
1. 유연성.
2. ARIMA모델과 다르게 정규화 시킬 필요도 없고 결측치를 구겨넣을 이유가 없다.
3. 직관적으로 파라미터를 조정할 수 있기때문에 모델 확장에 용이함.




처음 다루어본 시계열 데이터였고 Prophet모델을 사용하여 대회에 참여하였습니다.
![image](https://github.com/KOO-96/Average_temp_Seoul-Prophet-/assets/113090595/7d1ab196-389e-4a98-94bf-ff7d39901f25)
