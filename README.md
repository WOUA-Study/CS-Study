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
- LinkedList와 ArrayList의 차이점은 무엇인가요? - (시습)
- Stack을 사용하지 못하는 상황에서 대체할 수 있는 Collection은 무엇이 있을까요? - (시습)
- "오버라이드 된" equals와 ==의 차이는 무엇인가요? - (시습)
- hashCode의 의미는 무엇인가요? - (시습)
- HashMap에 대해서 설명해주시고, Hash Collision 발생 시 자바는 어떻게 대처하나요? - (국민)
- Hash Collision이 많이 발생할 경우 어떤 최적화가 진행될까요? - (국민)
- Java Compiler는 문자열 연산 최적화를 어떻게 진행하나요? (String Builder, String...) - (국민)
- SringBuilder를 사용하는 것과 String을 사용하여 연산하는 것에서 어떠한 큰 차이가 존재할까요? -(국민)
- 문자열을 리터럴(`string = "abcd"`)로 할당하는 것과 객체(`string = new String("abcd")`)로 할당하는 방식의 차이가 무엇인가요? - (국민)
- Managed - Unmanaged 언어의 차이는 무엇이고 어떤 장, 단점이 있나요? - (나겸)
- Java는 Call By Value일까요, Call By Reference 일까요? - (나겸)
- Shallow Copy와 Deep Copy의 차이는 무엇인가요? 자바에서 Deep Copy를 하기 위해서는 무엇을 사용하여야 하나요? - (나겸)
- JVM은 어떤 방식으로 코드를 해석하고 실행시키는지 흐름에 맞게 설명해 주세요. (Java 실행 흐름) - (정민)
  - [클래스 로딩 과정 정리](https://luxurious-syzygy-94d.notion.site/1b5e21d1cc3d80ae803eefb82daea6c3)
- JVM의 메모리 구조에 대해서 설명해 주세요. - (정민)
- Garbage Collector은 무엇이고, Parallel GC와 CMS GC, G1 GC, ZGC의 큰 차이는 무엇인지 설명해주세요. (mark-sweep-compact, concurrency-sweep, garbage-first) - (정민)
  - [자바 메모리 구조와 GC](https://luxurious-syzygy-94d.notion.site/Java-Memory-GC-19ee21d1cc3d8095ac8ee0abfc45252c)

### 여기까지 2주차
- foreach를 사용할 수 있는 자료구조는 어떤 인터페이스를 상속 받고 있나요?
- iterator와 iterable 차이는 무엇인가요?
- Fast-fail iterator는 무엇이고 어떤 것을 위해 사용되는 건가요?
- Java의 Functional interface는 무엇인가요?
- Java Lambda는 왜 만들어졌고, 어느 때 주로 사용할까요?
- Java Stream API의 특징은 무엇이 있나요?
- Java 8~21 버전에 추가된 중요 기능들에 대하여서 설명해주세요.
- 하나의 쓰기 스레드와 여러 읽기 스레드가 존재할 때 사용되어야 하는 Java의 동기화 기능은 무엇이고 어떻게 동작하게 되는지 설명해주세요.
- 스레드에서 Race condition에 대해서 설명해주세요.
- 자바의 synchronized 키워드에 대해 설명해주시고 Reentrant Lock와의 차이는 무엇인지 말씀해주세요.
- Java의 synchronized Lock 범위에 대해서 알려주세요. (Class Lock, Instance Lock)
- volatile 키워드에 대해 설명해 주세요.
- atomic Type과 CAS는 무엇이고 언제 사용되는 것인가요?
- Vector와 Stack을 사용하지 않는 이유는 무엇인가요?
- Lock Stripping은 무엇이고 어떠한 자료구조가 해당 방식을 구현하였나요?
- ConcurrentHashMap은 어떤 방식으로 스레드 동시성을 보장하나요?
- CopyOnWriteArrayList은 어떤 방식으로 스레드 동시성을 보장하나요?
- Java Reflection이란 무엇이고, 어떨 때 사용되는 것인가요?
- Java Instrumentation이란 무엇이고 사용했을 때 어떤 장점이 있을까요?
