CORS는 무엇인가요?

네 먼저, 브라우저에서는 보안적인 이유로 cross-origin HTTP 요청들을 제한합니다.

그래서 cross-origin 요청을 하려면 서버의 동의가 필요합니다. 

만약 서버가 동의한다면 브라우저에서는 요청을 허락하고, 동의하지 않는다면 브라우저에서 거절합니다.

이러한 허락을 구하고 거절하는 메커니즘을 HTTP-header를 이용해서 가능한데, 이를 CORS(Cross-Origin Resource Sharing)라고 부릅니다.

요약하자면, 브라우저에서 cross-origin 요청을 안전하게 할 수 있도록 하는 메커니즘입니다.
