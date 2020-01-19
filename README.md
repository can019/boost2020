# boost2020
2020부스트코스/201602068 정유성

### 배운점
1회성 연결을 지향한다. (listen은 하지만 request 올 때마다 그 요청만 처리하기 때문)
Get, post로 데이터를 주고 받으며, post는 보안측면이 강합니다.
text의 경우 body를 통해 전해지지만 중요하거나 노출을 꺼려하는 데이터는
헤더에 숨겨져서 전송됩니다.

### 생각해 보기 

https의 s는 secure을 뜻하며 이것이 http와 https의 차이라고 볼 수 있습니다. 
http는 정말 텍스트 그 자체를 주고 받기 때문에 내용이 노출 될 수 있으며, 악의 적인 해커들의 경우 단순 텍스트임을 이용해 명령문을 몰래 끼워 넣으면 실행된다는 점을 악용하기도 합니다.(xss)
물론 이러한 점을 막기 위하여 htmlspecialize 즉 특수 기호를 암호화 하지만 프로그래머에 따라 달라집니다.
하지만 https는 이 메세지를 암호화 하는데 이때 SSL프로토콜을 사용합니다.


### 함께하고자 하는 팀원

16신희강 16박기덕 16정유성
