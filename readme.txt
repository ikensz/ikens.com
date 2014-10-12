1、touch readme.txt：创建readme.txt文件
2、mkdir learn：创建learn文件夹
3、git add readme.txt：将readme.txt提交到stage缓存区
4、git commit -m "说明改了什么":对改动的文件进行提交到HEAD指向的master分支区域
5、git status：查看状态
6、git log：查看日志
7、git log --pretty=oneline ：美化显示日志
8、git reset --hard HEAD^ 回到上一个版本
9、git reset --hard HEAD^^ 回到上上个版本
10、cat readme.txt 查看readme.txt文件内容
11、git reset --hard 3628164 回到指定的版本(版本号：3628164)
12、git reflog 用来记录你的每一次命令
13、git diff HEAD -- readme.txt 可以查看工作区和版本库里面最新版本的区别
14、git checkout -- readme.txt 丢弃工作区的修改
15、git reset HEAD readme.txt  把暂存区的修改撤销掉（unstage），重新放回工作区
16、rm test.txt 删除工作区中的文件
17、git rm test.txt 从版本库中删除test.txt文件并且用 git commit -m "remove test.txt"指令确认删除

18、git remote add origin git@github.com:ikensz/ikens.com.git 将本地库和远程库进行关联
19、git push -u origin master 将本地库的所有内容推送到远程库上
20、只要对本地库做了修改都可以使用：git push origin master 指令提交到远程库
21、 git clone git@github.com:ikensz/ikens.com.git 从远程库上克隆一份到本地库

22、git checkout -b dev 创建dev分支并从master切换dev分支上 相当于：git branch dev(创建dev分支),git checkout dev(切换到dev分支上)
23、git branch 会列出所有分支，带*的表示当前分支
24、git checkout master 当dev分支工作完成之后，切换到master分支上
25、git merge dev 将dev分支上的工作内容合并到master分支上
26、git branch -d dev 删除dev分支
