# 使用 C# 对数字执行基本运算操作

|本期版本|上期版本
|:---:|:---:
`Sun Jun 23 17:09:20 CST 2024` | -

* 为了多个目的重复使用一个符号有时被称为“重载运算符”，并且经常在 C# 中发生


**添加括号向编译器阐明意图**

```c#
string firstName = "Bob";
int widgetsSold = 7;
Console.WriteLine(firstName + " sold " + (widgetsSold + 7) + " widgets.");
```

* 使用在值前面加括号括起来的数据类型名称来强制转换该数据类型。 在本示例中，将 (decimal) 添加到变量 first 和 second 之前。

**运算顺序**

