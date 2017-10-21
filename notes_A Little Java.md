### chpter 2
#### 不同的数据类型之间如何递归调用？
作者这一点上很像是ML在Java上的应用。dataclass定义了一个复合类型，由此生成的variant可以递归使用。而在这里，Java中的subtyping与之类似，作者定义了一个shish类，其subsclass为Onion、Tomato等，并且这些subclass同样是subclass。也会就是说，如果在ML中，dataclass class0中定义了class1,class2,class3，那么在Java中，Parent class0就是dataclass，而subclass就是subsclass1 ,subclass2,subclass3，并且这些子类的构造函数如果都设定接受Parent class0，那么它们同样可以相互调用。

#### 奇怪的原因
作者关于数据的构建与传统的方式很不相同。作者直接传递了new XXX()，**并没有命名**。传统的构建都是在命名之后才传递。