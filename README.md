## Overview

네이버 영화 리뷰 데이터(Naver Sentiment Movie Corpus,NSMC)와 미드 Friends 대화 데이터를 이용하여 감정 분석을 진행 하였습니다.

NSMC 데이터는 bert-base-multilingual-cased 모델과 monologg/koelectra-small-v2-discriminator 모델을 사용하여 비교 하였습니다.
Friends는 bert-base-multilingual-cased 모델을 이용하였습니다.

## 실행환경

* Google colab 에서 진행

* 런타임 유형 하드웨어 가속기 GPU 사용

* pytorch 이용

## NSMC(Naver Sentiment Movie Corpus) 감정 분석 

1. 소스 코드

>> NSMC_KoELECTRA.ipynb : KoELECTRA 모델 사용

>> NSMC_Bert : BERT base multilingual 모델 사용

2. 실행 방법
>> 1) 모든 셀을 차례대로 실행
>> 2) 데이터 전처리 및 모델 load
>> 3) Traning, Test 
>> 4) Kggle 결과 확인
  
3. 참고 문헌 및 코드

>> [KoELECTRA](https://github.com/monologg/KoELECTRA)

>> [https://colab.research.google.com/drive/1JZ-pXlmgRIYHm8yPLYY68Q28l9OYAL6H?usp=sharing](https://colab.research.google.com/drive/1JZ-pXlmgRIYHm8yPLYY68Q28l9OYAL6H?usp=sharing)

>> [https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP](https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP)



## Friends 영화 대본 감정 분석

1. 소스 코드

>> Friends_electra.ipynb :  BERT base multilingual 모델 사용

2. 실행 방법
>> 1) 모든 셀을 차례대로 실행
>> 2) 데이터 전처리 및 모델 load
>> 3) Traning, Test 
>> 4) Kggle 결과 확인
  
3. 참고 문헌 및 코드

>> [https://www.secmem.org/blog/2020/07/19/Sentiment-Analysis/] (https://www.secmem.org/blog/2020/07/19/Sentiment-Analysis/)
