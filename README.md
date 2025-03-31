# WOUA - CS 스터디

신입 개발자 수준에서 Java와 Spring을 학습하고 정리하는 저장소입니다.  
예제 코드는 Github을 통해 제공되며 질문에 대해 공부한 내용은 별도 링크를 통해 공유합니다.  
틀린 내용이 있을 수 있으니 주의가 필요합니다.  
질문은 Lob-dev님의 [Junior-Backend-Developer-Concepts 저장소](https://github.com/Lob-dev/Junior-Backend-Developer-Concepts/blob/main/50_Job%20interview.md)를 기반으로 합니다.

## Java (52개)
- 객체 지향 프로그래밍을 왜 사용한다고 생각하시나요? - (시습)
  - [객체지향프로그래밍](https://swaphome.tistory.com/7) 
- 객체 지향의 클래스, 객체, 인스턴스 차이에 대해서 설명해 주세요. - (시습)
  - [클래스, 객체, 인스턴스](https://swaphome.tistory.com/8)
- Java 접근 제어자에는 무엇이 있는지 설명해주시고 Protect와 Private는 어느 시점에 어떻게 사용될 수 있는지 이야기 해주세요. - (시습)
  - [접근제어자](https://swaphome.tistory.com/9)
- Wrapper Class란 무엇이고 Primitive Type과의 차이는 무엇인가요? - (시습)
  - [래퍼클라스와 프리미티브 타입](https://swaphome.tistory.com/10)
- Interface와 Abstract Class의 차이는 무엇인가요? - (국민)
- Interface가 사용되면 좋은 시점은 언제일까요? - (국민)
- Abstract Class가 사용되면 좋은 시점은 언제일까요? - (국민)
- Interface와 Abstract Class를 같이 상속받는 경우에는 왜 그렇게 작성하였을까요? - (국민)
  - [추상클래스와 인터페이스](https://velog.io/@mxcoogi/%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EC%99%80-%EC%B6%94%EC%83%81%ED%81%B4%EB%9E%98%EC%8A%A4)
- Java final 키워드에 대해서 설명해주세요. 각각의 쓰임에 따라 어떻게 동작하나요? (Class, Variable) - (나겸)
  - [final 키워드](https://nagul2.tistory.com/458)
- 불변 객체는 무엇이고 Java에서 어떻게 구현할까요? - (나겸)
- String이 final인 이유는 무엇인가요? - (나겸)
  - [불변 객체, String이 불변인 이유](https://nagul2.tistory.com/459)
- 데이터 직렬화(Serialization)과 역직렬화(Deserialization)에 대해서 설명해 주세요. - (정민)
- Java Serialization은 왜 만들어졌고, 어떤 단점들이 있을까요? - (정민)
  - [직렬화 역직렬화](https://luxurious-syzygy-94d.notion.site/1a9e21d1cc3d8088b25aea63a924c329?pvs=74)
- Java Generic에 대해서 설명해 주세요. - (정민)
- Java Generic의 반공변, 공변, 무공변은 무엇인지 설명해주세요. - (정민)
  - [제네릭](https://luxurious-syzygy-94d.notion.site/1aae21d1cc3d80429ce0caadd6e7bfd2)
  - [계산기 만들다 제네릭한테 맞은 썰](https://luxurious-syzygy-94d.notion.site/1a5e21d1cc3d8068a9befb26f2ec79bb)

### 2주차 분량
- Array와 ArrayList의 차이점은 무엇인가요? - (시습)
  - [Array와 ArrayList의 차이점](https://swaphome.tistory.com/55)
- LinkedList와 ArrayList의 차이점은 무엇인가요? - (시습)
  - [LinkedList ArrayList 차이점](https://swaphome.tistory.com/66)
- Stack을 사용하지 못하는 상황에서 대체할 수 있는 Collection은 무엇이 있을까요? - (시습)
  - [Stack을 대체 할 수 있는 컬렉션](https://swaphome.tistory.com/69)
- "오버라이드 된" equals와 ==의 차이는 무엇인가요? - (시습)
- hashCode의 의미는 무엇인가요? - (시습)
  - [equals hashcode](https://swaphome.tistory.com/70)
- HashMap에 대해서 설명해주시고, Hash Collision 발생 시 자바는 어떻게 대처하나요? - (국민)
- Hash Collision이 많이 발생할 경우 어떤 최적화가 진행될까요? - (국민)
  - - [HashMap Hash Collision](https://velog.io/@mxcoogi/HashMap-HashCollision)
- Java Compiler는 문자열 연산 최적화를 어떻게 진행하나요? (String Builder, String...) - (국민)
- SringBuilder를 사용하는 것과 String을 사용하여 연산하는 것에서 어떠한 큰 차이가 존재할까요? -(국민)
- 문자열을 리터럴(`string = "abcd"`)로 할당하는 것과 객체(`string = new String("abcd")`)로 할당하는 방식의 차이가 무엇인가요? - (국민)
  - [String StringBuilder](https://velog.io/@mxcoogi/String%EA%B3%BC-String-%EC%97%B0%EC%82%B0%EC%9D%98-%EC%B5%9C%EC%A0%81%ED%99%94)
- Managed - Unmanaged 언어의 차이는 무엇이고 어떤 장, 단점이 있나요? - (나겸)
  - [Managed - Unmanaged 언어의 차이](https://nagul2.tistory.com/473)
- Java는 Call By Value일까요, Call By Reference 일까요? - (나겸)
  - [Java는 Call By Value로 동작함](https://nagul2.tistory.com/474)
- Shallow Copy와 Deep Copy의 차이는 무엇인가요? 자바에서 Deep Copy를 하기 위해서는 무엇을 사용하여야 하나요? - (나겸)
  - [얕은 복사, 깊은 복사의 차이와 자바에서 Deep Copy 구현 방법](https://nagul2.tistory.com/475)
- JVM은 어떤 방식으로 코드를 해석하고 실행시키는지 흐름에 맞게 설명해 주세요. (Java 실행 흐름) - (정민)
  - [클래스 로딩 과정 정리](https://luxurious-syzygy-94d.notion.site/1b5e21d1cc3d80ae803eefb82daea6c3)
- JVM의 메모리 구조에 대해서 설명해 주세요. - (정민)
- Garbage Collector은 무엇이고, Parallel GC와 CMS GC, G1 GC, ZGC의 큰 차이는 무엇인지 설명해주세요. (mark-sweep-compact, concurrency-sweep, garbage-first) - (정민)
  - [자바 메모리 구조와 GC](https://luxurious-syzygy-94d.notion.site/Java-Memory-GC-19ee21d1cc3d8095ac8ee0abfc45252c)

### 3주차
- foreach를 사용할 수 있는 자료구조는 어떤 인터페이스를 상속 받고 있나요? - (시습)
- iterator와 iterable 차이는 무엇인가요? - (시습)
- Fast-fail iterator는 무엇이고 어떤 것을 위해 사용되는 건가요? - (시습)
- Java의 Functional interface는 무엇인가요? - (국민)
- Java Lambda는 왜 만들어졌고, 어느 때 주로 사용할까요? - (국민)
  - [자바 람다식과 함수형 인터페이스](https://velog.io/@mxcoogi/%EB%9E%8C%EB%8B%A4%EC%99%80-%ED%95%A8%EC%88%98%ED%98%95-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4)
- Java Stream API의 특징은 무엇이 있나요? - (국민)
  - [자바 스트림](https://velog.io/@mxcoogi/JAVA-Stream)
- 하나의 쓰기 스레드와 여러 읽기 스레드가 존재할 때 사용되어야 하는 Java의 동기화 기능은 무엇이고 어떻게 동작하게 되는지 설명해주세요. - (나겸)
- 스레드에서 Race condition에 대해서 설명해주세요. - (나겸)
- 자바의 synchronized 키워드에 대해 설명해주시고 Reentrant Lock와의 차이는 무엇인지 말씀해주세요. - (나겸)
- Java의 synchronized Lock 범위에 대해서 알려주세요. (Class Lock, Instance Lock) - (나겸)
  - [출금 예제를 통한 동시성 문제와 synchonized 동기화(간단한 레이스 컨디션 설명)](https://nagul2.tistory.com/429)
  - [LockSupport, ReentrantLock 설명](https://nagul2.tistory.com/430)
- volatile 키워드에 대해 설명해 주세요. - (나겸)
  - [메모리 가시성, volatile, 자바 메모리 모델](https://nagul2.tistory.com/427)
- atomic Type과 CAS는 무엇이고 언제 사용되는 것인가요? - (나겸)
  - [CAS 연산 설명](https://nagul2.tistory.com/433)
- Vector와 Stack을 사용하지 않는 이유는 무엇인가요? - (정민)
- Lock Stripping은 무엇이고 어떠한 자료구조가 해당 방식을 구현하였나요? - (정민)
- ConcurrentHashMap은 어떤 방식으로 스레드 동시성을 보장하나요? - (정민)
- CopyOnWriteArrayList은 어떤 방식으로 스레드 동시성을 보장하나요? - (정민)
  - [자바 컬렉션 프레임워크와 동기화](https://luxurious-syzygy-94d.notion.site/Java-Collection-FrameWork-1bae21d1cc3d80b7aba7fb52e3348cd8)
- Java Reflection이란 무엇이고, 어떨 때 사용되는 것인가요? - (정민)
- Java Instrumentation이란 무엇이고 사용했을 때 어떤 장점이 있을까요? - (정민)
  - [Reflection과 Instrumentation](https://luxurious-syzygy-94d.notion.site/Reflection-Instrumentation-1bbe21d1cc3d8004abf0cf8e86ee0f69)

## Spring
- 프레임워크와 라이브러리 차이는 무엇인가요?
  - [프레임워크와 라이브러리 차이: Spring과 JBDC](https://swaphome.tistory.com/96)
- 디자인 패턴이란 무엇인가요?
- Value Object, Data Transfer Object, Data Access Object 대해서 각각 설명해 주세요. (레이어드 아키텍처 같이)
  - [DTO, VO](https://velog.io/@mxcoogi/DTO-%EC%99%80-VO%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80)
- Spring이란 무엇인가요? Spring이 이야기하는 장점에는 무엇들이 있을까요? (EJB와 비교해서 설명하면 좋을듯)
- IoC, DI는 무엇이고 어떠한 장점이 있을까요? - (나겸)
  - [IoC, DI, 스프링의 DI](https://nagul2.tistory.com/484)
- Spring IoC Container란 무엇인가요?
- Spring Boot가 해결하려고 했던 문제는 무엇이고 어떻게 해결하였나요?
- Bean이란 무엇인가요?
- Bean Scope와 종류에 대해 아는 만큼 설명해주세요.
- Configuration은 어떻게 Bean을 등록하고 관리할까요? (Singleton을 지키는 매커니즘은?)
- Bean Lite Mode는 무엇인가요?
- Spring Bean Life-cycle에 대해서 말해주세요.
- @Bean과 @Component은 각각 언제 사용되고 어떤 차이점을 가지나요?
- 순환 참조는 무엇이고 어떤 상황에서 발생할까요?
- Spring으로 개발하실 때 어떠한 DI 방식을 사용하시나요? 사용하는 이유는 무엇이 있는 것일까요?
- Field Injection를 왜 사용하면 안된다고 하는 것인가요? 사용할 때 어떠한 단점이 있을까요?
- (Field 주입과 대비하여) 생성자 주입은 빈 생성 때 사용되는 리플랙션 외에 추가적인 리플랙션을 진행하나요?
- MVC 1, 2 개념에 대해서 설명해 주세요. - (정민)
  - [MVC1, MVC2 차이점](https://my-simple-blog-phi.vercel.app/posts/mvc1-mvc2)
- Front Controller Pattern은 무엇인가요? - (정민)
- Dispatcher Servlet이란 무엇인가요? - (정민)
- Spring MVC에서 HTTP 요청이 들어왔을 때의 흐름을 설명해 주세요. - (정민)
  - [Dispatcher Servlet Internal](https://my-simple-blog-phi.vercel.app/posts/dispatcher-servlet-internal)
- Interceptor와 Filter의 차이점을 말해주세요. - (정민)
  - [Filter Interceptor 차이점](https://my-simple-blog-phi.vercel.app/posts/fitler-interceptor)
- 스프링에서 Bean으로 Filter를 구현할 수 있을까요? 혹시나 가능하다면 어떻게 할 수 있을까요? - (정민)
- Message Converter는 어느 시점에 사용되고 어떤 기능을 제공하나요? - (정민)
- @Transactional를 스프링 Bean 메서드 A에 적용하였고, 해당 Bean의 메서드 B가 호출되었을 때 메서드 내부에서 메서드 A를 호출하면 어떤 요청 흐름이 발생하게 되나요?
- Spring AOP는 어떻게 동작할까요? (프록시는 언제 생성되고 요청은 어떻게 잡아내나요?)
- Spring AOP는 CTW, PCW, LTW, RTW 중에 무엇일까요?
- Dynamic Proxy의 CTW, BTW, LTW, RTW은 각각 어떤 시점에 개입하는 것일까요?
- (Spring AOP와 비교하여) AspectJ의 도입 시점은 어느 시점이 될까요? 본인 만의 생각을 알려주세요.
- A 라는 Service 객체의 메서드가 존재하고 내부에서 로컬 트랜잭션이 3개가 존재한다고 할 때, @Transactional을 A 메서드에 적용하였을 때 어떠한 일이 벌어지고, 어떤 요청 흐름이 발생하게 되나요?
- Reflection API는 Runtime에서 코드를 생성하는데 많이 사용됩니다. 이는 Spring에서도 자주 활용되는데요. 스프링 컨테이너는 이런 Reflection으로 생성된 Bean의 정보를 실행 이후에 알고 있네요? 어떻게 알 수 있을까요?
- Spring, Spring Boot의 차이점에 대해 각각 설명해 주세요.
- Monolitc Architecture, Micro Service Architecture에 대해 각각 설명해 주세요.
- Thread-safe한 프로그래밍이란 어떤 것인가요?
- CAP 이론에 대해서 아시나요?
- WEB API의 성능 최적화를 위해서는 어떤 부분들을 고려해야 할까요?
- Stateless와 Stateful의 차이점은 무엇인가요?