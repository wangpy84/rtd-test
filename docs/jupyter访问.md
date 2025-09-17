
# Jupyter访问容器实例
平台集成 Jupyter 作为一个Web化的集成开发环境（IDE），并通过浏览器来提供访问入口，支持用户创建和共享实时代码、文档等。

- 平台已在实例启动时内置 Jupyter 服务，用户无需进行服务安装与开启。
- 当容器实例状态为“运行中”时，用户可使用“Jupyter”开发工具。

## 使用Jupyter
1.登录控制台，进入 产品中心 -> 计算 -> 云容器实例页面。  
2.点击开发工具一栏中的 `Jupyter`
![alt text](..\images\jupyter01.jpeg)  

3.进入Jupyter工具界面。
![alt text](..\images\jupyter02.jpeg)  

左侧为文件目录，右侧为工作区。
>这个界面运行于当前连接的容器实例内部。  
在这里执行的所有操作，都等同于在容器内执行。  

4.可在界面中进行文件管理、使用Notebook、访问终端。

### 文件管理
1.在文件浏览区可进行文件管理。
![alt text](..\images\jupyter03.jpeg)

2.点击文件浏览区中的相关标识可创建文件夹、上传文件。

### 使用Notebook
在工作区域，点击 Notebook 可打开窗口。
![alt text](..\images\jupyter06.png)

### 访问终端
在工作区域，点击 Other -> Terminal 可打开一个终端。
![alt text](..\images\jupyter05.jpeg)