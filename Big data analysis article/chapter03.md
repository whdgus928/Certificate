# 3. 빅데이터 모델링
## 3.1 분석 모형 설계
### 통계기반 분석 모형 선정
1. 교차분석
- 독립변수 종속변수 모두 범주형 자료일때 관계 파악하기 적합
- 남여에 따른 지지정당
2. t-test와 분산분석
- 독립변수 범주형, 종속변수 연속형일때 독립변수의 하부 집단 수가 2집단이면 t-test, 3집단 이상이면 일원배치 분산분석
- a공장과 b공장에서 생산되는 음료의 농도를 비교 : t-test
- 공장이 세 개 이상이면 분산분석
3. 상관관계와 선형회귀분석
- 독립변수 종속변수 모두 연속형 일때
- 매체별 광고횟수와 매출간에 상관이 있는지 파악 
4. 로지스틱 회귀분석과 판별분석
- 정상인과 암 환자 집단의 특징 파악
- 신체 관련 변수, 건강행위 관련 변수중 어떤 변수가 유의한 영향을 미치는지를 파악

### 머신러닝 기반 모형 선정
1. 지도 학습
- 정답인 레이블이 포함된 학습
- 데이터를 통해 컴퓨터 학습
- 설명변수와 목적변수 간의 관계성을 표현, 미래 관측을 예측
- 인식, 분류, 진단, 예측
- 로지스틱 회귀
- 인공신경망 분석
- 의사결정나무
- 서포트 벡터 머신
- 랜덤 포레스트
- 감성 분석
2. 비지도 학습
- 정답인 레이블 없는 상태
- 데이터가 어떻게 구상되었는지를 파악
- 현상 설명, 특징 도출
- 데이터 마이닝 성격이 강함
- 군집화, 차원축소 기법, 딥러닝

### 데이터마이닝 기반 분석모형 선정
1. 분류
- 통계적 기법
- 트리기반 기법
- 최적화 기법
- 기계학습
2. 예측
- 회귀분석
- 의사결정나무
- 시계열 분석
- 인공신경망
3. 군집
4. 연관
- 장바구니 분석, 마켓팅에서 활용
- 어떤 상품이 같이 판매될 확률이 높은가? 연관된 규칙을 도출