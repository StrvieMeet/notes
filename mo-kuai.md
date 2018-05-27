###### 路飞题库V1.0\_出题例子

* ### 基础题

  ```
  难度等级：1星级
  说明：考察常识，普及类的死题目，凭记忆就可直接选出答案
  ```

---

##### \#python模块

###### 多选题

1、我们在开发过程中经常能够使用到模块这个知识，python中使用模块的好处是（）

A、使用模块的好处是避免变量和函数的冲突

B、使用模块的好处是可重用

C、使用模块的好处是提高运行速度

D、使用模块的好处是便于维护

```
正确答案：A,B,D
```

```
C：计算机中运行的速度只和硬件有关
```

2、我们知道能够在开发中提高开发效率的方式就是使用模块，以下哪种说法是正确的\(\)

A、一个.py文件就是一个模块

B、在一个模块中可以包含多个功能

C、模块与模块之间可以进行交互使用

D、模块与模块之间可以进行调用

```
正确答案：A,B,D
```

```
C：模块与模块之间是不可以能进行相互调用的
```

3、在python这门解释性的语言中模块也是有多个，模块的种类分为\(\)

A、内置模块

B、自定义模块

C、第三方模块

D、全局模块

```
正确答案：A,B,C
```

```
D：python编程语言是没有全局模块
```

4、我们有时候想要安装一个第三方的模块，但是不知道时候安装了，需要查看一下python中都安装了哪些第三方模块，以下正确的是\(\)

A、 help\('modules'\)

B、ls pip

C、pip list

D、 help\("modules"\)

```
正确答案：A,C,D
```

```
B：python编程语言中没有这样的语法可以查看已经安装的模块
```

5、我们将我们写好的功能封装在一个模块中，在不是同一个目录的条件下，别的文件下想要导入使用，正确的是\(\)

A、 添加到os.path中然后import

B、import

C、from…import

D、 form…import

```
正确答案：A,C
```

```
B：这样导入只会查找当前文件下的模块，没有找到就会报错
D：这个语法有问题不是form是from
```

6、我们在使用模块的时候，有以下哪几种模块导入的方式\(\)

A、 跨模块导入

B、绝对路径导入

C、相对路径导入

D、一个包下模块全部导入

```
正确答案：A,B,C,D
```

```
D：在导入模块的时候不建议将一个包下的所有模块导入例如：from...import *
```

7、模块的知识我们在开发中天天在用，并且我们也知道在导入模块的时候有多个方法，以下说法不正确的是\(\)

A、绝对路径导入将本来在C盘的剪切到D盘，这种导入不受影响。

B、跨模块导入将本来在C盘的剪切到D盘，这种导入不受影响。

C、在sys.path中添加要导入的模块时，找到要被导入的模块的父目录进行添加，然后使用from...import导入

D、在sys.path中添加要导入的模块时，找到要被导入的模块的父目录进行添加，然后使用import导入

```
正确答案：A,B,C
```

```
D：在sys.path中添加要导入的模块时，找到要被导入的模块的父目录进行添加，然后使用import导入，
找到要被导入的模块的父目录的父目录进行添加，然后使用from...import导入
```

8、time.localtime中共有9个参数，这9个参数中共有哪些\(\)

A、tm\_year,tm\_mday,tm\_min

B、tm\_mon,tm\_hour,tm\_sec

C、tm\_wday,tm\_isdst,tm\_yday

D、tm\_year,tm\_day,tm\_mon

```
正确答案：A,B,C
```

```
D：time.localtime中没有tm_day这样的参数
```

9 读以下代码，random.choice\('python'\)中选择你认为打印出来正确的结果\(\)

```
import random
print(random.choice('python'))
```

A、p

B、y

C、py

D、o

```
正确答案：A,B,D
```

```
C：因为random.choice是选择其中元素中任意一个返回
```

10 random.choice从序列中获取一个随机元素。其函数原型为：random.choice\(sequence\)参数sequence表示一个类型\(\)

A、可迭代

B、无序

C、有序

D、可变的

```
正确答案：A,C,D
```

```
B：random.choice(sequence)这个里的参数不能是无序的
```

