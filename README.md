# TIL

-10/02
+html 1-5 file 복습 새로 알게된것 : 콤보박스는 여러항목이 눌러야 보여서 선택하는 것이고 리스트 박스는 size를 설정해놔서 목록이 한눈에 다보인다.

-10/04 
+<link> 태그의 rel : relation의 줄임말. 링크 태그에 달리는 링크가 현재 페이지와 어떤 관계를 갖는지를 설명하는 attribute(속성)이다.
<link rel="stylesheet" type="text/css" href="css1.css"> 이것을 보고 찾아보게 되었는데 rel 뒤에 오는 말은 여러개가 있다. 그 중에 stylesheet라는 것은 스타일 시트를 가져온다는 의미로 써준것이다. 즉 css파일 가지고 올것이다 라는 말이다.

+text-indent :__px ; ->들여쓰기

-10/06
+ex)<img alt="" src="../images/image001.jpg">
꼭 이미지에는 alt 태그를 넣어야한다. 이미지가 정상적으로 인식되면 alt 안에 있던 텍스트 대신 이미지가 노출되지만, 만약 서버에 이상이 생겼다던지 혹은 이미지가 손상되었다면 이미지 대신 해당 메뉴가 뭔지 알 수 있게 해주는 것이 바로 alt 태그!
수업할때 src=""공란으로 계속 비워 둔것을 보고 비워놓는데 왜 필요하지 궁금해서 찾아보았다.

+return false - return;-> null값을 리턴  return true;-> true값을 리턴  return false;-> false 값을 리턴//
오늘 설문조사 or로그인 화면 같은 형식을 구현하면서 빈칸이 있는 것을 alter창이 뜨게 하는 것을했는데 return;을 써줘서 한가지가 비어있으면 뒤의 항목들 전부 물어보지 않게 순서상 맨처음 경고창만 뜨게 하는 것을 해서 return을 사용했다가 선생님이 return false를 쓰셔서 차이점을 찾아봤는데 그냥 return은 null값을 리턴해주는 것이고 retrun false는 false 값을 리턴해주는 것인데 
코드의 가독성에서 false로 명확하게 표시를 해주는 것이 더 좋은 것 같다는 의견들이 많았다.

-10/18
+이클립스 단축키 새로알게된것 : ctrl+D (행 삭제) ctrl+alt+a (컬럼선택) ctrl+ +/- (화면 확대/축소) ctrl+alt+down키 (행복사) ctrl+i(정렬) tab+shift(내어쓰기)

+변수(variable): 하나의 값을 저장하기 위한 공간//상수(constant) : 한 번만 값을 저장 가능한 변수 (앞에 final) //리터럴(literal) : 그 자체로 그 값을 의미하는 것

+e: 10^n의미한다. (ex. 1e3 == 10^3 == 1000.0d (e는 실수형이므로+ doubleg형이 default값)

+println은 10진수의 수만 출력가능하다.

+String타입에는 ""빈문자열 저장가능하지만  char타입에는 ''를 저장하려하면 에러가 난다.

+기본형(Primitive type) -8개 (boolean:논리형//char:문자형//byte, short, int, long:정수형//
float, double:실수형) -실제 값을 저장

참조형(Reference type)-기본형 제외 나머지 모두 (String, System 등) - 메모리주소를 저장

-10/19
+/n ,%n 둘다 줄바꿈으로 쓰는데(개행문자) /n은 os에 따라 적용이 안될수도 있다. %n은 os에 관계없이 개행문자 출력이 가능하다.

+ Scanner란 데이터를 입력받는 기능을 제공하는 클래스.
Scanner sc = new Scanner (System in) ->System in 은 화면으로 부터 입력을 받는다는 의미이다.

+"3" -> '3' 변환할시 : "3".charAt(0)
 '3'-'0' = 3(숫자 3)
 "3" + 1 = "3" + "1" = 31
 
+ 0.0 <= Math.random() < 1.0 : 0.0과 1.0사이의 임의의 double값을 반환 (0.0포함)

10/20
+ ctrl+shift+o ->import자동완성

+배열 선언
타입 [] (배열기호)  변수이름; ex) int [] score;

+배열 생성
변수이름 = new 타입[길이]; ex) score = new int[5]; 

+배열 선언과 생성 동시에
ex) int[] score = new int[5];

+객체배열
ex) Tv[] tvArr = new Tv[3]; -> Tv타입의 객체 3개를 배열로 생성한다

10/21
+ return문 : 실행중인 메서드를 종료하고 호출한곳으로 돌아간다.
 (주의)- return문은 반환타입이 void일 때만 생략가능하다
       - 조건식이 참일때 return값과, 거짓일 때 return값이 둘다 정의 되어있어야한다.
