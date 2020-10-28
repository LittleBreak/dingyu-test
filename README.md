创建workspace
根目录上的package.json上添加两个字段
private": true,
workspaces
在指定的workspace里执行npm init -y，成为一个包的目录结构

yarn workspace awesome-package add react react-dom --dev

进入workspaces的子目录install，没特殊情况的话，会把这个包安装到根目录上