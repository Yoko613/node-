#  node特定版本安装


### 1.在官网查找相应的版本压缩包 tar.gz

  官网地址：https://nodejs.org/dist/
### 2.服务器下载压缩包
  linux命令：
    wget 【node版本压缩包】| 
    实例：wget https://nodejs.org/dist/v4.6.2/node-v4.6.2-linux-x64.tar.gz
  解压文件：tar -zxvf node-v4.6.2-linux-x64
  node文件下找到bin文件夹- node ，npm 两个文件
### 3.node软链接全局安装

  ln -s /home/kun/mysofltware/node-v4.6.2-linux-x64/bin/node /usr/local/bin/node
  ln -s /home/kun/mysofltware/node-v4.6.2-linux-x64/bin/npm /usr/local/bin/npm
  *** /home/kun/mysofltware/这个路径是你自己放的，你将node文件解压到哪里就是哪里。
  
### 4.查看node是否全局安装
  node -v
  
  npm -v

