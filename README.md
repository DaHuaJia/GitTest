# GitTest git练习

### 将一段话输入到README.md 中
echo "# GitTest" >> README.md

### 初始化git
git init

### 提交所有文件 提交部分文件是 git add <文件名>
git add . 

### 添加提交日志
git commit -m "first commit"

### 添加远程仓库地址
git remote add origin https://github.com/DaHuaJia/GitTest.git

### 将提交的代码推送至远程仓库
git push -u origin master

### 将代码从命令行同步至本地
git pull

### 将git 上的包下载至本地
git clone https://github.com/DaHuaJia/GitTest.git

### 配置全局变量，将账号和密码设置为全局变量
git config --global.name "1158805583@qq.com"   
git config --global.password "xxxxxxxxxx"

2019年12月13日12:07:36
