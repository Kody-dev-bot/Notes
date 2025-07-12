
> Git是分布式的代码管理工具，远程的代码管理是基于SSH的，所以要使用远程的Git则需要SSH的配置。

github的SSH配置如下：
1. 设置Git的user name和email
```bash
git config --global user.name kdoy
git config --global user.email zj.wang.work@zohomail.cn
```
2. 生成SSH密钥过程：
```bash
ssh-keygen -t rsa -C "zj.wang.work@zohomail.cn"
```
