# **Visual Studio Code 专篇**

VS code作为一款轻量级的编辑器相当滴好用，一个很大的原因就是其插件机制。通过安装插件来支持各种语言和各种功能，不要了就切割，避免了从一开始就拉拖大的。下面是我推荐的不同语言安装的插件和妙妙小用法，欢迎大佬补充纠错！

插件也是支持离线包的，可以在[官网](https://marketplace.visualstudio.com/)上下载。有些插件开源，也可以在诸如GitHub等地方找到Release

## Python

个人的开发环境和推荐都是VSCode+miniconda打一波。有可能的话去搞个Github Copilot也不是不行。你问我为什么不用Pycharm？因为我觉得Pycharm没有插件完备的VScode好用。

### Python

微软推出的Python语言支持插件，代码高亮、Jupyter Notebook、代码补全、虚拟环境控制等feature

已验证✔[Official offline Windows vsix](https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-python/vsextensions/python/2024.11.2024072301/vspackage?targetPlatform=win32-x64)

已验证✔[Official offline Linux vsix](https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-python/vsextensions/python/2024.11.2024072301/vspackage?targetPlatform=win32-x64)

### Pylance

微软推出的Python语言支持插件，主要是高亮和纠错还有跳转非常好使。光标hover就能出class的define,左Ctrl按住接左键能直接跳转到代码块。

内含在Python中（？）

### Python Debugger

也是微软官推，提供Python的调试支持，打断点，实时变量查看等，这一波连起来能薄纱Anaconda的Spider了（个人体验）


未验证❌(可下载✔)[Official offline Cross Platform vsix](https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-python/vsextensions/debugpy/2024.9.12041013/vspackage?targetPlatform=darwin-arm64)


### Jupyter
如题。不过我个人并不用Jupyter。听说搞数据分析和可视化的经常用？

已验证✔[Official offline Windows vsix](https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-toolsai/vsextensions/jupyter/2024.7.2024072301/vspackage?targetPlatform=win32-x64)

已验证✔[Official offline Linux vsix](https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-toolsai/vsextensions/jupyter/2024.7.2024072301/vspackage?targetPlatform=linux-x64)