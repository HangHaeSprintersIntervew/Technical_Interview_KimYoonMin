# Day 5

1. 스프링 필터랑 인터셉터의 차이점이 무엇인가요?
수행되는 시점에 차이가 있다.
필터는 웹 어플리케이션(Web Application)에 등록합니다. 요청 스레드가 서블릿 컨테이너(Servlet Container)에 도착하기 전에 수행됩니다.
인터셉터는 스프링 컨텍스트(Context)에 등록합니다. 
서블릿 컨테이너를 통과한 후 컨트롤러에게 요청이 전달되기 전, 후에 대한 처리를 수행합니다. 스프링 컨텍스트 내에 존재하기 때문에 모든 빈(bean) 객체에 접근할 수 있습니다. 

2. JPA 장점, 단점에 대해 설명해보세요
- 장점 : 
  생산성 : SQL을 직접적으로 작성하지 않고 엔티티 필드가 되는 객체를 다뤄서 데이터베이스를 동작시키기 때문에 유지보수가 더욱 간결하다.
  성능 : 일반적인 Spring의 encache 기능처럼 동일한 쿼리에 대한 캐시 기능을 사용하기 때문에 더욱 높은 성능적 효율성을 경험할 수있다. 
- 단점 : 통계 쿼리처럼 매우 복잡한 SQL을 작성하기에는 적합하지 않다


3. ORM에 대해 설명해보세요
- ORM은 Object Relational Mapping 즉, 객체-관계 매핑의 줄임말이다. 
  객체-관계 매핑을 풀어서 설명하자면 우리가 OOP(Object Oriented Programming)에서 쓰이는 
  객체라는 개념을 구현한 클래스와 RDB(Relational DataBase)에서 쓰이는 데이터인 테이블 자동으로 매핑(연결)하는 것을 의미한다.


4. 생성자 주입 사용시 장점이 무엇이라고 생각하시나요?


5. Entity에 대해 아는대로 설명해보세요


6. Setter를 무분별하게 사용하면 안되는 이유는 무엇인가요?
