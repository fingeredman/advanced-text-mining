# ADVANCED TEXT MINING

> 본 강의는 비정형 데이터 중 텍스트 데이터에 집중하여, 연구/실무에서 활용 가능한 다양한 텍스트 마이닝 기법에 대해 다룹니다. 전통적인 텍스트 마이닝 기법부터 머신러닝/딥러닝을 활용한 분석까지 실제 적용사례와 함께 이해하고 실습합니다. 한국어 텍스트에 집중하고 프로그래밍 과정을 최대한 단순화하여, 빠르게 텍스트 마이닝 기법을 학습하고 연구/실무에 적용해 볼 수 있도록 강의 내용을 구성하였습니다.

- 본 자료는 텍스트 마이닝을 활용한 연구 및 강의를 위한 목적으로 제작되었습니다.
- 본 자료를 강의 목적으로 활용하고자 하시는 경우 꼭 아래 메일주소로 연락주세요.
- 본 자료에 대한 허가되지 않은 배포를 금지합니다.
- 강의, 저작권, 출판, 특허, 공동저자에 관련해서는 문의 바랍니다.
- **Contact : ADMIN(admin@teanaps.com)**

---
## Notice!
> - 강의자료 및 실습자료가 2021년 10주차 과정으로 개편되어 업로드되며, 지난 강의자료는 [`curriculum`](./curriculum/advanced-text-mining-2020/advanced-text-mining_curriculum.md#curriculum-advanced-text-mining)에서 확인 가능합니다.
> - 본 자료는 2019년 부터 연세대학교 텍스트 마이닝(비정형 데이터 분석) 강의자료로 활용되고 있습니다.

---
## Curriculum
> 이론수업을 통해 원리를 이해하고, 실습수업을 통해 적용 및 응용력을 기르는데 초점을 맞추어 강의를 진행합니다. 이론수업은 텍스트 마이닝 기본부터 머신러닝과 딥러닝을 활용한 고급 텍스트 마이닝기법까지 다루며, 실습수업은 이론수업에서 배운 내용을 Python 프로그래밍 언어를 활용하여 실제 적용해볼 수 있도록 진행합니다. 실습은 Python 기본문법을 반복적으로 다루고, 완성된 코드에 핵심 포인트를 수정하는 방식으로 진행하여 프로그래밍에 익숙하지 않아도 무리가 없도록 진행합니다. 과제는 주로 실무사례 케이스 스터디를 중심으로 진행되며, 학생들 간의 소통을 통한 학습효과 증진을 위해 그룹 텀프로젝트를 실시합니다.

> This course will cover the major techniques for mining and analyzing text data to extract potentially useful patterns and relationships.

#### WEEK 01. 텍스트 마이닝 개요
- 텍스트 마이닝 기본개념 및 유형
- 머신러닝/딥러닝을 활용한 텍스트 마이닝
- Python 3.7 & Jupyter Notebook
- 실습  
  > _W01-1. 실습환경: Python 3.x & Jupyter Notebook & Google Colaboratory [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_01/W01-1_advanced-text-mining_colaboratory.ipynb)_  

#### WEEK 02. 텍스트 마이닝 사례연구
- 텍스트 마이닝 연구/실무 적용사례
- 텍스트 데이터를 위한 Python 프로그래밍
- 실습  
  > _W02-1. 텍스트 데이터를 다루기 위한 Python: 기본문법 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_02/W02-1_text-mining-for-practice_python-basic.ipynb)_  
  > _W02-2. 텍스트 데이터를 다루기 위한 Python: 자료구조 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_02/W02-2_text-mining-for-practice_python-data-structure.ipynb)_  
  > _W02-3. 텍스트 데이터를 다루기 위한 Python: 반복문과 조건문 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_02/W02-3_text-mining-for-practice_python-conditional%26loop.ipynb)_  
  > _W02-4. 텍스트 데이터를 다루기 위한 Python: 함수와 파일입출력 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_02/W02-4_text-mining-for-practice_python-function%26file.ipynb)_  
  > _W02-5. 텍스트 데이터를 다루기 위한 Python: 패턴인식과 정규식 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_02/W02-5_text-mining-for-practice_python-regex.ipynb)_  

#### WEEK 03. 텍스트 데이터 수집 1
- 텍스트 데이터 유형 및 수집방법
- 웹 스크래핑 기초
- 머신러닝 기초
- 실습  
  > _W03-1. 데이터 크롤링 원리 이해하기 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_03/W03-1_advanced-text-mining_python-crawling-intro.ipynb)_  
  > _W03-2. 정적페이지 수집하기: 실시간검색어, 영화댓글 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_03/W03-2_advanced-text-mining_python-crawling-practice-1.ipynb)_   
  
