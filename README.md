23.03.02
-> 이벤트 핸들링과 동시에 for, if, else 활용하는 연습입니다.
코드의 설명은 주석에 담아뒀습니다.\

team.html
-> 이것은 퍼블리셔요 인터넷 노가디언
-> 이 파일을 마크업 형식이 아닌 js를 활용해 처음부터 끝까지 제작해보려 한다
1. 나는 html태그 만드는 것을 우선으로 했다.
2. 태그를 만든후 태그생성변수에 setAttribute를 하여 필요에 따라 id와 클래스를 만들어 줄 것이다.
3. 항상 제작하기 전에 부모자식 관계를 파악하고 제작! -> body의 자식으로 asdie와 div이 있다
4. createElement를 하다보니 머릿속에 함수로 만드는 것이 스쳐지나가지만 일단 만들어놓고 생각하기로 한다 ㅎㅎ -> 실력이 부족하니 구현 먼저 하자(캡슐화는 나중에)
5. body의 직계자식인 #root와 #move-btn은 생성 및 속성 부여를 완료했다.
이제 위치에 맞춰 생성(appendChild)하고 속성을 부여하면 됨
6. appendChilde를 여러번 호출하면 다중으로 생성될 줄 알았는데 그게 아님 for문 돌려야 할 듯 여기까지는 일단 정상적으로 작동하니 세이브하겠음