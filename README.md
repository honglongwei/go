# Go语言
---

* ### 配置Go运行环境 <br>
  (以centos6.5安装go1.6.1为例)

1. 下载go安装包(http://www.golangtc.com/download)  <br>
    wget http://www.golangtc.com/static/go/1.6.1/go1.6.1.linux-amd64.tar.gz

2. 创建安装路径,并解压
    mkdir -p /usr/local/go  <br>
    tar -zxvf go1.6.1.linux-amd64.tar.gz -C /usr/local/go

3. 配置环境变量
   vi /etc/profile  <br>
   ![Image](https://github.com/honglongwei/go/blob/master/images/1.jpg)
 
4. 建立Go的工作空间（workspace，也就是GOPATH环境变量指向的目录）<br>
   GO代码必须在工作空间内。工作空间是一个目录，其中包含三个子目录：<br>
   src ---- 里面每一个子目录，就是一个包。包内是Go的源码文件  <br>
   pkg ---- 编译后生成的，包的目标文件   <br>
   bin ---- 生成的可执行文件。    <br>
   mkdir -p /home/go/src && mkdir -p /home/go/pkg && mkdir -p /home/go/bin
