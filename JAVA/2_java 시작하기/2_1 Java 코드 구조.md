# Java 코드 구조

Java 코드는 일반적으로 다음과 같은 구조로 이루어 져 있다.

``` java
/* Class */
public class 클래스명 {

    /* Method 1 */
    public static void 메서드명(매개변수){...}

    /* Method 2 */
    public static void 메서드명(매개변수){...}
}
```

### Class
---
Java의 가장 바깥쪽 영역은 class 이다. class 명은 사용자 마음대로 설정이 가능하지만, 소스파일의 이름과 일치해야 한다.

### Method
---
Method는 class 안에 들어가는 함수를 의미한다. 하나의 클래슨 내에는 여러 개의 메서드를 만들 수 있다.

`static` : 메서드에 static 키워드가 붙으면 클래스 메서드가 되어 객체를 만들지 않아도 클래스명.메서드명 형태로 호출이 가능하다.

