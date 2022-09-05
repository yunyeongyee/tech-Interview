Promise와 async await 차이:     

1.   
promise는 활용할 시에는 then을 여러 번 사용할 경우에 가독성이 안좋아질 수 있고, 에러 핸들링을 할 때 catch() 메서드를 이용해 할 수 있습니다. 
async await은 프로미스 후속 처리 메서드 없이 동기 처리처럼 프로미스가 결과를 반환할 때까지 기다려 가독성이 좋아지고, try-catch문으로 에러 핸들링을 한다.    



2.   
① 에러 핸들링

Promise 를 활용할 시에는 .catch() 문을 통해 에러 핸들링을 해야 하지만,
async/await 은 try / catch를 통해 에러를 처리할 수 있다
② 코드 가독성

Promise의 후속 처리 메서드인 .then() 의 hell의 가능성
async/await 은 프로미스의 후속 처리 메서드 없이 마치 동기 처리처럼 프로미스가 처리 결과를 반환하도록 구현할 수 있기 때문에 코드 흐름을 이해 하기 쉽다.





Promise와 async await은 에러 핸들링과 코드 가독성에서 차이를 나타냅니다.

먼저 Promise를 활용할 시에는 .catch() 문을 통해 에러 핸들링을 해야 하지만,
async/await 은 try / catch를 통해 에러를 처리할 수 있습니다.

또한 Promise는 Promise의 후속 처리 메서드인 .then() 의 지옥에 빠지기 쉽고,
async/await 은 프로미스의 후속 처리 메서드 없이 마치 동기 처리처럼 프로미스가 처리 결과를 반환하도록 구현 할 수 있기 때문에 코드 흐름을 이해 하기 쉽다는 차이점이 있습니다.

