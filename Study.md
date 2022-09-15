# boostcourse


1) 2진법<br>
- 컴퓨터의 언어이다.(0, 1)<br>

#### bit
- 컴퓨터는 많은 수의 비트를 활용하여 정보를 표현한다.<br>
- bit 는 on/off로도 사용이 가능하며 1은 전원 on 상태를 0은 전원 off 상태로 표현하며 이를 2진수(binary) 또는 비트(Bit) 라고한다.<br>

#### byte
- 컴퓨터는 일반적으로 8개 단위의 비트(8bit)를 하나의 그룹으로 사용하는데 이를 바이트(Byte)라한다.( 8bit = 1byte )<br>

2) 정보의 표현<br>
#### ASCII<br>
- 정보 교환을 위한 미국 표준 코드로 8개의 bit만 사용.<br>

#### 유니코드<br>
- 8, 16, 24 혹은 32bit까지도 사용하며 훨씬 더 많은 0과 1의 패턴들을 나타낼 수 있고 이모티콘도 표현 가능하다.<br>

# RGB<br>
- 빨강(Red), 초fhr(Green), 파랑(Blue) 의 약자로 빝의 속성을 그대로 지니기 때문에 3가지 색상을 모두 섞으면 흰색이 된다.
- 16진수 색상코드(HEX 색상코드)는 16진수 2자리 16 * 16 = 256이므로 16진수 2자리당 0~ 255의 범위를 표현할 수 있다.
- 16진수 색상 코드는 앞에 (#)이 붙는다.

3) 알고리즘(algorithm) : 문제를 해결하는 절차나 방법을 자세히 설명하는 과정.
https://www.boostcourse.org/cs112/lecture/118999?isDesc=false

- 의사코드 : 프로그램 코드를 작성할 때 사용하기 위해, 프로그램의 진행 과정을 단계별로 기록해 놓은 것.

4) 스크래치 : 기초 
https://www.boostcourse.org/cs112/lecture/119000?isDesc=false

5) 스크래치 : 심화
https://www.boostcourse.org/cs112/lecture/119001?isDesc=false


1. Javascript
- WEB과 Javascript, HTML
- WEB이 처음 등장했을 때, 사람들은 HTML을 사용해서 정보를 주고받았습니다.
- 하지만 HTML은 정적입니다. 한 번 출력되면 그 모양이 바뀌지 않죠.
- 사용자와 동적으로 상호작용하는 WEB을 만들기 위해서 Javascript가 등장했습니다.
- 이제 우리는 HTML을 이용해 웹페이지를 만들고, Javascript를 이용해 사용자와 상호작용할 수 있도록 추가할 겁니다.
- 즉, 정적인 정보인 HTML을 Javascript가 동적으로 만들어 주는 것입니다.

2. Javascript, 동적 https://www.boostcourse.org/cs124/lecture/141897?isDesc=false
- Javascript는 사용자와 상호작용 하는 언어입니다. 그리고 우리는 실습을 통해서 어떻게 이러한 일이 가능한지 살펴보았습니다. 
- 웹 브라우저는 한 번 출력되면 바뀔 수 없지만, Javascript 코드에 따라서 style 속성이 추가되면서 디자인이 바뀌는 것입니다.
- 이러한 Javascript의 특성을 이용해서 우리는 웹페이지를 더 동적으로 만들 수 있습니다.

3. HTml과 JS의 만남 : script 태그 https://www.boostcourse.org/cs124/lecture/141898/?isDesc=false
- Script 태그 (HTML에서 Javasxript 코드를 사용하기 위해서 script 태그를 사용할 수 있다.)
- HTML / Javascript

4. HTMl 과 JS의 만남 : 이벤트 https://www.boostcourse.org/cs124/lecture/141899/?isDesc=false
- 이벤트(Event)
- onclick, onchange

5. HTMl과 JS의 만남 : 콘솔 https://www.boostcourse.org/cs124/lecture/141900/?isDesc=false
- 콘솔(Console) : 웹 페이지에서 F12 안에서 소스 코드를 볼수 있음.

6. 데이터 타입(문자열과 숫자열) https://www.boostcourse.org/cs124/lecture/194588/?isDesc=false
- Boolean
- Null
- Undefined
- Number
- String 'Hello world'.length 문자열의 글자 갯수를 알려준다.
- Symbol (new in ECMAScript 6)
- 참고 사이트 https://developer.mozilla.org/ko/docs/Web/JavaScript

7. 변수와 대입연산자 https://www.boostcourse.org/cs124/lecture/194589/?isDesc=false
- 변수(Variable의 약어 var)
- 대입 연산자
- 상수(Constant)
web 페이지 F12 콘솔 창에서 실행유보를 시키려면 Shift + Enter 키 사용.

8. 웹브라우저 제어 https://www.boostcourse.org/cs124/lecture/194590/?isDesc=false
- 웹 브라우저 제어 html은 정적인 언어로 제어능력이 없고 javascript 는 동적이며 웹페이지 제어가 가능하다.
- style, css

9. CSS기초(style) https://www.boostcourse.org/cs124/lecture/194591/?isDesc=false
- CSS (검색시에는 CSS background color property)
- style 속성(property)
- color, background-color
* 참고자료 https://www.w3schools.com/cssref/pr_background-color.asp

10. CSS기초(style)태그 https://www.boostcourse.org/cs124/lecture/194592/?isDesc=false
- div 태그 : 화면 전체를 사용하기 때문에 줄 바꿈이 가능.
- span 태그 : 화면 전체를 사용하지 않아 줄 바꿈이 되지 않는다.
* 모든 태그를 div나 span 태그로 감싸기가 힘들고 수정하기도 어렵기 때문에 class를 사용한다.
- class : CSS코드를 적용시킨다.

11. CSS기초(선택자) https://www.boostcourse.org/cs124/lecture/194593/?isDesc=false
- id 선택자 id는 어떤한가지만 식별할때 사용하고 #id명으로 시작한다.
- class 선택자 클래스를 지칭할때는 .클래스명 으로 시작한다.
** class는 그룹을 의미하고, id는 특정한 태그만 지정한다.
** class는 중복이 가능하지만, id는 한 페이지에서만 한번만 사용 가능하다.
- 태그 선택자
** 우선순위 id > class > 테그

12. 제어할 태그 선택하기 https://www.boostcourse.org/cs124/lecture/194594/?isDesc=false
- querySelector https://developer.mozilla.org/ko/docs/Web/API/Document/querySelector
- querySelector라는 함수를 사용하면 이러한 선택자를 이용해서 원하는 태그를 선택할 수 있습니다. 다음과 같이 사용할 수 있습니다.
- <input type="button" value="night" onclick="documnet.querySelector('body').style.backgroundColor = 'black';">

### Javascript 제어문
13. 프로그램, 프로그래밍, 프로그래머
