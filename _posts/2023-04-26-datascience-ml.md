---
title: "머신러닝 함수들 "
excerpt_separator: "<!--more-->"
categories:
  - datascience, ml
tags:
  - datascience, ml

toc : true
toc_sticky : true
---

## train and test sample 생성
```python
from sklearn.model_selection import train_test_split

```

## 상관 관계 -선형성 검사
```python
```


## 비계층 군집 분석 - k-mean
```python
```

## 단순 회귀 분석
```python
```

## 다중 회귀 부넉
```python
```

## 로지스틱 회귀분석
```python
```

## 나이브 베이즈
```python
```

## KNN
```python
```

## 의사결정트리
```python
```

[sklearn 설명](https://www.datamanim.com/dataset/98_sklearn/sklearn.html#)
<details>
<summary>sklearn tree</summary>
  
```
sklearn
│
├── 01 preprocessing (전처리)
│   │
│   ├── 스케일러
│   │   ├── MinMaxScaler
│   │   ├── RobustScaler
│   │   └── StandardScaler
│   │
│   └── 인코더
│       ├── LabelEncoder
│       └── OneHotEncoder
│  
├── 02 model_selection (모델링 전처리)
│   │
│   ├── 데이터셋 분리
│   │   ├── KFold
│   │   ├── StratifiedKFold
│   │   └── train_test_split
│   │
│   └── 하이퍼파라미터 튜닝
│       └── GridSearchCV
│
├── 03 모델학습
│   │
│   ├── ensemble
│   │   ├── AdaBoostClassifier
│   │   ├── GradientBoostingClassifier
│   │   ├── RandomForestClassifier
│   │   └── RandomForestRegressor
│   │
│   ├── linear_model
│   │   ├── LogisticRegression
│   │   └── RidgeClassifier
│   │
│   ├── neighbors
│   │   └── KNeighborsClassifier
│   │
│   ├── svm
│   │   ├── SVC
│   │   └── SVR
│   │
│   └── tree
│       ├── DecisionTreeClassifier
│       ├── DecisionTreeRegressor
│       ├── ExtraTreeClassifier
│       └── ExtraTreeRegressor
│
├── 04 모델평가
│   │
│   ├── metrics
│   │   ├── accuracy_score
│   │   ├── classification_report
│   │   ├── confusion_matrix
│   │   ├── f1_score
│   │   ├── log_loss
│   │   ├── mean_absolute_error
│   │   ├── mean_squared_error
│   │   └── roc_auc_score
│   │
│   └── model (정의된 모델에서 추출)
│       ├── predict
│       └── predict_proba
│
└── 05 최종앙상블
    │
    └── ensemble
        ├── StackingClassifier
        ├── StackingRegressor
        ├── VotingClassifier
        └── VotingRegressor
```
</details>
[scipy설명](https://www.datamanim.com/dataset/97_scipy/scipy.html)    
<details>
<summary>scipy tree</summary>
  
```
scipy
│
├── 01 integrate 수치적분, 미분방정식
│  
├── 02 linalg (선형대수, 매트릭스 분해)
│ 
├── 03 optimize (방정식 해 구하는 알고리즘, 함수 최적화)
│ 
├── 04 signal (신호 관련)
│
├── 05 sparse (희소 행렬, 희소 선형 시스템)
│
└── 06 stats (통계 분석) 
```
</details>
[statsmodels설명](https://www.datamanim.com/dataset/96_statsmodels/statsmodels.html)   
<details>
<summary>statsmodels tree</summary>
  
```
statsmodels
│
├── 01 사후분석
│   │
│   └──stats
│       └── multicomp
│           ├── MultiComparison
│           │   └── allpairtest
│           └── pairwise_tukeyhsd
│
├── 02 시계열분석
│   │
│   ├── graphics.tsaplots
│   │   ├── plot_acf
│   │   └── plot_pacf
│   └── tsa
│       ├── arima_model
│       │   └── ARIMA
│       └── statesplace.sarimax
│           └── SARIMAX
│
├── 03 ANOVA (scipy모듈과 함께써야 모두 커버가능, 이분산 anova의 경우 pingouin모듈의 welch_anova를 사용)
│   │
│   ├── 다원분산분석 or 이원분산분석
│   └── 일원분산분석
│       └── stats.anova
│           └── anova_lm
│
└── 04 회귀분석
    │
    └── formula.api
        └── ols
```
</details>
