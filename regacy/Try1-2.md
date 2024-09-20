# Mendeleev

주기율표에 기반한 원소들의 다양한 물리적, 화학적 특성을 제공하는 라이브러리
아래는 Mendeleev 라이브러리의 `fetch_table('elements')`로 가져온 원소 특성들의 목록과 그 설명입니다

### 원소 특성 목록 및 설명:

1. **annotation**: 원소에 대한 추가 설명이나 메모.
2. **atomic_number**: 원소의 원자 번호, 즉, 원자의 양성자 수.
3. **atomic_radius**: 원자의 반지름, 일반적으로 비결합 상태에서 측정된 값.
4. **atomic_volume**: 원자 하나의 부피 (보통 cm³/mol로 표현).
5. **block**: 원소가 주기율표의 어느 블록에 속하는지 (`s`, `p`, `d`, `f` 블록).
6. **density**: 원소의 밀도 (g/cm³).
7. **description**: 원소에 대한 설명 또는 정의.
8. **dipole_polarizability**: 원자의 쌍극자 편극도, 외부 전기장에 의해 유도된 전기적 변화를 나타냄.
9. **electron_affinity**: 전자 친화도, 원자가 전자를 얻을 때 방출하는 에너지.
10. **electronic_configuration**: 원자의 전자 배치 (예: 1s² 2s² 2p⁶).
11. **evaporation_heat**: 원소의 기화에 필요한 에너지 (kJ/mol).
12. **fusion_heat**: 원소가 녹을 때 필요한 에너지 (kJ/mol).
13. **group_id**: 원소가 속한 주기율표의 그룹 번호.
14. **lattice_constant**: 결정 구조에서 원자 간의 격자 상수.
15. **lattice_structure**: 원소의 결정 구조 (예: 면심 입방 구조).
16. **name**: 원소의 이름.
17. **period**: 원소가 속한 주기율표의 주기 번호.
18. **series_id**: 원소가 속한 시리즈 (예: 란타넘족).
19. **specific_heat_capacity**: 원소의 비열, 특정 온도에서 물질 1g의 온도를 1°C 올리는 데 필요한 열량 (J/g·K).
20. **symbol**: 원소의 화학 기호 (예: H, O, C).
21. **thermal_conductivity**: 원소의 열전도도, 열을 전달하는 능력 (W/m·K).
22. **vdw_radius**: 원소의 반데르발스 반지름, 분자 간 인력이 작용할 때의 원자의 크기.
23. **covalent_radius_cordero**: Cordero 연구에 기반한 원소의 공유 결합 반지름.
24. **covalent_radius_pyykko**: Pyykko 연구에 기반한 공유 결합 반지름.
25. **en_pauling**: 폴링 척도에서의 전기 음성도.
26. **en_allen**: 앨런 척도에서의 전기 음성도.
27. **jmol_color**: Jmol 시각화 도구에서 사용하는 원소의 색상.
28. **cpk_color**: CPK 모델에서 사용하는 원소의 색상.
29. **proton_affinity**: 원자가 양성자와 결합할 때 방출되는 에너지.
30. **gas_basicity**: 원소가 기체 상태에서 산염기 반응을 할 때 방출되는 에너지.
31. **heat_of_formation**: 원소가 형성될 때의 엔탈피 변화 (kJ/mol).
32. **c6**: 원소 간 분산력 상수 (van der Waals 힘).
33. **covalent_radius_bragg**: Bragg 연구에 기반한 공유 결합 반지름.
34. **vdw_radius_bondi**: Bondi 연구에 기반한 반데르발스 반지름.
35. **vdw_radius_truhlar**: Truhlar 연구에 기반한 반데르발스 반지름.
36. **vdw_radius_rt**: RT 연구에 기반한 반데르발스 반지름.
37. **vdw_radius_batsanov**: Batsanov 연구에 기반한 반데르발스 반지름.
38. **vdw_radius_dreiding**: Dreiding 연구에 기반한 반데르발스 반지름.
39. **vdw_radius_uff**: UFF (Universal Force Field) 모델에서의 반데르발스 반지름.
40. **vdw_radius_mm3**: MM3 (Molecular Mechanics) 모델에서의 반데르발스 반지름.
41. **abundance_crust**: 지각에서의 원소의 풍부도 (ppm).
42. **abundance_sea**: 바다에서의 원소의 풍부도 (ppm).
43. **molcas_gv_color**: MOLCAS 프로그램에서 사용하는 색상.
44. **en_ghosh**: Ghosh 척도에서의 전기 음성도.
45. **vdw_radius_alvarez**: Alvarez 연구에 기반한 반데르발스 반지름.
46. **c6_gb**: Grimme-Banner 연구에 기반한 C6 상수.
47. **atomic_weight**: 원소의 평균 원자 질량.
48. **atomic_weight_uncertainty**: 원자 질량의 불확실성.
49. **is_monoisotopic**: 원소가 단일 동위원소인지 여부.
50. **is_radioactive**: 원소가 방사성인지 여부.
51. **cas**: 원소의 CAS (Chemical Abstracts Service) 번호.
52. **atomic_radius_rahm**: Rahm 연구에 기반한 원자 반지름.
53. **geochemical_class**: 원소의 지구화학적 분류.
54. **goldschmidt_class**: Goldschmidt 지구화학적 분류.
55. **metallic_radius**: 금속 원소의 반지름.
56. **metallic_radius_c12**: 12-좌석 환경에서의 금속 반지름.
57. **covalent_radius_pyykko_double**: Pyykko 연구에서 이중 결합에 대한 공유 결합 반지름.
58. **covalent_radius_pyykko_triple**: Pyykko 연구에서 삼중 결합에 대한 공유 결합 반지름.
59. **discoverers**: 원소를 발견한 과학자(들).
60. **discovery_year**: 원소가 발견된 연도.
61. **discovery_location**: 원소가 발견된 장소.
62. **name_origin**: 원소 이름의 기원.
63. **sources**: 원소의 주요 출처.
64. **uses**: 원소의 주요 사용 용도.
65. **mendeleev_number**: 멘델레예프 번호 (원소의 주기적 배열 순서).
66. **dipole_polarizability_unc**: 쌍극자 편극도의 불확실성.
67. **pettifor_number**: Pettifor 주기율표에 따른 번호.
68. **glawe_number**: Glawe 연구에 기반한 원소 번호.
69. **molar_heat_capacity**: 몰당 열용량 (J/mol·K).


