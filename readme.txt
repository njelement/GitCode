1）首先设置用户名和邮箱地址（本地设置，建立了一个本地库，与网络端无关）
git config --global user.name "njelement"
git config --global user.email "adsl.com@163.com" 
git init
至此，一个本地git仓库建立完成。可以使用
git status查看仓库状态。可以使用
git add . 添加文件/文件夹到暂存区。可以使用
git commit . -m "版本注释" 提交暂存区文件/文件夹到仓库中。

2）