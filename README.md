# Maze-pathfinding-using-pygame-display
西安邮电大学智能科学与技术课设。   使用pygame作为可视化显示界面，mazelab包作为迷宫生成算法（迷宫生成是随机的）。

首先在设置界面 设置迷宫大小、迷宫类型、选用深度/广度优先算法(A* 作为扩展算法，在迷宫界面可以切换)，
在迷宫界面，可以看到迷宫寻路的过程，当前算法的步数等，以及算法切换。
可选择使用深度优先、广度优先、A*可视化

## 环境
**Python 3.8.8**  
**pygame 2.0.1** (SDL 2.0.14, Python 3.8.8)  
**mazelab** 项目链接（按介绍可安装） https://github.com/zuoxingdong/mazelab.git  
## 文件结构
**source:** 贴图、两个英文字体库、图标  
**findpathing.py:** 三种迷宫寻路算法。深度优先，广度优先，A* 算法  
**mazeMap:** 使用 _mazelab_ 生成迷宫  
**gui：** 界面显示（运行这个就行）  
其他文件没有用 :joy:  
## 可执行文件
可以使用 _py2exe_ 生成可执行文件(.exe)
但是生成的整个文件很大，有900+M

## 界面
界面只有三个: 开始界面、 设置界面、 迷宫界面   
### 开始界面  
![image](https://github.com/Rainbow452/Maze-pathfinding-using-pygame-display/blob/main/img/1.png)  
### 设置界面  
![image](https://github.com/Rainbow452/Maze-pathfinding-using-pygame-display/blob/main/img/2.png)  
### 迷宫界面  
![image](https://github.com/Rainbow452/Maze-pathfinding-using-pygame-display/blob/main/img/3.png)  