---

# RDKit 기반 원소 피처

•	atom.GetDegree(): 해당 원자에 연결된 결합의 개수를 나타냅니다.
•	atom.GetTotalDegree(): 명시적 및 암시적 수소를 포함한 결합의 총 개수를 반환합니다.
•	atom.GetFormalCharge(): 원자의 형식적 전하를 반환합니다.
•	atom.GetIsAromatic(): 원자가 방향족성인지 여부를 반환하고, 이를 1.로 변환하여 이진 피처로 사용합니다.
•	atom.GetNumImplicitHs(): 암시적 수소의 개수를 반환합니다.
•	atom.GetNumExplicitHs(): 명시적 수소의 개수를 반환합니다.
•	atom.GetTotalNumHs(): 명시적 및 암시적 수소의 총 개수를 반환합니다.
•	atom.GetNumRadicalElectrons(): 해당 원자가 가지고 있는 라디칼 전자의 개수를 반환합니다.
•	atom.GetImplicitValence(): 암시적 원자가를 반환합니다.
•	atom.GetExplicitValence(): 명시적 원자가를 반환합니다.
•	atom.GetTotalValence(): 명시적 및 암시적 원자가의 총합을 반환합니다.
•	atom.IsInRing(): 해당 원자가 고리 구조에 포함되어 있는지를 반환하며, 이를 1.로 변환하여 이진 피처로 사용합니다.


---
# RDKit Descriptors

아래는 `RDKit Descriptors`로부터 추출 가능한 210개의 피처에 대한 간단한 설명입니다. 각 피처는 분자의 다양한 물리적, 화학적 특성을 나타내며, 이를 통해 IC50 같은 생물학적 반응을 예측할 수 있습니다.

