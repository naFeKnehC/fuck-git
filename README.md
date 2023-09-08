# fuck-git
git学习 分享

# 配置
git config –global user.name "xxxxx"
git config –global user.email "xxx@xx.xxx"

注：查下是否配置成功，用命令
git config --global --list

# 生成秘钥
ssh-keygen -t rsa -C  "上面的邮箱"
注：执行上面命令后，连续回车3次

# 获取ssh-key
cd ~/.ssh
cat id_rsa.pub