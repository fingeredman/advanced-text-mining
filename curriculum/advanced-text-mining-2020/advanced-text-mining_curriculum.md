# Curriculum: ADVANCED TEXT MINING

## Advanced Text Mining - 2020
> 이론수업을 통해 원리를 이해하고, 실습수업을 통해 적용 및 응용력을 기르는데 초점을 맞추어 강의를 진행합니다. 이론수업은 텍스트 마이닝 기본부터 머신러닝과 딥러닝을 활용한 고급 텍스트 마이닝기법까지 다루며, 실습수업은 이론수업에서 배운 내용을 Python 프로그래밍 언어를 활용하여 실제 적용해볼 수 있도록 진행합니다. 실습은 Python 기본문법을 반복적으로 다루고, 완성된 코드에 핵심 포인트를 수정하는 방식으로 진행하여 프로그래밍에 익숙하지 않아도 무리가 없도록 진행합니다. 과제는 주로 실무사례 케이스 스터디를 중심으로 진행되며, 학생들 간의 소통을 통한 학습효과 증진을 위해 그룹 텀프로젝트를 실시합니다.

> This course will cover the major techniques for mining and analyzing text data to extract potentially useful patterns and relationships.

#### WEEK 01. 텍스트 마이닝 개요
- 텍스트 마이닝 기본개념 및 유형
- 머신러닝/딥러닝을 활용한 텍스트 마이닝
- Python 3.7 & Jupyter Notebook
- 실습  
  > _W01-1. 실습환경: Python 3.7 & Jupyter Notebook & Google Colaboratory [(Colab)](./practice-note/week_01/W01-1_advanced-text-mining_colaboratory.ipynb)_  

#### WEEK 02. 텍스트 마이닝 사례연구
- 텍스트 마이닝 연구/실무 적용사례
- 텍스트 데이터를 위한 Python 프로그래밍
- 실습 
  > _W02-1. 텍스트 데이터를 다루기 위한 Python: 기본문법 [(Colab)](./practice-note/week_02/W02-1_text-mining-for-practice_python-basic.ipynb)_  
  > _W02-2. 텍스트 데이터를 다루기 위한 Python: 자료구조 [(Colab)](./practice-note/week_02/W02-2_text-mining-for-practice_python-data-structure.ipynb)_  
  > _W02-3. 텍스트 데이터를 다루기 위한 Python: 반복문과 조건문 [(Colab)](./practice-note/week_02/W02-3_text-mining-for-practice_python-conditional%26loop.ipynb)_  
  > _W02-4. 텍스트 데이터를 다루기 위한 Python: 함수와 파일입출력 [(Colab)](./practice-note/week_02/W02-4_text-mining-for-practice_python-function%26file.ipynb)_  
  > _W02-5. 텍스트 데이터를 다루기 위한 Python: 패턴인식과 정규식 [(Colab)](./practice-note/week_02/W02-5_text-mining-for-practice_python-regex.ipynb)_  

#### WEEK 03. 텍스트 데이터 수집 1
- 텍스트 데이터 유형 및 수집방법
- 웹 스크래핑 기초
- 머신러닝 기초
- 실습  
  > _W03-1. 데이터 크롤링 원리 이해하기 [(Colab)](./practice-note/week_03/W03-1_advanced-text-mining_python-crawling-intro.ipynb)_  
  > _W03-2. 정적페이지 수집하기: 실시간검색어, 영화댓글 [(Colab)](./practice-note/week_03/W03-2_advanced-text-mining_python-crawling-practice-1.ipynb)_  
  
