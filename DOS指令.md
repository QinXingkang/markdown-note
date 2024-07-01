# 1.dir->查看当前目录中的所有文件 (dirctory)

![image-20240623183519660](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183519660.png)

##  dir +绝对路径 查看某一路径中的所有内容

###  dir d:

![image-20240623183544197](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183544197.png)

### dir d:\java\

![image-20240623183602452](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183602452.png)

# 2.cd 切换目录

## 切换到C盘 cd /d c:

## 切换到D盘 cd /d d:

![image-20240623183649714](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183649714.png)

### 切换到当前磁盘的某一目录下

#### （1）通过相对路径

![image-20240623183715119](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183715119.png)

从java路径切换到同一位置的office路径下（即先返回D:，再进入office）

#### （2）通过绝对路径

从office路径直接切换到java路径

![image-20240623183753551](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183753551.png)

#### 切换到上一级目录

 cd ..

![image-20240623183813700](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183813700.png)

切换到根目录

 cd \

![image-20240623183825071](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183825071.png)

# 3.tree 查看指定目录下的所有的子级目录

![image-20240623183840725](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183840725.png)

# 4.cls 清屏

# 5.exit 退出CMD

# 6.md 创建目录

![image-20240623183857834](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183857834.png)

# 7.rd 删除目录

# 8.copy 拷贝文件

![image-20240623183913325](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183913325.png)

# 9.del 删除文件

![image-20240623183923163](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183923163.png)

![img](data:image/png;base64,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)

# 10.echo 输入内容到文件中

Echo ok >pic.txt

![image-20240623183937903](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183937903.png)

![image-20240623183943122](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623183943122.png)

# 11.move 剪切

Move pic.txt d:\office

![image-20240623184006813](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623184006813.png)

# 12.type 创建文件

Type nul > new.txt

![image-20240623184021877](C:\Users\25050\AppData\Roaming\Typora\typora-user-images\image-20240623184021877.png)