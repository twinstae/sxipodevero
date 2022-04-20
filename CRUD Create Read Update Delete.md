CRUD는 파일이나 [[데이터 Data]]를 다루는 연산의 종류다. 각각

Create 생성
Read 읽기
Update 수정
Delete 삭제

에 대응한다. 파일을 생성하고, 읽어오고, 수정하고, 삭제하는 걸 생각하면 쉽게 이해할 수 있다.

데이터를 쓰거나 삭제하는 CUD는 [[부수효과 Side Effect]]를 일으켜서 데이터 내용을 바꿔버린다. 수정과 삭제는 [[멱등성 idempotent]] 을 만족하기 때문에, 여러 번 실행해도 같은 결과를 얻는다.

[[HTTP]]는 원래 [[정적 컨텐츠 vs 동적 컨텐츠 | 정적 파일]]을 전송하는 프로토콜이었기 때문에, CRUD에 대응되는 POST, GET, PUT/PATCH, DELETE [[HTTP 메서드 method]]를 가지고 있다. [[REST REpresentational State Transfer]]도 이런 사상에 입각해서 만들어졌다.

하지만 [[도메인 주도 설계에서는 CRUD로 모델링하는 걸 싫어한다]].  결제나 주문 같은 [[도메인 Domain]]의 개념들은 CRUD에 1대1로 대응하지 않기 때문이다. 