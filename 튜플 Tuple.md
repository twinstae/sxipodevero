튜플은 여러 타입의 값이 들어갈 수 있는 고정 길이의 배열인데, 어떤 타입이 어떤 순서로 들어갈지 정해놓기 때문에 메모리에서 어떤 공간을 차지할지도 정해둘 수 있다. 매우 가벼운 [[구조체 Struct]]처럼 널리 쓰인다.

[[타입스크립트 TypeScript]] 에도 튜플이 있지만 실제로는 [[배열 Array]]을 이용해서 구현된다.
```ts
type Position = [number, number]; // 튜플이다
```

[[파이썬 Python]]에도 평범한 튜플이 있는데. 신기하게도 구조체처럼 필드마다 이름을 붙인 Named Tuple이라는 것도 있다. 이거는 구조체와 정말 비슷하게 쓴다.
```python
# 그냥 튜플
position_of_point: Tuple[int, int] = (1,4)

# named tuple
Person = collections.namedtuple('Person', ['name', 'age'])
t = Person('taehee', 28)
t.name # 'taehee'
t.age # 28
```

[[러스트 Rust]]에서는 튜플도 구조체처럼 struct 키워드로 정의한다.
```rust
#[derive(Debug)]
struct Position(i16, i16); // 튜플이다.
```

[[오카믈 Ocaml]] 계열의 [[강타입 Strongly Typed]] 언어인 [[리스크립트 Rescript]]에서도 튜플을 지원한다.
```rescript
type coord3d = (float, float, float) let my3dCoordinates: coord3d = (20.0, 30.5, 100.0)
```

튜플을 지원하는 언어에서는 [[구조 분해 할당 Destructuring]]이나 [[패턴매칭 Pattern Matching]]을 적극적으로 사용하는 경우가 많다.

## 비교
[[구조체 vs 튜플]]
[[맵 vs 튜플]]
[[배열 vs 튜플]]