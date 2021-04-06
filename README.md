 echo "# jwu" >>README.md
 git init 
 git add README.md   //git add 1.c 2.c 等等
 git commit -m "first commit"  //真正的提交，需加-m 写提交信息
 git branch -M master
 git remote add origin git@github.com:Jerry-jwu/jwu.git
 git push -u origin master  //git push 同步远程仓库
