# 언어와 컴퓨터 (2021학년도 2학기, 서울대학교 인문대학 언어학과)

## 개요

+ 강좌명: 언어와 컴퓨터
+ 강좌번호: 100.130 (001 & 002)
+ 교수자: 박수지 (mam3b@snu.ac.kr, sut.i.palatalised@gmail.com)
+ 교재: Jurafsky & Martin, *[Speech and Language Processing 3rd edition](https://web.stanford.edu/~jurafsky/slp3/)*


## 목표

언어와 컴퓨터(100.130)는 컴퓨터언어학(108.413A)의 선수과목으로, 심층학습(딥러닝, 인공신경망)을 사용한 자연언어처리 기법을 학습하기 위해 필요한 컴퓨터언어학의 기본 지식을 습득하는 것을 목표로 한다. 이 과목을 이수함으로써 학생들은 인공신경망 모형이 도입되기 전까지 자연언어처리 분야에서 전통적으로 어떤 기법을 사용하고 어떤 과제를 처리했는지를 이해하고 파이썬으로 구현할 수 있게 될 것이다. 이 강좌의 전반부에서는 파이썬의 기초와 정규표현식에 대해 배우며, 이를 통해 최초의 규칙 기반 챗봇인 ELIZA를 구현한다. 후반부에서는 기계학습과 벡터 의미론에서 대해 배우며, 이를 활용하여 주어진 트위터 데이터가 악성 트윗인지 아닌지를 자동으로 예측하는 모형을 개발한다.

이 강좌에서는 수강생을 대학 입학 후 수학을 따로 공부하지 않은 인문대학 1–2학년생으로 가정하고, 후반부 수업은 조건부확률, 로그함수, 지수함수 등 기초적인 내용을 복습하는 데서 시작할 것이다.

## 일정

|회차|날짜|제목|슬라이드|실습|자료|
|--|--|--|--|--|--|
|1강|2021-09-01(수)|강의 소개 및 파이썬 시작|-|-|[[Eliza, Computer Therapist](http://psych.fullerton.edu/mbirnbaum/psych101/Eliza.htm)]<br>[[Sentiment Analysis - AllenNLP - Demo](https://demo.allennlp.org/sentiment-analysis/glove-sentiment-analysis)]<br>[[Korean Word2Vec](https://word2vec.kr/search/)]<br>[[Google Colaboratory](https://colab.research.google.com)]|
|2강|2021-09-06(월)|파이썬 기본 문법|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/02-20210906.pdf)]|-|[[Automate the Boring Stuff with Python: Chapter 1 – Python Basics](https://automatetheboringstuff.com/chapter1/)]|
|3강|2021-09-08(수)|반복 가능한 자료형|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/03-20210908.pdf)]|-|-|
|4강|2021-09-13(월)|반복문|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/04-20210913.pdf)]|-|[[Automate the Boring Stuff with Python: Chapter 4 – Lists](https://automatetheboringstuff.com/chapter4/)]|
|5강|2021-09-15(수)|조건문|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/05-20210915.pdf)]|-|[[Automate the Boring Stuff with Python: Chapter 2 – Flow Control](https://automatetheboringstuff.com/chapter2/)]|
|6강|2021-09-27(월)|함수와 모듈|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/06-20210927.pdf)]|-|[[Automate the Boring Stuff with Python: Chapter 3](https://automatetheboringstuff.com/chapter3/)]|
|7강|2021-09-29(수)|예외 처리|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/07-20210929.pdf)]|-|[[국어 정보화의 방향: 문자 코드를 중심으로](https://www.korean.go.kr/nkview/nklife/2015_2/25_0205.pdf)]<br>[[‘설믜를 설믜라 못 부르는 김설믜씨’ “제 이름을 지켜주세요”](https://www.hani.co.kr/arti/society/society_general/864914.html)]|
|8강|2021-10-06(수)|정규표현식 (1)|-|-|[[SLP3 Ch. 2](https://web.stanford.edu/~jurafsky/slp3/2.pdf)]<br>[[Slides: Basic Text Processing](https://web.stanford.edu/~jurafsky/slp3/slides/2_TextProc_Mar_25_2021.pdf)]<br>[[RegExr: Learn, Build, & Test](https://regexr.com)]<br>[[단어 임베딩과 음성적 유사도를 이용한 트위터 ‘서치 방지 단어’의 자동 예측](https://www.koreascience.or.kr/article/CFKO201731951960098.pdf)]|
|9강|2021-10-13(수)|정규표현식 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/09-20211013.pdf)]|-|[[SLP3 Ch. 2](https://web.stanford.edu/~jurafsky/slp3/2.pdf)]<br>[[ELIZA—a computer program for the study of natural language communication between man and machine](https://dl.acm.org/doi/10.1145/365153.365168)]|
|10강|2021-10-18(월)|파일 처리 (1)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/10-20211018.pdf)]|[["음식의 언어" Colab](https://colab.research.google.com/drive/1Wd5gP-zEMfACWaQ4fH8GcjMwRlVzC6Rq)]|[[식품영양성분 데이터베이스](https://various.foodsafetykorea.go.kr/nutrient/)]<br>[[The Unicode Standard, Version 14.0 - Hangul Jamo](https://www.unicode.org/charts/PDF/U1100.pdf)]|
|11강|2021-10-20(수)|파일 처리 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/11-20211020.pdf)]|-|[[Project Gutenberg: Free eBooks](https://www.gutenberg.org)]|
|12강|2021-10-25(월)|ELIZA 개발 관련 토의|-|-|-|
|13강|2021-10-27(수)|벡터, 통계, 데이터 시각화 (1)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/13-20211027.pdf)]|-|[["밑바닥부터 시작하는 데이터 사이언스" 예시 코드](https://github.com/insightbook/Data-Science-from-Scratch)]|
|14강|2021-11-01(월)|벡터, 통계, 데이터 시각화 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/14-20211101.pdf)]|-|-|
|15강|2021-11-03(수)|N그램 언어 모형 (1)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/15-20211103.pdf)]|-|[[SLP3 Ch. 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf)]|
|16강|2021-11-08(월)|N그램 언어 모형 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/16-20211108.pdf)]|[[Colab](https://colab.research.google.com/drive/1XFkZApol9a8fbHHqHSybQ8BMDF6FEscL)]|[[SLP3 Ch. 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf)]<br>[[The Berkeley Restaurant Project (BeRP) Transcripts](https://github.com/wooters/berp-trans)]<br>[[NLTK :: Sample usage for corpus](https://www.nltk.org/howto/corpus.html)]|
|17강|2021-11-10(수)|N그램 언어 모형 (3)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/17-20211110.pdf)]|-|[[SLP3 Ch. 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf)]|
|18강|2021-11-15(월)|단순 베이즈 분류기와 감정분석 (1)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/18-20211115.pdf)]|-|[[SLP3 Ch. 4](https://web.stanford.edu/~jurafsky/slp3/4.pdf)]|
|19강|2021-11-17(수)|단순 베이즈 분류기와 감정분석 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/19-20211117.pdf)]|[[Colab](https://colab.research.google.com/drive/1C8lM22-5ILMCH0CemzXKBCWXrHyc2yIJ?usp=sharing)]|[[SLP3 Ch. 4](https://web.stanford.edu/~jurafsky/slp3/4.pdf)]|
|20강|2021-11-22(월)|로지스틱 회귀분석 (1)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/20-20211122.pdf)]|-|[[SLP3 Ch. 5](https://web.stanford.edu/~jurafsky/slp3/5.pdf)]<br>[[Frequency of word-use predicts rates of lexical evolution throughout Indo-European history](https://www.nature.com/articles/nature06176)]|
|21강|2021-11-24(수)|로지스틱 회귀분석 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/21-20211124.pdf)]|[[Colab](https://colab.research.google.com/drive/19PcTY3eEm-Yy0NPiCIir-0M-6Uvu4K4l?usp=sharing)]|[[SLP3 Ch. 5](https://web.stanford.edu/~jurafsky/slp3/5.pdf)]<br>[[IMDb-Review-Analysis](https://github.com/LawrenceDuan/IMDb-Review-Analysis)]<br>[[VADER-Sentiment-Analysis](https://github.com/cjhutto/vaderSentiment)]|
|22강|2021-11-29(월)|로지스틱 회귀분석 (3)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/22-20221129.pdf)]|[[Colab](https://colab.research.google.com/drive/1AEUWk9MyA1PI8llZ7zVJD1kRqkyqxl_G?usp=sharing)]|[[SLP3 Ch. 5](https://web.stanford.edu/~jurafsky/slp3/5.pdf)]|
|23강|2021-12-01(수)|벡터 의미론 (1)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/23-20211201.pdf)]|[[Colab](https://colab.research.google.com/drive/1bBg_CcZduJiFS7DVTMQxg0iPgMyqodZT?usp=sharing)]|[[SLP3 Ch. 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf)]|
|24강|2021-12-08(수)|벡터 의미론 (2)|[[Slides](https://github.com/suzisuti/LangComp2021/blob/main/slides/24-20211208.pdf)]|[[Colab](https://colab.research.google.com/drive/1FxanqyGrBVHfFl77XQPrrYyFuxCkT6Ao?usp=sharing)]|[[SLP3 Ch. 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf)]<br>[[Automated Hate Speech Detection and the Problem of Offensive Language](https://github.com/t-davidson/hate-speech-and-offensive-language)]|
