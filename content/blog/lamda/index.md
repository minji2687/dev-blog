---
title: 파이썬 함수 및 람다(lambda)
date: "2020-07-08T22:40:32.169Z"
---

### 함수 정의 & 호출

```
def hello(world):
    print("Hello", world)


hello("Python!")
hello(777777)

```

> 함수 호출 위치 중요, 함수 선언 보다 호출을 먼저 하면 에러 발생

#### 함수 리턴

```
def hello_return(world):
    val = "Hello" + str(world)
    return val


str1 = hello_return("Python!!!!!!!!")
print(str1)

```

##### 함수 다중 리턴

```
def function_mul(x):
    y1 = x * 100
    y2 = x * 200
    y3 = x * 300
    return y1, y2, y3


val1, val2, val3 = function_mul(100)
print(type(val1), val2, val3)


# 타입 변환 후 리턴
def function_mul2(x):
    y1 = x * 100
    y2 = x * 200
    y3 = x * 300
    return (y1, y2, y3)


lt = function_mul2(100)
print(lt, type(lt))

```

#### 리스트 슬라이싱

```
print(d[0:3]) # [10, 100, 'Pen']
print(e[2][1:3]) # ['Banana', 'Orange']

```
