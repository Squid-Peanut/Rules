# Rules

## 필수

### 1. 코딩 방식 통일
* 변수명 지정
```python
# 유추 가능한 이름 지정
# Snake Case 사용

# 예제) 알파벳을 담은 변수 생성시
alphabet_a = 'a'
alphabet_list = ['abcdefghi']
alphabet_dict = {'a': 1, 'b': 2}
```
* 함수명 지정
```python
# 유추 가능한 동작명 지정
# Camel Case 사용

# 예제) 룰을 출력해 주는 함수 생성시
def printRules():
    print(rules)
```
* 클래스명 지정
```python
# 되도록 명사 사용
# Pascal Case 사용

# 예제) 룰이 담긴 클래스 생성시
class Rule:
    ...
```

### 2. 주석 표기 ( 영어 )
```python
# 함수의 경우 동작 설명

def sumAll(a_list):
    """
    Sum in list
    """
    return sum(a_list)

# 코드내 따로 주석이 필요한 부분
str_alphabet = 'abcdefg' # String Alphabet
```
### 3. 커밋 이름 지정 규칙
```bash
# 예제) 특정 함수를 수정해서 에러를 고쳤을 경우
$ git commit -m "Error Fix: New Someting Function Change"
```
<hr/>
