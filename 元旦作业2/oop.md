**面向对象编程****  ****练习题******

## 专题1 初识Java

### 一、填空题

1．自从Sun推出Java以来，按应用范围可分为三个版本，分别是（se）、（ ee）、（me ）。

2．环境变量的设置，若JDK安装在“D:\JDK”，则应设置Path为（ bin）、classpath为（ lib  ）。

3．Java源文件的扩展名为（），用Javac编译Java源文件，得到的字节码文件的扩展名为（.class）。

4．如果Java源文件中有多个类，那么只能有一个类是（public）类。

5．Java程序可以分成两类，即  （）   和（）。

### 二、选择题

1．作为Java应用程序入口的main方法，其声明格式是（）b

A．public static int main(String args[])     B．public static voidmain(String args[]) 

C．public void main(String args[])        D．public int main(Stringargs[])   

2．下面命令正确的是（）b

A．java AppFirst.java                         B．java AppFirst

C．java appfirst.class                          D．javac AppFirst

3．设有一个Java小程序，源程序名为FirstApplet.java，其HTML文件为FirstApplet.html，则运行该小程序的命令为（）A

A．java FirstApplet                          B．javac  FirstApplet.java

C．appletviewer FirstApplet.java                D．appletviewer FirstApplet.html

4．JDK安装完成后，主要的命令如javac、java等，都存放在根目录的（）文件夹下。A

A．bin          B．jre          C．include          D．doc

5．Java语言是一种  语言。 d

A．机器                    B．汇编             C．面向过程的        D．面向对象的

6、Java程序的最基本组成单位是(   )。 D

A．函数                    B．过程                    C．变量                    D．类

\7. main()方法的返回值类型是（）。  

A．boolean   B．int    C. void            D．static

\8. 下面哪个单词是Java语言的关键字（）A．False     B．FOR    C．For  D．for  D

\9. 、线程是Java的（ ）机制。

A．检查   B．解释执行  C．并行    D．并发

### 三、简答题

1．Java语言有哪些特点？

 

2．JDK安装完成后，如何设置环境变量？

 

3．简述Java应用程序和小应用程序的区别。

 

4．简述Java应用程序的开发过程

## 专题2 标识符、表达式、数据类型

### 一、填空题

1．Java逻辑常量有两个：（false）和（true）。

2．比较两个数相等的运算符是：    == 。

4、Java中的八种基本数据类型分别是：char、  byte   、 short    、 int    、 long     、double      、 boolean          和 float        。

### 二、选择题

1．下面这些标识符哪个是错误的（）c

A．Javaworld       B．_sum         C．2JavaProgram       D．$abc

2、下面哪个赋值语句不会产生编译错误（）d

A．char a=’abc’;     B．byte b=152;     C．float c=2.0;         D．double d=2.0;

3．下面哪个单词是Java语言的关键字（）d

A．False        B．FOR        C．For       D．for

4．若变量都已经正确说明，则以下程序段输出为（）b

   a=10; 

b=50;

 c=30;

   if(a>b)

 a=b;

b=c;

   c=a;

  System.out.println(“a=”+a+” b=”+b+”  c=”+c);

　A．a=10 b=50  c=10          B．a=10 b=30  c=10 

C．a=50 b=30  c=10        D．a=50 b=30  c=30

5．下列标识符中，正确的是    。 

A、1_Back       B、$_Money               C、$-money         D、2-Forward

6．现有一个int类型的整数和一个double类型的浮点数，当它们之间做了加法运算之后，得到的结果类型应该是  。b

A、int类型               B、double类型        C、float类型            D、long类型

7、对下面的语句执行完后正确的说法是：（）

int c=’c’/3;  // c = 99;

System.out.println(c);

 A．输出结果为21  B．输出结果为22   C．输出结果为32   D．输出结果为33

8、设有定义int a=12;则执行a*=12;语句后，a的值为：（ ） 。

A．144      B．12      C．24      D．0

## 专题3 流程控制语句

### 一、填空题

1．在switch语句中的表达式的类型必须是（  ）或者（）。

