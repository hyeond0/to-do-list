# Vanila JS Lecture Study

10주 스터디 진행중!
23/01/16 ~ 23/01/29

노마드 코더 바닐라 JS로 크롬 앱 만들기 강의

https://hyeond0.github.io/to-do-list/

### 어려웠던 점 정리

- 높이 설정이 어려웠다. reset css를 하고 100vh로 높이를 설정한 뒤, 위 아래로 margin을 주면 원하는 모양이 나올 줄 알았는데 box-sizing을 해줘도
페이지 스크롤이 넘어가는 현상이 계속 발생했다.

- @Import로 css 파일을 여러 개 나누고 싶었는데 reset css에 넣으면 작동했지만 새로운 파일 만들어서 그 안에 넣고 import를 시키면 작동하지 않았다.

- ID 와 클래스의 우선순위. 코코아톡 강의에서는 그냥 다 냅다 클래스로 지정햇는데, 이번 강의에선 id를 자주 사용하길래 id를 사용하는 방식으로 진행해봤는데
  추가된 class를 css 아래 순서로 보내도 id로 설정한 css가 더 우선순위에 있는 느낌을 받았다.

- 체크박스 커스텀이 어려웠다. 기본 체크박스는 커스텀하지 못하고, 그에 대응되는 label을 만들어 

- 투두리스트 입력 화면에서 시간이 지날때마다 너비가 달라져서 뚝뚝 끊기는걸 고정시켜주고 싶었는데 width를 px로 고정시키는 방법 말고는 떠오르지 않았다.
반응형 디자인에 대한 공부를 더 열심히 해야할 것 같다.
