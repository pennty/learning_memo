
### random模块

+ randint(a, b) 产生一个a和b之间且包括a和b的随机整数
+ randrange(a, b) 产生一个a和b-1之间且包括a和b的随机整数
+ random() 生成一个满足条件0<=r<=1.0的随机浮点数r

### if语句

- 单向if
- 双向if-else
- 嵌套if
- 多向if-elif-else

```python
if boolean-expression:
	statement(s)

if boolean-expression:
	statement(s)-for-the-true-case
else:
	statement(s)-for-the-false-case
```

### 循环

- while循环
- for循环
- break和continue

```python
while loop-continuation-condition:
	statement(s)

for i in sequence:
	statement(s)
```

### 函数

- 定义函数

```python
def functionName(list of parameters)
	# Function body
```

- return/return None
	无返回值时可以没有return或return后面没有值,再或者用return None

- 参数
	实参是作为位置参数和关键字参数被传递
	* 使用位置参数要求参数按它们在函数头的顺序进行传递
		+ 实参必须和函数头中定义的形参在顺序,个数和类型上匹配
	* 使用关键字参数时,参数可以以任何顺序出现
	* 位置参数和关键字参数可以被混在一起,但位置参数不能出现在任何关键字参数之后
	* Python中的所有数据都是对象,对象的变量通常都是指向对象的引用.  
	  当调用一个带参数的函数时,每个实参的引用值就被传递给形参(值传递).  
	  调用函数时,实参的值被传递给形参.这个值通常就是对象的引用值.  
	  如果实参是一个数字或都是一个字符串(不可变对象),  
	  那么不管函数中的形参有没有变化,这个实参是不受影响的.

- 模块化

可以将函数的定义放在一个被称为模块的文件中,这种文件的后缀名是.py.
之后这些模块可以被导入到程序中以便重复使用.这些模块文件应该和其他
程序一起放在同一地方.

```
# Function.py
def foo(n1, n2):
	# function body

# Main.py
from Function import foo		# Import the foo function

# 也可以用下面的语句来导入
import Function
# 但如果使用这个语句,就必须使用Function.foo才能调用函数foo
```

- 作用域
	+ 在函数内部定义的变量被称为*局部变量*
	+ 在所有的函数之外创建,可以被所有的函数访问的变量为*全局变量*
	+ 可以通过*global*语句,把一个局部变量的作用域绑定为全局的

- 默认参数
	+ Python不支持定义两个同名函数,后面的函数会取代先前的.可以通过  
	  默认参数来实现定义同名的多个函数的效果

- 返回多个值
	+ Python允许函数返回多个值. `return x,y,z`
	