2．break在循环语句中的作用是（）。

3．分支语句包括（）和（）。

4．while循环语句的循环次数（   ），do-while语句的循环次数（ ），for语句的循环次数（   ）。

\5. continue在循环语句中的作用是  （）。

## 专题4  面向对象

### 一、填空题

1．  如果一个方法不返回任何值，则该方法的返回值类型为     。

2．  如果子类中的某个方法名、返回值类型和_ ______与父类中的某个方法完全一致，则称子类中的这个方法      了父类的同名方法。

3．  接口中所有的属性均为 __、__ _____和_ _____的

4．       方法是一种仅有方法声明，没有具体方法体和操作实现的方法，该方法必须在      类之中定义。

5．  在Java程序中，通过类的定义只能实现      重继承，但通过   的定义可以实现多重继承关系。

6．  一般Java程序的类主体由两部分组成：一部分是   ，另一部分是  。

7．  分别用    关键字来定义类，用     关键字来分配实例存储空间。

8．  当一个类的修饰符为      时，说明该类不能被继承，即不能有子类。

9．  在Java中，能实现多重继承效果的方式是    。

### 二、选择题

1．       .有一个类A，对于其构造方法的声明正确的是（）。

A．void A(int x){…}     B．public A(int x){…}    

 C．A A(int x){…}        D．int A(int x){…}

2．       方法的形参（）。

A．可以没有                                                     B．至少有一个

C．必须定义多个形参                                D．只能是简单变量

3．       return语句（）

A．不能用来返回对象                                  B．只可以返回数值

C．方法都必须含有                                     D．一个方法中可以有多个

4．       main()方法的返回值类型是（）

A．boolean                                                         B．int

C．void                                                         D．static

5．       编译并运行下面的程序，运行结果是（）。

public class A{

   public static voidmain(String args[]){

​      A a=new A();

​      a.method(8);

   }

   void method(int i){

​     System.out.println(“int:  ”+i);

   }

   void method(long i){

​     System.out.println(“long:  ”+i);

   }

A．程序可以编译运行，输出结果为：“int:  8”        

B．程序可以编译运行，输出结果为：“long:  8”     

C．程序有编译错误，因为两个method()方法必须定义为静态（static）的

D．程序可以编译运行，但是没有输出

6．       能作为类及其成员的修饰符是（）。

A．interface                                                       B．class

C．protected                                                 D．public

7．       下列方法定义中，方法头不正确的是（）。

A．public static x(double a){…}                    B．public static int x(double y){…}****

C．void x(double d){…}                             D．public int x(){…}

8．       构造方法在（   ）时被调用。

A．类定义时                                                     B．使用对象的变量时

C．调用对象方法时                                    D．创建对象时

9．       下列哪个类声明是正确的（）。

A．public abstract class Car{…}                       B．abstract private move(){…}

C．protected private number;                         D．abstract final class H1{…}

10．    下列不属于面向对象程序设计的基本特征的是（）。

A．抽象                                                         B．封装

C．继承                                                        D．多态

 

11．    有一个类A，对于其构造函数的声明正确的是（）。

A．void A(int x){…}                                        B．public A(int x){…}

C．A A(int x){…}                                             D．int A(int x){…}

12．    关键字（）表明一个对象或变量在初始化后不能修改。

A．extends                                                     B．final

C．this                                                           D．finalize

13．    声明为static的方法不能访问（）类成员。

A．超类                                                          B．子类

C．非static                                                   D．用户自定义类

14．    定义类A如下：

class A{

  inta,b,c;

  public void B(int x,int y, int z){a=x;b=y;c=z;}

}

下面对方法B的重载哪些是正确的（）。

A．public void A(int x1,int y1, int z1){a=x1;b=y1;c=z1;}

B．public void B(int x1,int y1, int z1){a=x1;b=y1;c=z1;}

C．public void B(int x,int y){ a=x;b=y;c=0;}           

D．public B(int x,int y, int z){a=x;b=y;c=z;}

15．    编译运行下面的程序，结果是（）。

public class A{

 public static void main(String args[]){

B b=new B();

b.test();

  }

