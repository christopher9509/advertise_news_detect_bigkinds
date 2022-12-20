# Bigkinds_news_bigdata_hackerton_2022

## Main
<img src="https://github.com/christopher9509/advertise_news_detect_bigkinds/blob/main/plot/main.png" alt="drawing" width="900"/>


## Project
- Title: Ko-BERT 기반 기사형 광고 탐지 알고리즘, AN-DAE(Advertorial News-Detection Artificial modEl)
- prize : Excellence Award(3rd)
- Category: Classification, News data, NLP
- Tool Used: python, pandas, sklearn, pytorch

## Data
- Data : News data
- Period :  22.05.11 ~ 22.09.20
- Samples : Total 10,332
- From : bigkinds

## Evaluation
- Metric: Accuracy
- KoBERT : 0.5210
- Bert-base-multilingual-cased : 0.8199

## Insight
- 심사위원님들의 comment 중, 광고성 기사와 기사형 광고는 엄밀히 다르고 이에 대한 분류 기준이 명확해야한다고 함
- 특정 도메인에서 DL/ML을 활용하여 모델을 설계할 때, 데이터 단의 엄밀한 분석(Domain-knowledge)가 필요하다는 것을 느낌
- KoBERT 보다 Bert-base-multilingual-cased가 더 잘 나왔는데, 이유는 KoBERT가 업데이트가 안된지 좀 오래된 모델이기도 하고, pre-trained weight이 우리가 예측하고자한 문제랑 다르기 때문에 학습 데이터 양이 절대적으로 큰 BERT가 더 우수한 성능이 나오지 않았나 사료됨 
