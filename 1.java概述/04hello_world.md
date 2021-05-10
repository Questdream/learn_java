# 第04节： hello_world

### 一、创建项目

1. 打开idea软件，点击界面上的Create New Project
2. 选中Java，然后选择jdk，最后点击Next，进行下一步
3. 选择生成项目时是否创建java文件，勾选上Java Hello World后会生成一个默认的Hello world文件，点击Next进行下一步
4. 给项目命名，默认是untiled，自己填个名字吧，最后点击finish

### 二、创建类与运行项目

1. 鼠标右键点击src——>new——>package，创建一个文件包，并给包命名，
   **在真正项目中一般命名都是项目的网址倒叙，比如：com.lxx**
2. 在包下面创建java类文件，右键点击包名——>New——>Java Class; 注意java class的运行必须要要有main函数作为入口，大家只要知道main方法是整个程序的入口方法。所有的程序都从这里开始执行。即在Class中定义`public static void main(String[] args){}` 注意java中会区分大小写，因此对大小写敏感，不能错。在main中写入`System.out.println("Hello World!");`
3. 运行java文件，点击上方工具栏中的Run——>Run…;

### 三、注释

- 单行注释

  *//我是单行注释*

- 多行注释

  /\*  我是多行注释 

  我是多行注释 

  *我是多行注释 \*/*

