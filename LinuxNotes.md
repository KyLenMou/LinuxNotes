# LinuxNotes

cd

1. change directory 改变目录
   ```shell
   cd
   ```

   不加参数直接跳转到home目录

2. 相对路径和绝对路径

   1. 相对路径是从目前位置
   2. 使用绝对路径时最前面是"/“

3. 根目录 直接使用"/"
   ```shell
   cd /
   ```

   直接到根目录

4. "~" 用户的home目录
   ```shell
   cd ~
   ```

   到用户的home目录

5. "." 当前目录

6. ".." 上一级目录

7. "-" 上一次访问的目录



pwd 显示当前目录的绝对路径



mkdir

1. make directory 创建目录
2. 添加参数 -p 跳过已有的目录
3. 可以同时创建多个目录



rm

1. remove 永久删除文件
2. 添加参数 -r 递归删除目录
3. 删除一个文件夹里所有文件 "./*"



cp copy 复制+粘贴+重命名
```shell
cp a.txt d/b.txt
```



mv move 移动+重命名

```shell
mv a.txt b.txt
```





"*"

1. 表示通配符

2. 要删除a目录下的所有文件，不删除a目录
   ```shell
   rm a/*
   ```

3. 要删除后缀为.txt的文件
   ```shell
   rm *.txt
   ```




cat 查看文件内容
