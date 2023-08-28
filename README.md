# cartographer_detailed_comments_ws
git从本地仓库到远程仓库的连接:
方法一：
①在本地文件夹打开终端，执行  git init
②在远程仓库上新建一个仓库，要求是必须和本地仓库同名
③git remote add origin https://github.com/hailang-wang/MyGitTest.git 相当于给远程库取了个别名origin
④git remote set-url  origin https://xxxQHm@github.com/hailang-wang/MyGitTest.git   xxx为自己的token
⑤git add . //添加到暂存区
⑥git commit -m "message" //添加到版本库
⑦git push --set-upstream origin master // 设置对于的上游分支
⑦git push origin <本地分支>
⑧git branch -M main
⑨git push -u origin main

方法二：
①在远程仓库上新建一个仓库，要求是必须和本地仓库同名
②git remote add origin https://github.com/hailang-wang/MyGitTest.git
③将自己的文件都复制到clone的仓库里
④git add .
⑤git commit -m ""
⑥git push
