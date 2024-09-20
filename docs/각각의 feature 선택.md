1. find_feature1 0.519
numerical, categorical 구분없이 전체를 numerical로 가정하고 상관계수 0.3이상의 feature 선택

##### top10
NumAromaticHeterocycles    0.126144   
VSA_EState1                0.113756   
SlogP_VSA5                 0.099396   
BCUT2D_LOGPLOW             0.086893   
Chi2n                      0.047403   
SMR_VSA5                   0.045330   
PEOE_VSA4                  0.042557   
PEOE_VSA9                  0.031458   
TPSA                       0.030484   
HallKierAlpha              0.028509


2. find_feature2 0.582
numerical, categorical 구분없이 전체를 numerical로 가정하고 상관계수 0.4이상의 feature 선택

##### top10
NumAromaticHeterocycles    0.168440   
SlogP_VSA5                 0.133687   
BCUT2D_LOGPLOW             0.127009   
Chi2n                      0.077621   
SMR_VSA5                   0.074219   
Kappa3                     0.043036   
Kappa1                     0.039702   
Chi0                       0.039309   
SMR_VSA3                   0.037493   
fr_NH0                     0.035714  


3. find_feature3 0.600
numerical, categorical 구분없이 전체를 numerical로 가정하고 상관계수 0.45이상의 feature 선택

##### top6
Chi0                   0.241578   
Chi2n                  0.236681   
Kappa1                 0.200038   
Chi0n                  0.145961   
fr_pyridine            0.100863   
NumValenceElectrons    0.074878


4. find_feature4 0.592
numerical feature 만을 선택하여 가정하고 상관계수 0.4이상의 feature 선택 
##### 추가로 시도해볼만함

##### top
SlogP_VSA5        0.222996   
BCUT2D_LOGPLOW    0.170899   
SMR_VSA3          0.099971   
Chi2n             0.079974   
Chi0              0.070854   
Kappa3            0.061929   
Kappa1            0.056665   
SMR_VSA5          0.049032   
Chi1              0.038974   
HeavyAtomMolWt    0.036546   
Chi0n             0.028750   
Chi0v             0.027585   
LabuteASA         0.025448   
ExactMolWt        0.015247   
MolWt             0.015133


5. find_feature5 0.572
위의 4개의 모델에서 나온 feature importance에서 중요도가 높게 나온 feature를 임의로 선택

##### top
BCUT2D_LOGPLOW             0.214406   
SlogP_VSA5                 0.195539   
NumAromaticHeterocycles    0.191267   
Chi2n                      0.138186   
Kappa1                     0.095611   
Chi0                       0.089090   
SMR_VSA3                   0.075902
