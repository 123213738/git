# git
how to use github
```bash
---git
yum install -y git
ssh-keygen -t rsa -b 4096 -C "123213738@qq.com"
more /root/.ssh/id_rsa.pub
cd ~/.ssh/

vi config
Host github.com  
User 123213738@xx.com  
Hostname ssh.github.com  
PreferredAuthentications publickey  
IdentityFile ~/.ssh/id_rsa  
Port 443


ssh -T git@github.com

git clone git@github.com:123213738/k8s
git add .
git commit -m "learn k8s"
git push -u origin master

创建文件夹的时候，只需要在newfile文件名后面加'/'
```
