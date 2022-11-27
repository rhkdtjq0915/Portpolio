# 목표는 성실한 프로그래머
>다루었던 언어
- Python

>사용중인 언어
- HTML
- CSS
- Javascript
- PHP
- Mysql 
- C#

# HTML+CSS

헤더 바디가 없으면 그냥 바디로 인식
html 없는 태그면 없는거랑 같다
엔테티 코드 특수문자
여러개 연속적인 화이티 캐릭터는 한칸으로 취급
pre는 그대로 출력

인라인태그  
+ 내용과 앞뒤 태그의 내용을 같은 라인에 출력
+ 내용물의 크기가 태그의 영역이 된다.
+ 정해진 역할 X
+ 인라인태그는 자식으로 또다른 인라인태그만 올 수 있다

블럭 태그 
* 다른 라인에 출력
* 내용물의 크기와 상관없이 너비는100%고정 높이는 내용의 크기에 맞춤
* 자신의 내용만으로 한 라인을 독점해서 출력
* 영역(구조)을 만들때 사용 > 컨테이너 역할 > 레이아웃 구성(틀 만들기)
* 블럭 태그는 자식으로 또다른 블럭 태그 or 인라인 태그를 가질 수 있다.

blank
* 새 윈도우 창을 열어서, 웹페이지를 연다	. 
* 기존의 창은 그대로 남겨져 있다.

self 
* 현재 윈도우창에 그대로, 링크된 웹페이지를 연다. ( 현재의 프레임 )

parent 
* 현재 프레임의 부모 프레임에서 새웹페이지가 열린다 .만약 어떤 창 A에서 창 B를 새로 열었습니다. 그런데 창 B에서 _parent로 창을 열면 창 A에서 열리게 된다.

top 
* 최상위 프레임에서 열립니다. _parent와 비슷하다.  _parent는 바로 이전창(부모창)에서 열리는 반면_top은 최상위( 가장 최고 부모)창에서 열린다.

form
* 사용자로부터 데이터를 입력 받기 위한 페이지

required 
* 속성 뿐이지만 브라우져는 필수 입력으로 알고 값을 검증한다. 사용자가 올바로 입력하고 제출하기 버튼을 클릭한다면 기대한 것처럼 서버로 폼을 전송한다.

<input type email>
<form>
  <!-- required 속성을 추가했다 -->
  <input name="email" required />
  <button type="submit">제출</button>
</form>

GCP는 데이터 분석 및 AI 기술에 강점을 보이는 듯합니다. 
1. 다른 MS 서비스 및 제품과 일관된 통합
2. Linux 및 오픈 소스 애플리케이션 스택에 대한 많은 도움 제공
3. 하이브리드 클라우드에 완벽한 솔루션
4. 가상 환경에서 모두 잘 실행되는 사용 사례들
   
------------------------------------------------------------------------------
   
셀럭터 css 스타일 시트를 html 페이지에 적용하도록 만든 이름
html 태그의 모양을 꾸밀 스타일 시트를 선택하는 기능

css 참고 사이트
bootstrap
bulma

p태그는 em의 부모 태그

한개 이상을 지정할때 class
한개만 지정할때 id

strong 빈칸(띄어쓰기)

margin 바깥
padding 안쪽 여백

윈도우+. 이모지

display
position
z-index
visibility
overflow

https://ambler.kr/css   css게임

코드 스니펫

# Javascript

마우스 올리면 onmouseover 마우스 나가면 onmouseout

스크립트는 바디 제일 아래쪽에 있는게 좋다

web tech camp  javascript 파트 유튜브 참고
https://www.koreahtml5.kr/front/reference/referenceList.do?bbsId=BBS_00000000014 에서 교육자료

변수 선언에는 기본적으로 const를 사용하고, 재할당이 필요한 경우에 한정해 let 을 사용하는 것이 좋다.
Var : 중복 선언 가능 앵간하면 쓰지마라
호이스팅이란 함수 내부에 있는 선언들을 모두 끌어올려 해당 함수 유효 범위의 최상단에 선언하는 것을 뜻함

시프트 >> << >>> <<< bit로 들어감  ex) a << 1 = a x 2의1승  a << 2 = a x 2의2승 a >> 1 = a%2의1승  a >> 1은 a = -16  1 1 1 1 0 0 0 0  오른쪽으로 밀면(a >> 2) -8이 됨  제일 왼쪽이 0이면 플러스 1이면 마이너스
왼쪽 혹은 오른쪽으로 미는것
msb: 제일 왼쪽 비트,최상위 비트
보수까지 알아둘것

switch 값에 따라 서로 다른 코드를 실행할 때
eval 수식을 적어 놓으면 계산해주는 함수
parseint문자를 숫자로 바꿔주는 함수
isNaN 숫자가 아닌가 묻는 함수 맞으면 TURE 아니면 FALSE

-------------------------------------------------------
파라미터에 함수가 들어갈 수 있음(1급 함수)

객체
Class -> Object
명사, 동사
명사property, member variable, field
동사function, methon

Class
   변수 3개, 함수 2개
Object1, Object2,  Object3
OOP Object Oriented Programming 

코어 객체
자바스크립트 언어가 실행되는 어디서나 사용 가능 기본 객체
Array, date, string, math
객체와 멤버 사이에 점(.)연산자 이용

tml dom객체
html문서에 작성된 각 html 태그들을 객체화

배열
여려 개의 원소들을 연속적으로 저장
전체를 하나의 단위로 다루는 데이터 구조
배열은 []로 생성해도 array객체로 다뤄짐
concat 연결

브라우저 객체

(중요)
프롬프티 메소드 2가지가 있음
사용자 객체 만들기
1.직접 객체 만들기
new 
 Object()이용
리터럴 표기법 이용
2.객체의 틀()

----------------------------------------------
HTML DOM
웹페이지에 작성된 GTML 태그 당 객체 생성

HTML DOM 트리
HTML태그의 포함관계에 따라 dom 객체의 트리 생성
DOM 트리는 부모 자식 관계

DOM 객체
DOM 트리의 한 노드
HTML 태그 당 하나의 DOM 객체 생성

dom트리에서 하나씩 찍어주는것 렌더링

리엑트

DOM 트리의 특징
브라우저가 html 태그를 화면에 그리는 과정

렌더트리
Browser의 Rendering_2. Render Tree의 생성 https://twofivezero.tistory.com/56

태그 콘텐츠 합쳐서 엘리멘트
html 태그

dom객체의 프로퍼티와 dom 객체사이의 관계

com객체 다루기

this

document 객체

dom 트리에서 dom 객체 찾기

document.write()

open() close()

문서의 동적 구성


|Feature|Description|
|:--:|:--:|
|PHP|![cabin](https://user-images.githubusercontent.com/80075223/204135520-c9e038f4-a4c2-4fe8-af83-963f47539d4a.PNG)
|HTML + CSS|![circus](https://user-images.githubusercontent.com/80075223/204135538-94a28d03-c4bb-46a0-ab97-b58c9be3c9e4.PNG)
|Javascript|![safe](https://user-images.githubusercontent.com/80075223/204135550-8d75aac5-2be0-45c0-a0f4-a253d9d71acb.PNG)
|C#|![캡처3](https://user-images.githubusercontent.com/80075223/204135845-e31577f4-5efe-4f10-a985-a3591c350694.PNG)
   
GITHUB [here](https://rhkdtjq0915.github.io/Portpolio/)

NETLIFY [here](https://cerulean-blini-40f9b7.netlify.app)
