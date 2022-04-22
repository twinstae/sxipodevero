자동차 앞에 보면 본네트/후드라고 부르는 뚜껑이 있다. 이 뚜껑을 열면 엔진부터 배터리, 냉각수 등등 여러 자동차의 내부 구조를 보고 다룰 수 있는데. 그래서 정비소에 가면 엔지니어들이 일단 후드부터 까보곤 한다.

코딩에서 Under the Hood는 프레임워크나 라이브러리가, 다른 프레임워크나 라이브러리를 내부적으로 이용하고 있을 때 많이 쓰는 표현이다. 겉으로는 드러난 [[인터페이스 Interface]]만 봐서는 알 수 없는 [[내부 Internal]] 구조를 가리킨다.

[[EdgeDB]]는 내부적으로 [[PostgreSQL]]을 사용한다.

EasyRpc 라는 라이브러리는 FastAPI를 이용해 만들었다고 하며
[[FastAPI]]는 데이터 [[검증 Validation]]은 [[Pydantic]]을 이용하고, 서버 자체는 [[Starllete]]의 기능을 이용한다. Strallete은 또 Uvicorn으로 만들었다.
> Under the hood, FastAPI uses Pydantic for data validation and Starlette for tooling

[[Nest]] 는 내부적으로 [[Express]]를 사용하지만, [[Fastify]]를 이용한 [[어댑터 Adapter]]를 사용할 수도 있다.
> Under the hood, Nest makes use of robust HTTP Server frameworks like [Express](https://expressjs.com/) (the default) and optionally can be configured to use [Fastify](https://github.com/fastify/fastify) as well! - [Nest 공식 문서](https://docs.nestjs.com)

