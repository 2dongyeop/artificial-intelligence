# artificial-intelligence
인공 지능에 대해 공부한 내용을 기록합니다.

코드는 파이썬을 이용하여 작성하고, 매주 공부한 내용을 정리하여 기록합니다.

-----

- 1장 : [나의 첫 머신러닝](https://leedongyeop.notion.site/Chapter1-89be424aa39741aaa5ba2e2cb6f0f082)
  - **인공지능과 머신러닝, 딥러닝**의 개념에 대해 공부합니다.
  - **k-초근접 이웃** 알고리즘을 사용해 데이터를 구분하는 코드를 작성합니다.
    - `KNeighborsClassifier()` 클래스를 이용해 k-최근접 이웃 분류 모델을 구현합니다.

- 2장 : [데이터 다루기](https://leedongyeop.notion.site/Chapter2-8b957ac0cc294c8b943dc697758ed577)
  - **지도 학습과 비 지도 학습**의 차이를 공부합니다.
  - 모델을 훈련시키는 **훈련 세트**와 모델을 평가하기 위한 **테스트 세트**로 데이터를 나눠 학습합니다.
    - `numpy` 배열 라이브러리를 사용합니다.
  - 데이터 전처리에 대해 공부하고, 표준 점수를 이해합니다.
    - `scikit-learn` 클래스의 메소드들을 사용합니다.
  - 스케일이 다른 특성 처리에 대해 알아봅니다.

- 3장 : [회귀 알고리즘과 모델 규제](https://leedongyeop.notion.site/Chapter3-fc4ee0672b02452ba0af184d7c08a8f8)
  - 회귀와 더불어 k-최근접 이웃 회귀에 대해 공부합니다.
    - 결정 계수와 과대적합, 과소적합에 대해 공부합니다.
    - `KNeighborsRegressor` 클래스를 이용해 k-최근접 이웃 회귀 모델을 구현합니다.
  - 선형 회귀의 개념에 대해 공부합니다.
    - `LinearRegression` 클래스를 이용해 선형 회귀 모델을 구현합니다.
  - 다중 회귀와 더불어 특성 공학에 대해 공부합니다.
    - 선형 회귀 모델 중 릿지와 라쏘에 대해 차이를 배웁니다.
    - `pandas` 를 사용한 실습 코드를 추가합니다.