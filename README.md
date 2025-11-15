<br>
<br>

> 데이터로 더 나은 사용자 경험을 설계하는 AI 엔지니어입니다.  
"어떻게 하면 사용자에게 더 나은 경험을 줄 수 있을까?" 라는 질문에 데이터로 답을 찾습니다.  
16번의 AI 프로젝트를 통해 문제를 해결하고 성과를 창출해왔습니다.  
기술적 도전을 즐기며 동료와 함께 성장하는 것을 추구합니다. 🚀  

<br>
<br>

## 관심 분야
- **RecSys** &nbsp; ( Recommender System )
- **NLP** &nbsp; ( Natural Language Processing )
- **GNN** &nbsp; ( Graph Neural Network )
- **LLM** &nbsp; ( Large Language Model )

<br>
<br>

## 대표 프로젝트
### 음악 추천 서비스 Au-Dionysos
사용자의 요청 사항에 대해 ChatGPT를 활용하여 파악하고, 사용자의 요청 사항과 취향을 동시에 반영하는 GraphSAGE 기반 음악 추천 서비스  
> **RecSys** : Hybrid Recommender System, Feature Embedding, GraphSAGE  
> **NLP** : Textual Tag Extraction, Prompt Engineering, ChatGPT  
- 유형 : 네이버 부스트캠프 AI Tech 6기 프로젝트
- 기간 : 2024.01 ~ 2024.03 (3개월)
- 팀 구성 : 6인 프로젝트 (PM 1명, 추천 2명, 백엔드 2명, 프론트엔드 1명)
- 역할 : 추천 파트 리드 (추천 파이프라인 설계, GraphSAGE 모델 구현 및 학습, 추천 시스템 실험 및 평가)
- 목표 : 사용자의 요청 사항과 취향에 최적화된 음악 추천 서비스 개발 및 배포
- 기술
  - GraphSAGE 모델을 통해 Interaction 정보와 Meta 정보를 통합 학습하여 추천 정확도와 다양성 향상
  - ChatGPT 프롬프트 엔지니어링을 활용하여 사용자의 요청 사항을 키워드로 추출
- 성과
  - 음악 추천 서비스의 **사용자 만족도를 41%에서 77%로 36%p 향상**
  - Two-Stage 추천 파이프라인 설계를 통해 **서비스 응답 시간을 7초에서 2.7초로 61% 단축**
  - LastFM 데이터(Interaction 중심)는 CF 모델로, Spotify 데이터(Meta 중심)는 CBF 모델로 학습하여 **취향과 다양성 모두 반영**

&nbsp;&nbsp; <a href="https://github.com/JaeGwon-Lee/level2-3-recsys-finalproject-recsys-03"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a> <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%9D%8C%EC%95%85-%EC%B6%94%EC%B2%9C-%EC%84%9C%EB%B9%84%EC%8A%A4-Au-Dionysos"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a>

<br>

### GNN 기반 추천 시스템에서 텍스트 부가 정보의 활용 연구
텍스트 부가 정보를 그래프 임베딩의 초기값으로 활용하여 지식 그래프와 GNN 기반 추천 시스템의 콜드 스타트 성능을 68% 향상시킨 연구  
> **RecSys** : Knowledge Graph, Graph Neural Network, Hybrid Recommender System, KGAT  
> **NLP** : Text Embedding, Sentence-BERT
- 유형 : 수학/통계학과 데이터사이언스 전공 석사 학위 논문
- 기간 : 2023.01 ~ 2023.07 (7개월)
- 목표 : 텍스트 부가 정보 임베딩을 활용하여 GNN 기반 추천 모델의 성능 향상 및 Cold Start 문제 완화
- 기술 : KGAT 기반의 추천 시스템 개발 (지식 그래프를 통해 부가 정보 활용, GNN을 통해 지식 그래프 학습)
- 제안 방법 : Sentence-BERT 모델로 부가 정보를 텍스트 임베딩하고 그래프 임베딩의 초기값으로 사용하여 KGAT 모델 개선
- 성과
  - 텍스트 임베딩을 추가했을 때, 기존 KGAT 대비 **NDCG 16%, Recall 25% 향상**
  - Cold Start 상황을 가정한 실험에서 기존 KGAT 대비 **NDCG 68%, Recall 65% 향상**

&nbsp;&nbsp; <a href="https://www.riss.kr/link?id=T16834777"><img src="https://img.shields.io/badge/Paper-FF9900?style=flat&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/KGAT-with-TextEmbedding"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>

