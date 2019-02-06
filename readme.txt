1）首先设置用户名和邮箱地址（本地设置，建立了一个本地库，与网络端无关）
git config --global user.name "njelement"
git config --global user.email "adsl.com@163.com" 
git init
至此，一个本地git仓库建立完成。可以使用
git status查看仓库状态。可以使用
git add . 添加文件/文件夹到暂存区。可以使用
git commit . -m "版本注释" 提交暂存区文件/文件夹到仓库中。

2）与网络库建立关联（前提是已经在相应网站注册，并建立仓库），首先使用ssh-keygen产生密钥对
ssh-keygen -t rsa -C "adsl.com@163.com"
然后将生成的公钥拷贝到网络端（具体步骤为图形化操作步骤，不再赘述。一台机器仅需要一个密钥即可，不同的目录不用重复生成）

3）将本地仓库与远程仓库建立联系
git remote add origin git@github.com:njelement/GitCode.git
远程仓库名称这里命名为origin。

4）推送到远程仓库，使用-u是建立联系，此后再次推送可不必再使用远程地址/仓库名称
git push -u origin master

5）多分枝功能，使用git brance指令，配以不同的开关参数
git branch 查看当前分支状态（列表所有分支）
