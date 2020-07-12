# ADVANCED TEXT MINING

> 본 강의는 비정형 데이터 중 텍스트 데이터에 집중하여, 연구/실무에서 활용 가능한 다양한 텍스트 마이닝 기법에 대해 다룹니다. 전통적인 텍스트 마이닝 기법부터 머신러닝/딥러닝을 활용한 분석까지 실제 적용사례와 함께 이해하고 실습합니다. 한국어 텍스트에 집중하고 프로그래밍 과정을 최대한 단순화하여, 빠르게 텍스트 마이닝 기법을 학습하고 연구/실무에 적용해 볼 수 있도록 강의 내용을 구성하였습니다.

- 본 자료는 텍스트 마이닝을 활용한 연구 및 강의를 위한 목적으로 제작되었습니다.
- 본 자료를 강의 목적으로 활용하고자 하시는 경우 꼭 아래 메일주소로 연락주세요.
- 본 자료에 대한 허가되지 않은 배포를 금지합니다.
- 강의, 저작권, 출판, 특허, 공동저자에 관련해서는 문의 바랍니다.
- **Contact : FINGEREDMAN(fingeredman@gmail.com)**

---
## Notice!
> - 2020년 8월 부터 강의자료가 순차적으로 업로드될 예정입니다.
> - 본 자료는 2020년도 가을학기 `~ <텍스트 마이닝: 비정형 데이터 분석>` 강의자료로 활용되고 있습니다.

---
## Curriculum
> 이론수업을 통해 원리를 이해하고, 실습수업을 통해 적용 및 응용력을 기르는데 초점을 맞추어 강의를 진행합니다. 이론수업은 텍스트 마이닝 기본부터 머신러닝과 딥러닝을 활용한 고급 텍스트 마이닝기법까지 다루며, 실습수업은 이론수업에서 배운 내용을 Python 프로그래밍 언어를 활용하여 실제 적용해볼 수 있도록 진행합니다. 실습은 Python 기본문법을 반복적으로 다루고, 완성된 코드에 핵심 포인트를 수정하는 방식으로 진행하여 프로그래밍에 익숙하지 않아도 무리가 없도록 진행합니다. 과제는 주로 실무사례 케이스 스터디를 중심으로 진행되며, 학생들 간의 소통을 통한 학습효과 증진을 위해 그룹 텀프로젝트를 실시합니다.

> This course will cover the major techniques for mining and analyzing text data to extract potentially useful patterns and relationships.

#### WEEK 01. 텍스트 마이닝 개요
- 텍스트 마이닝 기본개념 및 유형
- 머신러닝/딥러닝을 활용한 텍스트 마이닝
- Python 3.7 & Jupyter Notebook
- 실습  
  > _W01-1. 실습환경: Python 3.7 & Jupyter Notebook & Google Colaboratory_  
  > _W01-2. 텍스트 데이터를 다루기 위한 Python: 기본문법 [(Colab)]()_  
  > _W01-3. 텍스트 데이터를 다루기 위한 Python: 자료구조 [(Colab)]()_  
  > _W01-4. 텍스트 데이터를 다루기 위한 Python: 반복문과 조건문 [(Colab)]()_  
  > _Assignment 01: 소설에서 가장 많이 쓰이는 단어 알아보기 [(Colab)]()_ 

#### WEEK 02. 텍스트 마이닝 사례연구
- 텍스트 마이닝 연구/실무 적용사례
- 텍스트 데이터를 위한 Python 프로그래밍
- 과제: 텀프로젝트 조편성
- 실습  
  > _W02-1. 텍스트 데이터를 다루기 위한 Python: 함수와 파일입출력 [(Colab)]()_  
  > _W02-2. 텍스트 데이터를 다루기 위한 Python: 패턴인식과 정규식 [(Colab)]()_  
  > _Assignment 02-1: 트위터에서 전화번호 추출하기 [(Colab)]()_  
  > _Assignment 02-2: 인스타그램 게시글에서 해시태그 가져오기 [(Colab)]()_  

#### WEEK 03. 텍스트 데이터 수집 1
- 텍스트 데이터 유형 및 수집방법
- 웹 스크래핑 기초
- 실습  
  > _W03-1. 데이터 크롤링 원리 이해하기 [(Colab)]()_  
  > _W03-2. 정적페이지 수집하기: 실시간검색어, 영화댓글 [(Colab)]()_  
  > _Assignment 03: 대량의 영화댓글 수집하기 [(Colab)]()_  
  
#### WEEK 04. 텍스트 데이터 수집 2
- 웹 스크래핑 자동화 및 실전 활용법
- 텍스트 데이터 핸들링
- 과제: 텀프로젝트 기획서
- 실습  
  > _W04-1. 동적페이지 수집하기: 카페 게시글 [(Jupyter)]()_  
  > _W04-2. 동적페이지 수집하기: 해시태그 [(Jupyter)]()_  
  
