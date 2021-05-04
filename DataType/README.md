#자바 자료형(Java Data Type)
---
##1. Java Data Type
기본형과 참조형이 있다.
기본형(Primitive Type)
1. 정수 타입 : byte, char, short, int, long
2. 실수 타입 : float, double
3. 논리 타입 : boolean

자료형 | 데이터 | 메모리 크기 | 표현 가능 범위
---|:---:|---:|---:
boolean | 참과 거짓 | 1byte | true, false
char | 문자 | 2byte | 모든 유니코드 문자
byte | 정수 | 1byte | -128 ~ 127
short | 정수 | 2byte | -32768 ~ 32767
int | 정수 | 4byte | -2147483648 ~ 2147483647
long | 정수 | 8byte | -9223372036854775808 ~ 9223372036854775807
float | 실수 | 4byte | 1.40239846e-45f ~3.40282347e+38f
double | 실수 | 8byte | 4.94065645841246544e-324~1.79769313486231570e+308

참조형(Reference Type)
1. 배열(Array) 타입 : 배열형은 기본형으로도 만들 수 있고 참조형으로도 만들 수 있다
2. 클래스(Class) : 기본형과는 다르게 객체를 참조하는 형태
3. 인터페이스(Interface)