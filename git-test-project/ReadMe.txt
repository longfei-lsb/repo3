git安装：
    1、安装git
    2、安装TortoiseGit
    3、安装chinese language 支持包
    4、检查版本号： git --version
git使用：
    创建本地仓库：git-repositorys/repo1
        创建文件夹：git-repositorys 、 repo1
    让repo1成为版本控制包：
        方式1：右键--git Bush here--$ git init
        方式2：右键--git GUI here--创建新的仓库（指定文件夹路径）
        方式3：右键--git repository here（记住不要勾选制作纯文本，除非不是本地仓库）
    标志：会出现一个名为：.git的隐藏文件夹

git结构：
    本地仓库（repo1）--》check out（down下来）--》工作区（repo1子文件以及文件夹）
                                                                           |
    ------------------------------------------------------------------------
    |
    --》add--》暂存区--》commit--》本地仓库--》push--》远程仓库--》clone--》本地仓库
                                                        |
                                                        ----》down and merge-------》工作区

文件操作：
    添加：
        1、右键--TortoiseGit--add
        2、右键--Tortoise commit master
    修改：
        （假设已经提交过的文件，再次修改后）
        1、右键--Tortoise commit master
    显示日志：
        1、右键--ToriseGit--show log
    比较版本差异：
        在show log窗口中选中不同版本右键--compare reversions
    删除：
        直接删除文件，但是版本库浏览器（右键 -- TortoiseGit -- Repo-browser）中还有
        需要再次在工作区中提交一次：右键--Tortoise commit master（缺失提交）
    删除版本库中的文件，但保留本地文件（delete but save local）：
        1、选中文件--右键--TortoiseGit--delete（keep local）
        2、commit工作区（前面有步骤）
    添加java工程到版本库：






