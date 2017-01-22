# 이곳은?

리액티브 프로그래밍과 함수형 리액티브 프로그래밍에 대해서 학습했던 자료 모음.

### 리액티브 프로그래밍

[리액티브 프로그래밍의 정의](https://en.wikipedia.org/wiki/Reactive_programming)

[데이터 플로우 프로그래밍의 정의](https://en.wikipedia.org/wiki/Dataflow_programming)

[On the development of reactive systems](http://dl.acm.org/citation.cfm?id=101990)

- 리액티브 프로그래밍의 개념이 탄생한 배경으로 거론되는 논문
- Reactive systems… are repeatedly prompted by the outside world and their role is to continusouly respond external inputs

[리액티브 메니페스토](http://www.reactivemanifesto.org/)

- 소프트웨어를 둘러싼 환경 변화를 소개하고, 새로운 환경에 어울리는 소프트웨어 모델로 “메시지 주도” 방식의 설계를 적극 활용하자는 주장
- “Reactive Systems rely on asynchronous message-passing to establish a boundary between components that ensures loose coupling, isolation and location transparency.”

### Rx(ReactiveX)

[Rx 공식 홈페이지](http://reactivex.io/intro.html)

[Erik Meijer and Wes Dyer - Reactive Framework (Rx) Under the Hood](https://channel9.msdn.com/Shows/Going+Deep/E2E-Erik-Meijer-and-Wes-Dyer-Reactive-Framework-Rx-Under-the-Hood-1-of-2)

- Rx를 소개하는 동영상
- 본래 Rx는 Reactive Framework였는데 정식 출시하면서 이름이 ReactiveX로 바뀐다. 하단에 달린 Charlse Torre의 댓글을 통해서 ReactiveX로 이름이 바뀐 이유를 유추해볼 수 있다.


[React Framework(Rx) first look](http://www.minddriven.de/index.php/technology/dot-net/reactive-framework-rx-first-look)

- Rx의 핵심을 쉽고 간결하게 설명하는 글

[Microsoft's New .NET Rx Framework Tackles Challenges of Asynchronous Programming](https://campustechnology.com/articles/2009/08/10/microsofts-new-.net-rx-framework-tackles-challenges-of-asynchronous-programming.aspx)

- Rx를 공개한 후 에릭 마이어가 언론과 가진 인터뷰
- Meijer and software design engineer Wes Dyer have designed what Meijer describes as a major breakthrough in asynchronous programming. "Of all the work I've done in my career so far, this is the most exciting," Meijer told session attendees. "I know it's a bold statement, but I really believe that the problem of asynchronous programming events has been solved."

[Your Mouse is Database](http://queue.acm.org/detail.cfm?id=2169076)

- 에릭 마이어가 직접 소개하는 데이터 관점의 Rx

    
[Subject/Observer is Dual to Iterator](http://csl.stanford.edu/~christos/pldi2010.fit/meijer.duality.pdf)

- Iterator와 Observable의 쌍대성을 소개
- 중간에 Rx와 FRP의 차이점을 간략하게 설명함

    
[Rx가 만들어진 배경인 Volta를 소개하는 기사](http://www.zdnet.com/article/microsoft-architect-compares-volta-and-googles-gwt/)

[Rx 릴리즈 노트](https://blogs.msdn.microsoft.com/rxteam/2010/10/28/release-notes/)

### RxJS

[The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)

- cyclejs를 만든 Andre Staltz가 소개하는 RxJS
- 튜토리얼 형식으로 쉽게 접근할 수 있음.

[Netflix JavaScript Talks - RxJS + Redux + React = Amazing!](https://www.youtube.com/watch?v=AslncyG8whg)

- redux의 약점 중 하나가 액션 레이어에서의 비동기 처리인데 rx를 이용해서 만든 redux-observable이라는 미들웨에로 이 문제를 해결하는 방법을 소개

### FRP

[Functional Reactive Animation by Conal Eliott and Paul Hudak](http://conal.net/papers/icfp97/)

- FRP 개념이 처음으로 등장한 것으로 알려진 논문

[FRAN tutorial](http://conal.net/fran/tutorial.htm)

- Functional Reactive Animation에서 소개한 개념을 실제 코드로 옮긴 예제

[Functional Reactive Animation 논문 요약/해설](https://blog.acolyer.org/2015/12/07/fran/)

- Functional Reactive Animation 논문을 요약하고 약간의 해설을 곁들여서 개요를 설명하는 글

[Essence and Origins of FRP](https://github.com/conal/talk-2015-essence-and-origins-of-frp)

- FRP의 창시자인 Conal이 생각하는 FRP의 본질.
- Continuous Time, Denotational Semantics가 FRP의 본질이라고 주장함.
    
[Haskell/Denotational Semantics](https://en.wikibooks.org/wiki/Haskell/Denotational_semantics)

- 하스켈 언어의 근간인 표기적 의미론을 설명하는 공식 문서
- 알듯말듯 알쏭달쏭...
    
[FRP Explanation using Reactive Banana](https://wiki.haskell.org/FRP_explanation_using_reactive-banana)

- 하스켈의 FRP 구현체인 Reactive Banana로 소개하는 FRP
    
[Concurrent FRP](http://elm-lang.org/papers/concurrent-frp.pdf)

- elm을 만든 Evan Czapplicki가 FRP로 주제로 작성한 논문
    
[A Farewell to FRP](http://elm-lang.org/blog/farewell-to-frp)

- Evan Czapplicki가 FRP를 지향하는 기존 Elm의 설계를 개선하면서 남긴 FRP에 대한  생각

[Functional Reactive Programming](https://www.manning.com/books/functional-reactive-programming)

- FRP 구현체인 Sodium을 가지고 함수형 리액티브 프로그래밍을 소개하는 책.
- FRP를 둘러싼 혼란을 소개하며 진짜 FRP의 개념은 어떻게 다른지 설명. 
- Rx와 FRP의 차이도 간략하게 설명.
- 한국어 버전이 곧 나올거라고 어디에서 들었다.

### Rx vs FRP

[Why I Cannot Say FRP But, I Just Did](https://medium.com/@andrestaltz/why-i-cannot-say-frp-but-i-just-did-d5ffaa23973b#.qjt799iso)

- FRP의 좁은 정의에 반대하는 cyclejs 개발자의 생각

[Rx vs FRP를 주제로 트위터에서 벌어진 토론](https://twitter.com/ReactiveX/status/483625917491970048)

- Andre Staltz와 Erik Meijer 그리고 Conal Eliott가 토론을 벌임.
- FRP에 대한 각자의 생각을 읽을 수 있음.    
    
[Clarify the differences between Functional Reactive Programming and Reactive Extensions](https://github.com/ReactiveX/reactivex.github.io/issues/130)

- Rx와 FRP의 차이를 묻는 질문으로 에릭 마이어의 코멘트를 통해 FRP에 대한 에릭 마이어릐 생각을 읽을 수 있음. 
- 에릭 마이어는, FRP와 Rx는 다르다는 걸 인정. FRP를 만든 Conal의 생각을 존중하며, Rx를 이용해서 현실의 문제를 해결할 수 있다면 용어는 중요하지 않다고 말함

### 김코딩 정리
- [(글)MS는 ReactiveX를 왜 만들었을까?](http://huns.me/development/2051)
- [(슬라이드와 동영상)웹 프론트엔드 개발자의 얕고 넓은 Rx 이야기](http://www.slideshare.net/jeokrang/rx-70197043)

