# learn-git
1. 在master分支上远程修改，本地pull 并解决冲突
2. 新建了1分支，并添加了a文件
3. 修改master远程的readme文件，在a分支上pull --rebase,发现本地的1仓库reademe文件也被修改了,1分支合并了master远程的更新
4. 执行 ```git reset --hard origin```, 本地1分支和远程的master同步，没有了a文件
