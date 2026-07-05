
---

##### <u>Problem Solving</u>

- The ability to formulate problems, think creatively about solutions and express a solution clearly and accurately.

##### <u>What is a Program?</u>

- A sequence of instructions that specifies how to perform a computation which could be mathematical (solving the equations), symbolic (searching and replacing text) or graphical (processing an image).

##### <u>Basic Instructions</u>

- The details appear different in various languages however the basic instructions appear in every language:

1. ==Input:== Get data from keyboard, file, network or some other source.
2. ==Output:== Display said data on the screen, save it in a file, send it over the network, etc.
3. ==Maths:=== Perform basic mathematical operations such as + and -.
4. ==Conditional Execution:== Check for certain conditions and run the appropriate code.
5. ==Repetition:== Perform some action repeatedly, usually with some variation.

- The process of breaking down large, complex tasks into smaller subtasks that can be performed with one of the above basic instructions.

###### <u>Running Python</u>

- Python Interpreter
	- A program that reads and executes Python code.
	- Typing python produces an output that contain information about the interpreter and the OS.

```python
python
```

```python
Python 3.14.3 (tags/v3.14.3:323c59a, Feb  3 2026, 16:04:56) [MSC v.1944 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
```

##### <u>The First Program</u>

- Print Statement:
	- Displays the result on the screen.
	- " " mark the beginning and end of the text to be *displayed*.**
	- ( ) indicate that ***print*** is a function.
	- <font color="#00b050">Example:</font>
```python
print("Hello, World!")
```

##### Arithmetic Operators

- Operators are symbols that represent computations like addition and multiplication.

| Operation      | Operator | Example  | Output |
| -------------- | -------- | -------- | ------ |
| Addition       | +        | 40+2     | 42     |
| Subtraction    | -        | 43-1     | 42     |
| Multiplication | *        | 6*7      | 42     |
| True division  | /        | 84/2     | 42.0   |
| Floor division | //       | 84/2     | 42     |
| Exponentiation | **       | 6**2 + 6 | 42     |
##### Values & Types

- Values are basic units that programs can work with such as a letter or number. 
- Values can be of varying types.

| Value           | Type    |
| --------------- | ------- |
| "Hello, World!" | String  |
| 42.0            | Float   |
| 2               | Integer |
- If unsure what type a value is, the interpreter can tell you.
	- <font color="#00b050">Example:</font>
```python
type(42.0)
```
	 <class 'float'>

- "class" is used as a category - a type is a category of values.

