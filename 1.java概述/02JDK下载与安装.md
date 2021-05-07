# 第02节：JDK下载和安装

### 一、JDK介绍

JDK是Java开发套件。

JRE是Java运行环境。

JRE在JDK里面，JVM在JRE里面。所以安装JDK就可以开发Java了

### 二、JDK下载

[JDK的下载地址](https://www.oracle.com/technetwork/java/javase/downloads/index.html)

### 三、JDK的安装

1. 运行安装包

   直接双击，一直下一步即可

2. 配置环境变量

   * 安装完成后，右击"我的电脑"，点击"属性"，选择"高级系统设置"；

   * 选择"高级"选项卡，点击"环境变量"；

   * 在 “系统变量” 中设置 3 项属性，JAVA_HOME、PATH、CLASSPATH(大小写无所谓),若已存在则点击"编辑"，不存在则点击"新建"。
     * 变量名：JAVA_HOME

       变量值：C:\Program Files (x86)\Java\jdk // 要根据自己的实际路径配置

     * 变量名：Path （path环境变量–帮助系统操作java）

       变量值：%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;

       ```
       // 在win10中path需要分开成两行添加
       %JAVA_HOME%\bin
       %JAVA_HOME%\jre\bin
       ```

     * 变量名：CLASSPATH （环境变量是java运行时默认去找的路径，java基本的jar包在里面。配置后可执行cmd中的java命令）

       变量值：.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar; //记得前面有个"."

   ### 四、JDK的运行

   在安装的JDK目录中：bin是存放java可执行文件的目录。

   在cmd控制台输入

   ```java
   java -version // 查询版本
   javac //将Java文件编译成class文件
   Java // 执行你边意思的class文件
   ```

   

