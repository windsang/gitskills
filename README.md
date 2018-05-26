# gitskills
Here is the git skills

1. 使用git@github.com是通过SSH连接的, 因此, 必须先设置SSH, 参考https://blog.csdn.net/mbuger/article/details/70226712
2. 使用完整的url路径, 是通过https连接的, 每次都需要输入用户名和密码, 如:https//github.com/windsang/gitskills.git
3. 如果git Clone时使用了https的链接, 那么无法使用SSH进行Push, 必须将本地repo目录.git/config修改为SSH的链接,
   即git@github.com:username/projectname.git
