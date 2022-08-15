자바스크립트는 ES6에서 도입된 let, const를 포함하여 모든 선언(var, let, const, function, class)을 호이스팅한다.

 

호이스팅이란, 임의의 선언문을 해당 스코프의 선두로 옮긴 것처럼 동작하는 특성을 말한다. var 키워드로 선언된 변수는 선언 단계와 초기화 단계가 한 번에 이루어지기 때문에, 

변수 선언문 이전에 변수에 접근하여도 스코프에 변수가 존재하기 때문에 에러가 발생하지 않는다.

 

하지만, 블록 레벨 스코프인 let keyword로 선언된 변수는 선언문 이전에 참조 시, 참조 에러(ReferenceError)가 발생한다.

이는 let 키워드로 선언된 변수는 스코프의 시작에서 변수의 선언까지 일시적 사각지대(Temporal Dead Zone; TDZ)에 빠지기 때문이다.



https://gmlwjd9405.github.io/2019/04/22/javascript-hoisting.html
