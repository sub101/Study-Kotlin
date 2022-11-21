# 1.2 클래스와 프로퍼티

### 프로퍼티
자바에서는 필드와 접근자를 묶어 프로퍼티라고 부른다.
코틀린 프로퍼티는 자바의 필드와 접근자 메소드 역할을 한다.
클래스에서 프로퍼티를 선언할 때는 변수 선언 방법과 동일하게 val 이나 var 사용한다.
(val은 읽기 전용, var은 변경 가능)

- 코틀린에서는 자바 클래스의 getter를 val 프로퍼티처럼 사용할 수 있고,
  getter/setter 쌍이 있는 경우 var 프로퍼티처럼 사용할 수 있다.
  (getter호출하는 대신 프로퍼티 직접 사용)

- 코틀린에서 getter/setter 이름 정하는 규칙
 * is로 시작하는 프로퍼티의 getter에는 get이 붙지 않고 원래 이름 그대로 사용
 * setter에는 is를 set으로 바꾼 이름 사용

#### 커스텀 접근자


### 클래스
kotlin, public이 기본으로 생략 가능
kotlin의 클래스 선언은 java의 멤버변수 선언 없이 사용 가능

class Person(var name : String, var isStudent : Boolean)
: Person 클래스 안에 String name , Boolean isStudent 멤버변수가 있다.

