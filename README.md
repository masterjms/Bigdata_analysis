# Bigdata_Analysis (25-1)
## 웹에서 Jupyter NoteBook실행하기
1. <code>pip install notebook</code> // jupyer노트북 install
2. <code>jupyter notebook</code> // 실행
## 파이썬 자료구조
### 데이터 표현
- 수치 데이터는 산술, 논리 연산 과정으로 사용되며 고정된 정수와 부동 소수점인 실수로 구성
- 비수치 데이터는 일상생활에서 사용하는 텍스트 또는 소리, 영상등과 같은 멀티미디어 데이터로 구성
- 빅데이터 시대로 접어들면서 대용량 데이터를 처리할 수 있게 되면서 비수치 데이터 세상이 도래
- 기본 연산 : <code> + 덧셈, - 뺄셈, *곱셈, ** 거듭제곱, /나누기, // 나눈 후 소수점이하의 수는 버리고 정수만 포함, %나눗셈 후 나머지만 구함.</code>
- 논리 연산 : <code> and , or , not </code>
- 자료형 <code>Tuples</code> : 튜플은 리스트와 유사한 시퀀스 데이터 자료형, 리스트와의 차이점은 리스트는 인덱스값을 변경 가능하다. 또한 list[]를 사용하지만 tuple()를 사용한다. 리스트가 더 많은 메모리를 차지한다.<br>
EX) <code>tuple[1:3]</code> 이면 index 1 부터 index 2까지를 의미한다. 끝 인덱스는 포함하지 않는다.<br>
EX) <code>(tuple + tuple) = (tuple *2)</code>
- 자료형 <code>Dictionary</code> : 쌍으로 만든 테이블 형식. key : value쌍으로 구성한다.
### 함수와 모듈
- Function : 반복적으로 사용되는 가치있는 부분을 한 그룹으로 묶어서 일정한 알고리즘을 사용해 결과값을 반환하는 식
- Module : 함수나 변수 또는 클래스를 모아 놓은 파일 - 프로그램 작성과 관리가 쉬워지고 공동작업이 편해지며 재활용이 쉽다. 주로 파이썬에서는 <code>import</code>를 사용하여 패키지를 가져온다. 
