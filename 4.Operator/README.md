# 연산자(Operator)
---
- 연산자 : 특정한 작업을 하기 위해 사용하는 기호를 의미
  작업의 종류에 따라 대입 연산자, 산술 연산자, 비교 연산자, 논리 연산자 등이 있다.

## 산술 연산자(Arithmetic)
- 수학적 계산에 사용되는 연산자다.
- 수학에서 사용하는 연산자와 프로그래밍에서 사용하는 연산자는 기호 모양이 조금 다르다.
- +(더하기), -(빼기), *(곱하기), /(나누기), %(나머지)
- 연산자는 숫자와 숫자를 더할 때도 사용하지만 문자열과 문자열을 결합할 때도 사용
```java
class ConcatDemo{
    public static void main (String[] args){
        String firstString = "This is";
        String secondString = "a concatenated String.";
        String thirdString = firstString + secondString;
        System.out.println(thirdString); // => This is a concatenated String.
    }
}
```

## 단항 연산자(Urary)
- 1+2 에서 사용한 연산자 + 는 이항 연산자(infix operator)이고 좌항인 1과 우항인 2를 더해주는 작업
- 단항 연산자는 하나의 항을 대상으로 연산이 이루어지는 연산자
- +) 양수를 표현한다. 실제로는 사용 할 필요가 없다.
- -) 음수를 표현한다.
- ++) 증가(increment) 연산자로 항의 값을 1씩 증가시킨다.
- --) 감소(Decrement) 연산자

## 비교 연산자(관계 연산자)
- 프로그래밍에서 비교란 주어진 값들이 같은지, 다른지, 큰지, 작은지를 구분하는 것
- 비교 연산자의 결과는 true나 false 중 하나

== | 좌항 우항 비교해서 서로 값이 같다면 true, 다르면 false
!= | '!'는 부정을 의미한다. '같다'의 부정은 '같지 않다'이다.
     ==와 정반대의 결과를 보여준다.
```java
(1 != 2); => true    (1 != 1); => false
```
`>` | 좌항이 우항보다 크다면 참, 아니면 거짓
`>=` | 좌항이 우항보다 크거나 같다.
.equal | 문자열을 비교할 때 사용하는 메소드다.
