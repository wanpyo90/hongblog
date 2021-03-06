---
layout: page
permalink: /web_1/
title: Web강의
description: "web special lecture"
tags: [Jekyll, theme, install, setup]
image:
  feature: lecture_3_logo.jpg

share: true
---


##- Front End Web Application 개발 기초 - 

###'14.11.04 현재.... 시작단계의 기술

강사님 = 문성훈 강사님 ( moon9342@gmail.com // 010 - 3764 - 7807 )

HTML5, javascript, jQuery, AJAX, UI Framework -> 공부해두면 매우 유용! 취직하는데도 좋다!

Front-End = 사용자에 밀착해 보여주고 기능 수행

Back-End = 기존기능(화면 뒤에서 보이지 않고 수행)

HTML / CSS = 정적!
javascript = 동적

### HTML
1. 보여줄 내용을 작성(문서 구조를 표현)
2. 클라이언트에서 보여줄 화면에 대한 문서구조
3. 문서내용을 작성하기 위한 프로그래밍 언어
4. 브라우저 언어 기반
5. W3C에서 표준안 제안

### CSS
1. 화면 구조 설계
2. 레이아웃 작성
3. 문서 장식
4. W3C에서 표준안 제안

### javascript
1. 이벤트담당(처리)
2. 화면의 동적제어 담당
3. "ECMA(유럽표준기구)"에서 표준안
4. 피상적인 사용(알면 좋지만 몰라도 긁어다 쓰면되지..)
5. 문법을 익혀서 쓰기보다는 긁어다 쓰는 정도의 언어라는 인식을 가진게 만년함(팽배함).
   ( cf. 하지만 현재 HTML 5가 부각되고 있는 만큼 javascript의 중요성은 매우 중요해짐!
* javascript 하나로 애플리케이션을 만들정도로 필요성이 부각됨! )
* 분위기가 전환되어 중요성이 매우 커짐! ( 학습 필요. )
* Front-End Application 만들 수 있음

조언) 자신의 무기 1개만 장착하라!
      하나만 제대로 알아서 다른 학습에서도 효과를 볼 수 있고, 경쟁력 있다. / 여러 language 얇게 아는 것은 부질없다. 

### [ HTML 5 역사? 등장 배경? ] or [ Front-End가 이제서야 각광받는 이유! ]
* W3C(1993년) - HTML 한계 인식(단점 : 1. 정형성이 없음(유지보수가 힘듬) // 2. 확장성 부재)
   (그래서 1999년 HTML 4.01버전을 마지막으로 버전업 종료.)
* → 2가지 문제점을 해결하기 위해 "XML" 도입 → "XHTML" 도입
* → 2000년도 "XHTML 1.0" 발표 (하지만 반응이 시원찮음)
* → 2004년도 "WHATWG"라는 working group 만듬 (모질라, 오페라, 애플 주도) = "HTML" 그 자체로 발전시켜보자!
* → "HTML 5" 탄생 → 2007년도 W3C에 제안!

### [ HTML5 주목받는 이유 ]
* 신기술이고 촉망받는 기술.
* Apple이 '10년 1월에 플래쉬 기능 제외 → HTML5 채택
* Google 역시 Apple과 동일한 행보

* HTML5 = 브라우저 위에 돌아가는 프로그램! ( HTML5를 이용 → WEB Application 제작 )

### [ HTML5 달라진 점 ]
1. 단순화(간소화)
2. semantic web(tag) - 태그를 구분! ( 프로그램이 웹페이지를 구분할 때 효과적! / but. 육안으로는 별차이 없음 )

### "css3" 진정한 의미
* 장점 : 서버 부하 저하
1. 화면 레이아웃 설정
2. 화면 데코레이션(장식)
3. 화면의 변경을 위한 네트워크 사용 - '리소스를 최소화'시킬 수 있다.

* chrome - HTML5 완벽 지원

* 추천도서 - 자바스크립트 객체지향 프로그래밍

cf. 사용할 IDE = 'WebStorm' // www.jetbrains.com접속 → "product" → "WebStorm" 다운로드

### 특성화 웹개발 특강의 목표 ( javascript 내용 위주로 진행 )
1. javascript 이해
2. 화면 제어(동적 처리)
3. jQuery - Front-End, javascript 분야에서 필수 기능
4. AJAX - 비동기서버와의 데이터통신

---

11월 6일

* "HTML5" 때문에 javascript 중요성 매우 커짐!!
* javascript (문법적으로 자유롭다 - 즉, 코딩이 어려울 수 있다.)
* 예전) 웹브라우저에서 사용하는 언어 / 웹 브라우저 내에서만 사용.
* 현재) 독립적인 어플리케이션을 만들수 있을 정도의 독립적으로 사용가능한 언어.

- 서버사이드에서 HTML, CSS, Javascript를 이용해서 클라이언트가 해당 웹페이즈를 볼 수 있도록 처리

1. 프로젝트 생성 후 소스코드 작성
2. 웹서버를 설치 ( 웹서버라는 특수한 프로그램이 있어야함! - 잘알려진 것은 '아파치(apache)' )
3. 웹서버에 우리 프로젝트를 configure시킨다.
4. 웹서버를 통해서 우리 프로젝트를 웹에 deploy시킨다.
5. 웹 클라이언트(브라우저-크롬)를 실행시켜서 해당 URL을 통해 접속!!

