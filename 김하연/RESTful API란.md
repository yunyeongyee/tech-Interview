
<!-- REST 구성 요소

REST는 다음과 같은 3가지로 구성이 되어있다. 

자원(Resource) : HTTP URI

자원에 대한 행위(Verb) : HTTP Method

자원에 대한 행위의 내용 (Representations) : HTTP Message Pay Load -->


REST란 
HTTP URI(Uniform Resource Identifier)를 통해 자원(Resource)을 명시하고,
HTTP Method(POST, GET, PUT, DELETE)를 통해
해당 자원(URI)에 대한 CRUD Operation을 적용하는 것을 의미합니다.



RESTFUL이란 REST의 원리를 따르는 시스템을 의미합니다. 
하지만 REST를 사용했다 하여 모두가 RESTful 한 것은 아닙니다.

REST API의 설계 규칙을 올바르게 지킨 시스템을 RESTful하다 말할 수 있으며

모든 CRUD 기능을 POST로 처리 하는 API 혹은 URI 규칙을 올바르게 지키지 않은 API는 

REST API를 사용하였지만 RESTful 하지 못한 시스템이라고 할 수 있습니다.

