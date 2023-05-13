# 1. 폼과 유효성 검사
## Form 이란?
폼, 입력 폼은 웹 프로그래밍의 기술의 하나이다. 클라이언트가 정보를 입력 · 선택하고, 웹 서버 등의 폼을 처리하는 에이전트로 제출하기 위한 기구이다.
<blockquote>
<body>
    <form action="" method="" enctype="">
        <input type="text" name="test"> <br><br>
        <input type="submit">
    </form>
</body>
</blockquote>
HTML의 폼은 위의 코드와 같이 클라이언트에게 보낼 Input 태그를 감싸는 형태로 작성된다.

form 태그의 속성인
action 은 데이터를 받아서 보낼 url 주소를 정한다.
method 는 데이터를 GET,POST,PUT...어떤 방식으로 보낼지 정한다.
enctype 은 데이터의 인코딩 방식을 정한다.


이렇게 form은 자신의 태그 안에 있는 input 태그들의 정보들을 모아 action에 설정된 url로 method에 정의된 방식으로 데이터를 enctype에 따라 보내게 된다.
이 코드는 첫번째 input인 test에 적은 값을 url로 보낸다. 하지만 action에 url을 지정하지 않았기에 아무일도 일어나지 않는다..
<code> </code>