11 我们都知道python中支持很多第三方的模块,以下对random描述正确的是\(\)

A、用于计算

B、可写验证码

C、随机数

D、可写发红包

```
正确答案：B,C,D
```

```
A：random模块不用用于计算的
```

12 在使用os模块下的getcwd方法,以下说法正确的是\(\)

A、需要加括号调用,例如os.getcwd\(\)

B、在调用的时候必须要传入参数

C、在调用的时候不用传入参数

D、在调用的时候传不传参数都行

```
正确答案：A,C
```

```
A,C:os.getcwd()在调用的时候需要加括号,但是括号中不能加参数
```

13 os.basename是获取我们写的路径中的基名,以下显示正确的是\(\)

A、C:\Users\93202\Desktop\自动化

B、Desktop\自动化

C、自动化

D、C:\Users\93202\Desktop

```
正确答案：A,C
```

```
A,C:os.getcwd()在调用的时候需要加括号,但是括号中不能加参数
```

14 sys.path可以点出以下哪些方法\(\)

A、count\(\)

B、index\(\)

C、inster\(\)

D、append\(\)

```
正确答案：A,B,C,D
```

```
所有的功能都使用,首先这些功能是列表的,sys.path获取到的就是一个列表,所以都可以使用
```

###### 

###### 

###### 

###### 

###### 

###### 

###### 

###### 

###### 单选题

1、我们知道在开发中想要提高开发效率需要使用模块，那在python中怎样调用模块（）

A、import/import… from

B、input/from…import

C、import/from … import …

D、input/input… from

```
正确答案：C
```

```
C:在python语言中模块的导入方式只用inport和from...import...这俩种。
```

2、在开发中我们需要把我们写好的功能封装在一个模块中，python中以下哪个方法是创建模块的正确流程\(\)

A、创建一文件，文件名‘my\_test’，写内容

B、创建一py文件，文件名‘模块’，写内容

C、创建一py文件，文件名‘my\_test’，写内容

D、创建一txt文件，文件名‘my\_test’，写内容

```
正确答案：C
```

```
C:在python中要创建一个模块文件后缀以.py，并且模块名要是英文的。（中文命名是不规范的）
```

3、我们通常都会有调用别的模块的需要，python在调用模块的时候，相当于做了什么以下那个操作\(\)

A、copy了文件内容

B、创建一py文件

C、执行了另一个py文件里的代码

D、把当前文件的代码加载到模块文件中

```
正确答案：C
```

```
C:我们在调用模块的时候，就是将模块中写的内容加载到当前文件中然后进行执行
```

4、在python中我们使用sys模块下的path方法获取到的是什么数据类型\(\)

A、字典

B、列表

C、集合

D、元祖

```
正确答案：B
```

```
B:我们在使用sys.path方法获取到模块搜索路径的字符串列表
```

5、修改python中使用sys.path的方法获取到的列表，这种修改的sys.path作用比正确的是\(\)

A、将当前文件添加到环境变量中

B、以便在不同目录下调用此模块

C、添加完后是永久有效

D、添加完后只有在当前进程中有效，结束此进程就失去sys.path的功能

```
正确答案：C
```

```
C：sys.path修改这个列表只是对当前有效
```

6、我们使用的time\(时间\)模块，以下说法正确的是\(\)

A、类型是字符串，共13位

B、类型是浮点型，共13位

C、类型是字符串，共18位

D、类型是浮点型，共18位

```
正确答案：D
```

```
D：时间戳是由17个数和一个小数点组成的浮点类型 例如：1526956655.2659512
```

