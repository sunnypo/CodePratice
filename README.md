# Python黄岗小状元

这里是一个从简单的语法练习到一些好玩的技巧练习的题库，是为了学习Python过程而使用的。其实用于其它的语言也不错。希望大家能Pull Request一些好题目进来。所有的题目都是4位数字，用来标示出题号，在 [PracticeResult](https://github.com/sunnypo/PracticeResult) 项目中有练习的一些成果，也欢迎你将自己的好代码Pull Request进去。

### 0000 随机座位

有四个数字：1、2、3、4，能组成多少个互不相同且无重复数字的三位数？各是多少？

> 可填在百位、十位、个位的数字都是1、2、3、4。组成所有的排列后再去 掉不满足条件的排列。

判断、循环、数字处理练习

### 0001 日历回收

输入某年某月某日，判断这一天是这一年的第几天？

> 以3月5日为例，应该先把前两个月的加起来，然后再加上5天即本年的第几天，特殊情况，闰年且输入月份大于2时需考虑多加一天。

判断、循环、数字和字符串处理练习

### 0002 填支票本

在北美生活需要手写支票，将一个数字转换成为英文大写。需要支持到百万和小数点后两位。

> 1-21; 30; 40; 50; 60; 70; 80; 90; 100; 1,000; 10,000; 100,000; 1,000,000的英文写法如下：

> One, Two, Three, Four, Five, Six, Seven, Eight, Nine, Ten, Eleven, Twelve, Thirteen, Fourteen, Fifteen, Sixteen, Seventeen, Eighteen, Nineteen, Twenty, Twenty-one, Thirty, Forty, Fifty, Sixty, Seventy, Eighty, Ninety, One Hundred, One Thousand, Ten Thousand, One Hundred Thousand, One Million

> 写完整数后，要加上 Dollars

> 当有小数点时，小数点写为 and ，小数点后的会写为 xxx Cents

> 举例： 175.25美元 one hundred seventy five dollars and twenty-five cents

判断、循环、函数、数字和字符串处理练习。也许可以试试递归

### 003 猜数字

经典的猜数字游戏，随机生成一个三位以内的数字作为答案。用户输入一个数字，程序会提示大了或是小了，直到用户猜中。记得提示用户猜中了多少次，看看谁用的次数少！

判断、循环、数字处理练习

### 004 猜数字AI版

输入一个三位以内的数字，AI不断的猜测数字，显示出猜测的次数和数字以及是大了或是小了，看看你写的程序需要用多少次才能猜中，看看谁写出来的AI最聪明！

判断、循环、数字处理练习

### 005 税务计算器

加拿大的个人所得税分为联帮个人所得税和各省各自征收的个人所得税。

以下是2019年的所得税税率，

联邦个人所得税率：47,630$以下为15%；47,630-95,259$为26%；147,667-210,371$为29%；210,371$以上为33%。

Quebec省个人所得税率：43,790$以下为15%；43,790-87,575$为20%；87,575-106,555$为24%;106,555$以上为25.75%。

请先输入一个年收入的数字，分别计算出联帮所有税、魁省所得税和要交的税收总额。

判断、循环、数字处理练习，试试数组吧

参考： https://www.canada.ca/en/revenue-agency/services/tax/individuals/frequently-asked-questions-individuals/canadian-income-tax-rates-individuals-current-previous-years.html

### 006 神奇排序

依次输入三个整数，请把这三个数字由小到大输出。

判断、循环、数字处理练习，试试Array或Set吧

### 007 兔子家庭

一般而言，兔子在出生两个月后，就有繁殖能力，一对兔子每个月能生出一对小兔子来。如果所有兔子都不死，那么一年以后可以繁殖多少对兔子？

输入一个月份，假设兔子都是老不死，看看能有多少对兔子。

数字和递归练习，可以搜索一下它的发现者列昂纳多·斐波那契（Leonardo Fibonacci）

### 008 乘法口诀

输出 9*9 乘法口诀表。就像这样

```
1*1=1
2*1=2 2*2=4
3*1=3 3*2=6 3*3=9
4*1=4 4*2=8 4*3=12 4*4=16
5*1=5 5*2=10 5*3=15 5*4=20 5*5=25
6*1=6 6*2=12 6*3=18 6*4=24 6*5=30 6*6=36
7*1=7 7*2=14 7*3=21 7*4=28 7*5=35 7*6=42 7*7=49
8*1=8 8*2=16 8*3=24 8*4=32 8*5=40 8*6=48 8*7=56 8*8=64
9*1=9 9*2=18 9*3=27 9*4=36 9*5=45 9*6=54 9*7=63 9*8=72 9*9=81
```

### 009 菱形

打印出如下图案（菱形）

```
   *
  ***
 *****
*******
 *****
  ***
   *
```


### 010 计算容量

已知信息如下：
 
 - iPhone 的容量以千兆字节 (GB) 计算。这部 iPhone 有 128GB 存储容量。
 - 1 千兆字节大约为 1,000 兆字节 (MB)。
 - 手机上已经存储了 39GB 资料。
 - 1 分钟的视频占用 150MB 空间。
 
创建一个字符串，告诉用户手机上可以存储几分钟的视频。首先，需要执行计算步骤，然后使用字符串插值来显示答案，格式如下
 
 ```
 你的手机有 XXX GB存储，
 现在已经使用了 XXX GB，
 还有 XXX GB剩余空间，
 你可以再记录 XXX 分钟视频。
```

 提示：执行所有计算时以兆字节为单位。
