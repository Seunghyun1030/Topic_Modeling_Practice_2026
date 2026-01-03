# 📚 Text Summary & Topic Modeling Practice

이 저장소는 텍스트 요약(Text Summarization) 및 토픽 모델링(Topic Modeling) 기법을 학습하고 실습한 내용을 담고 있습니다. 통계 기반 방법론부터 최신 임베딩 기반 모델까지 다양한 접근 방식을 다루며, 실제 데이터 수집 출처를 포함합니다.

## 📌 목차 (Table of Contents)

1. [텍스트 요약 (Text Summarization)](#-텍스트-요약-text-summarization)
2. [통계 기반 토픽 모델링 (Statistical Topic Modeling)](#-통계-기반-토픽-모델링-statistical-topic-modeling)
3. [임베딩 기반 토픽 모델링 (Embedding-based Topic Modeling)](#-임베딩-기반-토픽-모델링-embedding-based-topic-modeling)
4. [데이터 수집 (Data Collection)](#-데이터-수집-data-collection)

---

## 📝 텍스트 요약 (Text Summarization)

한국어 텍스트 요약에 특화된 딥러닝 모델 활용 실습입니다.

- **Korean T5 Model**
  - [HuggingFace: lcw99/t5-base-korean-text-summary](https://huggingface.co/lcw99/t5-base-korean-text-summary)
  - 한국어 요약문 생성에 최적화된 T5 모델입니다.

---

## 📊 통계 기반 토픽 모델링 (Statistical Topic Modeling)

단어의 빈도와 통계를 기반으로 문서의 주제를 추출하는 전통적인 방법론 계열입니다.

- **LSA (Latent Semantic Analysis)**
  - [잠재 의미 분석 개념 (Wikidocs)](https://wikidocs.net/24949)
  - 토픽 모델링의 기초적인 아이디어를 제공하는 차원 축소 기법입니다.

- **LDA (Latent Dirichlet Allocation)**
  - [LDA 개념 설명 (Wikidocs)](https://wikidocs.net/30708)
  - [LDA 실습 (Wikidocs)](https://wikidocs.net/40710)
  - 문서 내 단어 분포를 통해 토픽을 추론하는 가장 대표적인 통계적 방법입니다.

---

## 🤖 임베딩 기반 토픽 모델링 (Embedding-based Topic Modeling)

문맥과 의미를 반영하는 임베딩 모델(SBERT)을 활용하여 더 정교하게 토픽을 분석하는 계열입니다.

- **Sentence BERT (SBERT)**
  - [SBERT 개념 (Wikidocs)](https://wikidocs.net/156176)
  - 문장 단위의 의미를 벡터화하여 토픽 모델링의 성능을 높입니다.

- **BERTopic**
  - [BERTopic 영어 실습 (Wikidocs)](https://wikidocs.net/162076)
  - [BERTopic 한국어 실습 (Wikidocs)](https://wikidocs.net/162079)
  - BERT 임베딩과 클래스 기반 TF-IDF를 결합한 최신 토픽 모델링 라이브러리입니다.

---

## 💾 데이터 수집 (Data Collection)

본 프로젝트 및 실습에 사용된 데이터 수집 출처입니다.

- **Web of Science**
  - [Smart Search Link](https://www-webofscience-com-ssl.ca.skku.edu/wos/woscc/smart-search)
  - 학술 논문 및 인용 색인 데이터베이스

- **KCI (Korea Citation Index)**
  - [한국학술지인용색인](https://www.kci.go.kr/kciportal/main.kci)
  - 국내 학술지 정보 및 논문 검색
