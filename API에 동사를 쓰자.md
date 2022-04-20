특히 [[REST REpresentational State Transfer|REST]] [[API Application Programming Interface]]에서는 url에 명사만 쓰라 하는데, 일반적인 함수나 메서드처럼 api에 자연스러운 [[도메인 주도 설계 DDD|도메인]]의 동사를 쓰자는 주장이다.

http가 원래 html 파일 같은 자원을 전송하기 위해 만들어졌지만. api 가 복잡해지면서 단순한 [[CRUD Create Read Update Delete|CRUD]]에 대응되지 않는 동작이 많아졌다.

그래서 점점 [[RPC Remote Procedure Call]]로 api 서버를 바라보는 사람이 늘어나기 시작했다. api는 서버에 있는 함수를 호출하는 것일 뿐이라는 것이다. 비슷하게 [[GraphQL]] 생태계에서도 api에 동사를 쓰는 걸 자연스럽게 생각한다.

하지만 이를 꼭 [[gRPC]]나 [[GraphQL]] 같이 특이한 기술을 써야 하는 건 아니다. 기존 웹 API에서도 얼마든지 동사를 쓸 수 있고. 그래서 이를 지지하는 분들은 REST API 대신 [[HTTP]] API 라는 표현을 쓰신다.
