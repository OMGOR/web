# web

```bash 
>ssh-keygen -t rsa -C "youremail@example.com"
# 使用sra加密验证，按照你的邮箱生成一对密钥
>git config --global user.name "John Doe"
# 获得和设置配置变量，设置你的用户姓名
>git config --global user.email johndoe@example.com 
# 获得和设置配置变量，设置你的用户邮箱
```

```bash
# 初始化git项目
git init
# 把所有文件加入版本管理
git add README.md
# 提交到本地仓库
git commit -m "first commit"
# 添加远程仓库
git remote add origin git@github.com:OMGOR/web2.git
# 推送到远程仓库
git push -u origin master
```
