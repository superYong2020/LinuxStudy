1. 安装Git

sudo apt-get install git

2. 创建版本库
git init
git add filename / *
git commit -m "comment message"

3. 查看状态
git status

4. 查看git difference
git diff filename 

5. 查看日志、查看每一次命令、版本回退
git log
git reflog
git reset --hard commit_id

6. 丢弃工作区的修改
git checkout -- filename

7. 删除文件
git rm filename

8. 远程仓库添加
ssh-keygen -t rsa -C "youremail@example.com"  复制id_rsa.pub到SSH Keys
 
git remote add origin github@github.com:superYong/reposetory_name.git
 
9. clone文件到本地
git clone git_address
上传到服务器
git push --rebase origin master
之后提交代码只需要 git push origin master
