웹의 구조, 서버와 클라이언트의 request, response를 이용한 메시지 주고받기를 수행함. 웹은 url을 통해 특정 주소에 접속하고 
그 안에는 http, host 등의 키워드가 사용된다. http에는 get, post, put등의 리소스에 접근하는 메소드가 존재한다.
사용자가 직접적으로 보이지 않는 걸 다루는 파트가 백엔드 파트이다. 사용자 요청을 받아 데이터를 저장 및 관리하는 역할을 한다.
또한 API를 통해 서버와 클라이언트가 정해진 규칙으로 데이터를 주고받는다.

<img width="1174" height="547" alt="image" src="https://github.com/user-attachments/assets/6193cf0c-392b-40d4-8554-e448bbc00e04" />

HTTP Method: POST
URl: /items
HTTP Method: GET
URl: /items
HTTP Method: GET
URl: /items/{item_id}
HTTP Method: PATCH
URl: /items/{item_id}
HTTP Method: DELETE
URl: /items/{item_id}

HTTP Method: POST
URl: /orders
HTTP Method: GET
URl: /orders
HTTP Method: GET
URl: /orders/{order_id}
HTTP Method: PATCH
URl: /orders/{order_id}
HTTP Method: DELETE
URl: /orders/{order_id}
