# sasac_card_gpt
## 카드 추천 챗봇
* 이진희, 최은진, 최정우
## 1. 개발 목표
* 카드고릴라 사이트의 카드 데이터를 활용하여, 사용자의 조건과 선호를 자연어로 입력받아 맞춤형 신용·체크카드를 추천하는 gpt를 구현한다.
## 2. 구현 기능
* 카드고릴라 카드 데이터를 JSON 파일로 로드
* 카드별 혜택 정보를 텍스트로 구성하여 Document 생성
* 카드 데이터를 분할(Text Split)하여 임베딩 생성
* 임베딩 데이터를 Chroma Vector Store에 저장
* Vector Store 기반 Retriever 구성
* MMR(Maximal Marginal Relevance) 검색 전략 적용
* 사용자 질의에 대해 관련 카드 정보 검색
* 검색 결과를 기반으로 카드 추천 챗봇 응답 생성

