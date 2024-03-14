# EFK-dockercomposed
构建dockercompose来快捷部署EFK日志收集系统

# 结构
```text
.
├── docker-compose.yml
└── fluentd
    ├── conf
    │   └── fluent.conf
    └── Dockerfile
```
# 使用说明
需提前安装docker,以及docker-compose部件

在`efk_01`文件架下,使用`docker-compose up -d`进行一键安装

# 版本:
ES:7.13.1

fluentd: 1.12-debian-1

kibana: 7.13.1

