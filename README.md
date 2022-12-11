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
- Typescript

# HTML+CSS

헤더 바디가 없으면 그냥 바디로 인식
html 없는 태그면 없는거랑 같다
엔테티 코드 특수문자
여러개 연속적인 화이티 캐릭터는 한칸으로 취급
pre는 그대로 출력

![캡처6](https://user-images.githubusercontent.com/80075223/204142494-7a843763-70be-475e-bc73-694451631f56.PNG)

#> CSS 3가지 박스 유형 비교
|인라인 박스(display:block)|인라인 박스(display:inline)|인라인 블록 박스(display:inline-block)|
|---|---|---|
|항상 새라인에서 시작|새라인에서 시작 못함 라인안(inline)에 있음|새라인에서 시작 못함 라인안(inline)에 있음|
|블록박스 내에만 배치|모든 박스 내 배치|모든 박스 내 배치|
|옆에 다른 요소 배치 불가능|옆에 다른 요소 배치 가능|옆에 다른 요소 배치 가능|
|width와 geight으로 크기 조절|width와 height으로 크기 조절 불가능|width와 geight으로 크기 조절|
|padding, border, margin조절 기능|margin-top, margin-bottom조절 불가능|padding, border, margin조절 불가능|

# POSITION
|속성|속성값|설명|
|---|---|---|
|정적배치|static|요소를 문서의 흐름에 맞추어 배치. 위치지정이 필요없음|
|상대배치|relative|이전요소에 저연스럽게 연결해 배치하되 위치를 지정할 수 있음|
|절대배치|absolute|원하는 위치를 지정해 배치|
|고정배치|fixed|지정한 위치에 고정해 배치. 화면에서 요소가 잘릴 수도 있다|

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

```
.<input type email>
.<form>
  .<!-- required 속성을 추가했다 -->
  .<input name="email" required />
  .<button type="submit">제출</button>
.</form>
```

------------------------------------------------------------------------------
   
셀럭터 css 스타일 시트를 html 페이지에 적용하도록 만든 이름
html 태그의 모양을 꾸밀 스타일 시트를 선택하는 기능


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

코드 스니펫

# Javascript

마우스 올리면 onmouseover 마우스 나가면 onmouseout

스크립트는 바디 제일 아래쪽에 있는게 좋다

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
Browser의 Rendering_2. Render Tree의 생성

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

----------------------------------------------------------------

버튼 누르면 파일 다운로드 가능한 명령어
<a href="" download=""><button>↓ Free Download</button>

# 나의 포트폴리오

|Feature|Description|
|:--:|:--:|
|ABOUT|![1](https://user-images.githubusercontent.com/80075223/204162967-7ff4e882-a924-470e-9c81-5c75116eb36e.PNG)
|EDUCATION|![2](https://user-images.githubusercontent.com/80075223/204162977-0db6c820-b4ac-41c8-a5dd-d35810044ea4.PNG)
|SKILLS|![3](https://user-images.githubusercontent.com/80075223/204162985-e2b14886-008e-4be7-b54f-5e68fd08ceed.PNG)
|PORTFOLIO|![4](https://user-images.githubusercontent.com/80075223/204162993-2b13abb0-482c-4fe6-91dc-3f328f2693ab.PNG)
|LINK|[GITHUB](https://rhkdtjq0915.github.io/Portpolio/)/[NETLIFY](https://cerulean-blini-40f9b7.netlify.app)|
  
