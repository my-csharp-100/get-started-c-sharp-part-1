# 在 C# 中执行基本字符串格式设置


|本期版本|上期版本
|:---:|:---:
`Sun Jun 23 17:02:33 CST 2024` | -


* 逐字字符串字面量: `@`
* 字符串内插: `$"Hello,{name}"`


**合并逐字文本和字符串内插**

```c#
string projectName = "First-Project";
Console.WriteLine($@"C:\Output\{projectName}\Data");
```