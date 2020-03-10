# SQLite 安装概览

此文档将介绍在以Windows 64位系统为例的环境下如何安装SQLite。

## 第一步 SQLite下载

访问 [SQLite下载页面](https://sqlite.org/download.html)，下载对应的预编译的二进制文件及安装工具。如下图所示。

<img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200309214404402.png" alt="image-20200309214404402" style="zoom:50%;" />

## 第二步 解压文件

创建文件夹 C:\sqlite，并在此文件夹下解压上图所示的两个压缩文件，将得如下文件。

<img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200309220534494.png" alt="image-20200309220534494" style="zoom: 50%;" />

## 第三步 环境配置

1. 右键我的电脑，依次进入【属性】->【高级系统设置】->【高级】->【环境变量】；

<img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200309221431518.png" alt="image-20200309221431518" style="zoom: 50%;" />

2. 在系统变量列表中选择Path，并点击【编辑】；

   <img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200309221720393.png" alt="image-20200309221720393" style="zoom: 50%;" />

3. 点击【新建】，输入解压文件所在地址。点击【确定】完成安装。

   <img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200310083400840.png" alt="image-20200310083400840" style="zoom: 50%;" />

## 第四步 安装检测

运行CMD，在DOS窗口中输入 `sqlite3` 命令查看SQLite是否配置成功。如成功，将显示如下结果。

```
C:\sqlite3
SQLite version 3.31.1 2020-01-27 19:55:54
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite>
```