### E-State (EState)
1. **MaxAbsEStateIndex**: 최대 절대 E-State 지수.
2. **MaxEStateIndex**: 최대 E-State 지수.
3. **MinAbsEStateIndex**: 최소 절대 E-State 지수.
4. **MinEStateIndex**: 최소 E-State 지수.

### QED (Quantitative Estimation of Drug-likeness)
5. **qed**: 약물 유사성을 평가하는 지수.

### 기타 서술자
6. **SPS**: 분자의 표면적/부피 비율.

### 분자량 관련
7. **MolWt**: 분자량.
8. **HeavyAtomMolWt**: 무거운 원자(수소를 제외한 원자)의 분자량.
9. **ExactMolWt**: 정확한 분자량.

### 전자 관련
10. **NumValenceElectrons**: 원자의 원자가 전자 수.
11. **NumRadicalElectrons**: 라디칼 전자의 수.

### 부분 전하 관련
12. **MaxPartialCharge**: 최대 부분 전하.
13. **MinPartialCharge**: 최소 부분 전하.
14. **MaxAbsPartialCharge**: 최대 절대 부분 전하.
15. **MinAbsPartialCharge**: 최소 절대 부분 전하.

### 분자 지문 (Fingerprints)
16. **FpDensityMorgan1**: Morgan 지문 밀도 (반지름 1).
17. **FpDensityMorgan2**: Morgan 지문 밀도 (반지름 2).
18. **FpDensityMorgan3**: Morgan 지문 밀도 (반지름 3).

### BCUT2D
19. **BCUT2D_MWHI**: 높은 분자량의 BCUT2D 값.
20. **BCUT2D_MWLOW**: 낮은 분자량의 BCUT2D 값.
21. **BCUT2D_CHGHI**: 높은 전하의 BCUT2D 값.
22. **BCUT2D_CHGLO**: 낮은 전하의 BCUT2D 값.
23. **BCUT2D_LOGPHI**: 높은 LogP의 BCUT2D 값.
24. **BCUT2D_LOGPLOW**: 낮은 LogP의 BCUT2D 값.
25. **BCUT2D_MRHI**: 높은 몰 굴절률의 BCUT2D 값.
26. **BCUT2D_MRLOW**: 낮은 몰 굴절률의 BCUT2D 값.

### 분자 기하학적 서술자
27. **AvgIpc**: 분자의 평균 정보양.
28. **BalabanJ**: Balaban J 지수 (분자의 연결성).
29. **BertzCT**: 분자의 복잡도.

### 연결성 서술자 (Chi)
30. **Chi0**: 0차 Chi 지수.
31. **Chi0n**: 0차 Chi 지수 (비선형).
32. **Chi0v**: 0차 Chi 지수 (가변성).
33. **Chi1**: 1차 Chi 지수.
34. **Chi1n**: 1차 Chi 지수 (비선형).
35. **Chi1v**: 1차 Chi 지수 (가변성).
36. **Chi2n**: 2차 Chi 지수 (비선형).
37. **Chi2v**: 2차 Chi 지수 (가변성).
38. **Chi3n**: 3차 Chi 지수 (비선형).
39. **Chi3v**: 3차 Chi 지수 (가변성).
40. **Chi4n**: 4차 Chi 지수 (비선형).
41. **Chi4v**: 4차 Chi 지수 (가변성).

### 기타 분자 특성
42. **HallKierAlpha**: Hall-Kier 알파 지수 (분자의 분지화 정도).
43. **Ipc**: 정보 양 (Information content).

### Kappa 서술자
44. **Kappa1**: 1차 Kappa 지수.
45. **Kappa2**: 2차 Kappa 지수.
46. **Kappa3**: 3차 Kappa 지수.

### 분자 표면적
47. **LabuteASA**: 분자의 Labute 접근 가능한 표면적.

### PEOE_VSA 서술자 (Electrostatic Potential)
48-63. **PEOE_VSA1-PEOE_VSA14**: PEOE 방식으로 계산된 표면적과 전기음성도.

