[[HTTP]] [[프로토콜 Protocol]]에 기반하여 웹 [[API Application Programming Interface]]와 [[자원 Resource]]을 정의하는 방법론이자, 네트워크 아키텍처다. HTTP의 주요 저자인 [로이 필딩의 박사 논문](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)에서 처음 제시되었다.

표현적 상태 전송이라는 말처럼, api 서버의 상태를 그 구조 그대로 전송하기 위한 방법론이다.

api url에는 자원의 이름을 나타내는 명사만 써야한다고 해서, [[API에 동사를 쓰자]]고 하는 분들은 싫어하신다.

> Are you thinking to yourself, POST to _/add_batch_? That’s not very RESTful! You’re quite right. We’re being happily sloppy, but if you’d like to make it all more RESTy, maybe a POST to _/batches_, then knock yourself out!
> [Architecture Patterns with Python](https://www.cosmicpython.com/book/chapter_05_high_gear_low_gear.html#_carrying_the_improvement_through_to_the_e2e_tests)

> 검색 API를 디자인 하며 이거 이상하다고 느꼈고, 얼마 후 고통스럽게 TDD를 하고있는 나를 발견해 이거 함정이란 걸 깨달아 CQRS를 배웠다. 나는 미친 종교를 바로 탈출했고 조금의 죄책감도 없이 도메인 모델의 풍부한 동사들을 사용해 직관적인 API 경로를 디자인 했다. - [이규원 - 강남언니CTO](https://twitter.com/gyuwon_yi/status/1387765460691832835)

> api 에서 수행할 동작을 잘 표현할 수 있는 동사를 사용하는 것이 그것인데요. 이렇게 해서 어떻게 이 리소스를 어떻게 처리하는지가 계층적으로 잘 드러나게 됩니다
> [토스ㅣSLASH 21 - 결제 시스템의 SDK와 API 디자인](https://youtu.be/E4_0WWqmF3M?t=565)> [](https://youtu.be/E4_0WWqmF3M?t=565)