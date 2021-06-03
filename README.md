# TIL

## 코틀린으로 쇼핑몰 앱 만들기 (21-06-03)
### 1. 함수와 변수
코틀린에서 함수를 선언하는 방법에는 두 가지가 있다
- 일반적인 선언 방법
``` fun sum(a: Int, b: Int): Int {
return a+b
}

- 표현식이 본문인 함수
``` fun sum(a: Int, b: Int) = a+b
