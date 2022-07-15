# 파이썬 기초



## vs code

- 파일 이름 옆에 ● 있는 경우 저장 **X**
  - 저장:Crtl+s(파일이름은 영어,_만 사용)

- 터미널 만들기: Crtl+Shift+`
- 터미널 이동: Crtl+`



#### 저장-변수(variable)

- **숫자**
  - 크기를 가진다
- **글자**
  - `''(따옴표)` 안에 넣으면 됨 (`'숫자'`는 글자 취급을 함)
- **참/거짓**
  - true, false
  - 조건/반복을 위해 사용



#### 저장-리스트(list)

- `[](대괄호)`로 나타냄(`ex)[23,43,12]`)
  - **순서는 0부터 시작**



#### 저장-딕션너리(dictionary)

- 이름을 단 여러 개의 값을 저장할 수 있는 저장공간
- `{}(중괄호)`안에 넣으면 됨(`ex){"서대문구":23,"강남구":34, "영등포구":70,......`)
- 이름(key)는 중복 **X**



#### 조건-if/else

```python
if~~~:
    print()
else:
    print()
```

- if(~이면), else(아니면)
- 조건문 다음에 무조건 **들여쓰기(indentation)** 해야 함



#### 조건-elif

```python
dust = 70
if dust>150:
    print('매우나쁨')
elif dust>80:
    print('나쁨')
elif dust>30:
    print('보통')
else:
    print('좋음')
```

- if(~이면), elif(그렇지 않고 ~이며), else(아니면)



#### 반복-while

```python
n=0
while n<3:
    print(n)        
    n=n+1
```

- 횟수의 **`제한이 없는`** 반복



#### 반복-for

```python
dusts=[59,24,102]
for value in dusts:
    print(value)
```

- 회수의**`제한이 있는` **반복

