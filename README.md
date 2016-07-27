# Go语言
---

* 配置Go运行环境 <br>
  (以centos6.5安装go1.6.1为例)

1. 下载go安装包(http://www.golangtc.com/download)  <br>
    wget http://www.golangtc.com/static/go/1.6.1/go1.6.1.linux-amd64.tar.gz

2. 创建安装路径,并解压
    mkdir -p /usr/local/go  <br>
    tar -zxvf go1.6.1.linux-amd64.tar.gz -C /usr/local/go

3. 配置环境变量
   vi /etc/profile  <br>
   ![Image](https://github.com/honglongwei/go/blob/master/images/1.jpg)
 
4. 
