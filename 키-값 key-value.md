어떤 키를 가지고 대응되는 값을 연결하는 구조.

여러 언어에 구현된 [[자료구조 Data Structure|자료구조]]인 [[맵 Map]]이 대표적이다. [[해시 Hash]]나 [[트리 Tree]] 등을 이용해 구현한다.

세상에는 정말 많은 데이터들을 key-value로 저장한다.

브라우저의 localStorage도 대표적인 key-value 저장소다.
[[자바스크립트 Javascript|JS]]의 object나 이를 [[직렬화 Serialize]]한 [[JSON JavaScript Object Notation|JSON]]도 key-value로 데이터를 저장한다.
[[레디스 Redis]] 같은 key-value [[데이터베이스 Database]]도 있다.

key-value는 이런저런 [[캐싱 caching]]이나 [[인덱스 Index]]로 사용되기도 한다. key-value 저장소는 구조도 간단하고, 성능도 빠르기 때문이다. 이를 이용해 한 번 계산했던 값을 저장해두는 [[메모이제이션 Memoization]] [[알고리즘 Algorithm]]도 있다.