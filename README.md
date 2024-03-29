# 데이터 분석 프로젝트 : INCOME_PREDICT

[대회 설명 :개인의 특성과 관련된 다양한 데이터를 활용하여 개인 소득 수준을 예측할 수 있는 AI 모델 개발]
<br>https://dacon.io/competitions/official/236230/overview/description


<br>주어진 사회적 특성에 따른 개인의 소득을 예측하는 회귀 프로젝트를 진행했습니다.
<br>최대한 사고 과정을 단순하고 가져가려고 노력했습니다.
<br>순서는 다음과 같습니다.

- 1. Data Load : 데이터를 불러오고 기본적인 데이터셋 분석 진행
- 2. EDA : 다양한 가설을 세워보고, 피처에 따른 종속변수를 시각화, 결측값 처리
- 3. Encoding : 범주형 변수를 label, one-hot encoding
- 4. Feature Engineering : 파생변수 생성 및 일부 칼럼 정규화
- 5. Modeling : 여러 모델 중 가장 성능이 좋았던 LightGBM으로 Optuna 하이퍼파라미터 최적화


<br>여러 피처 엔지니어링 시도와 검증, 그리고 EDA를 집중적으로 수행했습니다. 
<br>생각보다 LB 점수를 올리는 것은 어려웠습니다. 하지만 다양한 가설들을 검증해보는 좋은 대회였습니다.



