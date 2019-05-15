## centos一键前端环境搭建
## 实现功能
  1. 更新yum源为阿里云源
  2. nodejs10 lts 最新版本
  3. yarn 最新版本
  4. git 2.21.0 编译安装
  5. 卸载centos自带的 mariadb-libs 并安装mysql 8.0.15
  6. nginx 最新版本安装
  7. acme.sh 自动申请ssl证书
  8. 添加nginx，mysql服务为开机启动
## 准备
- centos 7.0 以上系统
- 将域名解析到本机ip
- 需要使用root权限执行该脚本