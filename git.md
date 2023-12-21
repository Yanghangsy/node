```bash
//git默认远程库名称为origin
$ git remote rm origin
//关联github并设置别名为github
$ git remote add github @git/github.com:admin/demo.git
推送到GitHub
$ git push github master
//配置用户名及其邮箱
$ git config --global user.name "Tony"
$ git config --global user.email "Tony@gmail.com"
//初始化本地仓库
$ git init
//生成ssh密钥
$ ssh-keygen -t rsa -C "你的邮箱名"


```

