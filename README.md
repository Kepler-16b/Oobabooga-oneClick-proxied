# Oobabooga-oneClick-proxied  
## 简介
通过修改Oobabooga的一键安装脚本来加速中国用户下载
修改了bat中的github链接，使用ghproxy代理加速。下载install.bat，替换一键安装包中的文件，并运行即可。

---
## 相关链接
- Oobaboooga-webui 仓库地址：https://github.com/oobabooga/text-generation-webui
- 一键安装包下载地址：https://github.com/oobabooga/text-generation-webui/releases/download/installers/oobabooga-windows.zip

---
## FAQ
1. 
问题：出现 “conda env setup failed” 错误提示导致进行中断

解决方法：删除 oobabooga-windows\installer_files 下的 env文件夹，重新运行 install.bat
