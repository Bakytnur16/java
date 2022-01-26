# java
大小写敏感  
注释：  
单行 //  
多行 /* */  

public static void main(string[] args)  
访问修饰符 关键字 返回类型 方法名 string类 字符串数组  

访问控制修饰符 : default默认, public公共的 , protected受保护的, private私有的
非访问控制修饰符 : final, abstract, static, synchronized

abstract	声明抽象
class	类
extends	扩充,继承
final	最终值,不可改变的
implements	实现（接口）
interface	接口
native	本地，原生方法（非 Java 实现）
new	新,创建
static	静态
strictfp	严格,精准
synchronized	线程,同步
transient	短暂
volatile	易失
```
public class helloWorld {
    public helloWorld(String name){
        System.out.println("小狗的名字是 ：" + name);
    }
    public static void main(String[] args) {
        helloWorld myhelloWorld = new helloWorld("tommy");
    }
}
```
#### 变量：
局部变量：在方法、构造方法或者语句块中定义的变量被称为局部变量。
类变量（静态变量）：成员变量是定义在类中，方法体之外的变量。
成员变量（非静态变量）： static 类型

#### 数组
数组是储存在堆上的对象，可以保存多个同类型变量

#### 枚举
枚举限制变量只能是预先设定好的值


break	跳出循环
case	定义一个值以供 switch 选择
continue	继续
default	默认
do	运行
else	否则
for	循环
if	如果
instanceof	实例
return	返回
switch	根据值选择执行
while	循环

assert	断言表达式是否为真
catch	捕捉异常
finally	有没有异常都执行
throw	抛出一个异常对象
throws	声明一个异常可能被抛出
try	捕获异常

boolean	布尔型
byte	字节型
char	字符型
double	双精度浮点
float	单精度浮点
int	整型
long	长整型
short	短整型

super	父类,超类
this	本类
void	无返回值
保留关键字	
goto	是关键字，但不能使用
const	是关键字，但不能使用
