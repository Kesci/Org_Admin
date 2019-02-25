# Kernel内置工具包
K-Lab kernel中内置各类主流的机器学习、深度学习框架，集成了常见数据分析包，用户可以免除前期环境配置，直接开展分析工作。
工具包详情可以查看[K-Lab工具包](/ch8/chapter8.md)

K-Lab Kernel支持用户在与Kernel相连的Notebook中输入指令查看、安装和更新工具包。 
### 查看工具包
用户可在Notebook的Code Cell中键入相应指令查看预置的工具包。

* Python3 Kernel
```
!pip list --format=columns  #查看Kernel下所有预置的工具包
!pip show package_name      #查看Kernel是否有某个工具包
```

* Python2 Kernel    
```
!pip2 list --format=columns  #查看Kernel下所有预置的工具包
!pip2 show package_name      #查看Kernel是否有某个工具包
```

* R Kernel
```
pkgs <- installed.packages();
pkgs[is.na(pkgs[,"Priority"]), c("Package", "Version")]
installed.packages('package name')
```

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
!pip2 install package_name --upgrade #更新工具包。
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

**友情提示**：
* 手动安装好工具包后，请刷新页面，刷新后Kernel将完成工具包的更新部署。
* 用户自行安装的工具包不能被持久化，有持久化需求的工具包，可在K-Lab运行时内的帮助菜单下找到`工具包反馈 `，在弹出的对话框内填写工具包安装需求，我们将在2个工作日内给出答复。

![image description](/image/工具包反馈.png)  
