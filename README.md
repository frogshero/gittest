"# gittest" 
git checkout -b develop2 //创建一个分支develop2
git commit -a -m test3  //-a = -all
git push origin develop //git push <远程主机名> <本地分2支名>  <远程分支名>

git checkout master 切换到master
git merge --squash develop2
git commit -a -m develop2
git push origin master
git branch -D develop2

1
2
3
4
