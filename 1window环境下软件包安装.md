1. 安装 NodeJs
	1. https://npm.taobao.org/mirrors/node/v10.15.0/node-v10.15.0-x64.msi
2. 安装 cnpm 以使用淘宝镜像
	1. npm install -g cnpm --registry=https://registry.npm.taobao.org
3. 如果已经安装，可以查看cli版本号
	1. vue --version
4. 全局安装 vue-cli，并查看版本号
	1. cnpm install --global vue-cli（安装后需要重启cmd或PowerShell）
	2. vue --version
5. 在 cmd 下执行 vue --version 正常(2.9.6)，但在 PowerShell 下执行出现报错：……vue.ps1，因为在此系统上禁止运行脚本
