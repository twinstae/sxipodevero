- 로직의 파편화
	- 전체 흐름을 파악하려면 이 폴더 저 폴더 돌아다녀야함
	- refactoring할 때에도 특히 힘듬.
	- 여러 페이지에 걸쳐 일어나는 로직들을 정확하게 만들기 어려움
		- ex VWR, payment method
	- 페이지마다 나누는 것도 좋지만, domain에 따른 구분도 필요함 (payment method, VWR 등)
- 서스펜스와 지역 상태 우선으로 개발
	- useEffect나 onSuccess 등의 필요성을 매우 줄여줍니다
- 의존성 관리
	- localStorage vs cookie, clipboard, window(server)
		- 얼마 되지도 않는데 미리 감싸둡시다
	- client only
	- pages router => app router 전환을 대비
- validation pipeline
	- schema와 valibot 잘 사용하기
	- 보통 복잡해지는 로직들을 보면 검증이나 조건부 로직들임~
	- test 가능한 선언적 모델로 만들어야...
- 프로젝트 간 공용 로직
	- design token, components -> 예슬 님과 합의된 대로
	- expectTL, createQuery
-