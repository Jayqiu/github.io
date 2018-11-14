# Kotlin 学习笔记   

[Kotlin中文站 地址](https://www.kotlincn.net/)

  Kotlin中有两个关键字定义变量，这两个关键字外形看着差别很小就只差了一个字母，但实际差别很大的。

      var  是一个可变变量，这是一个可以通过重新分配来更改为另一个值的变量。这种声明变量的方式和java中声明变量的方式一样。

      val   是一个只读变量，这种声明变量的方式相当于java中的final变量。一个val创建的时候必须初始化，因为以后不能被改变。

### Kotlin关键字一览表

|关键字|说明|
|-----|-----|
|abstract|抽象声明，被标注对象默认是open|
|annotation|注解声明|
|by|类委托、属性委托|
|class|声明类|
|companion|伴生对象声明|
|const|	声明编译期常量|
|constructor|	声明构造函数|
|crossinline|	标记内联函数的lambda表达式参数，标识该lambda函数返回为非局部返回，不允许非局部控制流|
|data	|数据类，声明的类默认实现equals()/hashCode()/toString/copy()/componentN()
|enum	|声明枚举类
|field	|属性的幕后字段
|fun	|声明函数
|import	|导入
|in	|修饰类型参数，使其逆变：只可以被消费而不可以被生产
|init	|初始化块；相当于主构造函数的方法体
|inline	|声明内联函数
|inner	|标记嵌套类，使其成为内部类：可访问外部类的成员
|interface|	声明接口
|internal|可见性修饰符，相同模块内可见
|lateinit	|延迟初始化，避免空检查
|noinline	|禁用内联，标记内联函数不需要内联的参数
|object	|对象表达式、对象声明
|open	|允许其它类继承；kotlin类默认都是final，禁止继承
|operator	|标记重载操作符的函数
|out	|修饰类型参数，使其协变：只可以被生产而不可以被消费
|override	|标注复写的方法、属性
|package	|包声明
|private	|可见性修饰符，文件内可见
|protected	|可见性声明，只修饰类成员，子类中可见
|public	|kotlin默认的可见性修饰符，随处可见
|reified	|限定类型参数，需要配合inline关键字使用
|sealed|	声明密封类，功能类似枚举
|super	|访问超类的方法、属性
|suspend	|声明挂起函数，该函数只能从协程和其他挂起函数中调用
|throw|	抛异常
|typealias|	声明类型别名
|val	|声明只读属性
|var	|声明可变属性
|vararg|	修饰函数参数：声明为可变数量参数|



