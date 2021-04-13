[TOC]

# python-flask-docker

该模版演示基于 Python + Flask 实现全自动检出代码 -> 单元测试 -> 构建 Docker 镜像 -> 推送到 Docker 制品库 -> 部署到远端服务器

## 文件解释

样例包括:

- README.md - 本文件。项目概述及一些说明
- Dockerfile - 用以自动构建 Docker 镜像的脚本
- requirements.txt - 依赖包文件
- app.py - 主 Flask 服务器端源代码

## 快速开始

如下这些引导，假定你想在自己的电脑上开发本项目。

1. 安装依赖

```bash
$ pip3 install -r requirements.txt
```

1. 启动服务器

```bash
$ python3 app.py
```

1. 打开 <http://127.0.0.1:5000/> .
