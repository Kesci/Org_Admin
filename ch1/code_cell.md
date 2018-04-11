# Code Cell
Code Cell是Notebook的代码编写单元。用户在Code Cell内编写代码（目前K-Lab支持**Python2**、**Python3**和**R**等主流编程语言），代码由后端的Kernel运行，并返回结果到Code Cell。通过这样一个工作流，用户来**解决数据分析中如数据导入、模型搭建、数据可视化、参数调优等问题**。    


Code Cell有**编辑模式**和**命令模式**两种状态，状态可以相互切换：编辑模式下，按`Enter`键进入命令模式；命令模式下，按`Esc`键进入编辑模式。

* **编辑模式**：表示该cell允许被编辑，界面上显示cell单元框线为绿色，即用户可以在cell中键入代码或注释。
 ![image description](/image/code-cell-green.png)

* **命令模式**：表示该cell允许被执行，界面上显示cell的单元框线为蓝色，即用户可以通过点击`运行`按钮或快捷键`Shift + Enter`来运行cell。
  ![image description](/image/code-cell.png)

**Code Celll工具栏**：K-Lab的Code cell支持独有的沉浸模式，美化代码，代码片段功能，提高用户的代码编写效率。
* **沉浸模式**：K-Lab Code cell支持在沉浸模式下编写代码，让用户更专注于数据分析工作，不受打扰。
*  **美化代码**：K-Lab提供基于通用的PEP 8 规范的python代码美化，提升代码可读性。
* **代码片段**：K-Lab提供插入和收藏代码片段功能来减少用户在数据分析过程中重复思考和搜索代码的时间。
