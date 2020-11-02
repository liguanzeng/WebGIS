# Git常用操作

1. 初始化本地仓库

   `git init`

2. 查看状态

   `git status`

3. 添加文件

   添加单个文件

   `git add <file_name>`

   添加文件夹，首先cd到新的文件夹中

   `git add .`

4. 删除文件

   `git rm <file name>`

5. 将修改上传到暂存区

   每次修改，如果不用`git add`到暂存区，那就不会加入到`commit`中

6. 将所有修改加入到`commit`中

   `git commit -m "这里描述你的改动"`

7. 将操作推送到远程仓库

   `git push`or`git push origin main`