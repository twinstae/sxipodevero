네이티브 [[GraphQL]]에 기반한 [[분산형 Distributed]] [[그래프 데이터베이스 Graph Database]]

자체적으로 다른 데이터 솔루션과 비교를 해주고 있는데. GraphQL로 여러 데이터 소스를 통합해주는 [[Hasura]]나 [[객체 관계 맵퍼 ORM]]인 [[프리스마 Prisma]]와는 다르게, 네이티브 GraphQL이라 따로 변환과정이 필요없다.

그래프 데이터베이스인 [[Neo4J]]는 Cypher라는 자체 [[질의 언어 Query Language]] 가 있고, GraphQL은 실험적으로 [[자바스크립트 Javascript]] [[클라이언트 Client]]만 지원하지만. DGraph는 [[자바 Java]] [[파이썬 Python]] [[고 Go]] 등 여러 언어의 클라이언트를 지원한다.
DGraph는 분산 [[트랜잭션 Transaction]]을 염두에 두고 만들어졌기 때문에, 손쉽게 [[샤딩 Sharding]]이나 [[수평적 확장 Horizontal Scale Up]] 이 가능하다고 한다.

Dgraph는 [[HTTP]] 뿐만 아니라 [[gRPC]]같은 프로토콜도 지원한다.