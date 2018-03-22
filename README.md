# my_config
常用快捷命令

# 安装 wget
yum install wget

# 进入用户目录，用wget命令下载
cd ~
wget --no-check-certificate https://raw.githubusercontent.com/Lee19820206/my_config/master/comm_alias

# 覆盖~/.bashrc文件
mv comm_alias ./.bashrc

# 让.bashrc文件马上生效
source .bashrc

# ebp编辑该文件
# sbp让快捷命令立即生效
