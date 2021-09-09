## Day6 Study - props & state
* **(1)ch6-todo-list-입력창생성**<br/>
: p.131-134 : Input 컴포넌트 생성과 Component 파일에서 불러오도록 수정

* **(2)ch6-todo-list-입력창-props**<br/>
: p.134-136 : Input 컴포넌트의 재사용성을 향상하기 우해서 placeholder의 내용을 Props를 사용하여 부모 컴포넌트로부터 전달받은 데이터를 표시하도록 수정

* **(3)ch6-todo-list-사용자입력출력**<br/>
: p.136-138: 사용자로부터 입력받은 데이터를 단순히 개발자 콘솔에 출력하는 코드 (onChange, console.log 사용)
![(3)ch6-todo-list-사용자입력출력](https://user-images.githubusercontent.com/50728605/132688553-33ea2f7c-5b09-4b0a-a8b4-91255ed7f7c1.gif)

* **(4)ch6-todo-list-ToDoItem컴포넌트 생성**<br/>
: p.138-140: 새로운 ToDoITem이라는 컴포넌트를 구성한다.

* **(5)ch6-todo-list-ToDoItem컴포넌트 재사용**<br/>
: p.140-142: 새로운 ToDoITem이라는 컴포넌트를 재사용이 가능한 컴포넌트로 수정한다.

* **(6)ch6-todo-list-ToDoItem 부모컴포넌트로부터**<br/>
: p.143-144: 공통 컴포넌트로 만든 ToDoItem 컴포넌트를 부모 컴포넌트로부터 데이터를 받을 수 있도록 수정
![(6)ch6-todo-list-ToDoItem 부모컴포넌트로부터](https://user-images.githubusercontent.com/50728605/132688615-67581aab-8b2b-4ddd-8d49-d9091fe532d6.gif)

* **(7)ch6-todo-list-State_추가버튼 수정**<br/>
: p.144-146: useState, set함수를 활용하여 State를 사용하여 동적인 데이터를 다루기 위해 App컴포넌트를 수정<br.>  
==>  데이터를 입력하고 추가버튼을 눌렀을 때, 경고창의 값이 변경된다.
![useState 추가버튼 수정](https://user-images.githubusercontent.com/50728605/132695987-9aa649d1-a028-4def-a2b6-2d5b25d94ee3.gif)

* **(8)ch6-todo-list-최종본**<br/>
: p.146-154: 할 일 리스트 완성 (상당히 많은 수정과 코드의 변화가 있으니 책을 잘 보고 공부해볼 것!!!
![할일리스트 완성](https://user-images.githubusercontent.com/50728605/132696011-bc78efbe-a620-475f-a034-6bbce17331b3.gif)
