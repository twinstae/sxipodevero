[깃허브](https://esbuild.github.io)

> An extremely fast JavaScript bundler

[[고 Go]] 로 만들어서 [[웹팩 webpack]]보다 매우 빠른 js [[모듈 번들러 Module Bundler]]라고 한다. 짧게는 몇 초부터 길게는 1분 넘게 걸리는 webpack 번들링을 기다리는 고통을 줄여준다. 자체 벤치마크에 따르면 웹팩5로 41.53초가 걸리는 번들링을, 0.33초만에 끝낸다고 한다.

[esbuild는 왜 빠른가요?](https://esbuild.github.io/faq/#why-is-esbuild-fast)
웹팩은 [[자바스크립트 Javascript]]로 만들어졌는데 [[인터프리터 Interpreter]] 언어인 js보다 [[컴파일 Compile]] 언어인 [[고 Go]] 는 수 십 배 빠르기 때문이라 한다. 그 외에도 단일 [[스레드 Thread]]인 js와 달리 멀티 스레드로 [[병렬성 Parallelism]]을 잘 활용하고, 메모리도 더 효율적으로 쓴다고 한다. 