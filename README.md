[English Version Click Here](https://github.com/Terry-Su/debug-react-source-code#quick-start)

> 如果这个项目对你有帮助，欢迎**点个Star支持作者！**

## 快速使用
### 方法1: 线上调试
![](https://terry-su.github.io/debug-react-source-code/example/assets/example-17.0.2.png)
访问地址：https://terry-su.github.io/debug-react-source-code/example/react-17.0.2


### （推荐）方法2：下载对应直接调试源码文件
优势是可修改源码，比如在源码中添加注释。
使用步骤：

1 . 在[Releases](https://github.com/Terry-Su/debug-react-source-code/releases)中选择要下载的版本。
![](https://terry-su.github.io/debug-react-source-code/assets/images/release-download-hint.png)

版本列表（持续更新）：
* [debug-react-source-code-18.1.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v18.1.0)
* [debug-react-source-code-18.0.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v18.0.0)
* [debug-react-source-code-17.0.2](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v17.0.2)
* [debug-react-source-code-17.0.1](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v17.0.1)
* [debug-react-source-code-17.0.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v17.0.0)
* [debug-react-source-code-16.14.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v16.14.0)
* [debug-react-source-code-16.13.1](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v16.13.1)
* [debug-react-source-code-16.6.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v16.6.0)

2 . 将压缩包解压后，用vscode打开该文件夹。vscode需安装[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)插件，用于在vscode对源码添加断点

3 . 安装依赖后，开启服务
```
npm install
```
```
npm start
```

4 . 在源码中添加断点，按F5启动调试即可
![](https://terry-su.github.io/assets/blogs/debug-react-source-code-in-special-way/vscode-example.png)

## 目录结构
目录结构为：
```
/react.development/
/react-dom.development/
/babel.js
/dependency-main.html
/dependency-react.html
/dependency-react-dom.html
/index.html
/index.js
```
其中，`index.js`即为调试入口文件。


## 实现原理
[“另辟蹊径搭建阅读React源码调试环境-支持所有React版本断点调试细分文件”](https://terry-su.github.io/cn/debug-react-source-code-using-special-method)

---
---
---

## Quick Start
### Method 1: Debug Online
![](https://terry-su.github.io/debug-react-source-code/example/assets/example-17.0.2.png)
Visit Url：https://terry-su.github.io/debug-react-source-code/example/react-17.0.2


### （Recommended）Method 2：Download Corresponding Files for Debugging Source Codes 
The advantage is that you can modify the source code, such as adding comments to it.
Usage Steps：

1 . Select version to download at [Releases](https://github.com/Terry-Su/debug-react-source-code/releases)。
![](https://terry-su.github.io/debug-react-source-code/assets/images/release-download-hint.png)

Version list（Update continuously）：
* [debug-react-source-code-18.1.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v18.1.0)
* [debug-react-source-code-18.0.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v18.0.0)
* [debug-react-source-code-17.0.2](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v17.0.2)
* [debug-react-source-code-17.0.1](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v17.0.1)
* [debug-react-source-code-17.0.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v17.0.0)
* [debug-react-source-code-16.14.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v16.14.0)
* [debug-react-source-code-16.13.1](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v16.13.1)
* [debug-react-source-code-16.6.0](https://github.com/Terry-Su/debug-react-source-code/releases/tag/v16.6.0)

2 . Unzip compressed file，then open folder using vscodevscode need to install extension:[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)，for adding breakpoints on source codes in vscode.

3 . After installing dependencies, start service
```
npm install
```
```
npm start
```

4 . Add breakpoints on source codes, then just press F5 to start debugging
![](https://terry-su.github.io/assets/blogs/debug-react-source-code-in-special-way/vscode-example.png)

## Directory Structure
Directory structure is：
```
/react.development/
/react-dom.development/
/babel.js
/dependency-main.html
/dependency-react.html
/dependency-react-dom.html
/index.html
/index.js
```
notice `index.js` is the entry file for debugging.


## How does this work
> Maybe you need google translate. 

[“Create an environment for reading and debugging the React source code in a different way - support debugging breakpoints subdivision files of all react versions”](https://terry-su.github.io/cn/debug-react-source-code-using-special-method)
