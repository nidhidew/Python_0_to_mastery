# Python_0_to_mastery

## first program
`print('Hello World!')`
every file which ends on .py is python file. in the above code it will print the 'Hello World!' in the command line. this code will be written in python file.
![image](https://github.com/user-attachments/assets/dfdc29a2-4f45-4e0c-b4d7-1f4b67f6b42a)

`input('what is your name?')`
this piece of code will take input from user in command line.

```
name = input("what is your name?")
print(name)
```
above code will do the same but there is small difference. input value first stored in name variable. and then in print we will print the name value. 

- type keyword `type(2+4)` is use for to findout the datatype.
- round function `round(3.1)` will round up the number.
- abs function `abs(-20)` will give absolute / positive integer.

## DataTypes
- int(integer)
- float
- bool(boolean)
- str(string)
- list
- tuple
- set
- dict(dictionary)
- complex(for numbers, for complex math operation)
- bin(it will use to get binary representation of any input and using int we can convert the binary representation to integer)

* in programming for mathematical operations(add,substract,divison,multiply,double multiply(power of like 2**2=8),double divide(2//4=0),modulo(5%4=1 return reminder) int and float datatype used.

**Specialized Data types**
modules
None (nothing)

**Operator Precedance**
- different operators is used in any operation for eg: ((20-3)+2**2) so here first solve (), next **, next * and /. next + and -. this is the steps to solve the problem of this.

```
print((5 + 4) * 10 / 2) 
#45

print(((5 + 4) * 10) / 2)
#45

print((5 + 4) * (10 / 2))
#45

print(5 + (4 * 10) / 2)
#25.0

print(5 + 4 * 10 // 2)
#25
```
- follow the order of operations (PEMDAS/BODMAS), which stands for:

P/B: Parentheses/Brackets
E/O: Exponents/Orders(refer to raising a number to a power)
MD: Multiplication and Division (left to right)
AS: Addition and Subtraction (left to right)

**Variables**

- for storing information/data variables are in use. eg: `name="nidhi"` name is a variable and "nidhi" is a string type value/data of the name variable.
- this data is used for the operations.
- can be use '_' in variable name eg: `snake_case`
- it can be start with lowercase or underscore
- keywords should not be overwrite.

**Expression VS Statements**

```
iq=100
age=iq/5
```
here `iq/5` is a expression and `age = iq/5` and `iq=100` is a statement.

**Augmented assignment operator**

```
value = 5
value += 2
```
here `value += 2` will be add `5+2`. same thing can be done for /,*,- too.

**String concatenation**

- concat strings means adding only string together for eg:
  ```
  a="nidhi"
  b="dewangan"
  print(a+" "+b) #nidhi dewangan
  ```
  for giving space between a and b variable value we empty space between inverted commas. 2 different datatype cant be concat

**Type Conversion**
- converting any datatype to another datatype. for example:
  `str(100)` or `int("100")`

**Escape Sequence**
```
weather = 'It's a sunny'
```
here a one error will come that after 'It' for solving that follow the below method.
```
weather = "It's a sunny"
```
but what is the sting is written like this
```
weather = "It's "kind of" sunny"
```
then follow format like below
```
weather = "It\'s \"kind of\" sunny"
```
this is called escape sequence. so the 1st \ shows that whatever comes after this will be string only and when we add end \ then it closes.

for long space use \t and for new line use \n.

**Formatted Strings**

```
name = "Johnny"
age = "55"
print('hi'+name+'. you are '+age+'years old')
print(f'hi {name}. you are {age} years old') #formatted string(most recommanded)
```
 in python 3 this came.
```
print('hi{}. you are {} years old'.format('Johnny','55'))
print('hi{}. you are {} years old'.format(name,age))
print('hi{new_name}. You are {age} years old'.format(new_name='sally',age=100))
```
another formatted string method

**String indexes**

![image](https://github.com/user-attachments/assets/33e65376-ae34-455a-b132-e006e40280fe)

for example string is stored like this. then try to get 1st letter print and this string is stored in 'selfish' variable
```
selfish="me me me"
selfish[0] #m
```
if we use : in [] for getting a output from the string value
```
value = "01234567"
print(value[0:2]) #01
```
it will print from index 0 to 2 value but not index 2 value. its like [ start : stop ]. for getting full string do `value[0:8]`
if follow [ start:stop:stepover ] then it will be like below:
```
print(selfish[0:8:2]) #0246
```
if we do `value[1:]` then it will give full value.
if we do `value[:5]` the it will give 01234
if we do `value[::1]` then it will give 01234567
if we do `value[-1]` then it will give 7 because it counts from the end and numbering start from -1
if we do `value[::1]` then it will give 76543210

**Immutability**
- stings in python is immutable and they cant be modified
- for eg: if value is `value='123456'` and want to modify like `selfish[0]=8` then its not possible but `value+'8'` will modify to `12345678`

**Built-in functions + methods**
- string has len() method to print string length
```
  value = "4567985125"
  print(len(value))
```
- 
