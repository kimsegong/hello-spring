<h1>Spring정복기</h1>

Spring을 시작하기전 Java에 대한 기초지식이 있어야한다.

<h3>객체 지향 프로그래밍(OOP)</h3>
객체 지향 프로그래밍(Object Oriented Programming)은 컴퓨터 프로그래밍의 패러다임 중 하나이다.<br>
OOP 는 컴퓨터 프로그램을 명령어의 목록으로 보는 시각에서 벗어나 여러개의 독립된 단위인 객체들의 모임으로 파악하고자 하는 것이다.<br>
각각의 객체는 메시지를 주고받고 데이터를 처리할 수 있다.<br>
객체 지향 프로그래밍은 프로그램을 유연하고 변경이 용이하게 만들기 때문에 대규모 소프트웨어 개발에 많이 사용된다.<br>
참고 - 객체 지향 프로그래밍(위키백과)



<h3>🌈 SOLID - 좋은 객체 지향 설계의 5가지 원칙</h3>
<strong>SRP: 단일 책임 원칙(single responsibility principle)</strong><br>
한 클래스는 하나의 책임만 가져야 한다.<br>

OCP: 개방-폐쇄 원칙 (Open/closed principle)<br>
확장에는 열려 있으나 변경에는 닫혀 있어야 한다.<br>
기능을 추가하려면 소스코드의 수정이 불가피하다. 다형성을 이용하더라도 클라이언트 코드를 변경해야 한다. 이는 OCP 원칙에 위배되는 것이다. 이것을 해결하기 위해서는 객체를 생성하고, 연관관계를 맺어주는 별도의 조립, 설정자가 필요하다.<br>

LSP: 리스코프 치환 원칙 (Liskov substitution principle)<br>
프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 한다.<br>
다형성에서 하위 클래스는 인터페이스 규약을 다 지켜야 한다는 것, 다형성을 지원하기 위 한 원칙, 인터페이스를 구현한 구현체는 믿고 사용하려면, 이 원칙이 필요하다.<br>

ISP: 인터페이스 분리 원칙 (Interface segregation principle)<br>
특정 클라이언트를 위한 인터페이스 여러 개가 범용 인터페이스 하나보다 낫다.<br>

DIP: 의존관계 역전 원칙 (Dependency inversion principle)<br>
프로그래머는 “추상화에 의존해야지, 구체화에 의존하면 안된다.” 의존성 주입은 이 원칙 을 따르는 방법 중 하나다. 쉽게 이야기해서 구현 클래스에 의존하지 말고, 인터페이스에 의존하라는 뜻이다.<br>
