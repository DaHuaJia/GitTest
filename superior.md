# git 命令进阶

### 换行
> 末尾两个空格然后换行即可实现渲染之后的换行效果

### 每次git push 操作都需要输入账号密码 解决办法
> 主要原因是使用了https连接方式，改成ssh即可。
> 1. 查看连接方式 git remote -v。https开头表示是https，git开头表示是ssh
> 2. 删除原来的连接方式 git remote rm origin
> 3. 去github复制ssh连接方式！
> 4. 添加ssh连接，git remote add origin git@github.comxxxxxxxx
> 参考地址：https://www.cnblogs.com/sky6862/p/7992736.html
> 注意: git和github没有绑定ssh密匙，需要绑定，操作百度即可。
