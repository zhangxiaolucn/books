## 配置用户信息
```
$ git config --global user.name "runoob"
$ git config --global user.email test@runoob.com
```
## 查看配置信息
要检查已有的配置信息，可以使用 git config --list 命令：
```
$ git config --list
```
文本编辑器
设置Git默认使用的文本编辑器, 一般可能会是 Vi 或者 Vim。如果你有其他偏好，比如 Emacs 的话，可以重新设置：:

$ git config --global core.editor emacs

Git 创建仓库初始化
使用当前目录作为Git仓库，我们只需使它初始化。

```
git init
```

```
$ git add *.c
$ git add README
$ git commit -m '初始化项目版本'
```
git clone
我们使用 git clone 从现有 Git 仓库中拷贝项目（类似 svn checkout）。

克隆仓库的命令格式为：
```
git clone <repo>
```
如果我们需要克隆到指定的目录，可以使用以下命令格式：
```
git clone <repo> <directory>
```
参数说明：

repo:Git 仓库。
directory:本地目录。

比如，要克隆 Ruby 语言的 Git 代码仓库 Grit，可以用下面的命令：
```
$ git clone git://github.com/schacon/grit.git
```

```
$ git add .
$ git status -s
查看在你上次提交之后是否有修改。

```
## git commit
使用 git add 命令将想要快照的内容写入缓存区， 而执行 git commit 将缓存区内容添加到仓库中。

如果你觉得 git add 提交缓存的流程太过繁琐，Git 也允许你用 -a 选项跳过这一步。命令格式如下：
```
git commit -a
```





http://www.bootcss.com/p/git-guide/

https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013743256916071d599b3aed534aaab22a0db6c4e07fd0000

http://www.runoob.com/git/git-remote-repo.html


# 廖雪峰Git
https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000