 void test(){

System.out.print(“A”);

  }

}

class B extends A{

 void test(){

super.test();

System.out.print(“B”);

  }

}

A．产生编译错误                                       B．代码可以编译运行，并输出结果：AB

C．代码可以编译运行，但没有输出      D．编译没有错误，但会产生运行时异常

16．    已知类关系如下：

Class Employee{}

Class Manager extends Employee{}

Class Director extends Employee{}

则下列语句正确的是：（）。

A．Employee e=new  Manager();                     B．Director d=new  Manager();

C．Director d =new  Employee ();                     D．Manager m=new  Director ();

17．    接口是Java面向对象的实现机制之一，以下说法正确的是（ ）。

A．Java支持多重继承，一个类可以实现多个接口

B．Java只支持单重继承，一个类可以实现多个接口

C．Java只支持单重继承，一个类可以实现一个接口     

D．Java支持多重继承，但一个类只可以实现一个接口

21．下列方法的声明中不合法的是   。

A．float area( ){…}                                     B．void area( ){…} 

C．area{…}                                                 D．int area(int r){…}

22、下面哪个包是编程时不需要导入就可以直接使用的   。

A．java.net                B．java.lang              C．java.sql                D．java.util

23、调用构造方法是在   。

A．类定义时　　　　　　                       B．创建对象时

C．调用对象的方法时　　                       D．使用对象的变量时

24、在子类构造方法的哪个地方可以调用其父类的构造方法   。

A．任何地方                                               

B．构造方法的第一条语句 

C．构造方法的最后一条语句 

D．无法在子类构造方法中调用父类的构造方法

25、关于Java中的继承，下列说法错误的是    。

A．继承是面向对象编程的核心特征，通过继承可以更有效地组织程序结构。

B．继承使得程序员可以在原有类的基础上很快设计出一个功能更强的新类，而不必从头开始，避免了工作上的重复。

C．每一次继承时，子类都会自动拥有父类的属性和方法，同时也可以加入自己的一些特性，使得它更具体、功能更强大。

D．继承一般有多重继承和单一继承两种方式，在单一继承中每一个类最多只有一个父类，而多重继承则可以有多个父类。Java中的类都采用多重继承。

26、当方法中的局部变量与成员变量同名时，必须使用下列哪一个关键字指出成员变量   。

A．static                    B．super                    C．this                       D．new

27、什么样的方法不能被重写   。

A．私有（private）方法                                   B．最终（final）方法

C．受保护（protected）的方法                D．以上都不对

28、下列有关抽象类与接口的叙述中正确的是哪一个  。

A．抽象类中必须有抽象方法，接口中也必须有抽象方法

B．抽象类中可以有非抽象方法，接口中也可以有非抽象方法

C．含有抽象方法的类必须是抽象类，接口中的方法必须是抽象方法

D．抽象类中的变量定义时必须初始化，而接口中不是

29、以下程序的输出是     

   intx=1,y=0,a=0,b=0;

