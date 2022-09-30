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
- 프로그램(순서라는 의미) 
- 프로그래밍(순서를 만드는 의미)
- 프로그래머(순서를 만다는 사람)

#### HTML과 Javascript의 비교 https://www.boostcourse.org/cs124/lecture/194603?isDesc=false
- HTML로 만든 웹페이지는 시간의 순서에 따라 실행되지 않고, 한 번 만들어지면 바뀌지 않습니다. 때문에 HTML은 컴퓨터 프로그래밍 언어가 아닌 것이죠.
반면에 Javascript는 사용자와 상호작용하고, 이를 위해서 시간에 따라 여러 기능이 실행되어야 하기 때문에 프로그래밍이라는 형태를 띄게 됩니다. 따라서 Javascript는 컴퓨터 프로그래밍 언어라고 부를 수 있는 것입니다.
그리고 더 나아가서 시간에 따라 코드가 실행되는 것 외에도, 조건에 따라 다른 코드가 실행되도록 하거나, 같은 코드가 반복적으로 실행할 수 있는 방법도 고안하게 된 것입니다.

14. 조건문 예고 https://www.boostcourse.org/cs124/lecture/194604/?isDesc=false
- 조건문 : 프로그램이 조건에 따라서 다른 기능들이 다른 순서에 따라서 실행되도록 만들어주는 것
- if / else
- 토글(toggle) : 하나의 설정 값으로부터 다른 값으로 전환하는 것

15. 비교연산자와 블리언 https://www.boostcourse.org/cs124/lecture/194605/?isDesc=false
- 비교 연산자 ===
- 블리언(Boolean) : true & false
- 비교 연산자 <(&lt;) >(&gt;)

16. 조건문 https://www.boostcourse.org/cs124/lecture/194606/?isDesc=false
- if / else

17. 조건문의 활용 https://www.boostcourse.org/cs124/lecture/194607/?isDesc=false
- 조건문
- 토글
- querySelector와 value 구글 검색시 javascript element get value

18. 리팩토링(사용자가 편리하게 사용할 수 있도록 기능을 개선한다.) https://www.boostcourse.org/cs124/lecture/194611/?isDesc=false
- 리팩토링 : 비효율적인 코드를 효율적으로 만들어서 가독성을 높이고 유지보수가 쉽도록 만드는 것입니다. 코드의 기능적인 면에서는 변화가 없도록 말이죠.
- this : Javascript에는 자기 자신을 가리키기 위한 this라는 키워드가 있습니다. document.querySelector('#night_day') 대신 this를 써도 되는 것이죠. 
- 변수 : document.querySelector('body') 를 var target = document.querySelector('body'); 선언하여 긴 코드를 줄인다.

19. 반복문 예고 https://www.boostcourse.org/cs124/lecture/194612/?isDesc=false
- 반복문 : 같은 작업을 반복적으로 실행 하는 문법
var links = document.querySelectorAll('a');
var i = 0;
while (i<links.length) {
  links[i].style.color = 'powerblue';
  i=i+1;
}

20. 배열
- 배열(Array) : document.write(fruits[0]);
- length : document.write(fruits.length); (배열뒤에 length를 쓰면 그 배열의 길이를 나타낸다.)
- push : fruits(변수명).push(명령어)("coconut");(배열에 값 추가하기)

21. 반복문 https://www.boostcourse.org/cs124/lecture/194614/?isDesc=false
- While문 : 순서대로 실행되는 프로그램의 실행 프름을 제어하는 제어문이다. 
- 조건문 

22. 배열과 반복문 https://www.boostcourse.org/cs124/lecture/194615/?isDesc=false
- 반복문
- 배열

23. 배열과 반복문의 활용 https://www.boostcourse.org/cs124/lecture/194616/?isDesc=false
- 반복문과 배열
- querySelectorAll(Javascript element css selector multiple 검색) : querySelector와 사용 방법은 동일하며 선택자를 선택하여 배열과 비슷한 객체인 nodeList를 반환한다.

24. 함수 예고 https://www.boostcourse.org/cs124/lecture/194627
- 함수란 무엇인지 이해하고, 함수를 사용할 때의 장점을 알아본다.

