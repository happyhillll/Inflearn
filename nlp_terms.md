# 용어 소개
- **코퍼스** : 말뭉치. 자연어처리를 위해 모아놓은 텍스트 묶음. 소설, 뉴스기사, 위키피디아 등에서 수집한 텍스트
- **토큰** : 전체 문자열을 분석하고자 하는 단위로 나눈 것. 상황에 따라 문장 단위가 될 수도 있고, 단어 단위가 될 수도 있고, 형태소 단위가 될 수도 있음
- **어휘 집합** : 처리하는 문제영역의 전체 단어 집합. 어휘 집합에 포함되지 않은 단어는 <UNK>라는 특수 토큰으로 처리
- **토크나이징** : 전체 텍스트를 원하는 구분 단위로 나누는 것
- **원핫 인코딩** : 범주형 값을 이진화된 값으로 바꿔서 표현하는 것(binary value)
    - 원핫 인코딩 벡터의 크기는 사용하는 어휘집합의 크기가 된다.
    - 어휘 집합의 크기가 일반적으로 큰 값이기 때문에 단어 표현이 희박(sparse)해지게 된다. (ex.10000x1 행렬)
 - **NLTK 라이브러리** : 자연어처리를 위한 토크나이징 등 편리한 기능을 제공하는 자연어처리 파이썬 라이브러리