<br>

### 키워드 추출을 활용한 지식 그래프 기반 추천 시스템 연구
BERT 기반 모델을 통해 추출한 가사 키워드를 부가 정보로 활용하여 지식 그래프와 RNN 기반 음악 추천 시스템의 성능을 13% 향상시킨 연구  
> **RecSys** : Knowledge Graph, Recurrent Neural Network, Hybrid Recommender System, KPRN  
> **NLP** : Keyword Extraction, Sentence-BERT  
- 유형 : 한국데이터정보과학회 KCI 우수 등재 출판 논문
- 기간 : 2022.01 ~ 2022.10 (10개월)
- 목표 : 음악 추천 시스템의 성능 향상을 위해 노래의 가사 정보를 부가 정보로 활용하는 방법 제시
- 기술 : KPRN 기반의 추천 시스템 개발, 60만개의 가사 데이터 크롤링, 지식 그래프 구축
- 제안 방법 : Sentence-BERT 모델로 가사 키워드를 추출하여 지식 그래프의 품질을 향상시킴으로써 KPRN 모델 개선
- 성과
  - 가사 키워드를 통해 지식 그래프의 품질을 향상시켰을 때, 기존 KPRN 대비 **NDCG 13% 향상**
  - 긴 텍스트를 추천 시스템의 부가 정보로 활용하여 **Cold Start 문제 완화**
  - 효율적인 크롤링 구조 설계와 적절한 지연 시간 설정으로 **60만개의 가사 데이터 구축**

&nbsp;&nbsp; <a href="http://www.kdiss.org/journal/view.html?uid=2864&&vmd=Full"><img src="https://img.shields.io/badge/Paper-FF9900?style=flat&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/Music-KPRN-with-Lyrics-Keyword"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>

<br>

### POSTECH OIBC 태양광 발전량 예측
데이터 수집, 분석, 피처 엔지니어링을 통해 최적의 데이터셋을 구축하여 SVM 모델의 성능을 향상시킨 프로젝트  
> **Data** : Data Analytics, Data Preprocessing, Web Crawling, API Data Collection  
> **Feature Engineering** : Feature Selection, Derived Variables, Auto-Regressive Variables  
> **Machine Learning** : SVM, Grid Search  
- 유형 : POSTECH OIBC 태양광 발전량 예측 경진대회
- 기간 : 2020.07 (1개월)
- 팀 구성 : 3인 프로젝트
- 역할 : 데이터 수집/전처리/분석, 파생변수 생성, SVM 모델 실험 및 평가
- 기술
  - Open-API와 크롤링을 통한 데이터 수집, 데이터 분석과 시각화
  - 계절별/날씨별 파생변수와 자기회귀 변수를 활용하여 학습 데이터 품질 향상
  - 미래 일사량을 먼저 예측하고 예측한 일사량을 활용하여 미래 발전량 예측
  - 반복적인 변수 선택 실험과 그리드 서치를 활용하여 SVM 모델 튜닝
- 성과
  - 데이터 수집, 분석, 피처 엔지니어링으로 **머신러닝 모델 학습에 적합한 데이터셋 구축**
  - 변수 선택 실험과 그리드 서치를 활용하여 **SVM 모델 성능 향상**
  - **우수상(2위) 수상**

&nbsp;&nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%83%9C%EC%96%91%EA%B4%91-%EB%B0%9C%EC%A0%84%EB%9F%89-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/Projects/tree/main/%ED%83%9C%EC%96%91%EA%B4%91%20%EB%B0%9C%EC%A0%84%EB%9F%89%20%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>

<br>
<br>

## 프로젝트 목록
#### 2024
- **텍스트 기반 초개인화 음악 추천 서비스 [GraphSAGE]** <a href="https://github.com/JaeGwon-Lee/level2-3-recsys-finalproject-recsys-03"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a> <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%9D%8C%EC%95%85-%EC%B6%94%EC%B2%9C-%EC%84%9C%EB%B9%84%EC%8A%A4-Au-Dionysos"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a>
- **영화 추천 프로젝트 [LightGCN]** &nbsp; <a href="https://github.com/JaeGwon-Lee/level2-movierecommendation-recsys-03"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
- **DKT(Deep Knowledge Tracing) 프로젝트 [LightGCN]** &nbsp; <a href="https://github.com/JaeGwon-Lee/level2-dkt-recsys-03"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>

