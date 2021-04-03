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

<span style='color:red;background:white;font-size:28;font-family:楷体;'>3.2 Git初始化及仓库创建操作</span>