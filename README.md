# 머리를 식히는 Python
* 파이썬은 **인터프리트 언어(Interpreted Language)**
* 파이썬에서는 소스 파일을 **모듈(module)** 이라고 부른다.
* 파이썬은 모든 것이 **객체(object)** 다.

---

## 기본 자료형 (Data Type)
자료형 | 설명 | 예시
-------|------|-------
숫자형 | 정수, 실수 | 100, 1.43
문자열 | 문자들의 모음 | 'egg', 'spam'
리스트 | 순서를 갖는 임의의 객체 집합 | ['egg', 'spam']
세트 | 집합 형태 (합집합, 교집합, 차집합) | {1, 2, 3, 4}
튜플 | 순서를 갖는 임의의 객체 집합으로 변경 불가 | ('egg', 'spam')
딕셔너리 | 순서를 갖지 않는 객체의 집합 (키로 값을 꺼냄) | {'egg':4, 'spam':5}
 
* String (문자열)
    * 파이썬에서 한번 작성된 문자열은 변경이 불가능하다.
        > word = 'python'<br>
        word[0] = 'C' # TypeError: 'str' object does not support item assignment
* 리스트, 세트, 튜플은 서로 변환될 수 있다.

## Tuple & Set
* Tuple은 Immutable 타입의 리스트
    * 하지만, 튜플 요소가 Mutable하면 수정할 수 있음
* Set은 중복과 순서가 없는 자료형

## Crawling
* [Starting](crawling/started)