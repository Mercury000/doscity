# Hello World
这是一篇用于学习的文档

记录一下我的MD学习
在末尾添加两个或多个空格并按回车  
即可实现换行
或者使用HTML中的<br>标签也可以

# 强调语法  
## 粗体  
要加粗文本就需要在目标文本前后加上**双星号**或者 __下划线__使用星号也可以为单词的一部分加粗如 Mar**kD**own

## 斜体  
对于斜体，要用斜体显示文本，请在单词或短语前后添加一个*星号*或 _下划线_。要斜体突出单词的*中间*部分，请在字母前后各添加一个星号，中间不要带空格。  
## 粗体和斜体  
要同时用***粗体和斜体***突出显示文本, ____请在单词或短语的前后各添加三个星号或下划线___。要加粗并用斜体显示单词或短语的中间部分，请在要突出显示的部分前后各添加三个星号，中间不要带空格。  
## 删除线  
在~~要删除的字符~~前后加上两个波浪号就可以显示删除效果
# 引用语法   
## 块引用  
要创建块引用，请在段落前添加一个 > 符号  
> 这是一段被引用的话  
> 他所呈现的**效果**大致是这样的   
## 嵌套块引用
块引用也是可以嵌套的具体是使用更多的 > 符号
>这是一段引用
>>这是一段引用的引用
>>>这是一段引用的引用的引用  
# 列表  
## 有序列表  
要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。  
1. 这是一个列表
2. 很多罗列
4. 12313
3. 23123123   
   1. 这里是嵌套
   2. 和另一个
      1. 套中套
         1. 套中套中套
4. End
## 无序列表
要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。      
- 无序列表
- 第二项
- 另一项
- 还有一项
  - 嵌套一项
    - 看
      - 不同的符号
+ 试一下加号
* 以及星号


# 代码表示  
要将单词或短语表示为代码，请将其包裹在反引号 (`) 中。  
比如以下的一段代码 ``print(abc)``  
``int(abc)``  
``print(abc)``   
或者对于大量的代码使用围栏式代码块
```python
import random
import hashlib
key = int(random.randint(100000,999999))
key = str(key)
sha1 = hashlib.sha1()
sha1.update(key.encode('utf-8'))
sha1_data = sha1.hexdigest()
print(key)
inputkey = str(input("输入授权码"))
if inputkey == sha1_data:
    print("验证成功")
    max = int(input("抽签人数"))
    time = int(input("抽签次数"))
    while time > 0 :
        print(random.randint(1,max))
        time = time - 1
else:
    print("验证失败,禁止使用")
input("按回车键退出")
```   
---
分隔线
***
[这是一个链接](http://drive.kakuweb.top)  
[这是一个链接](http://drive.kakuweb.top "这是一个标题")  
<http://drive.kakuweb.top>  
<xiao_doubi9637@outlook.com>   
___   
# 图片引用  
[![只因](https://ts1.cn.mm.bing.net/th/id/R-C.47c8192eb5579bc4f2b4352865e95393?rik=Kqe39GZ27eeLiQ&riu=http%3a%2f%2fpic33.photophoto.cn%2f20141110%2f0035035997000951_b.jpg&ehk=3fXEUBEAQeDrASf%2f2X618%2boKGDDeAd0SKz%2fMXApDoaA%3d&risl=&pid=ImgRaw&r=0)](https://v50to.me)
# 添加复选框   
- [ ] 选项1
- [x] 选项2
- [ ] 选项3
- [x] 选项4

___

6666🔧🔧🔧🔧🔧6666  

