## NeStaticDynamicLibrary 编译原理及静态库、动态库
### 一、编译原理
#### 1.1 编译过程
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/compile_process1.png)  
##### 1.1.1 编译预处理
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/pre_process2.png)  
编译预处理命令  
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/pre_process_command3.png)  
##### 1.1.2 编译
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/compilation4.png)  
编译命令：     
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/compilation_command5.png)  
##### 1.1.3 汇编
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/assemble6.png)  
汇编命令：  
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/assemble_command7.png)  
##### 1.1.4 链接
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/linking8.png)  
链接命令：  
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/linking_command9.png)  
编译过程实操：  
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/my_compilation_command10.png)

### 二、静态库
#### 2.1 静态库
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/static_library11.png)  
#### 2.2 生成静态库命令
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/static_library_command12.png)  
#### 2.3 生成静态库实操
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/my_static_library_command13.png)  
**说明:**  
`-ltool表示要链接名称为tool的库， -L. 表示程序按照-L指定的路径（当前目录）寻找库文件`  



### 三、动态库
#### 3.1 动态库
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/dynamic_library14.png)  
#### 3.1 生成动态库命令
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/dynamic_library_command15.png)  
#### 3.1 生成动态库实操
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/my_dynamic_library_command16.png)  
**说明:**  
`-fPIC: file Position Independent Code—>与文件地址无关的代码`  

### 四、动态库静态库区别
![image](https://github.com/tianyalu/NeStaticDynamicLibrary/blob/master/show/difference17.png)

