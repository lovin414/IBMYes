## 使用许可 | Licences
本项目仅用于学习 Github Action/IBM Cloud Shell 和在法律允许范围内的使用，任何个人或集体不得使用本项目进行任何违反您所在地区的相关法律法规的活动。任何尝试下载、本地克隆或远程克隆本项目的任意分支，以及使用本项目内的任何代码片段即代表您同意本项目作者及贡献者不承担任何由于您违反相关法律法规所带来的任何法律责任。

This project can ONLY be used for learning Github Action/IBM Cloud Shell and use within the scope permitted by law. Any individual or group MAY NOT use the project for any violation of relevant laws and regulations of your region. Any attempt to download of any branch or clone the project, fork your own copy, use any code from the project constitutes your agreement that the author and the contributor of the project will not be liable for any legal liability arising from your violation of relevant laws and regulations.

## 本项目在[原项目](https://github.com/CCChieh/IBMYes)的基础上新增有：
+ 自动查找最新版本的二进制文件进行安装
+ 安装过程中可由用户输入自定义的 UUID, Websocket路径 以及 连接内部缓存大小
+ 接上一条，若不输入则生成随机 UUID以及 Websocket Path并自动配置
+ 安装结束后在 IBM Cloud Shell中输出相应的 vmesscode链接方便用户配置
+ 在服务端配置中新增[本地策略](https://www.v2fly.org/chapter_02/policy.html)，可用于优化连接质量，减少不必要的资源占用
+ 新增升级脚本(upgrade.sh), 可用于在保留原配置的情况下对二进制文件进行版本更新

## TODO
+ 利用Github Actions实现自动更新二进制文件
