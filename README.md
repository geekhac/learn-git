# learn-git
1. 在master分支上远程修改，本地pull 并解决冲突
2. 新建了1分支，并添加了a文件
3. 修改master远程的readme文件，在a分支上```git pull --rebase origin master```,发现本地的1仓库reademe文件也被修改了,1分支合并了master远程的更新
4. 执行 ```git reset --hard origin```, 本地1分支和远程的master同步，没有了a文件
5. ```git pull --rebase origin 1``` ,远程的1分支并没有改变，而1本地合并了1远程的分支，又有了a文件，reademe和master是同步的