#### WEEK 05. 텍스트 데이터 전처리
- 형태소분석과 개체명인식
- KoNLPy & NLTK & TEANAPS
- 실습  
  > _W05-1. 한국어 텍스트 데이터 전처리하기: KoNLPy [(Colab)]()_  
  > _W05-2. 영어 텍스트 데이터 전처리하기: NLTK [(Colab)]()_

#### WEEK 06. 단어의 가중치를 표현하는 방법
- 단어빈도와 TF-IDF
- 단어 네트워크와 중심성
- 실습  
  > _W06-1. 단어빈도와 TF-IDF 계산하기 [(Colab)]()_  
  > _W06-2. 단어 가중치를 활용해 워드클라우드 생성하기 [(Colab)]()_  
  > _W06-3. 동시출현빈도 계산과 단어 네트워크 생성하기 [(Colab)]()_  

#### WEEK 07. 문서를 벡터로 표현하는 방법
- 단어 단위 임베딩
- 문장/문서 단위 임베딩
- 실습  
  > _W07-1. 뉴스기사 텍스트 데이터를 벡터로 표현하기_  
  > _W07-2. 위키피디아 텍스트 데이터를 벡터로 표현하기_

#### WEEK 08. 텍스트 분석을 위한 딥러닝
- 시퀀스 모델링: 시퀀스 레이블링(CRF), RNN, LSTM
- 언어 모델링: Seq2Seq, Transformer 네트워크
- 과제: 보고서
- 실습  
  > _W08-1. TBU_  

#### WEEK 09. 텍스트 분석 방법론 1
- 텍스트 유사도와 군집화
- 토픽모델링
- 실습  
  > _W09-1. 뉴스기사 군집화로 이슈 모아보기 [(Colab)]()_  
  > _W09-2. 뉴스기사에서 주제 찾아내기 [(Colab)]()_  
  
#### WEEK 10. 텍스트 분석 방법론 2
- CNN, RNN을 활용한 텍스트 데이터 분류
- Transformer 모델 기반 텍스트 감성분석
- 실습  
  > _W10-1. 사전기반과 머신러닝 기반의 감성분석_  

#### WEEK 11. 텍스트 분석 방법론 3
- 문서요약: 추출요약과 생성요약
- 핵심 키워드 추출
- 실습  
  > _W11-1. 문서요약 알고리즘 활용하기: TextRank, LSA [(Colab)]()_  
  > _W11-2. 키워드추출 알고리즘 활용하기: PKEA, RKEA_

#### WEEK 12. 텍스트 데이터를 활용한 예측 모델링
- 예측 모델링을 위한 자질추출
- 텍스트 분류문제를 예측에 활용하는 방법
- 실습  
  > _W12-1. 뉴스기사를 활용한 KOSPI 등락여부 예측하기_
  
#### WEEK 13. 머신러닝/딥러닝 기반 대화 모델링
- Question & Answering
- Chat-bot: 질의응답부터 일상대화 까지
- 실습  
  > _W13-1. TBU_  
  
#### WEEK 14. 비즈니스를 위한 텍스트 분석
- 실습  
  > _W14-1. TBU_  
  
#### WEEK 15. 텀프로젝트 그룹 발표
- 과제: 텀프로젝트 
- 발표주제  
  > _1조 : TBU_  
  > _2조 : TBU_  
  > _3조 : TBU_  
  > _4조 : TBU_  
  > _5조 : TBU_  
  > _6조 : TBU_  
  > _7조 : TBU_  
  > _8조 : TBU_  
  
---
## References
> 본 강의자료는 아래 문헌들을 참고해 구성되었습니다.
- A Byte of Python [(Link)](https://python.swaroopch.com/)
- 패스트캠퍼스 <텍스트 분석 유치원 1기~5기> 실습자료 [(Link)](https://www.fastcampus.co.kr/data_class_textmining/)
- 텍스트 마이닝(Text Mining), 송민 지음, 청람출판사, 2017
- 파이썬을 이용한 머신러닝, 딥러닝 실전 개발 입문, 쿠지라 히코우즈쿠에, 위키북스, 2017
- Natural Language Processing with PyTorch, 김기현 [(Link)](https://kh-kim.gitbook.io/natural-language-processing-with-pytorch/)

---
## Update History
> 2020.07.05. 목차 구성 수정  
> 2020.06.07. 목차 구성 수정  
> 2020.05.24. 목차 구성 수정  


<br><br>
---
<center>ⓒ 2020. FINGEREDMAN all rights reserved.</center>
