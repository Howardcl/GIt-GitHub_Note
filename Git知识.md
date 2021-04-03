1、私有仓库只有自己或者指定的朋友才可以操作（私有仓库是收费的）

### 2、GitHub创建新项目

（1）一个仓库对应一个开源项目

（2）可以通过Git管理Git项目

（3）Github issues

作用：发现代码bug，需要讨论时使用，相当于一个讨论区

### 3、Git的使用

#### <span style='color:red;background:white;font-size:28;font-family:楷体;'>3.1 Git基本工作流程</span>

**Git工作区域：**

1.工作区working Directory 添加、编辑、修改文件等工作

2.暂存区：暂存已经修改的文件，最后统一提交到git仓库中

3.Git 仓库：最终确定的文件保存到仓库，成为一个新的版本并对他人可见。



向仓库中添加文件流程：

git status : 查看文件状态

git add hello.php :将文件从工作区添加到暂存区

git commit -m "提交描述"：从暂存区提交到仓库

### <span style='color:red;background:white;font-size:28;font-family:楷体;'>3.2 Git初始化及仓库创建操作</span>

**基本信息设置**

1.设置用户名

git config --global user.name 'Howardcl'

2.设置用户名邮箱

git config --global user.email 'linchenusc@163.com'

**初始化一个新的Git仓库**

1、创建文件夹 test

2、在文件夹内初始化仓库

git init

初始化之后，生成一个.git文件

3、向仓库中添加文件流程

（1）先创建文件

  (2）添加到暂存区

  (3) 将文件从暂存区提交到仓库

**修改仓库文件**

**删除仓库文件**

rm 文件名

git rm 文件名

### <span style='color:red;background:white;font-size:28;font-family:楷体;'>3.3 Git管理远程仓库</span>

使用远程操作的目的：

1.备份

2.实现共享

**将本地仓库同步到git远程仓库中**：git push

#### **Git克隆操作：**

**1.将GitHub项目下载到本地**

git clone 仓库地址

**2.将本地仓库同步到Git远程仓库中**

git push

### <span style='color:red;background:white;font-size:28;font-family:楷体;'>3.4 Github Pages搭建网站</span>

个人站点访问：

https://用户名.github.io

**搭建步骤**

1）创建个人站点 -> 新建仓库（仓库名必须是【用户名.github.io】）

2）在仓库下新建index.html的文件即可

![image-20210403180114906](C:\Users\chenlin\AppData\Roaming\Typora\typora-user-images\image-20210403180114906.png)

1.GitHub pages仅支持静态网页

2.仓库里面只能是html文件

![image-20210403180940968](C:\Users\chenlin\AppData\Roaming\Typora\typora-user-images\image-20210403180940968.png)