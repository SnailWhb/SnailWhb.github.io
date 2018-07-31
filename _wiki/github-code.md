# **git的基本流程**

![](leanote://file/getImage?fileId=5b3db602e9ac990a53000001)

    Workspace：工作区
    Index / Stage：暂存区
    Repository：仓库区（或本地仓库）
    Remote：远程仓库
# 一、新建代码库
在当前目录新建一个Git代码库

    git init

新建一个目录，将其初始化为Git代码库

    git init [project-name]

下载一个项目和它的整个代码历史

    git clone [url]


#二、提交代码

     git add . // 添加当前目录的所有文件到缓存区
     git commit -m　//评论
     git pull  //合并
     git push　
#五、分支

    列出所有本地分支
    
        git branch
    
    列出所有远程分支
    
         git branch -r
    
     列出所有本地分支和远程分支
    
        git branch -a
    
     新建一个分支，但依然停留在当前分支
    
         git branch [branch-name]
    
    新建一个分支，并切换到该分支
    
         git checkout -b [branch]
    
    新建一个分支，指向指定commit
    
         git branch [branch] [commit]
    
    新建一个分支，与指定的远程分支建立追踪关系
    
         git branch --track [branch] [remote-branch]
     切换到指定分支，并更新工作区
    
         git checkout [branch-name]
    
    切换到上一个分支
    
        git checkout -
    
    建立追踪关系，在现有分支与指定的远程分支之间
    
         git branch --set-upstream [branch] [remote-branch]
     合并指定分支到当前分支
    
         git merge [branch]
    
     选择一个commit，合并进当前分支
     
          git cherry-pick [commit]
    
     删除分支
    
        git branch -d [branch-name]
    
     删除远程分支
    
         git push origin --delete [branch-name]
         git branch -dr [remote/branch]

参考：
http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html

