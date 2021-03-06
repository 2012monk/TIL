## Overriding Overloading

---

- ##### Method Overriding

  > `상속관계에 있는 부모클래스에서 정의된 메소드를 자식클래스에서 재정의` _chage or modify_
  >
  > _자식클래스는 private member를 제외하고 모든 메소드 상속받음_
  >
  > - 메소드의 동작만 재정의 => 선언부가 기존 메소드와 같아야함
  > - 접근 제어자를 더 좁은범위로 변경안됨. 
  >   - 부모의 메소드보다 넓은 범위의 접근제어자 지정 해야함
  > - 예외범위를 더 크게 선언 안됨.
  > - 인스턴스 메소드를 static 메소드로 또는 그반대로 변경불가.
  > - 자식 클래스에서 부모의 메소드를 수정할때
  >   - 추상클래스, 인터페이스에서 필수적으로 사용
  > - 부모 메소드 은닉, 재정의된 메소드만 호출 _super._ 으로 부모 메소드 호출가능

- ##### Method Overloading

  > _Method Signature_ **메소드의 선언부에 명시되는 매개변수의 리스트**
  >
  > **_서로 다른 시그니처를 갖는 여러 메소드를 같은 이름으로 정의_**
  >
  > > 매개변수의 타입, 개수, 순서 중 하나가 달라야 가능.
  > >
  > > 시그니처는 같지만 리턴 타입이 다른경우 불가능.

  > - 매개값을 다양하게 받아 다양한 처리 가능.
  >
  > - 메소드의 이름을 절약
  > - 매개변수 타입이나 개수에 대해 신경쓰지않고 호출가능



##### Overriding vs Overloading

```
overloading - 기존에 없는 새로운 메소드 정의
overriding - 상속받은 메소드의 내용을 변경
```

