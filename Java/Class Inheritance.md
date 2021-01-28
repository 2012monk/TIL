#### 상속(Inheritance)

---

> `클래스간의 상하 관계` _SuperClass 혹은 ParentClass 로부터 SubClass를 만드는것
>
> `상속이라는 관계를 통해 계층구조 형성`

* SuperClass 의 필드와 메소드를 물려받은
* 새로운 필드 메소드 추가가능
* 물려받은 메소드 수정가능 Overriding
* 동일 superclass를 상속하는 모든 subclass는 타입 호환가능.

클래스 상속은 _**extends**_키워드를 사용한다.

* 다중상속은 지원하지않음.

##### IS - A 관계

* `부모클래스 object = new 자식클래스();` **가능**
* `자식클래스 object = new 부모클래스();`  **불가능**

> 자바에서 만드는 모든 클래스는 Object 클래스를 자동 상속한다.



