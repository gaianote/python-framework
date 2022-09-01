# python-framework
一个简单的 python 项目脚手架，用于快速的创建简单易用的 python 项目

1. 如果没有 cookiecutter,请先安装

```bash
pip3 install cookiecutter
```

2. 开始使用

```bash
cookiecutter https://github.com/gaianote/python-framework
# 输入项目名,中间不能带 - ,否则 pip install 会报错
project_name [pyframe]: chromespider
```

3. 安装 chromespider 框架 到本地

```bash
cd chromespider
pip3 install -e .
```

4. 查看是否成功

```bash
$ chromespider
hello world!
```
