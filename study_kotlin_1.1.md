# 1.1 함수와 변수

### 함수 
##### fun 함수이름 (매개변수 이름 : 매개변수 타입, 매개변수 이름 : 매개변수 타입) : 반환타입 {}

fun max(a : Int, b : Int) : Int{
    return if(a>b) a else b
}

1) 중괄호로 둘러싸인 함수 (블록이 본문인 함수)
return 필수
return type 지정 필수

2) 식이 본문인 함수 (중괄호 없이 등호와 식으로만 이뤄짐)
ex) fun max(a:Int,b:Int):Int = if(a>b) a else b

### 변수
값을 초기화하지 않으면 반드시 타입 명시해야 함.

var 
- variable
- mutable 변경가능한
- var 변수이름 : 변수타입
- 값 변경은 가능하지만 타입 변경은 불가

val
- value
- 변경 불가
- java의 final

- 쉽게 문자열 형식 지정
변수 앞에 $ 추가
ex) "Hello $name!"

${복잡한식} 형식으로 문자열에 넣을 수 있다.