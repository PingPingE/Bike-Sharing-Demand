# Bike-Sharing-Demand(2020.01.02~ )

예전에 RMSLE로 평가한 결과, 0.38665를 기록했다.(0에 가까울수록 좋은 결과)
좀 더 데이터, 회귀 모델, 평가 지표에 대해 분석하고 공부하고자한다.

# 문제 정의

워싱턴D.C.의 자전거 렌탈 키오스크 기계에 축적된 2년 동안의 데이터로 앞으로의 수요를 예측해본다.

다음과 같은 데이터가 주어진다.

- datetime 
- season : 1=봄, 2=여름, 3=가을, 4=겨울
- holiday
- workingday
- weather : 1=맑음, 2=조금 흐림, 3=흐림, 4=폭우,폭설
- temp : 실제 기온
- atemp : 체감 기온
- humidity
- windspeed
- casual : 비회원 렌탈 수(train에만)
- registered : 회원 렌탈 수(train에만)
- count : 전체 렌탈 수()
