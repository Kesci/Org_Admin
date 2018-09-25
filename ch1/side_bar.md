# 侧边栏
K-Lab的侧边栏包含了**文件树**、**数据集**、**代码片段**与**项目目录**几个功能。

## 文件树
文件树支持用户在侧边栏直观地查看`/home/kesci`路径下的文件，可以在该路径下创建新的文件目录、上传文件，如果在代码运行过程中磁盘里的文件更新了，可以手动刷新在侧边栏查看文件更新的状态。上传的单个文件最大**20M**，每次至多上传**5个**文件。

![image description](/image/文件树.png)

## 数据文件目录
当前项目挂载的数据集信息（数据集大小，文件路径，etc）可以在数据集一栏直接查看，点击文件名能够预览csv与zip格式的文件内容。

![image description](/image/dataset-preview.png)

## 代码片段
K-Lab提供代码片段功能来提升用户的编程效率，用户可以在该区域进行数据分析常用代码知识库的整理，并在编写代码时快速插入使用。代码片段分为**公有库**和**我的收藏**。

* 公有库：公有库为官方预置的数据分析、机器学习的常用代码。        

![image description](/image/code-storage.png)

* 我的收藏：用户在code cell收藏的的代码片段将在该区域呈现。

![image description](/image/code-favourite.png)

## 项目目录
在Notebook中添加Markdown标题，侧边栏内将自动生成可点击的项目目录。点击标题即可跳转到相应的内容板块。

![image description](/image/项目目录.png)