### SMR_VSA 서술자 (Molecular Refraction)
64-73. **SMR_VSA1-SMR_VSA10**: 몰 굴절률과 표면적의 조합.

### SlogP_VSA 서술자 (LogP와 표면적)
74-84. **SlogP_VSA1-SlogP_VSA12**: LogP(분자 지용성)와 표면적의 조합.

### 극성 표면적 (TPSA)
85. **TPSA**: 극성 표면적 (분자의 극성 부분 면적).

### EState_VSA 서술자 (E-State와 표면적)
86-98. **EState_VSA1-EState_VSA10**: E-State 지수와 표면적의 조합.

### VSA_EState 서술자 (Valence State와 표면적)
99-109. **VSA_EState1-VSA_EState10**: 원자의 원자가 상태와 표면적.

### Lipinski Rule of 5
110. **FractionCSP3**: sp3 혼성화 탄소의 비율.
111. **HeavyAtomCount**: 무거운 원자의 개수.
112. **NHOHCount**: 수소 결합 주개의 수.
113. **NOCount**: 수소 결합 수용체의 수.

### 고리와 관련된 서술자
114-122. **NumAliphaticCarbocycles-NumSaturatedRings**: 다양한 고리와 관련된 서술자 (포화, 방향족 등).

### 기타 분자 특성
123. **RingCount**: 고리의 개수.
124. **MolLogP**: LogP 값 (분자의 지용성).
125. **MolMR**: 몰 굴절률 (분자의 부피와 관련된 특성).

### 분자 기능성 그룹 (Fragment 서술자)
126-210. **fr_**로 시작하는 서술자들은 특정 분자의 기능성 그룹을 나타냅니다. 예를 들어:
- **fr_Al_COO**: 알킬 카복실산 그룹.
- **fr_Ar_N**: 방향족 질소 그룹.
- **fr_ether**: 에터 그룹.
- **fr_nitro**: 니트로 그룹.


---
# RDKit Lipinski

Lipinski의 규칙에 기반한 RDKit에서 추출할 수 있는 피처들은 주로 약물의 화학적 특성과 생물학적 활성에 관련된 중요한 분자적 특성을 설명합니다. 아래는 해당 피처들에 대한 설명입니다:

1. **FractionCSP3**:  
   - 분자 내 sp3 혼성화된 탄소 원자의 비율을 나타냅니다. 약물의 구조적 유연성에 영향을 미치며, 고도로 sp3 혼성화된 분자는 더 많은 구조적 다양성을 가질 수 있습니다.

2. **HeavyAtomCount**:  
   - 수소를 제외한 모든 원자의 개수를 의미합니다. 무거운 원자의 개수는 분자의 크기 및 복잡성을 나타냅니다.

3. **NHOHCount**:  
   - 분자 내 수소 결합을 할 수 있는 -OH 또는 -NH 그룹의 수를 의미합니다. 수소 결합 주개의 개수는 약물이 수용체와 결합할 수 있는 능력과 관련이 있습니다.

4. **NOCount**:  
   - 수소 결합 수용체가 될 수 있는 산소와 질소 원자의 수를 나타냅니다. 수소 결합을 통해 약물-수용체 상호작용에 영향을 줄 수 있습니다.

5. **NumAliphaticCarbocycles**:  
   - 지방족 탄소로만 이루어진 고리 구조(카보사이클)의 수를 의미합니다. 지방족 고리는 분자의 유연성에 영향을 줄 수 있습니다.

6. **NumAliphaticHeterocycles**:  
   - 지방족 이종 고리(heterocycle)의 수를 나타냅니다. 이종 고리에는 탄소 외의 원자가 포함되며, 이는 약물의 생물학적 활성에 영향을 미칠 수 있습니다.

7. **NumAliphaticRings**:  
   - 지방족 고리(알리파틱 링)의 총 개수를 나타냅니다. 이 값은 분자의 구조적 특징을 반영합니다.

8. **NumAromaticCarbocycles**:  
   - 방향족 탄소 고리의 수를 나타냅니다. 방향족 고리는 분자의 평면 구조와 상호작용에 영향을 줍니다.

