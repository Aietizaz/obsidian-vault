
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

##### <u>Arithmetic Operators</u>

- Operators are symbols that represent computations like addition and multiplication.

| Operation      | Operator | Example  | Output |
| -------------- | -------- | -------- | ------ |
| Addition       | +        | 40+2     | 42     |
| Subtraction    | -        | 43-1     | 42     |
| Multiplication | *        | 6*7      | 42     |
| True division  | /        | 84/2     | 42.0   |
| Floor division | //       | 84/2     | 42     |
| Exponentiation | **       | 6**2 + 6 | 42     |
##### <u>Values & Types</u>

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

##### <u>Formal & Natural Languages</u>

- Natural Languages:
	- Languages that people speak: English, French, Spanish, etc.
	- Not designed by people.
	- Evolved naturally.

- Formal Languages:
	- Languages such as: 
		- Mathematical notations to denote relationships among numbers and symbols.
		- Chemical formulas for structure of molecules.
		- Programming languages to express computations.
	- Designed by people for specific applications.
	- Strict **==syntax==** rules that govern the structure of statements. 2 important rules:
		- Tokens: basic elements of the language such as words, numbers, chemical elements...
		- Combination of tokens have to make sense and be structured correctly.
		- Reading a sentence in English or formal language, you have to figure out the structure (this is done subconsciously for natural languages) - this is called ==**Parsing**==.
		- <font color="#00b050">Example:</font>

| Correct statement | Incorrect statement |
| ----------------- | ------------------- |
| 3 + 3 = 6         | 3 + = 3$6           |
| H20               | ZZZ                 |

- Differences between Natural and Formal Languages
	1. ==Ambiguity==
		- Natural languages are ambiguous and are handles by people usually by contextual clues and other information. Formal Languages are designed to be completely unambiguous with a statement only having one meaning regardless of context.
	2. ==Redundancy==
		- Formal Languages are less redundant and more concise compared to natural which are verbose.
	3. ==Literalness==
		- Natural Languages contain metaphors, idioms and other illogical phrases. On the other hand, formal languages are purely logical and mean exactly what they state.


##### <u>Exercises</u>

1. <font color="#ffff00">Exercise 1-1</font>
- <font color="#ffff00">In a print statement, what happens if you leave out one of the parentheses or both?</font>
	- 