### Java String Class

---

##### Method

```java
String A = '12345';
A.charAt(int index) return char

compareTo(String anotherString) return int
concat(String anotherString) return string
equals()
equalsIgnoreCase()

```

charAt(int index) return char

> compareTo(String anotherString) int
>
> concat
>
> 

#### String Class

```java
String s1 = "123"
String s2 = "123"
String s3 = new String("123")
String s4 = new String("123")

s1 == s2 // true
s1.equals(s2)  // true
s3 == s4 // false
s3.equals(s4) // true
```

> **== 연산자는 주소값을 비교**
>
> 문자열 리터럴 "123"이 s1,s2 에 저장 s1,s2의 주소값은 같다
>
> new 연산자를 사용해 String인스턴스를 생성 s3,s4 주소값은 다르지만 value는 같다
>
> **소스파일 컴파일시 같은 내용의 문자열 리터럴은 한번만 저장된다**

