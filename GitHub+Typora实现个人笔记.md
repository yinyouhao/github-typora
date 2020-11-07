# GitHub+Typora实现个人在线笔记

## 1.注册GitHub账号

## 2.安装git并配置

## 3.安装并设置Typora

## 4.利用git实现笔记上传

1.新建一个库

2.将想要同步的文件夹右键Git Bush打开

3.链接到刚才的github新建库的SSH链接

​	1）获取SSH

![](https://github.com/yinyouhao/github-typora/blob/main/images/%E5%9B%BE%E7%89%874.1.jpg)

​	2）在刚在打开的Git Bash窗口中输入：

```
git clone XXXXX //XXX为刚才获取的SSH
```

4.执行完上述指令后，会在想要同步的文件夹下生成一个和Github仓库同名的文件夹，将想要上传的.md文件放到这个文件夹中

5.刚才的Git Bash界面输入：

```
cd XXX//XXX为新生成的文件夹名称 即与Github仓库同名
```

6.将项目文件加进缓冲区

```
git add. //.为该文件下的所有文件，如果只上传某个单文件则为单文件名
```

7.给上传的文件备注

```
 git commit -m “xxx” //xxx为备注信息  这一步不可省略 
```

8.上传文件

```
git push -u origin master
```

！！！特别注意这里的这个master，一定要和自己创建的那个库的分支名相同，一般默认的是main

查看分支名称的方法：

![](https://github.com/yinyouhao/github-typora/blob/main/images/%E5%9B%BE4.2.jpg)

9.刷新Github，即可查看新更新的文件

## 5.利用GitHub建立图床
此部分可以参考一下链接

https://blog.csdn.net/Sophia_11/article/details/95051346#%E3%80%903%E3%80%91%E4%B8%8A%E4%BC%A0%E5%9B%BE%E7%89%87

## 6.利用readme.md文件生成目录

 1.进入刚刚生成的仓库中，点击题目前方的链接图标

![](https://github.com/yinyouhao/github-typora/blob/main/images/%E5%9B%BE6.1.jpg)

![图6.1](assets/图6.1.jpg)

 2.复制上方链接

![](https://github.com/yinyouhao/github-typora/blob/main/images/%E5%9B%BE6.2.jpg)

![图6.2](assets/图6.2.jpg)

 3.点击README.MD文件，点击右上方的修改图标

![](https://github.com/yinyouhao/github-typora/blob/main/images/%E5%9B%BE6.3.jpg)

![图6.3](assets/图6.3.jpg)

 4.输入：

```
//上下各留出来一行
[目录名称](刚刚复制的链接)
//上下各留出来一行
```

5.拉到最后点击commit按钮



