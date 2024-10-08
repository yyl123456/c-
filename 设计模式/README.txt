#创建型模式
单例模式（Singleton Pattern）：

确保一个类只有一个实例，并提供一个全局访问点。
工厂方法模式（Factory Method Pattern）：

定义一个创建对象的接口，但由子类决定实例化哪一个类。
抽象工厂模式（Abstract Factory Pattern）：

提供一个创建一系列相关或相互依赖对象的接口，而无需指定它们的具体类。
建造者模式（Builder Pattern）：

将一个复杂对象的构建与其表示分离，使得同样的构建过程可以创建不同的表示。
原型模式（Prototype Pattern）：

通过复制现有对象来创建新对象，而不是通过实例化类。



#结构型模式
适配器模式（Adapter Pattern）：

将一个类的接口转换成客户希望的另一个接口，使得原本由于接口不兼容而不能一起工作的类可以一起工作。
桥接模式（Bridge Pattern）：

将抽象部分与它的实现部分分离，使它们都可以独立地变化。
组合模式（Composite Pattern）：

将对象组合成树形结构以表示“部分-整体”的层次结构，使得用户对单个对象和组合对象的使用具有一致性。
装饰模式（Decorator Pattern）：

动态地给对象添加一些额外的职责，就增加功能来说，装饰模式比生成子类更为灵活。
外观模式（Facade Pattern）：

为子系统中的一组接口提供一个一致的界面，使得子系统更容易使用。
享元模式（Flyweight Pattern）：

运用共享技术有效地支持大量细粒度的对象。
代理模式（Proxy Pattern）：

为其他对象提供一种代理以控制对这个对象的访问。



#行为型模式
责任链模式（Chain of Responsibility Pattern）：

使多个对象都有机会处理请求，从而避免请求的发送者和接收者之间的耦合关系。
命令模式（Command Pattern）：

将请求封装成对象，从而使你可以用不同的请求对客户进行参数化。
解释器模式（Interpreter Pattern）：

给定一个语言，定义它的文法的一种表示，并定义一个解释器，这个解释器使用该表示来解释语言中的句子。
迭代器模式（Iterator Pattern）：

提供一种方法顺序访问一个聚合对象中的各个元素，而又不暴露其内部的表示。
中介者模式（Mediator Pattern）：

用一个中介对象来封装一系列的对象交互，中介者使各对象不需要显式地相互引用，从而使其耦合松散，而且可以独立地改变它们之间的交互。
备忘录模式（Memento Pattern）：

在不破坏封装性的前提下，捕获一个对象的内部状态，并在该对象之外保存这个状态，以便以后恢复对象到原先保存的状态。
观察者模式（Observer Pattern）：

定义对象间的一种一对多的依赖关系，当一个对象的状态发生改变时，所有依赖于它的对象都得到通知并被自动更新。
状态模式（State Pattern）：

允许对象在内部状态改变时改变它的行为，对象看起来好像修改了它的类。
策略模式（Strategy Pattern）：

定义一系列的算法，把它们一个个封装起来，并且使它们可相互替换。本模式使得算法可独立于使用它的客户而变化。
模板方法模式（Template Method Pattern）：

定义一个操作中的算法的骨架，而将一些步骤延迟到子类中。模板方法使得子类可以不改变一个算法的结构即可重定义该算法的某些特定步骤。
