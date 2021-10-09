# javascript-note

## `<script>` 속성
* defer: html을 다 읽고 javascript를 실행 시켜주는 속성
* async: javascript를 바로 실행 시작 시키고, html을 계속 읽는다.(javascript가 언제 실행 될지는 모름)
* 속성이 없다면: 함수 처럼 javascript가 나왔을 때 실행을 모두 시킨 다음에 html을 진행한다. 

*.value, .innerHTML 이 가장 중요!
* eval: input 대화상자 내에서 javascript를 실행할 수 있다.(사용하면 안 됨)
* pre 태그가 div와 다른 점: 띄어쓰기 그대로 보여준다.
* innerHTML은 Delete가 안 됨. '' 공백으로 다시 써줘야 함.
* getElementsByName 는 배열로 가져다 준다.
