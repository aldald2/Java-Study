# 배열(Array)
---
- 배열 : 배열은 연관된 정보를 그룹핑하는데 사용한다.
- 배열의 개념
 + 배열은 연관된 데이터를 모아서 관리하기 위해 사용하는 데이터 타입이다.
   변수가 하나의 데이터를 저장하기 위한 것이라면 배열은 여러개의 데이터를 저장하기 위한 것

```java
String[] classGroup = {"김모모", "이모모", "최모모", "박모모"};
```

- 배열의 첫 번째 역할은 연관된 데이터를 저장하는 것이다.

### 배열을 정의하는 다른 방법과 배열에 담겨있는 값의 수를 알아내는 방법
```java
String[] classGroup = new String[4];
classGroup[0] = "김모모";
System.out.println(classGroup.length);
```

## 배열의 오류와 한계
### 오류
- ArrayIndexOfBoundsException : 존재하지 않는 인덱스를 사용하려 했을 때 발생
 + ex)
 ```java
 String[] members = {"김모모", "이모모", "최모모"};
 System.out.println(members[3]);
 ```
 배열을 선언할 때 이 배열의 크기를 3개의 문자열을 수용할 수 있는 크기로 지정했는데 더 많은 데이터를 추가하려 하기 때문에 발생한 에러

### 배열의 한계
- 배열은 초기화 할 때 그 크기가 정해진다. 그래서 정해진 크기 이상의 값을 넣을 수 없다.
  자바에는 컬렉션(Collection)이라는 기능이 있다. Container 라고도 부르는 이 기능을 이용하면
  Java Script의 배열과 같이 유연하게 배열을 사용할 수 있다.