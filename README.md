# 파이썬 문법(Python Syntax)

## 변수(Variables)와 자료형(Data Types)

### 1. Welcome!
- 고급 언어(High-Level Language)
- 인터프리터 언어(Interpreted Language)
- 객체 지향(Object-oriented)

print "Welcome to Python!"

### 2. 변수(Variables)
my_variable = 10

### 3. 자료형(Data Types)
my_int = 7

my_float = 1.23

my_bool = True

### 4. 변수의 값 다시 할당하기
my_int = 7

my_int = 3

print my_int

## 공백(Whitespace)과 명령문(Statements)

### 5. 공백(Whitespace)
def spam():

eggs = 12

return eggs

print spam()

> IndentationError : Line 2

### 6. 공백(Whitespace)은 올바른 공간을 의미합니다.
def spam():

    eggs = 12

    return eggs

print spam()

> 함수 안의 문장이면 꼭 Tab을 해줘야한다!

### 7. 해석(interpretation)의 문제
변수 선언 및 저장 및 실행

## 주석(Comments)

### 8. 한 줄 주석(Single Line Comments)
한 줄 주석 #

### 9. 여러 줄 주석(Multi-Line Comments)
여러 줄 주석 """ - """(triple quotation)

##수학 연산(Math Operations)

### 10. 수리 연산자(Arithmetic Operators)
사칙연산 + - * /

### 11. 거듭제곱(Exponentiation)
지수연산 **

ex) 2**3 == 8

### 12. 모듈로(Modulo)
나머지연산 %

# 문자열과 콘솔출력(Strings & Console Output)

## 문자열(Strings)

### 1. 문자열(Strings)
' ' 또는 " "사용

### 2. Practice

### 3. Escaping characters
\ 이용

ex) 'Help! Help! I\'m being repressed!'

### 4. Access by Index
PYTHON

0 1 2 3 4 5

Y를 원한다면 "PYTHON"[1]

## 문자열 메소드(String Methods)

### 5. len() 메소드
> len(variable)은 variable의 문자들의 수 출력

### 6. lower() 메소드
> variable.lower()은 소문자 변환

### 7. upper() 메소드
> variable.upper()은 대문자 변환

### 8. str() 메소드
> str(variable) variable을 문자열로 변환

### 9. 점 표기법(Dot Notation)
점 표기법은 .upper()와 .lower()처럼 문자열에 특화된 메소드에 사용한다. 즉, 그 외에는 작동하지 않는다.

반면에 len()와 str()는 다른 모든 종류의 객체(objects)에 작동할 수 있다. 따라서 점 표기법과 함께 문자열에 사용하지 않아도 된다.

## Print 키워드

### 10. 문자열 리터럴(String Literals) 출력하기
**print명령어**는 자바 스크립트의 console.log명령어와 같음

### 11. 변수(Variables) 출력하기
the_machine_goes = "Ping!"

print the_machine_goes

##출력하기, 고급편

### 12. 문자열 연결(String Concatenation)
print "Spam " + "and " + "eggs"

### 13. 명확한 문자열 변환(Explicit String Conversion)
str()를 이용하여 숫자를 문자열로 변환하여 출력

print "The value of pi is around " + str(3.14)

### 14. %를 이용한 문자열 포맷팅(String Formatting), Part 1
### 15. %를 이용한 문자열 포맷팅(String Formatting), Part 2

불행히도 파이썬의 문자열은 한 번 생성되고 난 뒤엔 변경이 불가능(immutable)하다.

하지만 문자열에 유연성을 부여할 방법으로 **문자열 포맷팅(String Formatting)**이 있다.

% 문자열 포맷터는 문자열 안의 %s(여기서 "s"는 "string"을 의미)를 소괄호 안의 변수로 대체해 넣는다. 

> print "%s와 %s" % (string_variable1, string_variable2)

#조건문과 흐름제어(Conditionals & Control Flow)

## 흐름 제어(Control Flow) 입문
### 1. 흐름 제어(Control Flow)

## 비교연산자(Comparators)
서로 같다 (==)
서로 같지 않다 (!=)
~보다 작다 (<)
~보다 작거나 같다 (<=)
~보다 크다 (>)
~보다 크거나 같다 (>=)
### 2. 자세히 비교하기!
### 3. 더 자세히... 비교하기!
### 4. 반대로 비교해보기

## 불린 연산자(Boolean Operators)
### 5. 같거나(And), 또는(Or), 반대(Not)이거나
### 6. And 연산자
### 7. Or 연산자
### 8. Not 연산자
### 9. 이것과 저것(또는 이것, 하지만 저건 말고!)
1. not 연산자를 제일 먼저 연산합니다
2. and 연산자를 그 다음으로 연산합니다
3. or 연산자를 제일 마지막으로 연산합니다

