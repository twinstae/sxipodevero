버전은 애플리케이션을 배포할 때 [[호환성 Compatability]]을 관리하는 방식 중에 하나다.

예를 들어 react@16.1.0 버전은 react@16.2.0 버전과 사용법이 비슷하기 때문에. 버전을 올려도 코드가 깨지지 않는다. 되도록이면 구 버전과 신 버전의 [[API|API]]를 비슷하게 해서 [[하위 호환 Backward Compatability]] 

하지만 마이너 버전이 아니라 메이저 버전이 올라갈 때에는 보통 [[파괴적 변경 Breaking Change]]이 일어나는데. [[인터페이스 Interface]]가 대대적으로 바뀌게 된다. 예를 들어 react@17에서 react@18로 올라가면서 ReactDom.render 메서드가 createRoot로 변하는 식의 변경이 있었다. 이런 변경 사항은 보통 [[마이그레이션 Migration]] 안내서 같은 곳에 적혀 있다.