25. 함수 https://www.boostcourse.org/cs124/lecture/194628/?isDesc=false
- 함수 : 프로그래밍에서 함수(function)란 하나의 특별한 목적의 작업을 수행하기 위해 독립적으로 설계된 프로그램 코드의 집합으로 정의한다.
- 함수를 사용하는 가장 큰 이유는 바로 반복적인 프로그래밍을 피할 수 있기 때문입니다.
- 프로그램에서 특정 작업을 여러 번 반복해야 할 때는 해당 작업을 수행하는 함수를 작성하면 됩니다.
- 그리고서 프로그램이 필요할 때마다 작성한 함수를 호출하면 해당 작업을 반복해서 수행할 수 있습니다.

26. 함수-매개변수와 인자 https://www.boostcourse.org/cs124/lecture/194629/?isDesc=false
- 매개변수(parameter) : sum의 괄호 안에 들어오는 두 숫자를 각각 left, right라는 변수에 넣는 것이죠. 이 때 이러한 변수를 매개변수라고 한다.
- function sum(left, right) {
  document.write(left + right);
}
- 인자(Argument) : sum(2,3); sum의 괄호 안에 넣어서 함수로 전달해주는 저 숫자 2, 3을 보고 인자라고 한다.

27. 함수-리턴 https://www.boostcourse.org/cs124/lecture/194630/?isDesc=false
- return이 필요한 이유는 return 을 사용하여 인자를 자유롭게 수정하여 다양한 결과를 만들수 있다.

28. 함수 활용 https://www.boostcourse.org/cs124/lecture/194631/?isDesc=false
- 함수를 잘 활용하면 중복되는 코드를 제거하고 가독성이 높아진다.
- this : 전역객체  = 당 코드가 포함된 태그를 가르켜 준다. self : 매개변수 = this를 script태그내의 function 함수의 매개변수로 가져온다.

29. 객체 예고 https://www.boostcourse.org/cs124/lecture/194638
- 객체(Object) : 서로 연관된 함수와 변수가 아주 많아지면 이를 정리하기 위해서 사용
- 메소드(Method) : document.querySelector('body'); 여기에서 document가 바로 객체이고, querySelector가 document라는 객체에 속해 있는 함수라고 생각할 수 있는 것입니다. 이렇게 객체에 속해 있는 함수들은 메소드(Method)라한다.
- 변수 

30. 객체(쓰기와 읽기) https://www.boostcourse.org/cs124/lecture/194639/?isDesc=false
- 객체 : 이름이 있는 정리 정돈 상자.

31. 객체(순회) https://www.boostcourse.org/cs124/lecture/194640/?isDesc=false
- 순회(iteration) : 모든 값들을 가져오는 방법
- for in 

32. 객체(프로퍼티와 메소드) https://www.boostcourse.org/cs124/lecture/194641/?isDesc=false
- 메소드 : 객체에 해당하는 함수들은 메소드
- 프로퍼티(Property) : 객체에 해당하는 변수

33. 객체의 활용 https://www.boostcourse.org/cs124/lecture/194642/?isDesc=false
Body.setColor('black');
Links.setColor('powderblue');
- 함수의 이름이 같아도 다른 객체에 소속된 메소드이기 때문에 충돌이 일어나지 않는 것이죠.
- 함수의 이름에 대한 부담이 덜어졌고 관련된 함수들을 객체 안에 모아둘 수 있어서 코드의 가독성이 올라갔다.

Quiz 4 
1) 객체에 대한 설명으로 옳은 것을 고르시오.
- 서로 연관된 함수와 변수를 그룹화해서 정리정돈하기 위한 도구이다.

2) 객체를 만들기 위한 방법으로 옳은 것을 고르시오.
- var coworkers = {"programmer" : "egoing"};

3) 객체의 사용법으로 올바르지 않은 것을 고르시오.
- coworkers.data scientist = "taeho";

4) 객체를 순회하기 위한 방법으로 옳은 것을 고르시오.
- for (var key in coworkers)

5) 객체의 메소드 안에서 객체 자신을 가리키는 키워드로 올바른 것을 고르시오.
- this

