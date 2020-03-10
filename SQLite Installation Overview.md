# SQLite Installation Overview

This document introduces how to install SQLite under the Windows 64-bit OS.

## Step 1 Download

Access [SQLite Download](https://sqlite.org/download.html) to download correspoding precompiled binaries file and installation tool shown as below.

![image-20200309214404402](C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20200309214404402.png) 

## Step 2 Extraction

Create folder C:\sqlite, and unzip the two sqlite files you downloaded previously into it.

<img src="file:///C:/Users/lenovo/Documents/WXWork/1688850238339508/Cache/Image/2020-03/WXWorkCapture_15838008868763.png" alt="img" style="zoom:67%;" />

## Step 3 Environment Configuration

1. Right-click [My Computer], and select [Properties] -> [Advanced system settings] -> [Advanced] -> [Environment Variables];

<img src="file:///C:/Users/lenovo/Documents/WXWork/1688850238339508/Cache/Image/2020-03/WXWorkCapture_158379987122.png" alt="img" style="zoom:67%;" />

2. Select [Path] in the list of [System variables], and click [Edit];

   <img src="file:///C:/Users/lenovo/Documents/WXWork/1688850238339508/Cache/Image/2020-03/WXWorkCapture_15838000089249.png" alt="img" style="zoom:67%;" />

3. Click [New], enter the location where sqlite files are saved, and click [OK] to complete.

   <img src="file:///C:/Users/lenovo/Documents/WXWork/1688850238339508/Cache/Image/2020-03/WXWorkCapture_15838001313718.png" alt="img" style="zoom:67%;" />

## Step 4 Installation Check

Run CMD, and input command line **`sqlite3`** in the DOS window to check if SQLite is installed successfully. If yes, it will show you the following messages.

```
C:\sqlite3
SQLite version 3.31.1 2020-01-27 19:55:54
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
slite>
```

