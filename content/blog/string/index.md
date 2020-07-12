---
title: 파이썬 Basic
date: "2020-07-08T22:40:32.169Z"
description: 파이썬 문자열 연산자
---

### len 함수

```
str1 = "I am Boy"
str2 = "NiceMan"
str3 = '  '
str4 = str('asdf')

print(len(str1), len(str2), len(str3), len(str4))
# 공백도 문자길이로 인식한다.
```

### escape 문자 사용

```
escape_str1 = "Do tou have a \"big eollection\""
print(escape_str1)
escape_str2 = "Tab\tTab\tTab"
print(escape_str2)
```

### 멀티라인

```

multi = \
    """
문자열

멀티라인

테스트
"""

print(multi)

# 개행을 하기 위해서는 첫줄에 \ 표시를 적어줘야함
```

### 문자열 연산

```
str_o1 = '*'
str_o2 = 'abc '
str_o3 = 'def'
str_o4 = "Niceman"

print(str_o1 * 100)
print(str_o2 + str_o3)
print(str_o1 * 3)
print('a' in str_o4)  # 순회가능한 시퀀스, 한번할당이 되면 수정이 불가능하다
print('f' in str_o4)  # 문자열이 있는지 True, False 로 반환한다
print('z' not in str_o4)

print(str(77) + 'a')
print(str(10.4))
```

### 문자열 형변환

```
print(str(77) + 'a')
print(str(10.4))
```

### 문자열 함수

```
a = 'niceman'
b = 'orange'

 print(a.islower())
 print(b.endswith('e'))
 print(b.capitalize())
 print(a.replace('nice', 'good'))
 print(list(reversed(b)))

```

### 문자열 슬라이싱

```
a = 'niceman'
b = 'orange'

print(a[0:3])
print(a[0:4])
print(a[0:len(a)])
print(a[:])
print(b[0:4:3])
print(b[1:-2])
print(b[::-1])
```
