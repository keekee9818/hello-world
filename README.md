# 2017261024 기수연 안드로이드 프로그래밍
## Markdown 명령어

## 1. 헤더 ##

큰 제목 : 문서 제목 
<pre><code> 
HELLO WORLD! 
============
</pre></code>

HELLO WORLD!
============

작은 제목: 문서 부제목

<pre><code> 
hello world!
-------------
</pre></code>

hello world!
-------------

글 머리: 첫 번째에서 여섯 번째까지만 가능하다.

<pre><code>
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
</pre></code>
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

####### This is a H7. << 일곱 번째부터 불가능

* * *

## 2.BlockQuote ##

이메일에서 사용하는 > 블럭인용문자를 이용한다.

<pre><code> > This is a blockqute. </pre></code>

>This is a blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.

>This is a blockqute.
 >+ test 1
  >+ test 2
  
* * * 

## 3. 목록 ##
## ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.

<pre><code>
1. 첫번째
2. 두번째
3. 세번째
</pre></code>

1.첫 번째
2.두 번째
3.세 번째

## ● 순서없는 목록(글머리 기호)
<pre><code>
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
</pre></code>

* 빨강
  * 녹색
    * 파랑

+ 빨강
   + 녹색
     + 파랑

- 빨강
   - 녹색
     - 파랑
  
* * *
## 4. 코드 ##

4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.
한줄 띄어쓰면 인식이 제대로 안되는 문제가 발생 하기도 한다.

<pre><code>
코드 연습 코드 연습
</pre></code>

* * *
## 5. 수평선 ##

아래 줄은 모두 수평선을 만든다.
마크다운 문서를 미리보기로 출력할 때 페이지 나누기 용도로 많이 사용한다.
<pre><code>
* * *

***

*****

- - -

---------------------------------------
</pre></code>

* * *
## 6. 링크 ##

+ 참조링크
<pre><code>
[link keyword][id]
[id]: URL "Optional Title here"

Link: [Google][googlelink]
[googlelink]: https://google.com "Go google"
</pre></code>

Link: [Google][googlelink] [googlelink]: https://google.com "Go google"

+ 인라인 링크
<pre><code>
syntax: [Title](link)
</pre></code>
Link: Google

+ 자동연결
<pre><code>
<http://example.com/>
<address@example.com>
</pre></code>
http://example.com/ address@example.com

* * *
## 7. 강조 ##
<pre><code>
*HELLO WORLD!*
_HELLO WORLD!_
**HELLO WORLD!**
__HELLO WORLD!__
~~HELLO WORLD!~~
</pre></code>
*HELLO WORLD!*
_HELLO WORLD!_
**HELLO WORLD!**
__HELLO WORLD!__
~~HELLO WORLD!~~

* * *
