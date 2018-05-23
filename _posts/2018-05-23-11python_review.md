---
layout: post
title:  python 모르는 부분 따로 정리
categories: [python]
---
`pyrhon` 정리

`enumerate` `index함수` `arguments`

<hr>

## index 함수

한 리스트 내에서 내가 원하는 valuew의 위치를 알고 싶을 때 사용하는 함수

기본 사용법

```
A = [0,1,2,3]

target = 1
A.index(target)
>>> 1
```

=> index()는 찾는 값의 첫번째 위치를 반환한다


## enumerate

enumerate는 열거하다라는 뜻으로 순서가 있는 자료형(리스트, 튜플, 문자열)을 입력으로 받아 인덱스 값을 포함하는 enumerate 객체를 리턴한다.

(보통 for문과 자주 사용된다.)

```
for i, name in enumerate(['body', 'foo', 'bar']):
... print(i, name)
...
>>> 0 body
    1 foo
    2 bar
```

순서값과 함께, body, foo, bar가 순서대로 출력되었다. 즉, 위 예제와 같이 enumerate를 for문과 함께 사용하면 자료형의 현재 순서(index)와 그 값을 쉽게 알 수 있다.

for 문처럼 반복되는 구간에서 객체가 현재 어느 위치에 있는 지 알려주는 인덱스 값이 필요할 때 사용하면 매우 유용하다.
