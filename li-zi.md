###### 路飞题库V1.0\_出题例子

* ### 基础题

  ```
  难度等级：1星级
  说明：考察常识，普及类的死题目，凭记忆就可直接选出答案
  ```

---

##### \#python发展史

###### 多选题

1、python是使用非常广泛的解释型语言，以下选项是关于python发展史的描述，请选择你认为正确描述（）：

A、python的作者是:吉多·范罗苏母，人称“龟叔”

B、python和C语言一样是一种解释性语言。

C、python在流行的框架是DJSsa框架，诞生于2000年

D、python的第一个编译器诞生于1992年

```
正确答案：A、D

解析：
    C：python第一个流行web框架是：Django，诞生于2004年
    B: python是一种解释性语言
```

2、python自诞生之日起，凭借其简单易学的语法风格，受到广大码农的追捧，并于2004年诞生了最流行的web应用\_\_\_\_\_框架.

###### 填空题

正确答案：Django

```
Django框架是python应用最广泛的公司
```

##### \#字符串定义

多选题

3、python的字符串是最常用的数据类型，那么字符串在python该如何定义呢？请选择定义正确的字符串选项（）：

A、meg="alex是一个很帅的出色的完美的人"

B、address=‘打的啥大多“

C、message="""达到独守空房杀人犯输入法女士打电话的"""

D、desc='python的第一"个"编译器诞生于1992年'

```
正确答案：A、C

    解析：python定义字符串，统一加上引号，引号常用三种：单引号、双引号、多引号
```

##### \#列表切片

多选题

4、列表是python常用的数据类型，定义好一个列表a=\[1,2,3,4,5,6,7\]。现在想对列表进行切片操作，以下哪些操作是合法的?

A: a\[::5\]

B: a\[2-3\]

C: a\[2:5\]

D: a\[10:20:2\]

```
正确答案：A、C
```

```
此题考查的是对 Python 中 切片（Slice）功能的理解：

    L[start : stop [ : step]]
        start 默认值是 0; 
        stop 默认值为 L 的长度;
        step 默认值是 1

A: a[::5] 其实是设定步长 => range(0, 100, 5)

B: a[2-3] => a[-1]

    取a当中倒数第i个数 => a[-1]=99;  a[-2]=98;  a[-3]=97

C：a[2:5]

    取排列a第2到13个数，其结果是2到5的一个排列

D：a[10:20:2]

    实际上是a[start:end:step]

    根据 a=range(100) 可得start的默认值是1, end的默认值是100

        step 的值因被 指定 所有 取 10 到 20的序列且步长为 2
```

##### \#变量引用

5、下面函数的执行结果是\(\)?

###### 填空题

```
NAMELIST=456
def func():
    NAMELIST=123
func()
print(NAMELIST)
```

```
确答案：456
    解析：变量引用是由于
```

### \#简单题

```
难度等级：2星级
说明：
```

---

##### \#相对导入、\#绝对导入

7、下图文件导入模块，执行文件是bin.py,计算cal文件中的计算式，lhf.文件中的导入语句是?

###### 多选题

![](/assets/QQ20180517-195425.png)

![](/assets/QQ20180517-194526.png)![](/assets/QQ20180517-194612.png)

###### 

A、import cal

B、from module import cal.py

C、from .. import cal.py

D、from bin import cal

```
确答案：B，C
    解析：导入是相对路径
```

##### 

##### \#global引用、\#变量引用

7、下面函数的执行结果是\(\)?

###### 填空题

```
NAMELIST=1
def func():
    NAMELIST=123
    global NAMELIST
func()
print(NAMELIST)
```

```
确答案：123
    解析：
```

##### 

### \#标准题

```
说明：
难度等级：3星级
```

---

##### \#全局变量、\#局部变量、\#位置参数

7、下面函数的执行结果是\(\)?

###### 单选题

```
total = 0; # 这是一个全局变量
# 可写函数说明
def sum( arg1, arg2 ):
   #返回2个参数的和."
   total = arg1 + arg2; # total在这里是局部变量.
   print （"函数内是局部变量 : ", total）
   return total;

#调用sum函数
sum( 10, 20 );
print（"函数内是局部变量 : ", total）
```

A、0、0

B、0、30

C、30、0

D、30、30

```
正确答案：
    解析：
```

##### \#global引用、\#LEGB查找顺序、\#嵌套函数

8、查看下面的代码内容，在下面选项选出执行结果（）

###### 单选题

```
name="root"
def func():
    name="seven"
    def outer():
        name="eric"
        def inner():
            global  name
            name="腻害了"
        print(name)
    print(name)
ret=func()
print(ret)
print(name)
```

A、eric、腻害了

B、eric、seven

C、root、腻害了

D、eric、腻害了

```
正确答案：
    解析：
```

### **\# 困难题**

```
说明：
难度等级：4星级
```

---

##### \#return返回、\# global应用、\#变量引用、\#嵌套函数

9、查看下面的代码内容，在下面选项选出执行结果（）

###### 单选题

```
a = 10
def warp():
    global a
    a += 40
    x = a
    def inner():
        nonlocal x
        x += 10
        return x
    return inner()
print(warp())
print(a)
```

A、10

B、50

C、60

D、40

```
正确答案：A
```

```
     解析：*****
```

##### 

##### \# global引用、\#变量引用、\#嵌套函数、\#高阶函数

###### 单选题

10、查看下面的代码内容，在下面查看最终打印过是（）

```
name="苍老师"
def outer(func):
    def inner():
        gloal name
        name="李杰"
        func()
    return inner
def show():
    print(name)

outer(show)()
```

A、李杰

B、苍老师

C、报错

D、None

```
正确答案：A
```

```
     解析：*****
```

##### 

### \#非常困难题

```
难度等级：5星级
说明：
```