### 10. 짜맞추기

## If, Else 그리고 Elif
### 11. 조건 명령문(Conditional Statement)의 문법
파이썬에서 공백은 중요하다. 파이썬에서는 공백(키보드의 tab 또는 space)이 중괄호의 역할을 한다.
### 12. 만약(if) 여러분이...
### 13. 그 외에(else) 문제가 있다면, 유감입니다…
### 14. 수많은 문제가 있지만, Switch는 문제가 아니죠.
파이썬은 좀 더 간단하게, 오직 elif만 사용한다

# 함수(Functions)

## 함수(Functions) 입문

### 1. 함수의 좋은점이 뭐죠?
D.R.Y. Don't Repeat Yourself, 즉 반복하지마라는 프로그래밍의 원칙 중 하나이다. 함수를 이용하면 반복을 피하기 훨씬 쉽다.

## 함수(Function) 문법

### 2. 함수(Function) 연결
1. **헤더(header)** 이 부분은 def 키워드와 함수의 이름, 그리고 소괄호(()) 안에 받아들이는 매개변수(parameters), 콜론(:)을 포함합니다. (다음 과제에서 매개변수에 관해 다룰 것입니다.)
2. **선택적 독스트링(docstring)** 이 부분은 세 개의 따옴표(""")로 처리하며, 여러 줄 주석에서 무슨 기능을 하는지 간단하게 설명했었습니다.
3. **바디(body)** 이 부분은 함수가 진행하는 과정을 나타내는 코드 블럭입니다. 바디 부분은 if, elif, else 명령문의 코드 블럭처럼 들여쓰기 합니다.

### 3. 호출(Call)과 응답(Response)
### 4. 인자(Arguments)와 매개변수(Parameters)
### 5. 함수를 호출하는 함수
### 6. Practice Makes Perfect

##모듈 임포트(Importing Modules)

### 7. 쿵푸, 알고 있죠
**모듈(module)**은 사용할 수 있는 여러 변수와 함수의 정의를 담고 있는 파일이다. 매번 변수와 함수들을 작성하는 건 인터프리터를 지저분하게 만들 수 있다. 따라서 모듈(module) 안에 이들을 담아두고 필요할 때마다 불러오는(import) 것이다.

### 8. 제네릭 임포트(Generic Imports)
이렇듯 단순한 방법으로 모듈을 불러올 때, 이를 **제네릭 임포트(generic import)**라고 부른다.

import module

module.function()

ex)

import math

math.sqrt()

### 9. 함수 임포트(Function Imports)
하지만 math 모듈 전체를 불러오는 것은 두 가지 이유로 성가시다고 할 수 있다: 첫째로, 오직 sqrt 함수만 필요해도 전체 모듈을 불러와야 하기 때문이고, 둘째로, math 모듈로부터 함수를 참조할 때 항상 math.sqrt()라고 작성해야만 하기 때문이다.

다행히도 주어진 모듈로부터 특정 변수나 함수만을 불러올 수 있다. 모듈로부터 하나의 함수를 불러오는 방법을 가리켜 **함수 임포트(function import)**라 부르고, 다음과 같이 from 키워드를 사용해서 작성할 수 있다.

from module import function

ex) from math import sqrt

### 10. 유니버셜 임포트(Universal Imports)
from math import *

### 11. 임포트(import) 주의사항
유니버설 임포트를 사용하면 어마어마한 양의 변수와 함수를 불러올 수 있지만, 이들이 여러분이 작성한 변수나 함수와 충돌을 일으킬 수 있다.

## 내장 함수(Built-In Functions)

### 12. 문자열 너머

### 13. max() 함수
여러 개의 인자(argument)를 받아들여 그 중에서 가장 큰 값을 반환한다.

max(1, 3, 7, 5, 9) = 9
 
### 14. min() 함수
인자로 받아들인 값 중에서 가장 작은 값을 반환한다.

min(3, 1, 5, 7, 9) = 1

### 15. abs() 함수
인자로 받아들인 숫자의 절댓값(absolute value)을 반환한다.

abs(-42) = 42

### 16. type() 함수
인자로 받아들인 값의 자료형(type)을 반환한다.

print type(42) = <type 'int'>

print type(4.2) = <type 'float'>

print type('spam') = <type 'unicode'>

print type({'Name':'John Cleese'}) = <type 'dict'>

print type((1,2)) = <type 'tuple'>

# 리스트형과 사전형(Lists & Dictionaries)

## 리스트형(Lists)

### 1. 리스트형(Lists) 입문
리스트형(Lists)은 자료형(data type)으로, 서로 다른 정보의 집합을 배열로써 하나의 변수 이름 안에 저장하는데 사용할 수 있다.
### 2. 색인(Index)으로 접근하기
### 3. 새로운 이웃

##리스트 용량(Capabilities)과 함수(Functions)

### 4. 나중에 추가하기 & 리스트 길이
파이썬에서, 우리는 리스트를 변경가능(mutable)하다고 여긴다.
리스트 내장 함수인 append()를 이용하여 다음과 같이 요소를 리스트에 추가할 수 있다.

suitcase = [ ]

suitcase.append("sunglasses")

### 5. 리스트 슬라이싱(List Slicing)
list_name[a:b]라는 코드는 리스트 list_name의 색인 a부터 시작해서 색인 b 이전까지의 위치를 반환한다.

my_list = [0, 1, 2, 3]

my_list[1:3] = [1, 2]

### 6. 문자열 슬라이싱(Slicing)
my_list[:2] -> 앞 부분의 두 요소를 잘라냄

my_list[3:] -> 뒤로부터 네 개의 요소를 잘라냄

ex)
animals = "catdogfrog"

cat = animals[:3]

dog = animals[3:6]

frog = animals[6:]

### 7. 순서 지키기
**index() 함수**를 이용해서 리스트를 검색할 수 있다. my_list.index("dog") 는 문자열 "dog" 를 가지고 있는 첫번째 색인을 반환한다. 만약 찾는 요소가 리스트에 없다면 오류가 발생한다.

**insert() 함수**를 이용하여 리스트의 중간에 요소를 추가할 수 있다. my_list.insert(4,"cat") 는 리스트 my_list안의 색인 4에 문자열 "cat"을 추가하고, 원래 색인 4에 있던 요소를 그 다음 색인으로 이동시킨다. (즉, 요소가 추가된 곳부터 시작해서 리스트가 끝날때까지의 모든 요소의 색인이 1씩 증가한다.)

### 8. 하나에서 열까지
my_list = [1,9,3,8,5,7]

for number in my_list:

    print number
    
### 9. 'for' 더 알아보기
sort() 함수를 사용해서 정리(sort)할 필요가 있다. my_list.sort()라는 코드는 리스트 my_list 안의 요소들을 숫자/알파벳 오름차순으로 정렬한다.

## 사전형(Dictionaries)

### 10. Key
사전형은 리스트와 유사하다. 그러나 인덱스(index) 대신 키(key*)를 통해 저장된 값에 접근한다. 문자열이나 숫자를 키로 사용할 수 있다. 사전은 다음과 같이 중괄호 열고 닫는다:

d = {'key1' : 1, 'key2' : 2, 'key3' : 3}

위의 코드는 d 라는 사전에 세 개의 키-값의 쌍(key-value pair)이 들어있음을 나타냅니다. 'key1' 이 값 1을 가리키고, 'key2' 는 2를 가리키는 식이다.

사전형은 이름과 전화번호의 쌍으로 이루어진 전화번호부나, 이메일과 사용자 이름의 쌍으로 이루어진 로그인 페이지 등에 매우 유용하게 쓸 수 있다.

### 11. 새 목록(Entries)
리스트와 마찬가지로, 사전형 역시 "변경 가능(mutable)"하다. 이 특성 덕분에 사전형은 생성된 후에도 변경될 수 있다. 이러한 장점 덕에 생성 후에도 다음과 같이 새로운 키/값 쌍을 추가할 수 있다:

dict_name[new_key] = new_value

비어있는 대괄호 []가 빈 리스트를 나타내듯, 사전형에서 비어있는 중괄호 {}는 빈 사전형을 의미한다.

### 12. 생각 바꾸기
사전형 안의 요소는 또한 del 명령어로 제거할 수 있다:

del dict_name[key_name]

위의 코드는 사전형에서 키 key_name와 해당 키와 관련있는 값을 삭제한다.

### 13. 위험하니 이것도 가져가세요!
마지막으로, my_list.remove(value)라는 코드는 리스트 my_list에서 value 값의 요소를 삭제한다.

del과 .remove()의 차이점은 다음과 같다:

**del dict_name[key_name]** del은 키(key)를 기준으로 해당 키와 여기에 연관된 값을 지운다. 

**dict_name[key_name].remove(value_name)** .remove() 는 값(value)을 기준으로 해당 값과 여기에 연관된 키를 지운다.

# 리스트(Lists)와 함수(Functions)

## 리스트(Lists) 되짚어보기
### 1. 리스트(Lists) 접근하기
### 2. 리스트 요소(List element) 수정
### 3. 리스트(List)에 추가하기
array.append()함수 이용
### 4. 리스트(Lists)에서 요소 제거하기
1. array.pop(index) : index에 저장된 요소 제거 및 반환
2. array.remove(item) : 리스트 안에 존재하는 요소 item 제거
3. del(array[index]) : .pop처럼 index에 저장된 요소를 제거하되, 반환은 하지 않음

## 함수(Function) 되짚어보기
### 5. 함수(Function)의 기능(Functionality) 변경하기
### 6. 하나 이상의 인자(argument)
### 7. 함수(Function) 안의 문자열

## 리스트(Lists)에 함수(Functions) 사용하기
### 8. 리스트(Lists)를 함수(Function)에 전달하기
### 9. 함수 안의 리스트로부터 요소 사용하기
### 10. 함수 안의 리스트에 들어있는 요소 변경하기
### 11. 함수 안의 리스트 조작

## 함수 안의 리스트 전체 사용하기
### 12. 함수 안의 리스트를 요소별로 출력하기

n = [3, 5, 7]
    
def print_list(x):

	for i in range(0, 3):
		print x[i]

print_list(n)

### 13. 함수 안의 리스트에 들어있는 각각의 요소를 변경하기

### 14. 함수에 레인지(Range) 전달하기

Range 함수는 하나나 둘, 또는 세 개의 인자를 가질 수 있습니다. 만약 하나의 인자를 사용하면, 레인지는 0부터 시작해서 인자보다 1만큼 작은 값에 다다를 때까지 순차적으로 1씩 증가합니다.

예를 들면:
range(1) # => [0]
range(2) # => [0,1]


만약 두 개의 인자를 사용한다면, 첫 번째 인자로부터 시작하여 두 번째 인자보다 1만큼 작은 값에 다다를 때까지 다음과 같이 1씩 증가합니다:
range(1,3) # => [1,2]


만약 세 개의 인자를 사용한다면, 레인지는 첫 번째 인자로부터 시작하여 두 번째 인자에서 끝나며, 세 번째 인자는 증가치가 되어 기본값인 1을 대신하여 레인지가 순차적으로 얼마만큼 증가할 지를 결정합니다.
예를 들면:
range(2,8,3) # => [2,5]
range(2,9,3) # => [2,5,8]

### 15. 함수 안의 임의 크기의 리스트에 들어있는 요소의 갯수 세기
range(0, len(array))이용

### 16. 함수 안의 리스트에 문자열 사용하기
	for item in list:
    	print item

	for i in range(len(list)):
    	print list[i]

## 함수 안에서 리스트의 리스트 사용하기
### 17. 함수에서 두 개의 인자에 두 개의 리스트 사용하기
### 18. 함수 안에서 여러 리스트로 이루어진 하나의 리스트 사용하기
list_of_lists = [[1,2,3], [4,5,6]]

	for lst in list_of_lists:
    	for item in lst:
        	print item
문제 풀면
n = [[1, 2, 3], [4, 5, 6, 7, 8, 9]]
def flatten(x):

	y = [ ]
    for i in range(0, len(x)):
        for j in range(0, len(x[i])):
            y.append(x[i][j])
    return y
print flatten(n)

# 반복문(Loops)
## While 반복문
### 1. 여러분이 여기있는 동안
### 2. 조건문(condition)
### 3. 여러분이 그것에 있는 동안
### 4. 간단한 오류
### 5. 무한 루프(Infinite loops)
### 6. 브레이크(break)
### 7. While/else 문
파이썬에서 완전히 다른 게 있다면 while/else 구조입니다. while/else는 if/else와 비슷하지만 차이점이 하나 있습니다: 반복문의 조건문이 False으로 판명되면 언제든지 else 블록을 실행한다는 것이죠. **이는 반복문이 한 번도 시작하지 않거나, 또는 일반적으로 종료되어도 else 부분이 실행된다는 의미입니다. 만약 반복문이 break로 인해 종료된다면 else 명령문은 실행되지 않을 겁니다.**

	from random import randrange
	random_number = randrange(1, 10)
	count = 0

	while count < 3:
    	guess = int(raw_input("Enter a guess:"))
    	if random_number == guess:
        	print 'You win!'
        	break
    	count += 1
	else:
    	print 'You lose'

### 8. 여러분 만의 while/else 문
## For 반복문
### 9. 여러분의 건강에 대해
### 10. 여러분의 취미에 대해
### 11. 문자열에 대해
### 12. A에 대해
print 명령문의 끝에 쉼표(,)를 달아 매번 새로운 줄에 값들이 출력되는 것을 막을 수 있다. 

	s = "A bird in the hand..."

	for alphabet in s:
    	if alphabet == 'A' or alphabet == 'a':
        	alphabet = 'X'
    	print alphabet,

> X bird in the hXnd...출력

### 13. 리스트에 대해
## 여러분의 'For' 반복문 설정하기
### 14. 사전형 반복시키기
사전형을 반복시키는 게 어떤 식으로 작동하는지 궁금해하실 겁니다. 키(key)와 값(value) 중 무엇을 얻게 될까요?

답부터 말씀드리자면, 키를 얻게 됩니다. 하지만 쉽게 값도 얻을 수 있죠. 왜냐하면 for key in d(d는 사전형을 의미)라는 코드를 보는 것이 일반적이기 때문입니다.

추가적으로, 하나의 줄에 여러가지 것들을 출력할 땐 쉼표(,)를 이용해서 서로 떼어놓으세요. **print "string", 6**이라고 작성하면 파이썬은 6을 문자열로 바꿀 것입니다. 하지만 만약 둘을 + 연산자로 연결하려고 하면 오류가 발생할 것입니다. 왜냐하면 int(정수형)과 str(문자열)을 합칠 수 없기 때문입니다.

	d = {'x': 9, 'y': 10, 'z': 20}

	for key in d:
    	print key, d[key]

> y 10
> x 9
> z 20 출력

### 15. 진행하는 대로 세기 : enumerate이용
이렇게 for 반복문을 개별 스타일의 반복에 사용하는 것의 약점은 현재 반복중인 색인(index)이 무엇인지 알 수 없다는 것입니다. 일반적으로 이는 문제가 되지 않지만, 리스트 안에서 어느 위치에 있는가를 아는건 유용한 일이죠. 고맙게도 내장 함수인 **enumerate**가 이를 도와줄 겁니다.

함수 enumerate는 전달하는 리스트 안의 개별 요소들에 상응하는 색인을 제공함으로써 작동합니다. 매번 반복이 진행될 때마다, 색인(index)은 하나씩 증가할 것이고, 요소(item)는 순서상에서 다음 요소로 옳겨갈 것입니다. 이는 일반적인 for 반복문을 리스트에 사용하는 것과 매우 유사합니다. 이 방법이 우리가 지금까지 얼마나 많은 요소를 봤는지 셀 수 있는 쉬운 길이라는 점만 제외하고 말입니다.

	choices = ['pizza', 'pasta', 'salad', 'nachos']

	print 'Your choices are:'
	for index, item in enumerate(choices):
    	print index+1, item

> Your choices are:
> 1 pizza
> 2 pasta
> 3 salad
> 4 nachos 출력

### 16. 여러 리스트 : zip이용
두 개의 리스트를 한 번에 반복해야 하는 것 또한 일반적인 경우입니다. 이런 상황에서 내장 함수 **zip**이 유용하게 쓰입니다.

함수 zip은 두 개의 리스트를 전달받아 요소의 쌍을 생성하고, **더 짧은 쪽의 리스트의 끝부분에서 생성을 멈춥니다**.

함수 zip은 세 개 뿐만 아니라 더 많은 리스트도 다룰 수 있습니다!

	list_a = [3, 9, 17, 15, 19]
	list_b = [2, 4, 8, 10, 30, 40, 50, 60, 70, 80, 90]

	for a, b in zip(list_a, list_b):
        if a > b:
            print a
        elif a < b:
            print b

> 3
> 9
> 17
> 15
> 30 출력

### 17. For/else 문
while 반복문처럼, for 반복문 또한 else 부분을 가질 수 있습니다.

이런 경우에 else 명령문은 for 다음에 실행되지만, **오직 for 반복문이 일반적으로 종료되었을 때만 실행됩니다. 즉, break 명령어를 통해 종료되지 않은 경우에 말이죠.**

### 18. 바꿔보기
### 19. 여러분 만의 반복문 작성

## 유용한 내장 함수 : string.split(), " ".join(string)
	def censor(text):
    	print text.split()
    	print " ".join(text)
	censor("this hack is wack hack", "hack")

> ['this', 'hack', 'is', 'wack', 'hack']
> this hack is wack hack

# 파이썬의 고급 논제들

## 반복에 관하여

### 1. 사전형(Dictionaries)에 대한 반복자(Iterators)
함수 items()는 사전형을 반복하여 그 안의 키/값 쌍(pair)을 반환합니다. **특정한 순서에 맞춰 키/값 쌍을 반환하지 않는다는 점, 기억하세요.**

### 2. keys()와 values()
함수 **items()**는 튜플(tuples)의 배열(array)을 반환하며, 각각의 튜플은 사전형으로 부터 가져온 키/값 쌍으로 구성됩니다.
함수 **keys()**는 사전형 안에 있는 키(key)들의 배열을 반환합니다.
함수 **values()**는 사전형 안에 있는 값(value)들의 배열을 반환합니다.
다시 말씀드리지만, 위의 함수들은 사전형으로부터 받은 키나 값을 어떤 특정 순서에 맞춰 반환하지 않습니다.

> 튜플*을 일종의 변경할 수 없는 리스트(좀 지나친 단순화이긴 하지만)라고 생각하셔도 됩니다: 튜플은 소괄호 ()로 감싸며, 어떤 종류의 자료형도 담을 수 있습니다.

### 3. 'in'연산자

## 리스트 내포(List Comprehensions)
### 4. 리스트 작성
하지만 만약 우리가 어떤 논리 구조에 따른 리스트를 생성하고 싶다면 어떨까요? 파이썬에서 이에 대한 해답은 리스트 내포(list comprehension)입니다. 리스트 내포는 for/in과 if 키워드를 사용하여 리스트를 생성하는 강력한 방법입니다.

	evens_to_50 = [i for i in range(51) if i % 2 == 0]
	print evens_to_50

> 0~50중 짝수 출력

### 5. 리스트 내포 문법
### 6. 이제 여러분의 차례입니다!

## 리스트 슬라이싱(List Slicing)
### 7. 리스트 슬라이싱 문법
리스트 슬라이싱은 리스트의 축약된 부분의 요소들에 접근할 수 있도록 합니다. 문법은 다음과 같습니다:

	[start:end:stride]

start 색인 부분 부터 시작하여, end 색인 바로 전 색인까지의 리스트를 잘라내며, stride는 리스트에서 잘려진 요소들의 간격을 나타냅니다.

### 8. 색인(index) 생략하기
### 9. 리스트 뒤집기
### 10. 스트라이드 길이(Stride Length)
### 11. 연습이 최고를 만듭니다

## 람다(Lambda)
### 12. 무명 함수(Anonymous Functions)
파이썬의 더욱 강력한 면 중 하나는 바로 함수형 프로그래밍(Functional Programming)이 가능하다는 겁니다. 이는 함수를 마치 변수나 값처럼 전달할 수 있다는 의미입니다. 종종 이를 당연시여깁니다만, 모든 프로그래밍 언어가 이를 지원하는 것은 아닙니다!

	lambda x: x % 3 == 0

위의 코드는 아래의 코드와 같은 내용입니다.

	def by_three(x):
		return x % 3 == 0

유일한 차이점은 함수에 이름을 지정하지 않는다는 겁니다; 해당 함수는 이름 없이도 작업을 수행하고 값을 반환합니다. 바로 이런 이유로 **람다(Lambda)를 통해 생성한 함수를 무명 함수(anonymous function)**이라고 부릅니다.

	my_list = range(16)
	print filter(lambda x: x % 3 == 0, my_list)

람다(lambda)를 함수 filter에 전달할 때, filter는 무엇을 걸러낼지 판단하는데 람다를 사용합니다. 그리고 두 번째 인자(숫자 0부터 15까지를 갖는 리스트 my_list)는 걸러내지는 리스트를 나타냅니다.

### 13. 람다(Lambda) 문법
### 14. 시도해보세요!
 
## 복습하기
### 15. 사전형(Dictionaries) 반복하기
### 16. 리스트 내포(list comprehension) 이해하기
### 17. 리스트 슬라이싱(List Slicing)
### 18. 람다(Lambda) 수식
 
# 비트 단위(Bitwise) 연산자 입문
## 이진 표현(Binary Representation)
### 1. 비트(Bit)
### 2. 이진법(The Base 2 Number System)
파이썬에서는 숫자를 `0b`으로 시작함으로써 이진법으로 해당 숫자를 작성할 수 있습니다.

	print 0b1, #1
	print 0b10, #2
	print 0b11, #3
	print 0b100, #4
	print 0b101, #5
	print 0b110, #6
	print 0b111 #7
	print "******"
	print 0b1 + 0b11 #4
	print 0b11 * 0b11 #9

### 3. 1100까지 셀 수 있어요!
### 4. bin()함수
함수 `bin()`을 이용해서 이진수로 숫자를 출력할 수 있습니다. 함수 bin()은 정수형 값을 입력값으로 받아 해당 값의 이진수 형태를 문자열로 반환합니다. (bin 함수를 사용한 뒤에는 더 이상 값을 숫자처럼 연산할 수 없다는 걸 염두에 두세요.)

또한 함수 `oct()`와 `hex()`를 이용해서 숫자를 각각 8진수와 16진수로 나타낼 수 있습니다. (하지만 여기서는 이와 관련된 내용을 다루진 않을 겁니다.)

### 5. int()함수의 두 번째 매개변수
여러분이 함수 int()에 관해 모르는 게 있습니다. `int()`가 추가적으로 두 번째 매개변수를 가질 수 있다는 사실이죠. 첫 번째 인자는 알다시피 정수형으로 변환할 숫자를 담은 문자열을 넣고, 두 번째 인자는 첫 번째 인자 안의 숫자가 몇진수인지를 나타내는 숫자를 입력합니다(예를 들어, 이진수면 2, 팔진수면 8). 그러면 함수는 결과로 해당 진수의 숫자를 십진수 정수형으로 반환할 겁니다. 따라서 `int("1010", 2)`라는 코드는 결과로 10을 반환합니다. 두 번째 인자가 2이므로, 이는 첫 번째 인자가 이진수 표기임을 나타내며, 0b1010은 십진수 값으로 10이기 때문입니다.

##비트 단위(Bitwise) 연산자
### 6. 왼쪽으로 넘기기! 오른쪽으로 넘기기!

좌측 시프트 연산 (<<)
0b000001 << 2 = 0b000100 (1 << 2 = 4)
0b000101 << 3 = 0b101000 (5 << 3 = 40)

우측 시프트 연산 (>>)
0b0010100 >> 3 = 0b000010 (20 >> 3 = 2)
0b0000010 >> 2 = 0b000000 (2 >> 2 = 0)

비트 단위 연산은 오직 정수형에서만 사용할 수 있다는 걸 명심하세요. 문자열이나 실수형에 이를 사용하면 무의미한 결과값을 보게될 겁니다!

### 7. 비트 단위의 AND연산 &
### 8. 비트 단위의 OR연산 |
### 9. 비트 단위의 XOR연산 ^
### 10. 비트 단위의 NOT연산 ~

##조금 더 복잡한 내용
### 11. 비트 마스크(Bit Mask)
비트 마스크(Bit Mask)는 비트 단위 연산을 돕기위해 사용하는 일반적인 변수입니다. 비트 마스크는 특정 비트를 켜고(1로 전환) 끄거나(0으로 전환), 어떤 정수 안의 비트 상태에 관한 정보를 모으는 등의 작업을 돕습니다.

예를 들어, 숫자 a 안의 오른쪽에서 세 번째 비트가 켜져있는지 확인하려 한다고 해봅시다.

	mask = 0b100 # 기준이 될 마스크 작성
	desired = a & mask # 확인하려는 숫자와 마스크를 비교

### 12. 비트 켜기
또한 | 연산자를 사용해서 숫자 안의 비트를 키는데 마스크를 사용할 수도 있습니다.

예를 들어, 숫자 a의 가장 오른쪽에 있는 비트를 켜진 상태로 만들고 싶다고 합시다.

	a = 0b110 # 변경하려는 숫자. 십진수 값으로 6
	mask = 0b1 # 기준이 될 마스크. 십진수 값으로 1
	desired = a | mask # 가장 오른쪽의 비트를 켬. 결과는 0b111, 또는 십진수 값으로 7

### 13. 비트 전환하기
비트를 전환시키는 데 XOR 연산자(^)를 사용하면 매우 유용합니다. 어떤 비트(0 또는 1)와 1에 ^ 연산자를 사용하면, 해당 비트가 전환된(0은 1로, 1은 0으로) 값을 결과로 반환합니다.

예를 들어, 숫자 a 안의 모든 비트를 전환하고 싶다고 합시다.

	a = 0b11101110 # 변경하려는 숫자
	mask = 0xFF # 기준이 될 마스크
	desired = a ^ mask # 모든 비트를 전환함. 결과는 0b10001

### 14. 마스크 안의 비트 옮기기

정수 a의 오른쪽으로부터 열 번째 비트를 키려고 한다 합시다.

	a = 0b101
	mask = (0b1 << 9) # 옮기려는 위치보다 하나 작은 수
	desired = a ^ mask

# 클래스(Classes) 입문

## 클래스(Class)의 기초
### 1. 왜 클래스를 사용하나요?
### 2. 클래스 문법
기본적인 클래스는 class 키워드, 클래스의 이름, 그리고 새로운 클래스가 상속(inherit)받을 클래스가 괄호 안에 들어간 형태로 구성되어 있습니다.

	class Animal(object): #object클래스 상속
	    pass

pass는 아무런 기능도 하지 않지만, 파이썬에서 코드가 필요한 부분에 사용하여 자리를 채우는 역할로 사용할 때 유용합니다.

### 3. 클래스다운 클래스
함수 `__init__()`는 클래스에 사용되며, 클래스가 생성하는 객체를 초기화(initialize)합니다. 이 함수 는 항상 적어도 하나의 인자 self를 갖는데요, 이는 생성된 객체를 나타냅니다.

### 4. 두 번째 매개변수 추가하기
### 5. 첫번째 객체(Object) 인스턴스화(Instantiatie)
	class Animal(object):
    	def __init__(self, name):
        	self.name = name

	zebra = Animal("Jeffrey") #객체 인스턴스화
	print zebra.name

>Jeffrey 출력

## 멤버 변수(Member Variables)와 멤버 함수(Member Functions)

### 6. 함수 __init__()과 self 더 알아보기
self는  __init__() 함수 정의 안에서만 사용되어야 합니다; self를 인스턴스 객체에 전달하지 않아도 됩니다.

### 7. 클래스 범위(Class Scope)
### 8. 메소드(method)
### 9. 멤버 변수 추가하기
### 10. 보다 현실적인 클래스와 객체

## 상속(Inheritance)
### 11. 경고: 상속의 주의사항
### 12. 상속 문법
### 13. 덮어쓰기(Override)!
### 14. super()함수 호출하기
파생 클래스(또는 서브클래스(subclass))를 가지고 작업을 하다보면, 종종 베이스가 되는 클래스(부모(parent) 클래스, 또는 슈퍼클래스(superclass))로부터 상속받은 속성이나 메소드를 덮어 썼는데, 알고 봤더니 상속받은 값이 필요하다는 걸 깨달을 때도 종종 있습니다. 겁먹지 마세요! 파이썬의 내장 함수인 `super()`를 호출해서 슈퍼클래스의 속성이나 메소드에 직접 접근할 수 있습니다.

	class DerivedClass(Base):
    	def some_method(self):
        	super(DerivedClass, self).method(args)

# 파일 입/출력(Input/Output)

## 파일 입/출력(File I/O) 입문
### 1. 백문이 불여일견
    my_list = [i**2 for i in range(1,11)]
    # 1부터 10까지 숫자의 제곱값으로 이루어진 리스트 생성

    f = open("output.txt", "w")

    for item in my_list:
        f.write(str(item) + "\n")

    f.close()

### 2. open() 함수

### 3. 쓰기(Writing)
`write()` 함수를 이용하여 파일을 쓸 수 있습니다. 이 함수는 하나의 문자열 인자만 갖습니다. 그러므로 f.write(str(item) + "\n") 이렇게 하나의 문자열로 변환해줘야합니다.
### 4. 읽기(Reading)
`read()` 함수를 이용하여 파일을 읽을 수 있습니다.

##악마는 디테일에 있다(The Devil's in the Details)
### 5. 한 줄씩 읽어나가기
만약 파일을 열고 해당 파일 객체에 `readline()` 함수를 호출하면, 파일의 첫 번째 줄의 데이터를 얻게 될 겁니다. 그 다음 readline() 함수 호출은 이어지는 줄의 데이터를 반환할 겁니다.

### 6. 데이터 버퍼링(Data Buffering)
아까부터 계속 파일을 읽거나 쓴 다음엔 항상 파일을 닫아야 한다고 이야기하고 있는데요, 왜 그래야 하는지 그 이유가 여기 있습니다.

파일 입/출력 과정 진행 중, 데이터들은 **버퍼(buffer)** 처리됩니다: 이는 해당 데이터들이 파일에 쓰여지기 이전에 일시적인 장소에 담겨있다는 의미입니다. 파이썬은 여러분이 작성을 끝냈다고 확인하기 전까지 **버퍼를 플러쉬(flush the buffer)**(즉, 파일에 데이터를 작성)하지 않습니다. 이를 위한 또 하나의 방법은 파일을 닫는 것입니다. 만약 파일을 닫지 않고 작성한다면, 데이터는 이를 타겟 파일로 만들지 못할 것입니다.

### 7. 'with'와 'as' 키워드
프로그래밍이란 건 결국 컴퓨터에게 작업을 시키기 위한 것입니다. 만약 파이썬에 파일을 자동으로 닫게끔 하는 방법이 있다면 어떨까요?

물론 존재합니다. 그래야 바로 파이썬이죠.

여러분은 모르시겠지만 파일 객체는 특별한 내장 메소드 쌍을 가지고 있는데요, `__enter__()`와 `__exit__()` 입니다. 이에 대한 세부 내용보다 중요한 것은 **파일 객체의 `__exit__()` 메소드가 적용될 때, 파일이 자동으로 닫힌다는 겁니다.** 그럼 이 메소드를 어떻게 적용시킬 수 있을까요? with와 as를 사용하면 됩니다.

문법은 다음과 같습니다:

	with open("text.txt", "w") as textfile:
    	textfile.write("Success!")

### 8. 혼자 힘으로 해보세요
### 9. 제대로 닫혔나요?
파이썬 파일 객체에는 `closed`라는 속성이 있는데 이는 파일이 닫혔을 땐 값으로 True를, 그렇지 않을땐 False를 갖습니다. fileobject.closed라고 작성함으로써 해당 파일이 닫혔는지 여부를 알 수 있으며, 만약 닫히지 않았을 땐 `close()` 함수를 호출해서 닫아줄 수 있습니다.

---
Python Language Study based on https://www.codecademy.com/ko/tracks/python-ko