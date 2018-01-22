# PythonWork

Python学习作业，大家做了作业，可以提交到对应日期目录。

请合理选择作业文档格式，比如txt，py，md。

## 2018.01.22

有以下两个文件：one.py和two.py

### one.py
```
def func():
    print("func() in one.py")

print("top-level in one.py")

if __name__ == "__main__":
    print("one.py is being run directly")
else:
    print("one.py is being imported into another module")
```

### two.py
```
import one

print("top-level in two.py")
one.func()

if __name__ == "__main__":
    print("two.py is being run directly")
else:
    print("two.py is being imported into another module")

```

1、直接执行one.py，输出内容是什么？

2、直接执行two.py，输出内容是什么？
