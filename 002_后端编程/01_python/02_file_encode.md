```python
zh = "你好世界"
jp = "こんにちは、世界"


def show(x):
    print('len = {}, type = {}'
          .format(len(x), type(x)))


show(zh)  # len = 4, type = <class 'str'>
show(jp)  # len = 8, type = <class 'str'>
show(zh.encode('utf8'))  # len = 12, type = <class 'bytes'>
show(jp.encode('utf8'))  # len = 24, type = <class 'bytes'>
show(zh.encode('gbk'))  # len = 8, type = <class 'bytes'>
show(jp.encode('sjis'))  # len = 16, type = <class 'bytes'>
```
