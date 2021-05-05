# elasticsearch
## **BDC103 빅데이터와정보검색 - 21년1학기 중간고사 대체 과제 **
- 빅데이터융합과 서문진, 학번:2020511021

## References
- (1) **BDC103(00) 빅데이터와정보검색 강의 실습 2강** - 소스
   서재형, 임희석 [고려대학교 자연어처리 연구실]

- (2) ElasticSearch 공식 홈페이지 : 본과제는 7.8.0 버젼 사용함<br>
https://www.elastic.co/kr/what-is/elasticsearch

- (3) 한글 형태소 분석기 사용(Nori)<br>
https://issues.apache.org/jira/browse/LUCENE-8231 <br>
https://github.com/apache/lucene-solr/tree/master/lucene/analysis/nori <br>
https://jvvp.tistory.com/1158?category=875256 <br>

- (4) Wiki데이터 추출기 : WikiExtractor <br>
 https://github.com/attardi/wikiextractor


## Dataset : 위키 데이터
- 영어 - https://dumps.wikimedia.org/enwiki/
- 한글 - https://dumps.wikimedia.org/kowiki/

## 실행 방법 / 유의사항
- Colab 일반 환경 실행
- 본인 구글Drive 연결하여 마운트 필요
- 소스는 위에서부터 순차적으로 실행
- Elasticsearch 서버는 Colab 세션이 끊기면 다시 설치 및 구동 필요

## 처리 순서 
- ElasticSearch 개요
- Clab과 Google Drive 연동하기
- Elasticsearch 서버 설치
- 한글 형태소 분석기 Nori 설치
- Elasticsearch 서버 구동 및 Python 연동
- 현재 작업 폴더 재설정하기
- 인덱싱 TEST
- 색인화 TEST
- Wiki 데이터(한글) 다운로드
- Wiki데이터 전처리(WikiExtractor)
- 검색기 작성 - Wiki데이터(한글) 데이터
- (END)

