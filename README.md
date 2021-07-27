# 入门基础知识

### 	一、常见的命令行

1. 查看文件命令
   + pwd	查看当前文件的绝对路径
   + ls         查看当前目录内容
   + cat       查看文件内容(显示文件中的全部内容)
   + head   查看文件内容(显示文件前10行)
     + 拓展 head -n 14(查看文件的前n行)
   + tail      查看文件内容(显示文件后10行)
     + 同理 tail -n 14(查看文件的后n行)
   + less     查看文件内容(分页查看，可拓展)
2. 插入文件命令
   + touch 1.txt	(创建空文件)
   + echo mmp > 4.txt   (将mmp添加至4.txt文件,会覆盖前面的内容)
     + ">" 覆盖文件中的内容
     + ">>" 向文件中追加一行内容
     + "使用转义字符/n即换行"  追加多行内容(echo -e "1\n2")
   + mkdir -p /a/b/c/d 创建目录
3. 删除文件命令
   + rm 1.txt(删除文件)
   + rm -rf a (删除目录)
4. 修改文件命令
   + code  1.txt
   + start 1.txt 
   + echo ' ' > 1.txt (清空文件)
5. 移动文件命令
   + mv 
6. 压缩文件命令
7. 查看所有命令 
   + ls --help


### 二、遇到的问题

1. vsCode中bash新旧版本的配置
2. cmder中npm i成功执行版本查看s时，bash: tldr: command not found
3. cmder中λ与$的更换

### 三、加入代码
  ```javascript
  let a = 3;
  console.log(a);
  ```
