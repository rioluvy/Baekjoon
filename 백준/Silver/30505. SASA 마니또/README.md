# [Silver I] SASA 마니또 - 30505 

[문제 링크](https://www.acmicpc.net/problem/30505) 

### 성능 요약

메모리: 2608 KB, 시간: 16 ms

### 분류

많은 조건 분기, 구현

### 제출 일자

2024년 6월 1일 21:20:47

### 문제 설명

<p>세종이를 포함한 $N$명의 학생이 자신이 뽑은 친구를 도와주는 마니또 활동을 진행하고 있다. $N$명의 학생은 $1$부터 $N$까지의 서로 다른 정수 번호가 붙어 있다. $N$명의 학생은 모두 서로 다른 학생 한 명의 마니또가 되었으며, 자신이 스스로의 마니또가 되거나 마니또가 없는 학생은 없다.</p>

<p>그러나 예상과 달리 학생들이 스스로 자신이 누구의 마니또인 지 밝힌 바람에 이벤트가 재미없어질 위기에 처했다! 이에 <strong>마니또 활동에 참가하지 않는</strong> 영재는 마니또를 공개하기 전에 학생들의 마니또가 누구인지 맞혀 보고자 한다. 하지만 $N$명의 학생의 마니또를 모두 맞히는 것은 힘들다고 생각해 세종이의 마니또만을 맞혀 보기로 했다. 밝혀진 정보들을 바탕으로 세종이의 마니또로 가능한 사람의 수를 출력하는 프로그램을 작성하시오.</p>

### 입력 

 <p>첫째 줄에 마니또 활동에 참가하는 학생의 수 $N$과 밝혀진 정보의 수 $M$이 공백으로 구분되어 주어진다. $(2\leq N\leq 100\, 000;$ $1\leq M\leq N)$</p>

<p>둘째 줄부터 $M$개의 줄에 걸쳐 줄마다 서로 다른 두 양의 정수 $a$, $b$가 공백으로 구분되어 주어진다. $(1\leq a,b\leq N)$ 이는 $a$번 학생의 마니또가 $b$번 학생임을 의미한다. 이전까지의 정보와 중복되는 입력은 주어지지 않으며, 항상 $N$명의 학생이 모두 조건에 맞게 마니또가 될 수 있는 경우만 입력으로 주어진다.</p>

<p>마지막 줄에 세종이의 번호 $s$가 주어진다. $(1\leq s\leq N)$</p>

### 출력 

 <p>첫째 줄에 세종이의 마니또로 가능한 사람의 수를 출력한다. 단, 이때 가능한 사람의 수가 $1$명이라면 대신 첫째 줄에 <span style="color:#e74c3c;"><code>NOJAM</code></span>을 출력한다.</p>

