---
layout: page
permalink: /web1/
title: 웹특강_1
description: ""
tags: [Jekyll, theme, install, setup]
image:
  feature: abstract-12

share: true
---

<html>
	<body>
	
	

		<div style="background-image: URL({{ site.url }}/images/list2.png); height: 410px; width: 200px; border: 2px solid black; position: fixed; top: 35px; right: 35px;">
  			<br><a href="#01" style="color: white"> &nbsp;01.수치 자료형 </a> <br>
  			<a href="#1-1" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1-1 정수형 상수 </a> <br>
  			<a href="#1-2" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1-2 실수형 상수 </a> <br>
  			<a href="#1-3" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1-3 Decimal 자료형 </a> <br><br>
  			<a href="#02" style="color: white"> &nbsp;02 파이썬 연산자 </a> <br>
  			<a href="#2-1" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2-1 산술 연산자 </a> <br>
  			<a href="#2-2" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2-2 관계 연산자 </a> <br>
  			<a href="#2-3" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2-3 논리 연산자 </a> <br>
  			<a href="#2-4" style="color: white"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2-4 비트 단위 연산자 </a> <br><br>
  			<a href="#problem" style="color: white"> &nbsp; 연습문제 </a> <br>
  			<a href="#coding" style="color: white"> &nbsp; 코딩 실습 </a> <br>
  			<a href="#forum" style="color: white"> &nbsp; Forum </a> <br>
		</div>
		
	</body>
</html>

<div id="1-1"></div>

- Front End Web Application 개발 기초 - '14.11.04 현재.... 시작단계의 기술

강사님 = 문성훈 강사님 ( moon9342@gmail.com // 010 - 3764 - 7807 )

HTML5, javascript, jQuery, AJAX, UI Framework -> 공부해두면 매우 유용! 취직하는데도 좋다!

* Front-End = 사용자에 밀착해 보여주고 기능 수행
* Back-End = 기존기능(화면 뒤에서 보이지 않고 수행)

* HTML / CSS = 정적!				//	javascript = 동적
*HTML = 보여줄 내용을 작성(문서 구조를 표현) / 클라이언트에서 보여줄 화면에 대한 문서구조 / 문서내용을 작성하기 위한 프로그래밍 언어 / 브라우저 언어 기반 / W3C에서 표준안 제안
* CSS = 화면 구조 설계 / 레이아웃 작성 / 문서 장식 / W3C에서 표준안 제안
* javascript = 이벤트담당(처리) / 화면의 동적제어 담당 / "ECMA(유럽표준기구)"에서 표준안 / 피상적인 사용(알면 좋지만 몰라도 긁어다 쓰면되지..) - 문법을 익혀서 쓰기보다는 긁어다 쓰는 정도의 언어라는 인식을 가진게 만년함(팽배함). ( cf. 하지만 현재 HTML 5가 부각되고 있는 만큼 javascript의 중요성은 매우 중요해짐! - javascript 하나로 애플리케이션을 만들정도로 필요성이 부각됨! ) / 분위기가 전환되어 중요성이 매우 커짐! ( 학습 필요. ) - Front-End Application 만들 수 있음

조언) 자신의 무기 1개만 장착하라! - 하나만 제대로 알아서 다른 학습에서도 효과를 볼 수 있고, 경쟁력 있다. / 여러 language 얇게 아는 것은 부질없다. 

[ HTML 5 역사? 등장 배경? ] or [ Front-End가 이제서야 각광받는 이유! ]
W3C(1993년) - HTML 한계 인식(단점 : 1. 정형성이 없음(유지보수가 힘듬) // 2. 확장성 부재) 그래서 1999년 HTML 4.01버전을 마지막으로 버전업 종료. → 2가지 문제점을 해결하기 위해 "XML" 도입 → "XHTML" 도입 → 2000년도 "XHTML 1.0" 발표 (하지만 반응이 시원찮음) → 2004년도 "WHATWG"라는 working group 만듬 (모질라, 오페라, 애플 주도) = "HTML" 그 자체로 발전시켜보자! → "HTML 5" 탄생 → 2007년도 W3C에 제안!

[ HTML5 주목받는 이유 ]
- 신기술이고 촉망받는 기술.
- Apple이 '10년 1월에 플래쉬 기능 제외 → HTML5 채택
- Google 역시 Apple과 동일한 행보

* HTML5 = 브라우저 위에 돌아가는 프로그램! ( HTML5를 이용 → WEB Application 제작 )

[ HTML5 달라진 점 ]
1. 단순화(간소화)
2. semantic web(tag) - 태그를 구분! ( 프로그램이 웹페이지를 구분할 때 효과적! / but. 육안으로는 별차이 없음 )

* "css3" 진정한 의미
- 장점 : 서버 부하 저하
1. 화면 레이아웃 설정
2. 화면 데코레이션(장식)
3. 화면의 변경을 위한 네트워크 사용 - '리소스를 최소화'시킬 수 있다.

* chrome - HTML5 완벽 지원

* 추천도서 - 자바스크립트 객체지향 프로그래밍

cf. 사용할 IDE = 'WebStorm' // www.jetbrains.com접속 → "product" → "WebStorm" 다운로드

* 특성화 웹개발 특강의 목표 ( javascript 내용 위주로 진행 )
1. javascript 이해
2. 화면 제어(동적 처리)
3. jQuery - Front-End, javascript 분야에서 필수 기능
4. AJAX - 비동기서버와의 데이터통신

