<h2>문서의 구조와 슈퍼스타들</h2>

<h4>구조를 정리하자!</h4>

- \<title\> : 홈페이지의 타이틀 ( 검색엔진이 보는 엔트리포인트 )

- 영어가 아닌 문자가 깨지는 이유
    - 웹페이지가 저장된 문자 표현 방식 != 웹브라우저가 웹페이지를 해석하는 방식
    - use >>  \<meta charset="utf-8"\>

- title & meta : 본문을 설명하는 정보
    - 이들은 \<head\>
    - 본문은 \<body\>

- 이 문서가 HTML로 만들어짐을 알리는 코드
    - \<!doctype html\>
    - \<html\> - \</html\> :  사이에 head와 body로 나누는 것이 최종적인 그림.


<h2>HTML 태그의 제왕</h2>

<h4>길을 만들자! a tag, Link</h4>

- 페이지와 페이지, 정보간의 연결성을 만든다.
<br>
- a : anchor(닻)
- href : HyperText Reference
- target : _blank >> 새 창에 열리도록 설정
- title : tooltip, 어떤 내용을 담고 있는지
    ~~~
    <a href="https://www.w3.org/TR/html5/" target="_blank" title="html5 specification">Hypertext Markup Language (HTML)</a>
    ~~~


<h2>웹사이트 완성</h2>

<h4>최종적인 그림을 만들자!</h4>

- 순서대로 각 링크에 대한 파일명, 경로를 잡자.
    - index.html(main page), HTML.html, CSS.html, ...
    - 이를 a 태그로 엮으면 최종 완성!
        - 일단 웹 페이지의 구성이 만들어진 것이다.


<h2>원시 웹</h2>

<h4>웹의 시작은 어디인가.</h4>

- 인터넷 != 웹
    - 인터넷(1960 등장), 웹(1990 등장)
    - 웹은 인터넷의 일부 부분집합에 불과하다.
    - 그러나 웹으로 인해 인터넷이 일반적으로, 보편적으로 발전할 수 있었다.

- 최초의 웹사이트 (1990, 팀 버니스리)
    - http://info.cern.ch
    - 이후 인터넷과 웹은 동시에 폭발적으로 발전
