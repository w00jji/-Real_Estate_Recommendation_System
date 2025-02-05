# "Real_Estate_Recommendation_System
 
### 데이터 수집
부동산 매물 정보를 웹 크롤링하여 아파트 이름, 가격, 평수, 층수, 방향 등 다양한 속성을 포함한 데이터셋을 생성합니다. 이 데이터는 사용자의 아파트 선택에 기반한 추천 시스템의 기초 자료로 활용됩니다.

### 데이터 전처리
크롤링한 데이터에서 문자열 형태의 데이터를 수치형 데이터로 변환합니다. 

### 행렬 인수분해
(SVD)행렬 인수분해 기법을 사용하여 데이터를 분해합니다. 이를 통해 각 아파트의 특성과 사용자의 선호도를 잠재 요인으로 변환합니다.

### 코사인 유사도 계산
추천하고자 하는 아파트와 다른 아파트 간의 코사인 유사도를 계산합니다. 코사인 유사도는 두 벡터 간의 각도를 기반으로 유사성을 측정하며, 1에 가까울수록 더 유사한 것으로 간주됩니다.

### 추천 시스템 구축
사용자가 선호하는 아파트 이름을 입력하면, 해당 아파트와 코사인 유사도가 높은 다른 아파트를 추천합니다. 추천된 아파트 목록에는 각 아파트의 가격, 평수, 층수, 방향 등의 정보를 포함하여 사용자에게 제공합니다.

### 결과 제공
추천된 아파트 리스트를 사용자에게 보여주고, 각 항목에 대한 상세 정보를 제공하여 사용자가 더 나은 결정을 내릴 수 있도록 지원합니다.
