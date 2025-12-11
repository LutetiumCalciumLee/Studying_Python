<details>
<summary>ENG (English Version)</summary>

## 1. Programs and Programming Languages

- **Program**: A collection of sequential instructions written to be executed by a computer.  
- **Programming**: The process of creating programs using a programming language.  
- **Programming Language**: A language used to instruct a computer to perform tasks.  
  - Low-level language (machine-oriented), high-level language (human-oriented)

## 2. Introduction to Python and Its Features

- **Interpreter language**: Executes commands line by line.  
- **Dynamically typed**: Variable types are determined at runtime.  
- **Platform-independent**: Runs on various operating systems.

## 3. Python Practice Environment

- **Google Colab**: A web-based Python environment offering free GPUs. Chrome browser recommended.

## 4. Basic Python Syntax

### 4.1 Keywords
Predefined reserved words in Python:  
`False`, `None`, `True`, `and`, `as`, `assert`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`, `nonlocal`, `not`, `or`, `pass`, `raise`, `return`, `try`, `while`, `with`, `yield`

### 4.2 Identifier Rules
- Can use letters, numbers, and underscores `_` (cannot start with a number)  
- Case sensitive  
- Reserved words cannot be used  
- Special characters not allowed  

### 4.3 Statements
- One statement per line is recommended.  
- Multiple statements on one line separated by `;`.  
- Multi-line statements use `\` or parentheses.

### 4.4 Indentation and Comments
- Code blocks defined by indentation (4 spaces).  
- Single-line comment: `#`  
- Multi-line comment: `'''` or `"""`

### 4.5 Docstrings
- Used to describe functions, classes, modules.  
- Accessed via `__doc__`.

---

## 5. Variables, Constants, and Literals

### 5.1 Variables
- Store values; no type declaration needed; use `=` assignment.

### 5.2 Constants
- Typically uppercase with `_`; reassignment not strictly prevented.

### 5.3 Literals
- Values directly written in code (numbers, strings, booleans, etc.).

### 5.4 Special Literals & Collections
- Special: `None`, `True`, `False`  
- Collections: list, tuple, dictionary, set

---

## 6. Python Data Types

| Type       | Characteristics                       |
| :--        | :--                                   |
| Number     | Integer, float, complex               |
| List       | Ordered, mutable, allows duplicates   |
| Tuple      | Ordered, immutable, allows duplicates |
| String     | Sequence of characters, immutable     |
| Set        | Unordered, mutable, no duplicates     |
| Dictionary | Key-value pairs, ordered, mutable     |

Everything is an object; data types are classes, variables are instances.

---

## 7. Type Conversion and Casting

- **Implicit**: Automatically handled by the interpreter.  
- **Explicit**: Use `int()`, `float()`, `str()`, etc.

---

## 8. Input, Output, and Import

- Output: `print()`  
- Input: `input()`  
- Importing: `import`, `from ... import ...`, or use `as` for alias.

---

## 9. Python Operators

| Type        | Example Operators         | Description                    |
| :--         | :--                      | :--                            |
| Arithmetic  | +, -, *, /, //, %, **    | Basic math operations          |
| Comparison  | ==, !=, >, <, >=, <=     | Compare values                 |
| Logical     | and, or, not             | Boolean logic                  |
| Bitwise     | &, |, ^, ~, <<, >>       | Bit-level operations           |
| Membership  | in, not in               | Check if element in sequence   |
| Identity    | is, is not               | Compare object identity        |

---

## 10. Control Flow

- Conditional: `if`, `elif`, `else` (can nest)  
- Loops: `for`, `while`, `break`, `continue`, `pass`  
- `range()`: generates a sequence of numbers.

---

## 11. Functions

- Define with `def`.  
- Supports default, keyword, and variable-length arguments (`*args`, `**kwargs`).  
- Return values with `return`.  
- Recursive and lambda functions supported.  
- Variable scope: global, local, nonlocal.

---

## 12. Modules and Packages

- **Module**: A `.py` file containing functions, classes, variables.  
- **Package**: A folder containing multiple modules (`__init__.py`).

---

## 13. File Input/Output

- Open/close: `open()`, `close()`  
- Read/write: `read()`, `write()`, `readline()`, `readlines()`  
- Use `with` for automatic closing.

---

## 14. Exception Handling

- Common types: `SyntaxError`, `ZeroDivisionError`, `IndexError`, `KeyError`, etc.  
- Syntax: `try`, `except`, `else`, `finally`, `raise`.  
- Custom exception classes possible.

---

## 15. Object-Oriented Programming (OOP)

- Define classes with `class`.  
- Instance = object of a class.  
- Uses attributes (variables) and methods (functions).  
- Key principles: inheritance, polymorphism, encapsulation, overloading/overriding.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

## 1. 프로그램과 프로그래밍 언어

- **프로그램**: 컴퓨터가 실행할 명령어들의 집합  
- **프로그래밍**: 프로그래밍 언어를 사용해 프로그램을 만드는 과정  
- **프로그래밍 언어**: 컴퓨터에게 명령을 전달하기 위한 언어  
  - 저급 언어(기계 중심), 고급 언어(인간 중심)

## 2. 파이썬 소개와 특징

