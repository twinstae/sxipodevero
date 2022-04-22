특히 [[REST REpresentational State Transfer|REST]] [[API Application Programming Interface]]에서는 url에 명사만 쓰라 하는데, 일반적인 함수나 메서드처럼 api에 자연스러운 [[도메인 주도 설계 DDD|도메인]]의 동사를 쓰자는 주장이다.

http가 원래 html 파일 같은 자원을 전송하기 위해 만들어졌지만. api 가 복잡해지면서 단순한 [[CRUD Create Read Update Delete|CRUD]]에 대응되지 않는 동작이 많아졌다. "[[도메인 주도 설계에서는 CRUD로 모델링하는 걸 싫어한다]]"는 것과 연결되니 해당 항목의 예시를 참조하자.

그래서 점점 [[RPC Remote Procedure Call]]로 api 서버를 바라보는 사람이 늘어나기 시작했다. api는 서버에 있는 함수를 호출하는 것일 뿐이라는 것이다. 비슷하게 [[GraphQL]] 생태계에서도 api에 동사를 쓰는 걸 자연스럽게 생각한다.

하지만 이를 꼭 [[gRPC]]나 [[GraphQL]] 같이 특이한 기술을 써야 하는 건 아니다. 기존 웹 API에서도 얼마든지 동사를 쓸 수 있고. 그래서 이를 지지하는 분들은 REST API 대신 [[HTTP]] API 라는 표현을 쓰신다.


> Are you thinking to yourself, POST to _/add_batch_? That’s not very RESTful! You’re quite right. We’re being happily sloppy, but if you’d like to make it all more RESTy, maybe a POST to _/batches_, then knock yourself out!
> [Architecture Patterns with Python](https://www.cosmicpython.com/book/chapter_05_high_gear_low_gear.html#_carrying_the_improvement_through_to_the_e2e_tests)

> 검색 API를 디자인 하며 이거 이상하다고 느꼈고, 얼마 후 고통스럽게 TDD를 하고있는 나를 발견해 이거 함정이란 걸 깨달아 CQRS를 배웠다. 나는 미친 종교를 바로 탈출했고 조금의 죄책감도 없이 도메인 모델의 풍부한 동사들을 사용해 직관적인 API 경로를 디자인 했다. - [이규원 - 강남언니CTO](https://twitter.com/gyuwon_yi/status/1387765460691832835)

> api 에서 수행할 동작을 잘 표현할 수 있는 동사를 사용하는 것이 그것인데요. 이렇게 해서 어떻게 이 리소스를 어떻게 처리하는지가 계층적으로 잘 드러나게 됩니다
> [토스ㅣSLASH 21 - 결제 시스템의 SDK와 API 디자인](https://youtu.be/E4_0WWqmF3M?t=565)> [](https://youtu.be/E4_0WWqmF3M?t=565)