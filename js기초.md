# ***✔️혼.공.스 책 정리***
<br>   
   
## 자바스크립트 기본자료형
    숫자(number), 문자열(string), 불(boolean)   
 * 문자 그대로 사용하고싶다면 \   
   + \n 줄바꿈
   + \t 탭
   + \\\ (\\) 그 자체

 * 문자열 길이(length)
```
   > "안녕하세요".length   
     5
```

 * 불 자료형 &nbsp; ***p.90***
   + 참과 거짓 값을 표현   
     true, false 두가지
   + 비교연산자 사용
```
=== 양쪽이 같다
!== 양쪽이 다르다
```   
 * 불 부정 연산자
   + !기호를 사용해 참을 거짓으로, 거짓을 참으로 바꿈.
 * 불 논리합/곱 연산자
```
&& - 논리곱 - 둘다 포함해야 가능
|| - 논리합 - 둘 중 하나만 포함해도 가능
```
 * 자료형 검사(typeof)
   + typeof(자료)
 * 템플릿 문자열  &nbsp;  ***p98***
   + (`)백틱기호로 감싸 만듬
   + ``내부에 ${...}를 사용, 문자열 안에서 계산   

<br>

## 상수와 변수
    상수는 변하지 않는 값 const
    변수는 변하는 값 let   

## 자료형 변환 &nbsp; ***p116***
 * 문자열 입력(pormpt)
   + prompt(메세지 문자열, 기본 입력 문자열)
 * 불 입력(confirm)
   + confirm(메세지 문자열)
 * 숫자 자료형으로 변환
   + Number()
   + 숫자연산자를 통해서도 변환 가능   
     \> "52"- 0   
         52
 * 문자열 자료형으로 변환
   + String()
   + \>273 + ""   
      "273"
 * 불 자료형으로 변환
   + Boolean()
   + 논리부정연산자를 두번 사용   
    \> !!273   
      true

<br>

## if 조건문
    if(불 값이 나오는 표현식) {
     불 값이 참 일때 실행할 문장
     }
 * if else 조건문
```
 if(불 값이 나오는 표현식) {
 불 값이 참 일때 실행할 문장
 } else {
 불 값이 거짓일 때 실행할 문장
     }
```
 * 중첩 조건문
   + 조건문 안에 조건문을 중첩
 * if else if 조건문
   + 중첩 조건문에서 중괄호를 생략한 형태   
   + 겹치지 않는 3가지 이상의 조건으로 나눌 때 사용
<br>   

## switch 조건문과 짧은 조건문  &nbsp; ***p142***
 * switch조건문
   + 값에 따라 조건분기를 걸어줌
 * 조건문 연산자
   + A?B:C 같은 형태로 피연산자 3개로 구성
 * 짧은 조건문
   + 논리연산자의 성질을 이용
<br>   

## 배열(arrary) &nbsp; ***p160***
    여러 개의 변수를 한 번에 선언해 다룰 수 있는 자료형      
    
 * 배열 만들기   
   + 대괄호[]사용   
   + 내부 값은 요소(element)   
   + 요소의 순서는 인덱스(index)
   + 배열의 이름은 복수형
   + 요소의 개수를 확인 할땐 length
   + 배열[배열.length - 1] > 배열의 마지막요소 선택
 * 배열 뒤에 요소 추가
   + 요소 추가 > 배열.push(요소)
 * 배열 요소 제거  &nbsp; ***p165***
   + 배열.splice(인덱스, 제거할 요소의 개수)
 * 특정위치에 요소 추가
   + 배열.splice(인덱스, 0, 요소) 
<br>
   
## 반복문
 * for in
 * for of
 * **for**
 * while
 
<br>   

## 함수의 기본 형태  &nbsp; ***p196***
 * 익명 함수
 * 선언적 함수
## 함수 고급 &nbsp; ***p220***
 * 콜백 함수
    - forEach()
    - map()
    - filter()
 * 화살표 함수
 * 타이머 함수
 * 즉시 호출 함수
  
<br>   

## 객체의 기본
 * 여러자료를 다룰때 객체(object)를 사용
## 객체의 속성과 메소드 사용하기
 * 객체 자료형
   + 속성과 메소드를 가질 수 있는 모든 것은 객체 (배열, 함수..)
 * 기본 자료형
   + 실체가 있는 것중에 객체가 아닌 것 (숫자, 문자열, 불)
     - 객체가 아니므로 속성을 가질 수 없다
 * 기본 자료형을 객체로 선언하기  &nbsp; ***p259***
   + new 객체 자료형 이름()
 * JSON객체  &nbsp; ***p272***
 * Math 객체  &nbsp; ***p276***
## 객체와 배열 고급
 * 속성 존재 여부 확인
 * 배열기반 다중 할당
 * **객체기반 다중 할당** &nbsp; ***p295***
 * 배열 전개 연산자
   + 얕은 복사
     - 참조복사, 다른 이름이 붙을 뿐
   + 깊은 복사
     - 독립적으로 작동
     - 전개 연산자 사용 [...배열]
 * 객체 전개 연산자
   + 얕은 복사
     - 참조복사, 다른 이름이 붙을 뿐
   + 깊은 복사
     - 독립적으로 작동
     - 전개 연산자 사용 [...객체]
  
<br>   

## 구문 오류와 예외
 * 오류의 종류
   + 구문 오류 (SyntaxError)
     - 프로그램 실행 전에 발생, 실행되지 않음.
   + *예외* 또는 *런타임 오류*
     - 실행 중에 발생, 실행됨
   + 기본 예외 처리  &nbsp; ***p369***
     - 조건문을 사용해 예외가 발생하지 않게 만듬
   + 고급 예외 처리  &nbsp; ***p370***
     - try catch finally
## 예외 처리 고급
 * 예외 객체
   + try catch 구문에 catch 괄호 안에 입력하는 식별자, 보통 *e*나 *exception*
 * 강제 예외 발생 &nbsp; ***p378***
   + throw
   + 예외를 강제로 발생시켜 사용 유도 
  
<br>   

## 클래스의 기본 기능
 * 추상화
   + 프로그램에 필요한 요소만 사용해 객체를 표현
 * 같은 형태의 객체 만들기
 * 클래스 선언하기
## 클래스의 고급 기능
 * 상속
