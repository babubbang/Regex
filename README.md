# RegEx(Regular-Expression)
1. 정규 표현식 (Regular Expression)

- 정규 표현식에 대해 조사하고, 본인의 깃허브에 public 프로젝트로 등록하여 정리하시오.

- 정규 표현식이 왜 필요한지, 파이썬에서의 기본 사용법, 코드 예제가 필수로 포함되어야 함

<h2> 1️⃣ 정규 표현식이란❓ (Regular Expression) </h2>
 복잡한 문자열에서 우리가 원하는 특정한 패턴을 찾아 처리할 경우 유용하게 사용 가능한 일종 기법이며, 파이썬 뿐만이 아닌 모든 언어에서 공통적으로 사용한다.

<h2> 2️⃣ 정규 표현식의 필요성❗ </h2>
 특정한 조건에 맞는 문자를 추출할 경우, 코드 작성 시 길고 복잡한 절차를 거치게 되지만 정규식을 사용한다면 훨씬 직관적이고 간단하게 작성이 가능하기 때문에
 효율성을 위해 주로 사용한다.

<h2> 3️⃣ 파이썬에서의 기본 사용법⭕ </h2>
 <b> ① 파이썬은 정규 표현식을 지원하기 위해 re 모듈을 제공한다. </b><br>
  <패턴 객체를 이용하는 4가지 방법><br>
   - <b>re.match()</b> : 문자열의 처음부터 정규식과 매치되는지 조사한다. | match의 결과로 match객체 혹은 None을 리턴해준다. <br>
   - <b>re.search()</b> : 문자열 전체를 검색하여 정규식과 매치되는지 조사한다. | match 메서드와 search 메서드는 문자열의 처음부터 검색할지의 여부에 따라 다르게 사용해야 한다. <br>
   - <b>re.findall()</b> : 정규식과 매치되는 모든 문자열(substring)을 리스트로 리턴한다. <br>
   - <b>re.finditer()</b> : 정규식과 매치되는 모든 문자열(substring)을 반복 가능한 객체로 리턴한다. | finditer는 findall과 동일하지만 그 결과로 반복 가능한 객체(iterator object)를 리턴한다. <br>
   
  <br> <match 객체의 메서드> <br>
   - <b>group()</b> :	매치된 문자열을 리턴한다. <br>
   - <b>start()</b>	: 매치된 문자열의 시작 위치를 리턴한다. <br>
   - <b>end()</b> :	매치된 문자열의 끝 위치를 리턴한다. <br>
   - <b>span()</b> :	매치된 문자열의 (시작, 끝)에 해당하는 튜플을 리턴한다. <br>