* 자바스크립트 코드는 head 내에 <script> ~ </script> 사이에 작성! (유지보수 문제 발생)
* sol) <script src="js/index.js"></script> 참조
* 1) js 폴더를 생성.
* 2) 폴더 내에 index.js 이름을 가진 javascript 파일을 생성.

* Browser가 특정 URL에 접속해서 서버로부터 HTML, CSS, Javascript를 받는다!

* ( Chrome 기준으로 설명! )
* **(중요)** 브라우저가 HTML을 분석(어떤 태그가 있고, 상관관계가 어떻게 구성되는지 등등 분석) -> DOM Tree(화면에 보여되는 형태로 브라우저가 만드는것)를 생성.
* **(중요)** CSS(HTML에 포함되어 같이 딸려옴)를 분석 -> Rendering Tree(그리기 위한 트리를 만듬)
* **(중요)** DOM Tree와 Rendering Tree를 2개의 구조를 결합해서 화면을 구성하고 브라우저에 보여줌.

* **(중요)** HTML을 분석할 때 순차적으로 한줄 한줄씩 interpreting(해석) 된다! 

- 자바스크립트 내용임 -> console.log("이건 콘솔창에 출력되요!!"); 
  웹스톰에서 실행 후 F12(개발자도구 메뉴임)를 누르고 'console'란에 내용 나옴

- 변수명 앞에 타입이 와도 되고 안와도 됨.
    var myVariable = "홍길동"; // 동작 됨
    variable2 = "김길동"       // 동작 됨

** Data Type은 기억할 것! **

* 자바스크립트에서 함수를 사용 할 땐 'function' 무조건 나와야 함
* 리턴 구문은 사용할 수 있으나 리턴 타입을 따로 명시하지는 않음.
  (데이터타입은 존재하나 무시하기 때문에 리턴타입을 따로 선언해줄 필요가 없음)

* 함수내에 '함수' = 메서드
* 함수내에 '변수' = 프로퍼티

배열을 많이 사용 하지 않음(자바의 경우) - 데이터 타입 일치. 사이즈 변경 불가능.
but) 자바스크립트 = 데이터 타입 일치X, 사이즈 제한 X
( 자바스크립트는 배열을 굉장히 활발히 사용됨. 매우 유용! )

** 자바스크립트의 객체를 잘 이해할 것!

* 자바스크립트로 로직(코드) 구현할 줄을 알아야 한다.
  (긁어와서 사용하는 예전 방식을 구사할려고 하지 말고!)

* <div>태그는 라인 단위로 블록영역을 확보한다. - id를 선언해주면 태그자체를 이용할 수 있다.

* startClock() - 자바스크립트의 선언적 함수.
* document object(문서객체) - HTML 태그를 자바스크립트의 객체화시키는 것.
* 태그 정식 명칭 = Element
* HTML 영역에 제어하고 싶은 영역을 javascript로 가져와야 내가 원하는 것으로 수정이 가능하다.
* 자바스크립트에는 내가 정한 시간마다 함수를 호출하는 매서드가 있다.
  (기본함수이기에 중요!! 암기!!) window.setinterval("함수", "밀리세컨드초");

* 자바스크립트 암기! = alert(팝업창 알람)

* <head> 부분은 설정에 대한 내용을 담고 있음.
* <body> 내용 부분

* 익스플로러, 크롬, 파이어폭스, 오페라, 파이어월 = 5대 브라우저(메이저 브라우저)가 화면상에 뜸. (클릭하는 순간 서버(브라우저)로 전송해서 브라우저로 코딩 결과 출력!)

* 브라우저 = 내가 요청한 내용을 html 파일로 받아오는것. 

* cf) 개인적으로 javascript 꼭 숙지해볼 것!
* cf) blocking method (함수의 실행이 끝날때까지 멈춰있는 것)
* 프로그래밍 = **이해될 부분**과 **숙지(암기)**해야될 부분으로 구분됨.

* cf) 웹스톰에 서버가 1개 내장되어 있기 때문에 익스플로러로 바로 코딩한 부분을 확인할 수 잇음.
* cf) 오늘 배우는 용어(커뮤니케이션 수단이기 때문에 중요함..신경써서 숙지!)나 프로세서(매커니즘)은 암기해야됨(상식상 알고 있어야함)
* cf) 웹스톰은 30일 평가판 사용이라 기한이 만료되면 재설치해서 사용할것!

- 웹스톰 사용법 -
* 모두 디폴드값으로 실행까지 전개.

1. create new project로 만들되 name은 공백없이 영어로 작성
2. '액세스 허용'선택
3. new -> HTML file -> name설정
4. 서체수정 -> file -> setting -> color & fonts -> save as 하나 만들어주면 셋팅 가능!

내용은 body에 기록

---

1. javascript의 언어적 특성 -> 다른 언어와 비교해서!
2. 간단한 화면 제어!

* javascript Event + HTML5 Drag and Drop