#### WEEK 04. 텍스트 데이터 수집 2
- 웹 스크래핑 자동화 및 실전 활용법
- 텍스트 데이터 핸들링
- 실습  
  > _W04-1. 동적페이지 수집하기: 네이버 카페 게시글/댓글_  
  > _W04-2. 동적페이지 수집하기: Apple 앱스토어 _    
  
#### WEEK 05. 텍스트 데이터 전처리
- 형태소분석과 개체명인식
- KoNLPy & NLTK & TEANAPS
- 실습  
  > _W05-1. 한국어 텍스트 데이터 전처리하기: KoNLPy & TEANAPS [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_05/W05-1_advanced-text-mining_python-korean-nlp.ipynb)_  
  > _W05-2. 영어 텍스트 데이터 전처리하기: NLTK & TEANAPS [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_05/W05-2_advanced-text-mining_python-english-nlp.ipynb)_  
  > _W05-3. 개체명인식 수행하기: TEANAPS NER [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_05/W05-3_advanced-text-mining_python-ner.ipynb)_  

#### WEEK 06. 단어의 가중치를 표현하는 방법
- 단어빈도와 TF-IDF
- 동시출현빈도와 
- 실습  
  > _W06-1. 단어빈도와 TF-IDF 계산하기 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_06/W06-1_advanced-text-mining_python-tf-idf.ipynb)_  
  > _W06-2. 동시출현빈도 계산: 연관어 분석 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_06/W06-2_advanced-text-mining_python-co-word.ipynb)_  
  
#### WEEK 07. 텍스트 분석 방법론 1
- CNN, RNN을 활용한 텍스트 데이터 분류
- Transformer 모델 기반 텍스트 감성분석
- 실습  
  > _W07-1. 문장 의도분류 및 감성분석 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_07/W07-1_advanced-text-mining_text-classification.ipynb)_  
  
#### WEEK 08. 텍스트 분석 방법론 2
- 텍스트 유사도와 군집화
- 토픽모델링
- 실습  
  > _W08-1. K-평균 군집화와 LDA 토픽모델링을 활용해 문서 군집화하기 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_08/W10-1_advanced-text-mining_text-clustering.ipynb)_  

#### WEEK 09. 텍스트 분석 방법론 3
- 문서요약: 추출요약과 생성요약
- 핵심 키워드 추출
- 실습  
  > _W09-1. 뉴스기사 요약과 키워드 추출 [(Colab)](https://colab.research.google.com/github/fingeredman/advanced-text-mining/blob/master/practice-note/week_09/W09-1_advanced-text-mining_text-summerization.ipynb)_  

#### WEEK 10. 머신러닝/딥러닝 기반 대화 모델링
- Question & Answering
- Chat-bot: 질의응답부터 일상대화 까지
- 카카오 i 오픈빌더 
- 실습  
  > _W10-1. 카카오 i 오픈빌더를 활용해 Q/A 챗봇 구축하기_  

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
> 2021.05.08. `WEEK 09` 강의자료 및 실습자료 업데이트  
> 2021.04.25. `WEEK 07~08` 강의자료 및 실습자료 업데이트  
> 2021.04.01. `WEEK 06` 강의자료 및 실습자료 업데이트  
> 2021.04.03. `WEEK 05` 강의자료 및 실습자료 업데이트  
> 2021.03.28. `WEEK 04` 실습자료 업데이트  
> 2021.03.14. `WEEK 01~03` 강의자료 및 실습자료 업데이트  
> 2021.03.07. 2021 커리큘럼 업데이트   
> 2020.12.26. `WEEK 13` 강의자료 업로드  
> 2020.11.28. `WEEK 11~12` 강의자료 및 실습자료 업로드  
> 2020.11.08. `WEEK 04~10` 강의자료 및 실습자료 업로드  
> 2020.09.20. `WEEK 03` 강의자료 및 실습자료 업로드  
> 2020.09.12. 목차 구성 수정, `WEEK 02` 실습자료 업로드  
> 2020.09.06. 목차 구성 수정, `WEEK 01~02` 강의자료, `WEEK 01` 실습자료 업로드  
> 2020.07.05. 목차 구성 수정  
> 2020.06.07. 목차 구성 수정  
> 2020.05.24. 목차 구성 수정  


<br><br>
---
<center>ⓒ 2021. TEANAPS all rights reserved.</center>