#### WEEK 04. 텍스트 데이터 수집 2
- 웹 스크래핑 자동화 및 실전 활용법
- 텍스트 데이터 핸들링
- 실습  
  > _W04-1. 동적페이지 수집하기: 네이버 카페 게시글/댓글 [(Jupyter)](https://github.com/fingeredman/advanced-text-mining/blob/master/practice-note/week_04/W04-1_advanced-text-mining_python-crawling-practice-2.ipynb)_  
  > _W04-2. 동적페이지 수집하기: 인스타그램 해시태그 [(Jupyter)](https://github.com/fingeredman/advanced-text-mining/blob/master/practice-note/week_04/W04-2_advanced-text-mining_python-crawling-practice-3.ipynb)_    
  
#### WEEK 05. 텍스트 데이터 전처리
- 형태소분석과 개체명인식
- KoNLPy & NLTK & TEANAPS
- 실습  
  > _W05-1. 한국어 텍스트 데이터 전처리하기: KoNLPy & TEANAPS [(Colab)](./practice-note/week_05/W05-1_advanced-text-mining_python-korean-nlp.ipynb)_  
  > _W05-2. 영어 텍스트 데이터 전처리하기: NLTK & TEANAPS [(Colab)](./practice-note/week_05/W05-2_advanced-text-mining_python-english-nlp.ipynb)_  
  > _W05-3. 개체명인식 수행하기: TEANAPS [(Colab)](./practice-note/week_05/W05-3_advanced-text-mining_python-ner.ipynb)_

#### WEEK 06. 단어의 가중치를 표현하는 방법
- 단어빈도와 TF-IDF
- 단어 네트워크와 중심성
- 실습  
  > _W06-1. 단어빈도와 TF-IDF 계산하기 [(Colab)](./practice-note/week_06/W06-1_advanced-text-mining_python-tf-idf.ipynb)_  
  > _W06-2. 동시출현빈도 계산과 단어 네트워크 생성하기 [(Colab)](./practice-note/week_06/W06-2_advanced-text-mining_python-co-word.ipynb)_  
  
#### WEEK 07. 문서를 벡터로 표현하는 방법
- 단어 단위 임베딩
- 문장/문서 단위 임베딩
- 실습  
  > _W07-1. TEANAPS를 활용해 데이터 시각화하기 [(Colab)](./practice-note/week_07/W07-1_advanced-text-mining_python-visualization.ipynb)_  
  > _W07-2. 단어 임베딩 이해하기 [(Colab)](./practice-note/week_07/W07-2_advanced-text-mining_python-w2v.ipynb) [(Model Download)](https://drive.google.com/file/d/1qBMDr-WSMt-OG1IO2CXeqVqodKGYIxr2/view?usp=sharing)_  

#### WEEK 08. 텍스트 분석을 위한 딥러닝
- 시퀀스 모델링: 시퀀스 레이블링(CRF), RNN, LSTM
- 언어 모델링: Seq2Seq, Transformer 네트워크
- 과제: 보고서
- 실습  
  > _W08-1. TEANAPS 자연어처리 API 활용하기 [(Colab)](./practice-note/week_08/W08-1_advanced-text-mining_teanaps-nlp-api.ipynb)_  
  > _W08-2. TEANAPS를 활용한 자연어처리 [(Colab)](./practice-note/week_08/W08-2_advanced-text-mining_pre-processing.ipynb)_  
  
#### WEEK 09. 텍스트 분석 방법론 1
- CNN, RNN을 활용한 텍스트 데이터 분류
- Transformer 모델 기반 텍스트 감성분석
- 실습  
  > _W09-1. 문장의 의도 분류하기 [(Colab)](./practice-note/week_09/W09-1_advanced-text-mining_text-classification.ipynb)_  
  > _W09-2. 감성분석 활용하기 [(Colab)](./practice-note/week_09/W09-2_advanced-text-mining_sentiment-analysis.ipynb)_  
  
#### WEEK 10. 텍스트 분석 방법론 2
- 텍스트 유사도와 군집화
- 토픽모델링
- 실습  
  > _W10-1. K-평균 군집화와 LDA 토픽모델링을 활용해 문서 군집화하기 [(Colab)](./practice-note/week_10/W10-1_advanced-text-mining_text-clustering.ipynb)_  
  
#### WEEK 11. 텍스트 분석 방법론 3
- 문서요약: 추출요약과 생성요약
- 핵심 키워드 추출
- 실습  
  > _W11-1. 뉴스기사 요약하기: 추출요약 [(Colab)](./practice-note/week_11/W11-1_advanced-text-mining_text-summerization.ipynb)_  
  > _W11-2. 키워드 추출 모델 학습하기 [(Colab)](./practice-note/week_11/W11-2_advanced-text-mining_kea.ipynb)_  

#### WEEK 12. 텍스트 데이터를 활용한 예측 모델링
- 예측 모델링을 위한 자질추출
- 텍스트 분류문제를 예측에 활용하는 방법
- 실습  
  > _W12-1. 개봉직후 영화리뷰를 활용해 최종 관객수 예측하기 [(Colab)](./practice-note/week_12/W12-1_advanced-text-mining_python-movie-viewer-prediction.ipynb)_  
  
#### WEEK 13. 머신러닝/딥러닝 기반 대화 모델링
- Question & Answering
- Chat-bot: 질의응답부터 일상대화 까지
- 카카오 i 오픈빌더 
- 실습  
  > _W13-1. 카카오 i 오픈빌더를 활용해 Q/A 챗봇 구축하기_  

#### WEEK 14. 비즈니스를 위한 텍스트 분석
- 텍스트 분석을 활용한 연구/실무 케이스 스터디
  
#### WEEK 15. 텀프로젝트 그룹 발표 1 (`20 가을학기)
- 과제: 텀프로젝트 
- 발표주제  
  > _08조 :  CNN-Attention for Subject Classification of Tweets_  
  > _10조 : 텍스트마이닝 기법과 ARIMA 모델을 활용한 '배달의 민족' 앱 리뷰 주제 분류 및 이상치 탐지_  
  > _05조 : 도서 베스트셀러 예측 모델링_  
  > _12조 :  코로나-19로 인한 심리방역 현황 및 향후 대응방안을 위한 제언_  
  > _09조 :  뱅샐과 토스의 사용자는 무슨 생각을 할까?_  
  > _02조 :   재테크 관련 소셜데이터 분석을 통한 사회 초년생의 금융 생활 분석_  

#### WEEK 16. 텀프로젝트 그룹 발표 2 (`20 가을학기)
- 과제: 텀프로젝트 
- 발표주제  
  > _11조 : 플랫폼 별 콘텐츠 댓글 소비 행태 비교_  
  > _07조 : Exploring the mechanism of aging through Literature-based discovery(LBD)_  
  > _04조 : 소비자 리뷰와 휴대폰 판매량 간의 비교연구_  
  > _06조 : 웹툰 아마추어 작가의 게시글 분석_  
  > _01조 : 인플루언서의 인플루언서를 찾아서_  
  > _03조 : 토픽모델링 & 감성분석을 통한 간편걸제 앱 서비스 비교분석: Big-bank vs. Big-tech 중심으로_  

<br><br>
---
<center>ⓒ 2021. TEANAPS all rights reserved.</center>