9. **NumAromaticHeterocycles**:  
   - 방향족 이종 고리의 수를 나타냅니다. 방향족 이종 고리는 생물학적 활성에 중요한 역할을 합니다.

10. **NumAromaticRings**:  
    - 방향족 고리의 총 개수를 의미합니다. 이는 전자적 안정성 및 생물학적 상호작용에 중요한 요소입니다.

11. **NumHAcceptors**:  
    - 수소 결합을 수용할 수 있는 원자의 개수를 의미합니다. 보통 산소나 질소와 같은 전기음성 원자들이 수소 결합 수용체로 작용합니다.

12. **NumHDonors**:  
    - 수소 결합을 제공할 수 있는 원자의 수를 의미합니다. 보통 -OH 또는 -NH 그룹이 수소 결합 주개 역할을 합니다.

13. **NumHeteroatoms**:  
    - 탄소 외의 다른 원자의 개수를 의미합니다. 이종 원자는 분자의 화학적 반응성과 생물학적 활성을 결정짓는 중요한 요소입니다.

14. **NumRotatableBonds**:  
    - 회전 가능한 단일 결합의 수를 나타냅니다. 회전 가능한 결합의 수는 분자의 유연성을 나타내며, 이는 분자가 수용체와 상호작용하는 방식을 결정합니다.

15. **NumSaturatedCarbocycles**:  
    - 포화된 탄소 고리의 개수를 나타냅니다. 포화 고리는 고리 내 모든 탄소가 단일 결합으로 연결된 구조를 의미합니다.

16. **NumSaturatedHeterocycles**:  
    - 포화된 이종 고리의 수를 나타냅니다. 이종 고리는 탄소 외의 원자가 포함된 고리 구조입니다.

17. **NumSaturatedRings**:  
    - 포화된 고리의 총 개수를 나타냅니다. 이는 고리 내의 모든 결합이 단일 결합인 구조입니다.

18. **RingCount**:  
    - 분자 내 모든 고리의 총 개수를 나타냅니다. 이는 분자의 구조적 복잡성과 안정성을 나타내는 중요한 지표입니다.

---
# RDKit Crippen

RDKit의 **Crippen** 모듈에서 추출할 수 있는 두 가지 주요 피처인 **MolLogP**와 **MolMR**에 대한 설명입니다:

1. **MolLogP**:
   - **LogP**는 **오일/물 분배 계수**를 나타냅니다. LogP는 분자가 지질(지방) 친화적인지, 아니면 물 친화적인지를 나타내는 지표로, 약물의 흡수 및 투과성에 중요한 영향을 미칩니다. 
   - LogP 값이 클수록 분자가 지질 친화적이고, 값이 작을수록 물 친화적입니다.
   - **MolLogP**는 분자의 LogP 값을 계산한 것으로, 약물 설계에서 약물의 생체 이용률, 막 투과성, 배포 등을 예측하는 데 중요한 역할을 합니다.

2. **MolMR**:
   - **몰 굴절률(Molecular Refractivity, MR)**은 분자의 크기, 분극화 가능성 및 결합 성질을 반영하는 물리적 특성입니다.
   - 몰 굴절률은 분자가 빛을 어떻게 굴절시키는지에 관한 정보로, 분자의 부피와 전자적 구조에 관련된 중요한 지표입니다.
   - **MolMR**은 분자의 몰 굴절률을 나타내며, 약물-수용체 상호작용 및 물리적 특성(예: 용해도, 막 투과성)을 예측하는 데 사용됩니다.


---
# RDKit rdMolDescriptors

**RDKit의 `rdMolDescriptors`로부터 추출할 수 있는 다양한 분자 서술자들에 대한 간단한 설명**:

