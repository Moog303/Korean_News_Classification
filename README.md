# Korean News Data Classificaiton
한국어 기사를 정치(0), 경제(1), 사회(2), 생활/문화(3), 세계(4), 기술/IT(5), 연예(6), 스포츠(7)로 분류되어 있는 1600개의 기사를 1280개의 샘플로 Train 하여 320개의 Test Set의 클래스를 추론.
----
## 1. Pre-Processing
- Mecab 한국어 형태소 분석기 사용
- 동사와 명사만 활용

## 2. Word Embedding
- Fast Text 사용
- 32707 Vocab size Word-Vector Model 생성

## 3. Model
- LSTM, GRU, CNN, CNN+LSTM, CNN+GRU 5가지 모델의 성능 비교
- Validation Ratio : 0.15
<img src="./img/modelEvaluation.png" style="width: 200px;">

## 4. Reference
1. 조휘열, et al. "컨볼루션 신경망 기반 대용량 텍스트 데이터 분류 기술." 한국정보과학회 학술발표논문집 (2015): 792-794.
2. Kim, Yoon. "Convolutional neural networks for sentence classification." arXiv preprint arXiv: 1408.5882 (2014).