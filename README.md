## Overview

네이버 영화 리뷰 데이터(Naver Sentiment Movie Corpus,NSMC)와 미드 Friends 대화 데이터를 이용하여 감정 분석을 진행 하였습니다.

NSMC 데이터는 bert-base-multilingual-cased 모델과 monologg/koelectra-small-v2-discriminator 모델을 사용하여 비교 하였습니다.
Friends는 bert-base-multilingual-cased 모델을 이용하였습니다.


## Data

네이버 영화리뷰 감정분석 데이터 다운로드

```
git clone https://github.com/e9t/nsmc.git
```

Friends 데이터 다운로드

```
http://doraemon.iis.sinica.edu.tw/emotionlines/download.html
```

## Model

* bert-base-multilingual-cased

* monologg/koelectra-small-v2-discriminator

## environment

* Colab 에서 실험 하였고, GPU 를 사용

## Reference

[KoCharELECTRA](https://github.com/monologg/KoCharELECTRA)

[https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP](https://colab.research.google.com/drive/1JZ-pXlmgRIYHm8yPLYY68Q28l9OYAL6H?usp=sharing)

[https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP](https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP)

