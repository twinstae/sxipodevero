[GraphQL: The Documentary - 유튜브 영상](https://youtu.be/783ccP__No8)
[GraphQL Explained in 100 Seconds - FireShip](https://youtu.be/eIQh02xuVw4)
[GraphQL is not just a network protocol](https://blog.cometkim.kr/posts/graphql-is-not-just-a-network-protocol/)
[Thinking in GraphQL](https://blog.cometkim.kr/posts/thinking-in-graphql-ko/)

[[페이스북 Facebook]]에서 만든 [[API|API]]를 위한 언어. [[REST REpresentational State Transfer|REST]] API를 대체하는 것처럼 소개되지만, 이름처럼 SQL 대신 [[Dgraph]]같은 데이터베이스의 쿼리 언어로도 사용된다.

[[도구 tooling|툴링]]이 괜찮은 편인데. [[OpenAPI]]처럼 [[스키마 Schema]]를 작성할 수 있고, 자동으로 여러 [[프로그래밍 언어 Programming Language|언어]]의 [[클라이언트 Client|클라이언트]]나 [[타입 Type|타입]] 정의 파일, 프로젝트의 틀을 [[자동 생성 Auto Generation|자동으로 생성]]해주기도 한다.

중첩된 데이터를 가져오는 경우에, REST API는 지나치게 많은 요청을 보내야 하는 경우가 많았는데. [[N+1 문제]]처럼 성능 상으로도 문제지만, 변경되는 API를 관리하기도 어려웠다.

GraphQL에서는 원하는 데이터를 명시해주면 [[리졸버 Resolver]]라는 걸 이용해서 각 자원의 데이터를 가져오고, 이 데이터들을 조합해서 한 번에 클라이언트로 보내준다.

이러면 서버에서 N+1 문제가 생기지 않을까 싶겠지만, 요즘은 GraphQL의 특성을 그대로 이용해서 성능 최적화를 해주는 [[객체 관계 맵퍼 ORM]]이나 [[EdgeDB]] 같은 데이터베이스도 등장했다.

데이터를 읽어오는 Query와 추가, 변경, 삭제하는 Mutation의 리졸버를 분리하여, [[명령 질의 책임 분리 CQRS|CQRS]]를 핵심에 두고 있다.