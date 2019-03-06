"# gittest" 
git checkout -b develop2 //创建一个分支develop2
git commit -a -m test3  //-a = -all
git push origin develop //git push <远程主机名> <本地分2支名>  <远程分支名>

git checkout master 切换到master
git merge --squash develop2
git commit -a -m develop2
git push origin master
git branch -D develop2

git push origin develop3  //develop3 -> develop3 (non-fast-forward) push之前develop3已经被修改了
git pull -r origin develop3  //
git push origin develop3

4
5
6
7
8
9
10
11
12



