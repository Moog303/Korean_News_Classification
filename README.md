# Korean News Data Classificaiton
----
## 1. Pre-Processing
- Mecab 한국어 형태소 분석기 사용
- 동사와 명사만 활용

## 2. Word Embedding
- Fast Text 사용
- 32707 Vocab size Word-Vector Model 생성

## 3. Model
- LSTM, GRU, CNN, CNN+LSTM, CNN+GRU 5가지 모델의 성능 비교
- <img src="./img/modelEvaluation.png" style="width: 200px;">

## 4. Reference
1. 조휘열, et al. "컨볼루션 신경망 기반 대용량 텍스트 데이터 분류 기술." 한국정보과학회 학술발표논문집 (2015): 792-794.
2. Kim, Yoon. "Convolutional neural networks for sentence classification." arXiv preprint arXiv: 1408.5882 (2014).