   switch(x){

​      case 1:

​        switch(y){

​            case 0: a++;break;

​            case 1: b++;break;

​         }

​      case 2:

​         a++;break;

​      case 3:

​         a++;b++;

​    }

​    System.out.println(“a=”+a+”,b=”+b);  

 

30、下列类的声明中不合法的是    。

A．class People（）{…}                            B．class 植物{…} 

C．class A{…}                                            D．public class 共有类{…}

32、能作为类的修饰符, 也能作为类成员的修饰符的是    。

A．public                  B．extends                C．Float                    D．static

33、试完成下述程序片段   。

public classPoint{

​       int x,y;

​       public Point(int x,int y){

​              (   )=x; 

​              (   )=y;

​        }

​        ......

}

A．Point.x   Point.y                                  B．this.x   this.y

C．super.x  super.y                                     D．无解

34、在JAVA 中，下列说法正确的是：  。

A．一个子类可以有多个父类，一个父类也可以有多个子类

B．一个子类可以有多个父类，但一个父类只可以有一个子类

C．一个子类只可以有一个父类，但一个父类可以有多个子类

D．上述说法都不对

35、Father和Son是两个java类，下列（）正确的标识出Father是Son的父类？

A．class Son implements Father                  B．class Father implementsSon

C．class Father extends Son                        D．class Son extends Father 

36、重载指的是方法具有相同的名字，但这些方法的参数必须不同。下列哪种说法不属于方法参数的不同    。

A．形式参数的个数不同。                       B．形式参数的类型不同。

C．形式参数的名字不同。                       D．形式参数类型的排列顺序不同。

39、关于接口的定义和实现，以下描述正确的是  。

A．接口定义的方法只有定义没有实现          

B．接口定义中的变量都必须写明final和static

C．如果一个接口由多个类来实现，则这些类在实现该接口中的方法时采用统一的代码

D．如果一个类实现接口，则必须实现该接口中的所有方法，但方法未必申明为public

 

### 三、阅读程序题

1、写出运行结果：     。

public classComputer{     

​       String mainbord,cpu;

​       public Computer(String s1,String s2){  

​              mainbord=s1;

​              cpu=s2;         

​       }

​       public static void main(String[]args){    

​              Computerc=new Computer("微星","AMD");

​              System.out.println("mainbord:"+c.mainbord+",cpu:"+c.cpu);         

​       }     

}     

2、写出运行结果：        。

public classPerson{   

​       String name;

int age;

public Person(String name,int age){      

​       this.name=name;

​       this.age=age;

}

public static void main(String[]args){    

​       Personc=new Person("Marry",18);

​       System.out.println(c.name+"is "+c.age+" years old!");

}

}

3、** ****下面是一个类的定义，请将其补充完整******

   class ___ ___{

​      String name;

​      int age;

​      Stud(______ name, inta){

​         __ ___.name=name;

​         age=a;

​      }

}

 

**4****．下面是一个****B.java****源文件，请将其补充完整******

​     class  B{

​      String x;

​      ___ ___ int a=3;

​      B(String x){

​         this.x=       ;

​      }

static intgetA(){

​                  returna;

}

}

 

## 专题5  异常处理

### 一．填空题

1．一个try语句块后必须跟（  ）语句块，（   ）语句块可以没有。

2．自定义异常类必须继承（    ）类及其子类

3．异常处理机制允许根据具体的情况选择在何处处理异常，可以在（  ）捕获并处理，也可以用throws子句把他交给（      ）处理

### 二．选择题

1.  finally语句块中的代码（   ）

A．总是被执行    

B．当try语句块后面没有catch时，finally中的代码才会执行

C．异常发生时才执行                          

D．异常没有发生时才被执行

2.  抛出异常应该使用的关键字是（  ）

A．throw

B．catch

C．finally

D．throws

3.  自定义异常类时，可以继承的类是（   ）

A．Error

B．Applet

C．Exception及其子类

D．AssertionError

4.  在异常处理中，将可能抛出异常的方法放在（   ）语句块中

A．throws

B．catch

C．try

D．finally

### 三．简答题

1．try/catch/finally如何使用？

 

2．Throw/throws有什么联系和区别？

​                                                             

3．谈谈final、finally的区别和作用

4．Error和Exception有什么区别？

## 专题7  输入输出

### 一、填空题

1．根据流的方向，流可以分为两类：（     ）和（     ）

2．根据操作对象的类型，可以将数据流分为（     ）和（）两种

3．在java.io包中有4个基本类：InputStream、OutputStream、Reader和（）类

4．（）类是java.io包中一个非常重要的非流类，封装了操作文件系统的功能。

 

 

 

 

1.编写一个Java程序，定义一个Shape类，具有：属性：形状(form)——String类型，功能：求面积（double area( )）；     再定义Shape类的子类**Circle**，具有：属性：半径（raduis）——double型，功能：设置半径（void setraduis(doublenewRaduis)），把新半径赋给raduis。

 

\2. 定义一个人类，包括属性：姓名、性别、年龄；包括方法：吃饭、睡觉，工作。根据人类，派生一个学生类，增加属性：学校、学号；学生的工作是学习。

 

 