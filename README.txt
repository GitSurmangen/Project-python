1.配置公钥
ssh-keygen -t rsa -C 仓库登录账号
2.C:\Users\用户名.ssh文件夹我们会发现，公钥和私钥已经生成 
3.检测是否配置成功
  ssh -T git@github.com
