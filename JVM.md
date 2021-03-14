## JVM的位置

硬件-->OS-->JVM-->字节码文件-->用户User

## JVM的整体结构

![image-20210314090825395](C:\Users\wy123\AppData\Roaming\Typora\typora-user-images\image-20210314090825395.png)

## JVM的生命周期

1. 启动：通过类加载器创建一个初始类（Initial Class）来完成，这个类有VM的具体实现指定
2. 执行：程序开始执行时他才运行，程序结束时他就停止。JVM进程去执行一个程序
3. 退出： 
   - 正常结束
   - 异常终止：遇到异常；OS出现错误
   - Runtime类的halt()方法或System类的exit()方法