#### 2023
- **책 평점 예측 프로젝트 [DeepCoNN, CatBoost]** &nbsp; <a href="https://github.com/JaeGwon-Lee/level1-bookratingprediction-recsys-04"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
- **텍스트 부가 정보 활용을 위한 그래프 신경망 기반 추천 시스템 [KGAT, Sentence-BERT]** &nbsp; <a href="https://www.riss.kr/link?id=T16834777"><img src="https://img.shields.io/badge/Paper-FF9900?style=flat&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/KGAT-with-TextEmbedding"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>

#### 2022
- **가사 키워드 추출을 활용한 지식 그래프 기반 음악 추천 시스템 [KPRN, Sentence-BERT]** &nbsp; <a href="http://www.kdiss.org/journal/view.html?uid=2864&&vmd=Full"><img src="https://img.shields.io/badge/Paper-FF9900?style=flat&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/Music-KPRN-with-Lyrics-Keyword"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
- **BK21 FOUR 산학협력 버섯 질병 이미지 분류 경진대회 [ResNet]**
- **KRX 금융 빅데이터 활용 경진대회 - 뉴스 민감 지수로 투자하기 [FinBERT]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%89%B4%EC%8A%A4-%EB%B3%80%EB%8F%99%EC%84%B1-%EC%A7%80%EC%88%98-%EC%82%B0%EC%B6%9C%EC%9D%84-%EC%9C%84%ED%95%9C-%EA%B2%BD%EC%A0%9C-%EB%89%B4%EC%8A%A4-%EA%B0%90%EC%84%B1-%EB%B6%84%EC%84%9D"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a> <a href="https://dacon.io/competitions/official/235914/overview/description"><img src="https://img.shields.io/badge/Dacon-326CAC?style=flat&logoColor=white"/></a> <a href="https://dacon.io/codeshare/5550"><img src="https://img.shields.io/badge/Code Share-326CAC?style=flat&logoColor=white"/></a>

#### 2021
- **뉴스 요약 프로젝트 [KoBertSum]**
- **Dacon 주차 수요 예측 AI 경진대회 [CatBoost]** &nbsp; <a href="https://dacon.io/competitions/official/235745/overview/description"><img src="https://img.shields.io/badge/Dacon-326CAC?style=flat&logoColor=white"/></a>
- **시계열 데이터의 이미지화를 통한 CNN 기반 KOSPI 주가지수 예측 프로젝트 [ResNet]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-Kospi-%EC%A3%BC%EA%B0%80%EC%A7%80%EC%88%98-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a>
- **Dacon 태양광 발전량 예측 경진대회 [XGBoost]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-Dacon-%ED%83%9C%EC%96%91%EA%B4%91-%EB%B0%9C%EC%A0%84%EB%9F%89-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a> &nbsp; <a href="https://dacon.io/competitions/official/235680/overview/description"><img src="https://img.shields.io/badge/Dacon-326CAC?style=flat&logoColor=white"/></a>

#### 2020
- **Kaggle 타이타닉 예측 프로젝트 [Ensemble]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%83%80%EC%9D%B4%ED%83%80%EB%8B%89-%EC%83%9D%EC%A1%B4%EC%9E%90-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a> <a href="https://www.kaggle.com/competitions/titanic/overview"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logoColor=white"/></a>
- **POSTECH OIBC 태양광 발전량 예측 경진대회 [SVM]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%83%9C%EC%96%91%EA%B4%91-%EB%B0%9C%EC%A0%84%EB%9F%89-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/Projects/tree/main/%ED%83%9C%EC%96%91%EA%B4%91%20%EB%B0%9C%EC%A0%84%EB%9F%89%20%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
- **농산물 시세 예측 프로젝트 [ARIMA]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%86%8D%EC%82%B0%EB%AC%BC-%EC%8B%9C%EC%84%B8-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a> <a href="https://github.com/JaeGwon-Lee/Projects/tree/main/%EB%86%8D%EC%82%B0%EB%AC%BC%20%EC%8B%9C%EC%84%B8%20%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>

#### 2019
- **COMPAS 김해시 화재 발생 예측 경진대회 [RandomForest]** &nbsp; <a href="https://velog.io/@jaegwon-lee/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%99%94%EC%9E%AC-%EB%B0%9C%EC%83%9D-%EC%98%88%EC%B8%A1"><img src="https://img.shields.io/badge/Blog-20C997?style=flat&logo=Velog&logoColor=white"/></a>

<br>