- **인터프리터 언어**: 명령을 한 줄씩 실행  
- **동적 타이핑 언어**: 변수의 자료형이 실행 시점에 결정  
- **플랫폼 독립적**: 다양한 운영체제에서 실행 가능

## 3. 파이썬 실습 환경

- **Google Colab**: 웹 기반 파이썬 실행 환경, 무료 GPU 제공, Chrome 브라우저 권장

## 4. 기본 문법

### 4.1 키워드
파이썬에서 미리 정의된 예약어  
예: `False`, `None`, `True`, `and`, `as`, `assert`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`, `nonlocal`, `not`, `or`, `pass`, `raise`, `return`, `try`, `while`, `with`, `yield`

### 4.2 식별자 규칙
- 문자, 숫자, 언더스코어(`_`) 사용 가능 (숫자로 시작 불가)  
- 대소문자 구분  
- 예약어 사용 불가  
- 특수문자 사용 불가

### 4.3 문장(Statement)
- 한 줄에 한 문장 권장  
- 여러 문장을 한 줄에 작성 시 `;` 사용  
- 여러 줄 문장은 `\` 또는 괄호로 연결

### 4.4 들여쓰기와 주석
- 코드 블록은 들여쓰기로 구분 (보통 4칸)  
- 한 줄 주석: `#`  
- 여러 줄 주석: `'''`, `"""`

### 4.5 독스트링(Docstring)
- 함수, 클래스, 모듈의 설명용 문자열  
- `__doc__` 속성으로 접근 가능

---

## 5. 변수, 상수, 리터럴

### 5.1 변수
- 값을 저장, 자료형 선언 불필요, `=` 사용해 할당

### 5.2 상수
- 일반적으로 대문자와 `_`로 표현, 재할당은 막지 않음  

### 5.3 리터럴
- 프로그램 코드에 직접 작성된 값 (숫자, 문자열, 불린 등)

### 5.4 특별 리터럴 및 집합 리터럴
- **특별 리터럴**: `None`, `True`, `False`  
- **집합 리터럴**: list, tuple, dictionary, set

---

## 6. 파이썬 자료형

| 유형       | 특징                                   |
| :--        | :--                                   |
| Number     | 정수, 실수, 복소수                    |
| List       | 순서 있음, 변경 가능, 중복 허용       |
| Tuple      | 순서 있음, 변경 불가, 중복 허용       |
| String     | 문자 시퀀스, 변경 불가                 |
| Set        | 순서 없음, 변경 가능, 중복 없음       |
| Dictionary | 키-값 쌍, 순서 있음, 변경 가능        |

모든 것은 객체이며, 자료형은 클래스, 변수는 인스턴스입니다.

---

## 7. 형 변환

- **묵시적 변환**: 인터프리터가 자동 변환  
- **명시적 변환**: `int()`, `float()`, `str()` 등 함수 사용

---

## 8. 입출력과 모듈 불러오기

- 출력: `print()`  
- 입력: `input()`  
- 모듈: `import`, `from ... import ...`, `as`로 별칭 사용 가능

---

## 9. 연산자

| 종류        | 예시 연산자          | 설명                    |
| :--         | :--                 | :--                    |
| 산술 연산자 | +, -, *, /, //, %, ** | 기본 수학 연산 |
| 비교 연산자 | ==, !=, >, <, >=, <= | 값 비교 |
| 논리 연산자 | and, or, not | 논리 판단 |
| 비트 연산자 | &, |, ^, ~, <<, >> | 비트 단위 연산 |
| 멤버 연산자 | in, not in | 시퀀스 포함 여부 확인 |
| 식별 연산자 | is, is not | 객체 동일성 비교 |

---

## 10. 제어문

- 조건문: `if`, `elif`, `else` (중첩 가능)  
- 반복문: `for`, `while`, `break`, `continue`, `pass`  
- `range()`: 숫자 시퀀스 생성

---

## 11. 함수

- `def`로 정의  
- 기본값, 키워드 인수, 가변 인수(`*args`, `**kwargs`) 지원  
- `return`으로 반환  
- 재귀, 람다 함수(`lambda`) 가능  
- 변수 범위: 전역, 지역, 비지역(nonlocal)

---

## 12. 모듈과 패키지

- **모듈**: 함수, 클래스, 변수 등이 들어있는 `.py` 파일  
- **패키지**: 여러 모듈을 포함한 폴더 (`__init__.py` 포함)

---

## 13. 파일 입출력

- 파일 열기/닫기: `open()`, `close()`  
- 읽기/쓰기: `read()`, `write()`, `readline()`, `readlines()`  
- `with`문 사용 시 자동으로 닫힘

---

## 14. 예외 처리

- 주요 예외: `SyntaxError`, `ZeroDivisionError`, `IndexError`, `KeyError` 등  
- 구문: `try`, `except`, `else`, `finally`, `raise`  
- 사용자 정의 예외 클래스 가능

---

## 15. 객체 지향 프로그래밍 (OOP)

- `class`로 클래스 정의  
- 객체(인스턴스): 클래스의 구체적 실체  
- 속성(변수)과 메서드(함수) 사용  
- 상속, 다형성, 캡슐화, 오버로딩/오버라이딩 지원

</details>
