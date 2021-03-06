解释器模式(Interpreter):给定一个语言，定义他文法的一种表示，并定义一个解释器，这个解释器使用该表示来解释语言中的句子。  
UML结构图:  
![](https://ws1.sinaimg.cn/large/006mOQRagy1g520eajbccj31su14o7wh.jpg)  

什么时候使用解释器模式呢？  
当有一个语言需要解释执行，并且你可将该语言的句子表示为一个抽象语法时，可使用解释器模式。  

缺点：  
解释器模式也有不足的，解释器为文法的没一条规则至少定义一个类，因此包含许多规则的文法可能难以管理和维护。建议当文法非常复杂时，使用其他的技术如语法
分析程序或编译生成器来处理。  