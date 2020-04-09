# item_recommender_with_nlp
NLP 기법을 이용한 아이템 추천 시스템 실험

## Dataset
MovieLens(https://grouplens.org/datasets/movielens/)

## Codes
* item2vec.ipynb: item2vec 이용해 이용자-아이템 셋에서 아이템 임베딩 추출
* n_gram.ipynb: n-gram 이용해 영화 추천 리스트 생성
* apriori.ipynb: apriori rule 이용해 support 계산
* rnnlm.py: lstm을 이용한 언어모델로 아이템 basket 생성
* crawling.py: 네이버 영화 사이트에서 영화 목록 크롤링
* movies.py: movieLens 데이터 전처리

### 데이터 전처리
* 총 영화 갯수: 62423개
* 두개 이상의 평가가 있는 영화 갯수: 59047개(전체 데이터의 94.6%)
* 그중 frequent items(전체 itemset의 0.05% 차지): 8658개(전체 데이터의 14.6%)

## References
* ITEM2VEC: Neural Item Embedding for Collaborative Filtering(https://arxiv.org/pdf/1603.04259.pdf)