1. **AtomPairsParameters**: 원자쌍과 관련된 서술자로, 분자 내 두 원자 간의 거리를 나타냅니다.
2. **BCUT2D**: 2D BCUT 서술자는 분자의 원자 간 상호작용에 기반한 특성으로, 분자의 전자적 및 입체적 정보를 제공합니다.
3. **CalcAUTOCORR2D / CalcAUTOCORR3D**: 2D 및 3D 자가상관 서술자는 분자의 2D 또는 3D 구조에서 원자 간의 상호작용을 기반으로 합니다.
4. **CalcAsphericity**: 분자의 구형 대칭성을 측정하는 서술자입니다. 값이 클수록 분자가 비구형임을 나타냅니다.
5. **CalcChi0n / CalcChi0v / CalcChi1n / CalcChi1v / CalcChi2n / CalcChi2v / CalcChi3n / CalcChi3v / CalcChi4n / CalcChi4v**: Chi 서술자 시리즈는 분자의 접힘 및 구조적인 복잡성을 나타내며, 치환된 고리 시스템 등의 특성을 측정합니다.
6. **CalcChiNn / CalcChiNv**: 분자의 수소 및 비수소 원자를 고려한 Chi 서술자입니다.
7. **CalcCoulombMat**: 분자의 쿨롱 매트릭스를 계산하여 분자의 전하 분포를 나타냅니다.
8. **CalcCrippenDescriptors**: Crippen의 LogP 및 몰 굴절률(MR)을 계산하는 서술자입니다.
9. **CalcEEMcharges**: 분자 내 각 원자에 할당된 부분 전하를 계산합니다.
10. **CalcEccentricity**: 분자의 이심률을 나타내며, 구조적인 비대칭성을 측정합니다.
11. **CalcExactMolWt**: 분자의 정확한 분자량을 계산합니다.
12. **CalcFractionCSP3**: sp³ 혼성화된 탄소 원자의 비율을 나타냅니다.
13. **CalcGETAWAY**: 원자 가중 거리를 기반으로 한 분자의 특성을 나타냅니다.
14. **CalcHallKierAlpha**: 분자의 수소 원자의 배치를 기반으로 하는 분자의 입체적 구조 특성입니다.
15. **CalcInertialShapeFactor**: 분자의 관성 모멘트 비율을 나타냅니다.
16. **CalcKappa1 / CalcKappa2 / CalcKappa3**: 분자의 분기성과 형태를 나타내는 Kappa 인덱스입니다.
17. **CalcLabuteASA**: 분자의 Labute 접근성 표면적(ASA)을 계산합니다.
18. **CalcMORSE**: 3D 구조를 기반으로 하는 분자 상관 서술자입니다.
19. **CalcMolFormula**: 분자의 화학식을 반환합니다.
20. **CalcNPR1 / CalcNPR2**: 비구형성 비율을 나타내며, 분자의 비구형성을 측정합니다.
21. **CalcNumAliphaticCarbocycles / CalcNumAliphaticHeterocycles / CalcNumAliphaticRings**: 분자 내 알리파틱 탄소 고리, 이종고리, 및 고리 수를 나타냅니다.
22. **CalcNumAmideBonds**: 아마이드 결합의 개수를 나타냅니다.
23. **CalcNumAromaticCarbocycles / CalcNumAromaticHeterocycles / CalcNumAromaticRings**: 방향족 탄소 고리, 이종고리, 고리 수를 나타냅니다.
24. **CalcNumAtomStereoCenters**: 분자 내 입체 중심(카이랄 중심) 수를 나타냅니다.
25. **CalcNumAtoms**: 분자 내 원자의 총 개수를 계산합니다.
26. **CalcNumBridgeheadAtoms**: 분자 내 브리지헤드 원자의 개수를 계산합니다.
27. **CalcNumHBA / CalcNumHBD**: 수소 결합 수용체(HBA) 및 주개(HBD)의 개수를 나타냅니다.
28. **CalcNumHeavyAtoms**: 분자 내 무거운 원자(탄소보다 무거운 원자)의 수를 나타냅니다.
29. **CalcNumHeteroatoms**: 분자 내 이종 원자의 수를 계산합니다.
30. **CalcNumLipinskiHBA / CalcNumLipinskiHBD**: 리핀스키 규칙을 기반으로 한 수소 결합 수용체 및 주개의 수를 계산합니다.
31. **CalcNumRings**: 분자 내 고리의 총 개수를 나타냅니다.
32. **CalcNumRotatableBonds**: 회전 가능한 단일 결합의 수를 나타냅니다.
33. **CalcNumSaturatedCarbocycles / CalcNumSaturatedHeterocycles / CalcNumSaturatedRings**: 포화된 탄소 고리, 이종 고리, 고리의 개수를 나타냅니다.
34. **CalcNumSpiroAtoms**: 분자 내 스피로 원자의 개수를 나타냅니다.
35. **CalcNumUnspecifiedAtomStereoCenters**: 입체 중심이 지정되지 않은 원자의 수를 계산합니다.
36. **CalcOxidationNumbers**: 원자의 산화수를 계산합니다.
37. **CalcPBF**: 분자 입자의 비구형성을 나타냅니다.
38. **CalcPMI1 / CalcPMI2 / CalcPMI3**: 주관성 모멘트(PMI)를 계산하여 분자의 공간 구조를 나타냅니다.
39. **CalcPhi**: 분자의 3D 구조에 기반한 지표입니다.
40. **CalcRDF**: 방사 함수(Radial Distribution Function)를 계산하여 분자 내의 거리 기반 상관관계를 나타냅니다.
41. **CalcRadiusOfGyration**: 분자의 중심에서 각 원자까지의 거리의 평균을 나타냅니다.
42. **CalcSpherocityIndex**: 분자의 구형성을 나타내는 지표입니다.
43. **CalcTPSA**: 극성 표면적(TPSA)을 나타내며, 약물의 막 투과성을 예측하는 데 중요한 지표입니다.
44. **CalcWHIM**: 3D 분자의 형태, 크기, 입체적 상관관계를 나타냅니다.
45. **CustomProp_VSA_**: 사용자 정의 가능한 VSA(분자 표면적)를 기반으로 한 특성입니다.
46. **DoubleCubicLatticeVolume**: 분자의 3D 격자 부피를 나타냅니다.
47. **GetAtomFeatures**: 각 원자의 피처를 추출하는 함수입니다.
48. **GetAtomPairAtomCode / GetAtomPairCode / GetAtomPairFingerprint**: 원자 쌍 상관관계 및 지문을 계산합니다.
49. **GetConnectivityInvariants**: 분자의 연결성을 나타냅니다.
50. **GetFeatureInvariants**: 분자 내 주요 피처들의 불변성을 나타냅니다.
51. **GetHashedAtomPairFingerprint / GetHashedAtomPairFingerprintAsBitVect**: 원자 쌍 지문을 해싱된 형식으로 반환합니다.
52. **GetHashedMorganFingerprint / GetHashedTopologicalTorsionFingerprint**: Morgan 및 위상학적 회전 지문을 해싱된 형식으로 반환합니다.
53. **GetMACCSKeysFingerprint**: MACCS 지문을 반환합니다.
54. **GetMorganFingerprint / GetMorganFingerprintAsBitVect**: Morgan 지문을 반환합니다.
55. **GetTopologicalTorsionFingerprint**: 분자의 위상학적 비틀림 지문을 반환합니다.
56. **GetUSR / GetUSRCAT / GetUSRDistributions**: USR(유사성 지표) 및 USRCAT 지표를 계산하여 분자의 3D 유사성을 나타냅니다.
57. **MQNs_**: 분자의 특정 속성에 대한 지표를 나타냅니다.
58. **MakePropertyRangeQuery**: 분자 속성의 범위를 설정하여 쿼리합니다.
59. **NumRotatableBondsOptions**: 회전 가능한 결합 수를 계산하는 옵션을 제공합니다.
60. **PEOE_VSA_**: 분자의 표면적과 전자적 특성을 기반으로 한 특성입니다.
61. **Properties / PropertyFunctor / PropertyRangeQuery / PythonPropertyFunctor**: 분자의 속성 계산을 위한 유틸리티입니다.
62. **SMR_VSA_**: SMR(몰 굴절률) 및 분자 표면적을 기반으로 한 특성입니다.
63. **SlogP_VSA_**: LogP 및 분자 표면적을 기반으로 한 특성입니다.
