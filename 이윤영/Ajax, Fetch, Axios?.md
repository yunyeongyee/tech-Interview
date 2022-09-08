## ✅  Ajax, Fetch, Axios?
<br>

<div markdown="1">

<pre>
[Ajax]
XMLHttpRequest(XHR) 객체를 이용해서 전체 페이지가 아닌 필요한 데이터만 불러올 수 있다.
Error, Success, Complete의 상태를 통해 실행 흐름 조절 가능하다.
Jquery를 통해 쉽게 구현 가능하다.
Promise 기반이 아니다.

[Fetch]
비동기 HTTP 통신을 위한 JavaScript의 내장 라이브러리로 별도의 설치가 필요하지 않다.
url이 Fetch() 함수의 인자로 들어간다.
.json()메서드를 사용하여 객체를 문자열으로 변환한 뒤 body에 할당해야한다.
네트워크 에러 발생 시 response timeout이 없어 기다려야 한다.
호환되지않는 브라우저 환경이 있어 호환성이 떨어진다.

[Axios]
axios는 Promise API를 활용한 HTTP 통신 라이브러리로 써드파티 라이브러리이기때문에 별도의 설치가 필요하다.
url이 option 객체로 들어간다.
자동으로 JSON데이터 형식으로 변환된다.
네트워크 에러 발생시 요청을 취소할 수 있고 timeout속성을 설정 객체에 추가하여 타임아웃을 지정할 수 있다.
크로스 브라우징 최적화로 브러우저 호환성이 뛰어난다.
</pre>
</div>

<br />
