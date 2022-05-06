[[구조체 Struct]]는 데이터들을 묶어놨다는 점에서는 [[객체 Object]]와 비슷하지만, 객체는 데이터보다는 어떤 [[역할 Role]]을 하는 행동, 즉 [[메서드 Method]]를 묶어놨다는 점에서 다르다.

객체는 [[자료구조 Data Structure]]가 아니다.

객체는 행동이 중심이고, 데이터는 부차적이다. 하지만 구조체는 데이터를 묶어놓은 게 본질이고 행동은 없다.

[[자바 Java]]나 [[코틀린 Kotlin]], [[파이썬 Python]]처럼 [[클래스 Class]]를 기반으로 하는 [[객체지향 Object Oriented]] 언어에서는 구조체처럼 메서드 없이 데이터만 있는 클래스를 [[데이터 클래스 Data Class]]라고 부르고, 보통 [[불변 Immutable]]인 [[값 객체 Value Object]]로 만들어서 사용한다.

```kotlin
data class Person(val name: String, val age: Int)
```