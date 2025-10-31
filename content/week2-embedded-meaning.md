## Notes
- **Variables:**
	- Strings and Integers will be important while word embedding
- **Collection Types:**
	- lists: ordered
	- tuples
	- set: unordered - tho order is not , no duplicates
	- dictionary: 
- **Syntax:**
	- indentations carry meaning
	- whitespaces around operators make your code easier to read & understand
	- colons indicate blocks
- **Conditionals:**
	- "if" statement
	- "if - else" statement
	- "if - elif - else" statement

### Cheatsheet for Data Types and Data Structures in Python

| Name       | Type    | Category | Example           | Trick         | Mutable |
| ---------- | ------- | -------- | ----------------- | ------------- | ------- |
| string     | `str`   | text     | `"William"`       | quotes        | no      |
| integer    | `int`   | number   | `1`               | no decimal    | no      |
| float      | `float` | number   | `1.1`             | with decimal  | no      |
| Boolean    | `bool`  | boolean  | `True`            | True or False | no      |
| list       | `list`  | sequence | `[1, 1.1, "one"]` | []            | yes     |
| tuple      | `tuple` | sequence | `(1, 1.1, "one")` | ()            | no      |
| set        | `set`   | sequence | `{1, 1.1, "one"}` | {} - unique   | yes     |
| dictionary | `dict`  | mapping  | `{"name": "tom"}` | {key:value}   | yes     |
### Working with Strings as Data
- ##### String Methods
	- string.upper() — LIKE THIS.
	- string.lower() — like this.
	- string.capitalize() — Like this.
	- string.replace("the thing to replace", "the thing you want to replace it with")
	- string.split("argument to split from")

### Cheatsheet for Mathematical Operations

|operation|code|description|example|result|
|---|---|---|---|---|
|addition|`+`|adds numbers together|`1+1`|2|
|subtraction|`-`|subtracts one number from another|`1-1`|0|
|multiplication|`*`|multiplies two numbers|`1*2`|2|
|exponential multiplication|`**`|performs exponential multiplication|`2**2`|4|
|division|`/`|divides one number from another|`2/2`|1|
|modulo|`%`|remainder|`2%7`|1|
|floor|`//`|occurences|`2//7`|3|
### Mutability vs Immutability
- mylist.append("one")