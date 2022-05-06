C에서 구조체는 서로 다른 타입의 데이터를 정해진 이름과 형태로 묶어둔 [[자료구조 Data Structure]]다. 여러 [[자료형 Data Type]]의 데이터를 묶어서 커스텀 [[타입 Type]]을 정의할 때 사용한다. 데이터의 [[고정 vs 가변 길이 fixed vs variable length|길이를 고정]]하고 싶어 하는 [[저수준 Low Level]] 언어에서 많이 사용한다. 다음은 [[C]], [[러스트 Rust]], [[고 Go]]에서 구조체를 정의하는 예제다.

```c
// C
struct Person {    // 구조체 이름
    char name[20];        // name은 길이가 20인 문자 배열이다
    int age;              // age는 정수 타입이다
};
```
```rust
// 러스트
#[derive(Debug)]
struct Person {
    name: String,
    age: u8,
}
```
```go
// 고
type Person struct {  
  name string  
  age int
}
```

## 비교
[[구조체 vs 튜플]]
[[구조체 vs 객체]]
[[구조체 vs 맵]]