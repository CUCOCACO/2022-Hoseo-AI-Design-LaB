# 2022-Hoseo-AI-Design-LaB
Lee Hyun Woo

### FOS(Feature Outlier Socre) ###
"""
Setting 모듈은 FOS(Feature Outlier Score) 산출을 위하여 value range 별 산출된 Shap vlaue의 평균과 표준편차를 뽑는 작업으로
간단하게 산출을 위한 뼈대를 만드는 모듈.

Analysis 모듈은 Setting에서 산출된 Shap vlaue의 평균과 표준편차를 사용하여 CDF, 및 통계적 기법을 통해 모델이 내린 결과에 대해 오탐지가
발생했을 가능성이 높은 데이터의 확률을 산출하는 모듈
"""


### Decision Tree ###
"""
Decision Tree로 시각화하여 각 라벨이 산출된 원인을 제공하고 Rule , Acc, Cob 등이 산출되어 Exaplainable을 제공 받을 수 있음  
첨부된 코드는 4가지 network에서 발생하는 공격을 탐지하고 그 원인을 제공하는 예시의 Decision Tree code 임
"""
