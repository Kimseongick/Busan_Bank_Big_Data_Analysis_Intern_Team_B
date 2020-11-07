# Busan_Bank_Big_Data_Analysis_Intern_Team_B
Results of Big Data Analysis Intern Team B at Busan Bank

# 부산은행 빅데이터 분석 인턴 B팀
### 개요
1. 직위 : 인턴
2. 직책 : (인턴들 중) 팀장
3. 직무 : 고객 데이터 분석
4. 기간 : 2019.10.14. ~ 2020.04.13. (약 6개월)
5. 역할 : 고객의 수입 내역 데이터를 분석하여 다음 달 수입을 예측하는 모델 만들기
6. 주요 성과
- 고객의 수입 내역 데이터 중 정기성 거래를 찾아내는 알고리즘 개발
- 개발한 알고리즘을 통하여 예측 모델의 예측 성공률을 10%에서 50%까지 올림

### 세부 내용
 **"고객 맞춤 상품 추천 및 금융 컨설팅"을 주제로 한 빅데이터 분석**을 진행하였습니다. 수많은 단계 중 1단계 고객의 다음 달 수입 금액을 맞추는 모델을 개발하는 것이 저희 팀의 업무였습니다. 
#
 층화 추출을 통해 표본 데이터를 선정하여 고객의 거래내역을 하나하나 살펴보았고, 개인 간의 거래나 보험 해약금 등 불특정한 이벤트가 많이 발생한다는 것을 알게 되었습니다. 그렇기에 정기적 성질을 띄는 거래 데이터의 특성을 파악하여 거래내역의 정기성을 구별해 주는 알고리즘을 개발하였습니다. 이 알고리즘에 의해 정기거래로 분류된 데이터들에 대하여 시계열 분석(ARIMA)을 진행한 결과, 예측 성공률이 50%로 향상되는 성과를 이뤄냈습니다.
#
* 예측 성공률 : 고객의 예측값 전체 중에서 오차율 10% 이내로 맞춘 값들의 비율
> 예)

> 정답 : 100만 원 -> 모델이 90만 원 ~ 110만 원으로 예측할 경우 예측 성공

> 정답 : 2000만 원 -> 모델이 1800만 원 ~ 2200만 원으로 예측할 경우 예측 성공

### 주의 사항
1. 본 PPT 자료는 부산은행 내부 데이터 관련 자료를 포함하고 있던 자료입니다.

> 내부 데이터를 외부에 유출 시키면 안되기에, 부득이하게 내부 데이터 관련 자료는 PPT에서 삭제 및 마스킹 처리 하였습니다.

2. 부산은행은 내부에서 개발한 코드를 밖으로 유출 시키는 것은 금지되어 있습니다. 

> 따라서 코드를 첨부하지 못하였습니다.
