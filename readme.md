# Kaggle House Prices
미국 특정 지역의 주택 가격을 예측하는 프로젝트

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

## 기간
- 2022.06

## 사용 기술
### Language
- python3
### Library
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## 설명
- 미국 Iowa주 Ames 도시의 주거용 주택 가격을 예측하는 대회입니다.
- 데이터는 주거용 주택의 각종 정보들로 구성되어 있습니다.
- 데이터를 자세히 파악하여 논리적 추론에 따른 전처리에 집중하였습니다.
- 차원축소나 하이퍼 파라미터 튜닝 등을 시도하여 모델 성능 개선에 집중했습니다.

## 결과
- 0.12438의 RMSE로 리더보드 상위 12% 달성했습니다.

## 회고 / 느낀 점
- 아무리 논리적으로 전처리를 진행해도 결국 사람이 하는 것이기 때문에 최적의 답을 얻기는 어렵다는 결론을 얻었습니다. 그러나 인공지능이 최적의 예측 신경망을 모사하는 것처럼, 최고의 데이터를 위해 최대한 논리적이고 합리적인 처리를 진행하려 노력했습니다.
- 모델링 계속될수록 실험한 하이퍼 파라미터의 관리가 어려워져, 다음번에는 MLflow등의 실험 관리 도구를 사용해 보려고 합니다.
