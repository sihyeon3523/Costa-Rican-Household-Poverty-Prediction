# Costa-Rican-Household-Poverty-Prediction

[가구빈곤수준 예측모델 개발](https://www.kaggle.com/c/costa-rican-household-poverty-prediction)
<br>

### 주제 설명 & 선택 이유 
- 한 가정이 가지고 있는 140여 개의 속성을 기반으로 가구별 빈곤 레벨을 예측
- 변수가 많아, 많은 변수 중 모델의 예측력을 높이고, 합리적 근거를 갖는 변수를 선택하는 과정이 재미있을 것 같아 선택 
<br>

### 데이터 전처리 
- 가구 구성원들의 Target 값 통일 (가구의 가장 기준)
- 결측 값 처리 
- 상관관계가 높은 쌍 중 한 변수 제거
- 순서형 변수 생성(의미가 같은 여러 개의 변수를 하나의 순서형 변수로 통합)
- 의미가 중복되는 변수는 합쳐 하나의 변수로 생성(소유한 태블릿수 + 소유한 폰 수 = Tech 변수 생성)
<br>

### 모델링 
- f1-score 기준
- 변수 정규화 진행
- 라벨을 골고루 학습한 모델 사용
<br>

### 분석 산출물
- [주제 설명 & 선택 이유](https://github.com/sihyeon3523/Costa-Rican-Household-Poverty-Prediction/blob/c3fdcb9b4cda136a0e9ac24d8ac76e468fb98265/%EB%B6%84%EC%84%9D%20%EC%82%B0%EC%B6%9C%EB%AC%BC/1.%20%EB%B6%84%EC%84%9D%EC%A3%BC%EC%A0%9C%EC%84%A4%EB%AA%85.pdf)
- [데이터 전처리](https://github.com/sihyeon3523/Costa-Rican-Household-Poverty-Prediction/blob/c3fdcb9b4cda136a0e9ac24d8ac76e468fb98265/%EB%B6%84%EC%84%9D%20%EC%82%B0%EC%B6%9C%EB%AC%BC/2.%20%EB%B6%84%EC%84%9D%EB%8D%B0%EC%9D%B4%ED%84%B0%ED%83%90%EC%83%89.pdf)
- [모델링](https://github.com/sihyeon3523/Costa-Rican-Household-Poverty-Prediction/blob/c3fdcb9b4cda136a0e9ac24d8ac76e468fb98265/%EB%B6%84%EC%84%9D%20%EC%82%B0%EC%B6%9C%EB%AC%BC/3.%20%EB%B6%84%EC%84%9D%EB%AA%A8%EB%8D%B8%EB%A7%81.pdf)

<br>

참고 자료 : [A Complete Introduction and Walkthrough](https://www.kaggle.com/willkoehrsen/a-complete-introduction-and-walkthrough)