7、我们经常使用的time\(时间\)模块，以下那是正确的时间戳\(）

A、152695665.52659512

B、15269566552.659512

C、1526956655.2659512

D、15269566.552659512

```
正确答案：C
```

```
C：时间戳是由17个数和一个小数点组成的浮点类型 例如：1526956655.2659512
```

8、我们想要使用结构化时间就要使用到time.localtime,结构化时间在显示的时候有几对数据\(\)

A、12

B、10

C、9

D、6

```
正确答案：C
```

```
C：我们想要使用结构化时间就要使用到time.localtime,结构化时间在显示的时候共有9对数据
```

9、我们在计算机中使用time.localtime\(\)获取到的是一个元祖，那这个元祖中对应的时间是以下那个\(\)

A、全球时间

B、网络时间

C、操作系统时间

D、中欧时间

```
正确答案：C
```

```
C：我们所看到的时间是操作系统的时间。
```

10、读以下代码，选择你认为正确的结果\(\)

```
import time
print(time.strftime('%m-%Y-%d %H:%M:%S'))
```

A、18-05-22 16:54:01

B、2018-05-22 17:01:12

C、05-2018-22 17:01:46

D、22-2018-05 17:01:46

```
正确答案：B
```

```
B：%Y对应的是年,%m对应的是月,%d对应的是日,%H对应的是时,%M对应的是分,%S对应的是秒
```

11、读以下代码，选择你认为正确的结果\(\)

```
import time
t = time.strftime('%m-%Y-%d %H:%M:%S')
print(time.strptime(t,'%m-%Y-%d %H:%M:%S'))
```

A、time.struct\_time\(tm\_year=5, tm\_mon=2018, tm\_mday=22, tm\_hour=17, tm\_min=15, tm\_sec=10, tm\_wday=1, tm\_yday=142, tm\_isdst=-1\)

B、time.struct\_time\(tm\_year=2018, tm\_mon=5, tm\_mday=22, tm\_hour=17, tm\_min=15, tm\_sec=10, tm\_wday=1, tm\_yday=142, tm\_isdst=-1\)

C、time.struct\_time\(tm\_year=18, tm\_mon=5, tm\_mday=22, tm\_hour=17, tm\_min=15, tm\_sec=10, tm\_wday=1, tm\_yday=142, tm\_isdst=-1\)

D、time.struct\_time\(tm\_year=22, tm\_mon=5, tm\_mday=2018, tm\_hour=17, tm\_min=15, tm\_sec=10, tm\_wday=1, tm\_yday=142, tm\_isdst=-1\)

```
正确答案：B
```

```
B：%Y对应的是年,%m对应的是月,%d对应的是日,%H对应的是时,%M对应的是分,%S对应的是秒
```

12、读以下代码，选择你认为正确的结果\(\)

```
import datetime
datetime_dt = datetime.datetime.today()
datetime_str = datetime_dt.strftime("%m-%d/%Y %H:%M:%S")
print(datetime_str)
```

A、05-2018/22 20:18:17

B、2018-05-22 20:18:17

C、05-22/2018 20:18:17

D、22-2018-05 20:18:17

```
正确答案：C
```

```
C：%Y对应的是年,%m对应的是月,%d对应的是日,%H对应的是时,%M对应的是分,%S对应的是秒
```

13 我们在使用random\(随机数\)模块中randrange\(2,100,2\)中的参数分别代表什么,以下正确是\(\)

A、步长,起始位置,终止位置

B、步长,终止位置,起始位置

C、起始位置,终止位置,步长

D、起始位置,步长,,终止位置

```
正确答案：C
```

```
C：起始位置,终止位置,步长
```

14 random.randint\(a, b\)，用于生成一个指定范围内的整数。其中参数a和参数b是以下哪种\(\)

A、上限,下限

B、下限,上限

C、起始位置,步长

D、步长,,终止位置

```
正确答案：B
```

```
B：下限,上限
```

15 我们知道\(random\)随机数模块中有sample功能,以下描述正确的是\(\)

A、random.sample\(sequence, k\)，从指定序列中随机获取指定长度的片断。sample函数会将原有序列打乱。

B、random.sample\(sequence, k\)，从指定序列中随机获取指定长度的片断。sample函数不会修改原有序列。

C、random.sample\(sequence, k\)，从指定序列中随机获取指定长度的片断。sample函数会修改原有序列。

D、random.sample\(sequence, k\)，从指定序列中随机获取指定长度的片断。sample函数会将原有序列改成降序。

```
正确答案：B
```

```
B：random.sample(sequence, k)，从指定序列中随机获取指定长度的片断。sample函数不会修改原有序列。
```

16 读以下代码，random.sample\(list, 6\)中选择你认为解释正确的结果\(\)

```
import random
list = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10,11,12]
slice = random.sample(list, 6)
print(slice)
```

A、random.sample\(list, 6\),list对应的是一个数据类型,6代表从数据的起点跨6个数

B、random.sample\(list, 6\),list对应的是一个数据类型,6代表从数据的终点跨6个数

C、random.sample\(list, 6\),list对应的只能是列表,6代表从数据的中提取6个数

D、random.sample\(list, 6\),list对应的是一个数据类型,6代表从数据的中提取6个数

```
正确答案：D
```

```
D：random.sample(list, 6),list对应的是一个数据类型,6代表从数据的中提取6个数
```

17 random.random\(\)用于生成以下哪种\(\)

A、生成一个0到1的随机符点数

B、生成一个0到10的随机整数

C、生成一个0到10的随机符点数

D、生成一个0到1的随机字符串

```
正确答案：A
```

```
A、random.random()用于生成一个0到1的随机符点数: 0 <= n < 1.0
```

18 读以下代码\(random模块\)，选择你认为正确的结果\(\)

```
import random
print(random.randrange(0,100,2))
```

A、随机选取0到100间的偶数：

B、随机选取0到100间的奇数：

C、随机选取多个0到100间的偶数：

D、随机选取多个0到100间的奇数：

```
正确答案：A
```

```
A、随机选取0到100间的偶数：
```

19 读以下代码\(os模块\)，选择你认为正确的结果\(\)

```
import os
print(os.getcwd())
```

A、C:\Users\93202\Desktop\自动化\自动化\test.py

B、自动化\自动化\test.py

C、C:\Users\93202\Desktop\自动化\自动化

D、自动化\自动化

```
正确答案：C
```

```
C:os.getcwd()获取到的是当前文件的目录绝对路径
```

20 有如下这种格式,在windows系统上使用os .listdir功能查看正确的代码及运行结果是\(\)

```
Users
└── coding
    └── python
        ├── hello.py    - 文件
        ├── word.py     - 文件
        └── web         - 目录
```

A、print\(os.listdir\('python'\)\) 运行结果:\[hello.py,word.py,web\]

B、print\(os.listdir\('Users/coding/python'\)\) 运行结果:\[hello.py,word.py\]

C、print\(os.listdir\('Users\coding\python'\)\) 运行结果:\[hello.py,word.py\]

D、print\(os.listdir\('python'\)\) 运行结果:\[hello.py,word.py\]

```
正确答案：A
```

```
A:查看指定目录下的所有文件 os.listdir(“dirname”)
```

21 我们使用os.path.exists功能是为了判断在本路径下有没有某个文件,下列返回结果正确的是\(\)

A、存在''文件名字'',不存在''''

B、存在\[文件名字\],不存在\[\]

C、存在\(文件名字\),不存在\(\)

D、存在Ture,不存在False

```
正确答案：D
```

```
D:我们使用os.path.exists功能是为了判断在本路径下有没有某个文件,有文件的话就返回Ture,不存在的话就返回False
```

22 读一下代码\(os模块\),以下代码是在windows系统上运行从以下选项中选择正确的\(\)

```
Users
└── coding
    └── python
        ├── hello.py    - 文件
        ├── word.py     - 文件
        └── web         - 目录

import os
if os.path.exists('hell.py'):
    print('文件存在',os.getcwd()+'test2.py')
else:
    print('文件不存在')
```

A、文件存在 Users\coding\python\hello.py

B、文件不存在

C、文件存在 Users/coding/python/hello.py

D、报错

```
正确答案：B
```

```
B:因为以上代码中hello.py中少一个o,所以查找的时候就是False
```

23 我们在学习os模块的时候知道os下有os.path.dirname\(\)方法,对这个方法的描述正确的是\(\)

A、获取的是dirname中文件的全部路径,包含文件

B、获取的是dirname中文件的前部分路径,不包含文件

C、获取的是dirname中文件的后部分路径,不包含路劲

D、无法获取到路劲

```
正确答案：B
```

```
B:获取的是dirname中文件的前部分路径,不包含文件
```

24 os.basename是获取我们写的路径中的基名,以下显示正确的是\(\)

A、C:\Users\93202\Desktop\自动化

B、Desktop\自动化

C、自动化

D、C:\Users\93202\Desktop

```
C
```

```
C:os.basename是获取我们写的路径中的基名,正确的是自动化
```

25 os.mkdir\(\) 方法用于以数字权限模式创建目录,读以下代码选择参数解释正确的

```
os.mkdir(path,mode)
```

A、path是要打开文件的路径,mode是读取方式

B、path是要打开文件的路径,mode是对文件的权限

C、path是要创建文件的路径,mode是读取方式

D、path是要创建文件的路径,,mode是对文件的权限

```
D
```

```
D:os.mkdir(path,mode)path是要创建文件的路径,,mode是对文件的权限
```

26 os.makedirs\(\) 方法用于以数字权限模式创建目录,读以下代码选择参数解释正确的

```
os.makedirs(path,mode)
```

A、path是要打开文件的路径,mode是读取方式

B、path是要创建文件的路径,,mode是对文件的权限

C、path是要创建文件的路径,mode是读取方式

D、path是要打开文件的路径,mode是对文件的权限

```
B
```

```
B:os.makedirs(path,mode)path是要创建文件的路径,,mode是对文件的权限
```

27 我们使用os.stat功能能够获取当前文件的详细信息,在多个关键字中st\_atime代表的意思是\(\)

A、文件创建时间

B、文件上次修改时间

C、文件上次访问时间

D、文件同步时间

```
C
```

```
C:我们使用os.stat功能能够获取当前文件的详细信息,在多个关键字中st_atime代表的意思是文件上次访问时间
```

28 读一下代码\(os.stat\),以下中正确的结果是\(\)

```
import os
ret = os.stat('test.py')
print(ret)
```

A、C:\Users\93202\Desktop\自动化

B、C:\Users\93202\Desktop\自动化\test.py

C、os.stat\_result\(st\_mode=33206, st\_ino=18858823439676712, st\_dev=3430564453, st\_nlink=1, st\_uid=0, st\_gid=0, st\_size=4669, st\_atime=1526374697, st\_mtime=1526374697, st\_ctime=1522815833\)

D、os.stat\_result\(st\_mode=33206, st\_ino=18858823439676712, st\_dev=3430564453, st\_nlink=1, st\_uid=0, st\_gid=0, st\_size=4669, st\_atime=1526374697, st\_mtime=1526374697, st\_createtime=1522815833\)

```
C
```

```
os.stat_result(st_mode=33206, st_ino=18858823439676712, st_dev=3430564453, st_nlink=1, st_uid=0, st_gid=0, st_size=4669, st_atime=1526374697, st_mtime=1526374697, st_ctime=1522815833)
```

29 读一下代码\(os.rename\),以下中正确的结果是\(\)

```
Users
└── coding
    └── python
        ├── hello.py    - 文件
        ├── word.py     - 文件
        └── web         - 目录

import os
if os.rename("hello.py","hello2.py"):
    print('098K')
elif os.rename("hello2.py","hello.py"):
    print('6666')
else:
    print('erro')
```

A、098k

B、erro

C、报错

D、6666

```
B
```

```
正确答案是B,因为os.rename没有返回值所以打印出来的是erro
```

30 使用os.path.dirname\(os.path.abspath\('\_\_file\_\_'\)\)的功能是\(\)

A、获取当前文件的父目录路径

B、获取当前文件的总目录路径

C、获取当前文件的路径

D、获取当前文件中的方法

```
A
```

```
获取当前文件的父目录路径
```

31 os.path.dirname\(os.path.dirname\(os.path.abspath\('\_\_file\_\_'\)\)\)\)的功能是\(\)

A、获取当前文件的父目录路径

B、获取当前文件的总目录路径

C、获取当前文件的父目录的父目录路径

D、获取当前文件中的方法

```
C
```

```
获取当前文件的父目录的父目录路径
```

32 sys.path是动态地改变[Python](http://lib.csdn.net/base/11)搜索路径,sys.path获取到的是什么数据类型\(\)

A、字典

B、集合

C、元祖

D、列表

```
D
```

```
sys.path是动态地改变Python搜索路径,sys.path获取到的是列表
```

33 看下方代码,选择你认为描述正确的\(\)

```
import sys
print(sys.argv)
```

A、获取到的是字典

B、获取到的是集合

C、获取到的是元祖

D、获取到的是列表

```
D
```

```
sys.argv获取到的是列表
```

34 shutil.copymode\( src, dst\) 以下对这个模块描述正确的是\(\)

A、copy文件

B、copy数据类型

C、复制其权限其他的东西是不会被复制的

D、复制其权限和文件

```
C
```

```
shutil.copymode( src, dst) 只是会复制其权限其他的东西是不会被复制的
```

35 copyfile\( src, dst\) 从源src复制到dst中去。当然前提是目标地址是具备可写权限。抛出的异常信息为IOException. 如果当前的dst已存在的话\(\)

A、不做任何操作

B、将原文件覆盖

C、在源文件中追加写入

D、报错

```
B
```

```
copyfile( src, dst) 从源src复制到dst中去。当然前提是目标地址是具备可写权限。抛出的异常信息为IOException. 如果当前的dst已存在的话将原文件覆盖
```

36 在shutil模块中shutil.copyfileobj\(fsrc, fdst\[, length\]\)中fsrc,fdst,length分别对应的是\(\)

A、新文件,源文件,复制多少内容

B、源文件,新文件,复制多少内容

C、新文件,源文件,一次读取多少内容

D、源文件,新文件,一次读取多少内容

C

在shutil模块中shutil.copyfileobj\(fsrc, fdst\[, length\]\)中fsrc,fdst,length分别对应的是新文件,源文件,一次读取多少内容

###### 

###### 填空题

1、我们要使用别人写好的模块\(第三方模块\)首先需要安装，python中如何源码安装模块的时候我们需要执行 python setup.py build进行编译，然后使用什么命令进行安装\_\_\_\_\_\_。

```
正确答案：python setup.py install
```

```
这个是python中源码安装第三方模块中规定好的的语句
```

2、我们要使用别人写好的模块\(第三方模块\)首先需要安装，python中不使用源码安装的另一种安装命令是\_\_\_\_\_\_。

```
正确答案：pip install
```

```
这个是python中源码安装第三方模块中比较简答方便的命令语句
```

3、我们使用的第三方模块都是由python开发者进行贡献的，我们要对第三方模块进行贡献需要访问\_\_\_\_\_\_网站，注册，登录后进行代码的贡献.

```
正确答案：www.pypi.org
```

4、在python中\_\_\_\_\_\_我们可以看作一个包含\_\_init\_\_.py 和一系列.py 文件的文件夹，这样做的目的是为了区别包和普通字符串。

```
正确答案：包
```

```
包就是了__init__.py 和一系列.py 文件的文件夹
```

5、在我们学习中有一个模块可以帮我获取到当前的时间，time.time\(\)这种获取到的字符串内容我们都称它为\_\_\_\_\_\_\_。

```
正确答案：时间戳
```

```
时间戳是由17个数和一个小数点组成的浮点类型 例如：1526956655.2659512
```

6、我们不想使用别人写好的模块\(第三方模块\)为了节省电脑的空间我们需要将安装好的模块卸载，python中卸载模块命令是\_\_\_\_\_\_。

```
正确答案：pip uninstall
```

```
我们想要卸载第三方模块就是使用pip uninstall命令。
```

6、我们在通过pip install命令安装了第三方模块但是不知道版本，python中查看模块命令是\_\_\_\_\_\_。

```
正确答案：pip show
```

```
我们想要第三方模块就是使用pip show命令。
```

7、我们在通过pip install django命令安装了第三方模块但是想要指定安装1.11版本，python中安装命令是\_\_\_\_\_\_。

```
正确答案：pip install django==1.11
```

```
我们在使用第三方模块的时候想要指定版本就需要使用pip install django==1.11这样的命令
```

8、`time.time()`获得的是时间戳，只不过这个时间对人不太友好，它是以\_\_\_\_\_\_年 1 月 1 日 0 时 0 分 0 秒为计时起点。

```
正确答案：1970
```

```
time.time()获得的是时间戳，只不过这个时间对人不太友好，它是以 1970 年 1 月 1 日 0 时 0 分 0 秒为计时起点。
```

9、我们使用的localtime结构化时间，time.localtime\(\)获取到的是\_\_\_\_\_类型。

```
正确答案：元祖
```

```
我们使用的localtime结构化时间，time.localtime()获取到的是元祖类型。
```

10、python中的时间模块最开始我们使用的时候返回的是一个时间戳，要将时间戳转换成结构化时间用time模块的\_\_\_\_方法

```
正确答案：time.localtime()
```

```
我们使用的localtime结构化时间，time.localtime()获取到的是元祖类型。
```

11、python中的时间模块最开始我们使用的时候返回的是一个时间戳，要将时间戳转换成格式化时间用time模块的\_\_\_\_方法

```
正确答案：time.time.strftime()
```

```
我们使用的time.strftime格式化时间，time.strftime()获取到的是字符串，提供给用户查看。
```

12、python中我们获取到结构化时间，想要将这个结构化时间转化成时间戳用time模块中的\_\_\_\_\_方法

```
正确答案：time.mktime()
```

```
我们使用的time.mktime()方法就可以把结构化时间转换成时间戳
```

13、python中我们获取到字符串时间，想要将这个字符串时间转化成结构化时间用time模块中的\_\_\_\_\_方法

```
正确答案：time.strptime()
```

```
我们使用的time.strptime()方法就可以把字符串时间转换成结构化时间
```

14 我们知道time模块可以对时间进行操作,现在我们使用datetime模块来获取2018-05-22 18:23:46.370885这样的数据的方法是\_\_\_\_\_

```
正确答案：datetime.datetime.today()
```

```
我们使用的datetime.datetime.today()方法就可以获取到2018-05-22 18:23:46.370885
```

15 我们知道time模块可以对时间进行操作,现在我们使用datetime模块来获取2018-05-22 这样的数据的方法是\_\_\_\_\_\_\_\_

```
正确答案：datetime.datetime.today().date()
```

```
我们使用的datetime.datetime.today().date()方法就可以获取到2018-05-22
```

16 我们在使用random\(随机数\)模块的中的randrange\(2,100\)方法获取到的数据类型是\_\_\_\_\_\_

```
正确答案：整型
```

```
我们在使用random(随机数)模块的中的randrange(2,100)方法获取到的数据类型是整型
```

17 random.randint\(a, b\)，用于生成一个指定范围内的\_\_\_\_\_。其中参数a是下限，参数b是上限，生成的随机数n: a &lt;= n &lt;= b

```
正确答案:整数
```

```
random.randint(a, b)，用于生成一个指定范围内的整数。其中参数a是下限，参数b是上限，生成的随机数n: a <= n <= b
```

18 我们在代码中想要查看某个文件夹中的内容,我们就使用os.listdir\(文件名\)

我们这样写就是将我们指定的文件夹下所有的内容获取到以列表的形式进行显示这种描述正确吗?\_\_\_\_\_\_\(正确/不正确\)

```
正确答案:正确
```

```
我们在代码中想要查看某个文件夹中的内容,我们就使用os.listdir(文件名)
我们这样写就是将我们指定的文件夹下所有的内容获取到以列表的形式进行显示这种描述正确
```

19 我们在写代码的时候会有去除文件名的需求,我们知道os模块中提供这个方法,这个方法是\_\_\_\_\_

```
正确答案:os.path.dirname
```

```
我们在写代码的时候会有去除文件名的需求,我们知道os模块中提供这个方法,这个方法是os.path.dirname
```

20 读一下代码\(os.path.abspath模块\),以下代码是在windows系统上运行,最终返回的结果是\(Ture/False\)中其中一个,这句话正确吗?\_\_\_\_\_\(回答:正确/不正确\)

```
Users
└── coding
    └── python
        ├── hello.py    - 文件
        ├── word.py     - 文件
        └── web         - 目录

import os
print(os.path.abspath(r'Users\coding\python\hello.py'))

答案:不正确
解析:返回的是字符串
```

21 os模块下有这获取我们想要的某个路径下的文件的基名,要使用到os模块下的那个方法os.\_\_\_\_\_\_

```
正确答案:basename
```

```
os模块下有这获取我们想要的某个路径下的文件的基名,要使用到os模块下的那个方法os.basename
```

22 os.mkdir\(\) 方法用于以数字权限模式创建目录。默认的模式为 \_\_\_\_\_ \(八进制\)。

```
正确答案：777
```

```
os.mkdir() 方法用于以数字权限模式创建目录。默认的模式为 777 (八进制)。
```

23 os.makedirs\(\) 方法用于递归的创建目录,mkdir\(\)只能只能创建单个文件夹这个描述正确吗?\_\_\_\_\_\(正确/不正确\)

```
正确答案：正确
```

```
os.makedirs() 方法用于递归的创建目录,mkdir()只能只能创建单个文件夹
```

24 我们在使用代码操作文件的时候想将文件修改什么os下什么功能os.\_\_\_\_\_\_\_

```
rename
```

```
我们在使用代码操作文件的时候想将文件修改什么os下什么功能os.rename
```

25 如果path是一个存在的目录，则返回True。否则返回False。这个方法是os.\_\_\_\_

```
isdir
```

```
如果path是一个存在的目录，则返回True。否则返回False。这个方法是os.isdir
```

26 如果path是一个存在的文件，则返回True。否则返回False。这个方法是os.\_\_\_\_

```
isfile
```

```
如果path是一个存在的文件，则返回True。否则返回False。这个方法是os.isfile
```

27 如果path是绝对路径，则返回True。否则返回False。这个方法是os.\_\_\_\_\(不用加括号\)

```
isabs
```

```
如果path是绝对路径，则返回True。否则返回False。这个方法是os.isabs
```

28 我们使用os模块改变当前工作目录,这个方法是os.\_\_\_\_\(不用加括号\)

```
chdir
```

```
如果path是绝对路径，则返回True。否则返回False。这个方法是os.isabs
```

29 我们使用os模块改变文件的权限,这个方法是os.\_\_\_\_\_\_\(不用加括号\)

```
chmod
```

```
我们使用os模块改变文件的权限,这个方法是os.chmod(不用加括号)
```

30 我们在使用os模块想要将文件名分离,使用os.\_\_\_\_\_\_\_\_\_\(不用加括号\)

```
path.split
```

```
我们在使用os模块想要将文件名分离,使用os.path.split
```

31 我们在使用os模块;判断是否是链接文件,使用os.\_\_\_\_\_\(不用加括号\)

```
path.islink
```

```
我们在使用os模块;判断是否是链接文件,使用os.path.islink
```

32 读以下代码\(sys模块\),运行结果是\_\_\_\_\_

```
import sys
sys.stdout.write('hello'+'\n')
```

```
hello
```

```
读以下代码(sys模块),运行结果是hello
```

33 在python中print 会调用 sys.stdout 中的\_\_\_\_\_ 方法

```
write
```

```
在python中print 会调用 sys.stdout 中的write 方法
```

34 在python中通过代码获取当前系统平台应该使用sys.\_\_\_\_\_方法

```
platform
```

```
在python中通过代码获取当前系统平台应该使用sys.platform方法
```

35 `sys.modules`是一个全局字典，该字典是python启动后就加载在内存中。每当程序员导入新的模块，`sys.modules`

将自动记录该模块。当第二次再导入该模块时，python会直接到字典中查找，从而加快了程序运行的速度。它拥有字典所拥有的一切方法,这句话正确吗\_\_\_\_\_\_\_\_\(正确/不正确\)

```
正确
```

```
sys.modules是一个全局字典，该字典是python启动后就加载在内存中。每当程序员导入新的模块，sys.modules
将自动记录该模块。当第二次再导入该模块时，python会直接到字典中查找，从而加快了程序运行的速度。它拥有字典所拥有的一切方法,这句话是正确的(正确/不正确)
```



