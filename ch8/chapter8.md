# K-Lab工具包
### 安装、升级工具包
用户可在Notebook的Code Cell中键入相应bash指令安装、更新所需要的工具包
* Python3 Kernel
```
!pip install package_name==version #安装工具包
!pip install package_name --upgrade #更新工具包
```
* Python2 Kernel
```
!pip2 install package_name==version #安装工具包
!pip2 install package_name --upgrade #更新工具包
```

* R Kernel
```
install.packages(package_name) #安装工具包。
```

* 如果要安装系统软件包，请使用以下命令：
```
!sudo apt-get update
!sudo apt-get install cowsay
!/usr/games/cowsay -f ghostbusters Who you Gonna Call
```

### 更改工具包下载镜像
* 在Python3环境下，使用以下命令：
```
!pip install package_name -i https://pypi.douban.com/simple/ #从指定镜像下载安装工具包，镜像URL可自行修改
```
* 在R环境下，使用以下命令：
```
install.packages('package_name')
options("repos" = c(CRAN="https://mirrors.tuna.tsinghua.edu.cn/CRAN/"))#从指定镜像下载安装工具包，镜像URL可自行修改
```
### 查看K-Lab Kernel内置的全部工具包：

* [Python3 工具包](./py3.md)
* [Python2 工具包](./py2.md)
* [R 工具包](./r.md)