6) 다음 코드에서 querySelector를 부르는 용어로 올바른 것을 고르시오.
document.querySelector("body");
- method

7) 객체의 프로퍼티와 프로퍼티를 구분하는 기호로 올바른 것을 고르시오.
- ,

34. 파일로 쪼개서 정리 정돈하기 https://www.boostcourse.org/cs124/lecture/147572
- js파일 : 이 짧은 script 코드를 필요한 페이지에 붙여 넣으면 이 Javascript 코드를 한 번에 관리할 수 있는 것이다. 
- 코드를 재사용할 수 있고, 동시에 코드를 수정할 수 있어서 유지보수가 편리해집니다. 코드가 명확해지고 가독성이 좋아진다는 장점이 있다.
- script의 src(source)속성 : 
- 생각해보기 : 여러 js 파일을 가져오고 싶다면 어떻게 하면 좋을지 알아봅시다. (힌트: html include multiple js files 라고 검색해보세요!)

35. 라이브러리와 프레임워크 https://www.boostcourse.org/cs124/lecture/147573
- 라이브러리 : 프로그램에 필요한 부품이 되는 소프트웨어가 정리되어 있는 것
- 프레임워크 : 만들고자 하는 프로그램의 종류에 따라서 공통적인 부분을 미리 만들어놓는 것
- jQuery : Javascript 라이브러리 중 하나는 jQuery입니다. 이 라이브러리를 사용하면 생산성을 높일 수 있습니다. 인터넷에서 jQuery를 다운로드하는 방법도 있고, CDN이라는 방법을 사용해도 됩니다. CDN을 사용하면 코드를 한 줄 추가하는 것만으로도 라이브러리를 가져와서 사용할 수 있습니다. 예를 들어 jQuery의 구글 CDN은 다음과 같습니다. (jQuery 홈페이지에서 찾을 수 있습니다.)
- <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
- 생각해보기  jQuery를 직접 자신의 HTML 파일에 추가해보고, 이를 이용해서 모든 h1 태그의 글자 크기를 바꾸는 코드를 작성해 봅시다.
- <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
$('h1').css('font-size', '20px');

36. UI vs API
- UI(User Interface) 
- API(Application Programming Interface)
- 생각해보기 UI 와 API는 어떤 관계를 가지고 있을까? 개발자가 호풀하도록 만든 장치(API)를 사용자가 화면을 통해 조작한다(UI)

37. 수업을 마치며
- 프로젝트  
1. 모든 개념을 총 동원하려고 하지 말것 최소한의 도구로 문제로 해결.
2. 순서대로 실행된다.


웹 개발과 관련된 검색어
- 하지만 이렇게 여러 개념들을 활용하다보면 다시 한계에 부딪히게 될 겁니다. 그 때에는 여러분들이 새롭게 공부를 시작하셔야 합니다. 그 때 도움이 될만한 여러 검색어를 알아봅시다.
- 먼저 태그를 삭제하거나 자식 태그를 추가하고 싶은 경우에는 document라는 객체를 살펴보세요. 그래도 찾을 수 없다면 DOM 객체에 대해서도 살펴보세요.
- 만일 웹브라우저 자체를 제어해야 하는 경우, 예를 들면 웹페이지의 주소를 알아낸다거나, 창을 열거나 해야 하는 경우에는 windows 객체의 프로퍼티나 메소드를 찾아보세요.
- 웹페이지를 새로고침하지 않고도 정보를 변경하고 싶다면 ajax를 사용해보세요. 반대로 웹페이지가 새로고침되어도 현재 상태를 유지하도록 만들고 싶으면 cookie에 대해서 배워보세요.
- 인터넷이 끊겨도 동작하는 웹페이지를 위해서는 offline web application을 찾아보세요. 
- 화상 통신 웹 앱을 만들고 싶을 때에는 webRTC를 찾아보면 됩니다. 음성을 인식하거나 음성과 관련된 것을 처리하고 싶을 때에는 speech로 시작되는 API들을 살펴보세요.
- 3차원 그래픽을 이용하고 싶다면 webGL, 가상현실에 대해서 알아보고 싶다면 webVR에 대해서 찾아보시면 됩니다.
