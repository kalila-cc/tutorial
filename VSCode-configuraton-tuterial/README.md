## 傻瓜式配置 C/C++/VSCode (for Windows 10)

> 一个傻瓜式配置C/C++/VSCode 的编译运行环境的教程

> 若在本教程出现解压压缩包失败或解压出的文件夹为空的情况，请下载专业解压缩软件后进行解压缩，推荐下载[360压缩]( https://yasuo.360.cn/ )

### 观前提示
请先将本项目[下载]( https://github.com/kalilacc/VSCode-Installer/archive/main.zip )下来并解压，解压后找到名为 `VSCode-Configuration-tuterial` 的文件夹，以下简称项目文件夹。

### 下载资源

1. [点击下载 **mingw-w64**]( https://udomain.dl.sourceforge.net/project/mingw-w64/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/8.1.0/threads-posix/seh/x86_64-8.1.0-release-posix-seh-rt_v6-rev0.7z )，将下载所得压缩包**解压为同名文件夹**(不是解压到当前文件夹!)，并重命名该文件夹为 `mingw-w64`，将其移动至**D盘根目录**，随后删除该下载所得的压缩包
2. [点击下载 **VSCode**]( https://aka.ms/win32-x64-user-stable )，双击运行下载所得的 `.exe` 程序，并傻瓜式点击下一步，直至安装完成，随后删除该下载所得的 `.exe` 程序
3. 双击运行项目文件夹内的 `init.exe`，看见 `finished!`表示此步骤成功

### 安装插件

1. 打开 **VSCode**
2. 点击左侧第四个图标 **"扩展"**（或点击`Ctrl + Shift + X`）
3. 分别搜索`Chinese`, `code runner`并都取第一个搜索结果进行安装

### 设置插件

1. 点击左侧最后一个图标 **"管理"**，再点击 **"设置"**
2. 搜索 `Code-runner:Executor Map`，点击搜索结果的 **"<u>在settings.json中编辑</u>"**
3. 将项目文件夹内的 `settings.json` 文件内容**复制**进该文件，替换掉其内容，并进行保存（或点击`Ctrl + S`）

### 配置环境

1. 打开**文件资源管理器**，并右键 **"此电脑"**，点击 **"属性"**
2. 点击 **"高级系统设置"**，随后点击 **"环境变量"**
3. 在下方的 **"系统变量"** 找到 **"Path"** 或 **"PATH"**，并双击
4. 点击 **"新建"**，将 `D:\mingw-w64\mingw64\bin` 复制进去，并一路点击确定

### 新建项目（每次新建项目均用到）

1. 任意地方新建文件夹作为项目（推荐自己新建一个项目文件夹统一存放项目）
2. 将项目文件夹内的 **.vscode** 文件夹**复制**至该新建的文件夹
3. 打开 **VSCode**，点击左上角 **"文件"->"打开文件夹"**，找到新建的文件夹（即新建的项目）并打开
4. 往后随时在该项目文件夹内 **(不要在 `.vscode` 内!)** 新建 `.c` 或 `.cpp` 文件，即可直接编译运行

---

**有任何问题可以留言或咨询本人：wxid: cc3071927804**

**了解本人开发的更多作品请[点击这里]( https://github.com/kalilacc/Introduction )**

---
### 欢迎打赏
+ **欢迎一键三连(好评+打赏+收藏)，你的支持是作者维护下去的最大动力！**
+ [打赏通道]( https://s1.ax1x.com/2020/11/08/BTeRqe.png )

