# TIL

-10/02- html 1-5 file 복습 새로 알게된것 : 콤보박스는 여러항목이 눌러야 보여서 선택하는 것이고 리스트 박스는 size를 설정해놔서 목록이 한눈에 다보인다.

-10/04 -<link> 태그의 rel : relation의 줄임말. 링크 태그에 달리는 링크가 현재 페이지와 어떤 관계를 갖는지를 설명하는 attribute(속성)이다.
<link rel="stylesheet" type="text/css" href="css1.css"> 이것을 보고 찾아보게 되었는데 rel 뒤에 오는 말은 여러개가 있다. 그 중에 stylesheet라는 것은 스타일 시트를 가져온다는 의미로 써준것이다. 즉 css파일 가지고 올것이다 라는 말이다.

-text-indent :__px ; ->들여쓰기

-10/06
ex)<img alt="" src="../images/image001.jpg">
꼭 이미지에는 alt 태그를 넣어야한다. 이미지가 정상적으로 인식되면 alt 안에 있던 텍스트 대신 이미지가 노출되지만, 만약 서버에 이상이 생겼다던지 혹은 이미지가 손상되었다면 이미지 대신 해당 메뉴가 뭔지 알 수 있게 해주는 것이 바로 alt 태그!
수업할때 src=""공란으로 계속 비워 둔것을 보고 비워놓는데 왜 필요하지 궁금해서 찾아보았다.

-return false - return;-> null값을 리턴  return true;-> true값을 리턴  return false;-> false 값을 리턴//
오늘 설문조사 or로그인 화면 같은 형식을 구현하면서 빈칸이 있는 것을 alter창이 뜨게 하는 것을했는데 return;을 써줘서 한가지가 비어있으면 뒤의 항목들 전부 물어보지 않게 순서상 맨처음 경고창만 뜨게 하는 것을 해서 return을 사용했다가 선생님이 return false를 쓰셔서 차이점을 찾아봤는데 그냥 return은 null값을 리턴해주는 것이고 retrun false는 false 값을 리턴해주는 것인데 
코드의 가독성에서 false로 명확하게 표시를 해주는 것이 더 좋은 것 같다는 의견들이 많았다.


