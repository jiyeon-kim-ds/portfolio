# 습관형성도움 어플리케이션 이용자 데이터 자연어 처리

2021.04 ~ 2021.05 / 기업 협업 / **개인정보 보호를 위해 프로젝트 링크를 제공하지 않습니다.**

### 요약

- 습관형성을 도와주는 어플리케이션 한국어 이용자들의 텍스트 데이터를 자연어 처리하고 Word2Vec으로 유사성 있는 습관을 찾아 본다.

### 주요 업무

[scikit-learn, gensim, pandas, 한국어 자연처 처리]

- pandas 라이브러리를 이용한 데이터 전처리

- 다양한 언어 중 한국어 데이터만을 선택하여 한국어에 맞는 텍스트 데이터 전처리
- 한국어 데이터를 토큰화, 벡터화하고 Word2Vec을 사용하여 유사성 있는 습관 찾기

# B2C 대출 상환 여부 예측 머신러닝 모델 구현

2021.03 ~ 2021.04 / 2인 협업 / [Github Link](https://github.com/jiyeon-kim-ds/loan-default-prediction-model)

### 요약

- Home Credit(비은행 금융 기관) 이용자의 데이터를 이용하여 대출 상환 여부를 판단하는 다양한 머신러닝 모델 구현
- Home Credit 데이터셋을 바탕으로 경기도의 기본대출 정책을 시행함에 있어 유의점을 알아 본다.

### 주요 업무

​	[데이터 전처리, 특성 공학(Feature Engineering), 데이터 탐색, 시각화, 머신러닝 모델 설계]

- 데이터 전처리 및 특성 공학
- XGBClassifier 머신러닝 모델 설계
- SHAP value, Permutation Feature Importance 을 통한 feature의 중요도 파악
- Randomized Search를 통한 Parameter Tuning
- 데이터 탐색 및 시각화
- 성과 : 데이터 전처리 및 특성 공학을 실행하고 머신러닝 모델 설계를 해볼 수 있었다. 또한, 데이터 탐색 및 시각화를 통해 인사이트를 도출할 수 있었다.

# 음악 아티스트의 군집화(clustering) 및 텍스트 데이터(NLP)를 활용한 아티스트 분류

2021.02 ~ 2021.03 / 개인 프로젝트 /  [Github Link](https://github.com/jiyeon-kim-ds/artist-classifier)

요약

- 사용자의 음악 재생 목록을 이용해 아티스트 별로 군집화(clustering)하여 임의의 라벨(label)을 생성하고, 1. 음악 평론글 텍스트 데이터와 2. 음악적 특성을 수치화한 데이터를 input으로 하는 두 가지 모델을 설계하여 성능을 비교해본다.

### 주요 업무

​	[자연어 처리(NLP), 데이터 전처리, 군집화, 머신러닝 모델 설계]

- 음악 평론 텍스트 데이터의 자연어 처리
- 머신러닝(Random Forest) 모델 설계
- Surprise 라이브러리를 사용한 군집화
- 데이터의 전처리와 특성공학
- 성과 : 여러 출처의 데이터를 병합, 영어 텍스트 데이터의 전처리와 임베딩(embedding), 머신러닝 모델 설계 등을 해볼 수 있었다.

# flask와 Spotify API를 이용한 음악 취향 예측 웹 어플리케이션 만들기

2020.12 ~ 2020.12 / 개인 프로젝트 /  [Github Link](https://github.com/jiyeon-kim-ds/music-tastes-web-app) / [web app link](https://dsft-spotify-app.herokuapp.com/)

요약

- flask와 SQLite을 사용하여 Spotify의 데이터를 불러와 음악 취향을 예측해주는 웹 어플리케이션을 만들어 본다.

### 주요 업무

​	[flask, SQLite, SQLAlchemy, Spotify API, pandas]

- flask와 SQLite를 사용하여 웹 어플리케이션의 CRUD 기능 구현 및 리모트 데이터 베이스 관리
- Spotify API를 사용한 개인 플레이리스트 데이터 불러오기
