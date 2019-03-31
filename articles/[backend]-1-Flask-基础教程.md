# Flask基础教程

## 先决条件

请先配置[Python基本开发环境](./[python]-1-Python-开发环境配置指南.md)。

## 创建 Python3.6 虚拟环境

> 为什么不使用 Python3.7？
>
> Python3.7 虽然在语法上与 Python3.6 相兼容，但是由于 Python3.7 发布时间仍较短，许多Python Package仍未提供 Python3.7 的构建版本，因此，目前仍建议使用 Python3.6 进行开发工作。

1. 新建项目目录 `dms-flask-server` 。
2. 进入该目录, 打开命令行工具，使用以下命令创建 python3.6 虚拟环境 `pipenv --python=3.6` 。
3. 使用 `pipenv install [package_name]` 命令安装以下依赖库。
   - Flask
   - Flask_CORS



