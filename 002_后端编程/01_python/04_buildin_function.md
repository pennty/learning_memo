: 函数名 :|:类别:|:相关魔法方法:|:函数签名|:说明
memoryview()|字符串相关||class memoryview(obj)|返回由给定实参创建的“内存视图”对象。
ascii()|字符串相关||ascii(object)|就像函数  repr()，返回一个对象可打印的字符串，但是  repr()  返回的字符串中非 ASCII 编码的字符，会使用  \x、\u  和  \U  来转义。
input()|字符串相关||input([prompt])|如果存在 prompt 实参，则将其写入标准输出，末尾不带换行符。
str()|字符串相关||"class str(object='')
class str(object=b'', encoding='utf-8', errors='strict')"|返回一个 str 版本的 object
ord()|字符串相关||ord(c)|对表示单个 Unicode 字符的字符串，返回代表它 Unicode 码点的整数。
bytearray()|字符串相关||class bytearray([source[, encoding[, errors]]])|返回一个新的 bytes 数组。
bytes()|字符串相关||class bytes([source[, encoding[, errors]]])|返回一个新的“bytes”对象， 是一个不可变序列，包含范围为  0 <= x < 256  的整数。
format()|字符串相关||format(value[, format_spec])|将 value 转换为 format*spec 控制的“格式化”表示。
chr()|字符串相关||chr(i)|返回 Unicode 码位为整数 i 的字符的字符串格式。
open()|文件相关||open(file, mode='r', buffering=-1, encoding=None, errors=None, newline=None, closefd=True, opener=None)|打开 file 并返回对应的 file object。如果该文件不能打开，则触发 OSError。
print()|文件相关||print(\_objects, sep=' ', end='\n', file=sys.stdout, flush=False)|将 objects 打印到 file 指定的文本流，以 sep 分隔并在末尾加上 end。
set()|容器相关||class set([iterable])|返回一个新的 set 对象，可以选择带有从 iterable 获取的元素。
all()|容器相关||all(iterable)|如果  iterable  的所有元素为真（或迭代器为空），返回  True 。
dict()|容器相关||"class dict(**kwarg)
class dict(mapping, **kwarg)
class dict(iterable, \*\*kwarg)"|创建一个新的字典。
min()|容器相关||"min(iterable, *[, key, default])
min(arg1, arg2, *args[, key])"|返回可迭代对象中最小的元素，或者返回两个及以上实参中最小的。
any()|容器相关||any(iterable)|如果  iterable  的任一元素为真则返回  True。 如果迭代器为空，返回  False。
next()|容器相关|**next**()|next(iterator[, default])|通过调用 iterator 的 **next**() 方法获取下一个元素。
slice()|容器相关||"class slice(stop)
class slice(start, stop[, step])"|返回一个表示由 range(start, stop, step) 所指定索引集的 slice 对象。
sorted()|容器相关||sorted(iterable, key=None, reverse=False)|根据 iterable 中的项返回一个新的已排序列表。
enumerate()|容器相关|**next**() |enumerate(iterable, start=0)|返回一个枚举对象。iterable 必须是一个序列，或 iterator，或其他支持迭代的对象。
filter()|容器相关||filter(function, iterable)|用 iterable 中函数 function 返回真的那些元素，构建一个新的迭代器。
iter()|容器相关||iter(object[, sentinel])|返回一个 iterator 对象。
tuple()|容器相关||class tuple([iterable])|虽然被称为函数，但 tuple 实际上是一个不可变的序列类型
len()|容器相关||len(s)|返回对象的长度（元素个数）。
property()|容器相关||class property(fget=None, fset=None, fdel=None, doc=None)|返回 property 属性
frozenset()|容器相关||class frozenset([iterable])|返回一个新的 frozenset 对象，它包含可选参数 iterable 中的元素。
list()|容器相关||class list([iterable])|虽然被称为函数，list 实际上是一种可变序列类型
range()|容器相关||"class range(stop)
class range(start, stop[, step])"|虽然被称为函数，但 range 实际上是一个不可变的序列类型
zip()|容器相关||zip(*iterables)|创建一个聚合了来自每个可迭代对象中的元素的迭代器。
map()|容器相关||map(function, iterable, ...)|返回一个将 function 应用于 iterable 中每一项并输出其结果的迭代器
reversed()|容器相关|**reversed**() |reversed(seq)|返回一个反向的 iterator
max()|容器相关||"max(iterable, *[, key, default])
max(arg1, arg2, *args[, key])"|返回可迭代对象中最大的元素，或者返回两个及以上实参中最大的。
abs()|数值相关|**abs**()|abs(x)|返回一个数的绝对值
hash()|数值相关|**hash**()|hash(object)|返回该对象的哈希值
hex()|数值相关|**index**() |hex(x)|将整数转换为以“0x”为前缀的小写十六进制字符串。
divmod()|数值相关||divmod(a, b)|它将两个（非复数）数字作为实参，并在执行整数除法时返回一对商和余数。
bin()|数值相关|**index**()|bin(x)|将一个整数转变为一个前缀为“0b”的二进制字符串。
oct()|数值相关|**index**()|oct(x)|将一个整数转变为一个前缀为“0o”的八进制字符串。
bool()|数值相关||class bool([x])|返回一个布尔值，True 或者 False。
int()|数值相关|**int**()|class int([x])|返回一个基于数字或字符串 x 构造的整数对象，或者在未给出参数时返回 0。
pow()|数值相关||pow(base, exp[, mod])|返回 base 的 exp 次幂
float()|数值相关||class float([x])|返回从数字或字符串 x 生成的浮点数。
complex()|数值相关|**complex**()|class complex([real[, imag]])|返回值为  real + imag*1j 的复数，或将字符串或数字转换为复数。
round()|数值相关||round(number[, ndigits])|返回 number 舍入到小数点后 ndigits 位精度的值。
delattr()|语言相关||delattr(object, name)|实参是一个对象和一个字符串。该字符串必须是对象的某个属性。如果对象允许，该函数将删除指定的属性。
help()|语言相关||help([object])|启动内置的帮助系统
setattr()|语言相关||setattr(object, name, value)|其参数为一个对象、一个字符串和一个任意值。 字符串指定一个现有属性或者新增属性。
dir()|语言相关|**dir**()|dir([object])|如果没有实参，则返回当前本地作用域中的名称列表。如果有实参，它会尝试返回该对象的有效属性列表。
id()|语言相关||id(object)|返回对象的“标识值”。
object()|语言相关||class object|返回一个没有特征的新对象。
staticmethod()|语言相关||@staticmethod|将方法转换为静态方法
eval()|语言相关||eval(expression[, globals[, locals]])|实参是一个字符串，以及可选的 globals 和 locals。
breakpoint()|语言相关||breakpoint(*args, \*\*kws)|此函数会在调用时将你陷入调试器中。
exec()|语言相关||exec(object[, globals[, locals]])|这个函数支持动态执行 Python 代码。
isinstance()|语言相关||isinstance(object, classinfo)|如果参数 object 是参数 classinfo 的实例或者是其 (直接、间接或 虚拟) 子类则返回 True。
issubclass()|语言相关||issubclass(class, classinfo)|如果  class  是  classinfo  的 (直接、间接或   虚拟) 子类则返回  True。
super()|语言相关||super([type[, object-or-type]])|返回一个代理对象，它会将方法调用委托给 type 的父类或兄弟类。 这对于访问已在类中被重载的继承方法很有用。
callable()|语言相关|**call**() |callable(object)|如果参数  object  是可调用的就返回  True，否则返回  False。
type()|语言相关|**class**|"class type(object)
class type(name, bases, dict)"|传入一个参数时，返回 object 的类型
vars()|语言相关|**dict**|vars([object])|返回模块、类、实例或任何其它具有 **dict** 属性的对象的 **dict** 属性。
classmethod()|语言相关||@classmethod|把一个方法封装成类方法。
getattr()|语言相关||getattr(object, name[, default])|返回对象命名属性的值。
locals()|语言相关||locals()|更新并返回表示当前本地符号表的字典
repr()|语言相关|**repr**()|repr(object)|返回包含一个对象的可打印表示形式的字符串。
compile()|语言相关||compile(source, filename, mode, flags=0, dont_inherit=False, optimize=-1)|将 source 编译成代码或 AST 对象。代码对象可以被 exec() 或 eval() 执行。
globals()|语言相关||globals()|返回表示当前全局符号表的字典。
**import**()|语言相关||**import**(name, globals=None, locals=None, fromlist=(), level=0)|此函数会由 import 语句发起调用。
hasattr()|语言相关||hasattr(object, name)|如果字符串是对象的属性之一的名称，则返回 True，否则返回 False。
