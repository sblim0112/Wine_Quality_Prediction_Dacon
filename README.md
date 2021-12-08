# Wine_Quality_Prediction_Dacon

### baseline
* 기본 변수 EDA 후 LGBClassifier만을 이용한 베이스라인 코드

### 02.기본변수 + oversampling
* 타겟변수 불균형 해결을 위한 oversampling 시도
* SMOTE, ADASYN 사용
* 여러 모델 LGB, XGB, RandomForest 및 ExtraTreesClassifier 예측결과 평균으로 제출 --> 제출 후 성능향상 확인

### 03.파생변수생성 및 VotingClassifier
* 여러 변수들을 집단시각화(subplots)하는 과정 소개(대학원 그룹스터디 소개용)
* 파생변수 생성 및 실험
* 투표기반 앙상블 VotingClassifier 이용하여 제출 --> 제출 후 성능 향상 확인
