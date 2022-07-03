# Git

### git的常用命令

#### git stash

会将未提交到本地仓库或远程服务器上的文件暂时放到储存区

#### git stash pop

 恢复由git stash 存储到储存区的文件（git stash 的逆操作）

#### git rebase

主要用于合并分支，区别于merge的合并；在进行合并代码分支前需要先解决合并分支造成的冲突

#### git add

将代码文件提交到暂存区进行保存

#### git status

查看暂存区的文件

#### git  commit

将文件提交到本地的数据仓库   ； -m参数可以为提交的代码文件进行备注

#### git push

将本地数据仓库中的代码文件上传到远程的服务器仓库

#### git fetch

能把代码文件的提交记录写到。。。。（不记得了）（补充更新git remote 中所有的远程repo 所包含分支的最新commit-id, 将其记录到.git/FETCH_HEAD文件中（不会用））

#### gitk --all

弹出gui窗口查看分支提交的记录和时间

#### git gui

git 的gui操作界面

#### git pull = =（git fetch+git merge    ）

拉取分支代码的更新

#### git ls-files

查看暂存区中的所有文件

#### git rm --cache 文件名(路径)

仅将文件从暂存区中移除

#### （***慎用***）git rm -f 文件名（路径）

将文件从本地仓库和暂存区中的文件删除

#### git reset（--soft、--mixed、--hard）版本库id

--soft：撤销已提交的版本库

--mixed：撤销暂存区和版本库（被弃用，，用 ‘--’ 进行替代 ）

--hard：撤销撤销暂存区、版本库、工作区

#### git log

可以查找git 提交记录的日志信息，及对应的版本库id

#### git restore --staged 文件名

仅仅能撤回由git add提交到暂存区的文件

#### git pull

git pull = git fetch + git merge 获取分支代码并进行合并

### git 的环境配置问题

#### 1、git push失败

![](C:\Users\gollum\AppData\Roaming\marktext\images\2022-06-28-13-45-25-image.png)

如上图的情况，可以打开系统 的 `凭据管理器` 查看普通凭据 所记录的信息与实际信息是否有出入（像是用户名密码不匹配的问题，建议采用邮箱+密码的方式进行登录）

#### 
