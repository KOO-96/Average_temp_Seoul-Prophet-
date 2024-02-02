# Average_temp_Seoul(Prophet)

시계열 데이터를 다뤄보기 위해 데이콘에서 진행하는 서울시 평균 기온예측 해커톤에 참여하였습니다.

![image](https://github.com/KOO-96/Average_temp_Seoul-Prophet-/assets/113090595/c285b258-bdf1-4347-bf75-2a21477fa64f)

---

# Prophet모델이란?
2017년 Facebook에서 공개한 시계열 예측을 위한 오픈 소스 라이브러리로 정확도가 높은 편이며 직관적인 파라미터로 모델 수정이 용이하다.  

![image](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FFZsNQ%2FbtrlTkDZhlx%2FfWaYV5dbXhWQCaMaDjHL61%2Fimg.png)  

## 01_이론
Prophet모형은 구성요소로 Growth(트렌드), Seasonality(계절성), Holidays(휴일) 입니다.  

![image](https://github.com/KOO-96/Average_temp_Seoul-Prophet-/assets/113090595/fbc1f9de-698a-45b9-8627-d696508ca140)  
- g(t) : 주기적이지 않은 변화
- s(t) : 주기적인 변화 ex_주간/연간
- h(t) : 불규칙한 이벤트 ex_휴일
- ϵt : 정규분포를 따르는 잔차

자세한 부분은 velog에서 작성하였습니다.

[Review](https://velog.io/@rntjdwns1030/Prophet%EB%AA%A8%EB%8D%B8) 현재 진행중...

## References(Prophet)
- [시계열 예측 패키지 Prophet 소개](https://hyperconnect.github.io/2020/03/09/prophet-package.html)
- [paper](https://peerj.com/preprints/3190.pdf)
