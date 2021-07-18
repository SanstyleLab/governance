# Sanstyle 项目管理

[![GitHub issues](https://img.shields.io/github/issues/SanstyleLab/governance)](https://github.com/SanstyleLab/governance/issues) [![GitHub forks](https://img.shields.io/github/forks/SanstyleLab/governance)](https://github.com/SanstyleLab/governance/network) [![GitHub stars](https://img.shields.io/github/stars/SanstyleLab/governance)](https://github.com/SanstyleLab/governance/stargazers) [![GitHub license](https://img.shields.io/github/license/SanstyleLab/governance)](https://github.com/SanstyleLab/governance/blob/main/LICENSE)  ![repo size](https://img.shields.io/github/repo-size/SanstyleLab/governance.svg) [![contributors](https://img.shields.io/github/contributors/SanstyleLab/governance.svg)](https://github.com/SanstyleLab/governance/graphs/contributors) [![watcher](https://img.shields.io/github/watchers/SanstyleLab/governance.svg)](https://github.com/SanstyleLab/governance/watchers) ![](https://github.com/SanstyleLab/governance/actions/workflows/docs.yml/badge.svg)


本项目借鉴于 [jupyter/governance: The governance process and model for Project Jupyter](https://github.com/jupyter/governance)。

这个存储库的目的是将 Sanstyle 项目自 2021 年创建以来非正式使用的治理过程正式化。本文档阐明了决策是如何做出的，以及我们社区的各种元素是如何相互作用的，包括开源协作开发和可能由营利性或非营利性实体资助的工作之间的关系。

## 导航

```{tableofcontents}
```

## Sanstyle 组织与仓库

GitHub 上的 Sanstyle 组织与仓库见：[资源库](https://xinetzone.github.io/sanstyle-book/about.html)。

## 基础结构

这个存储库中的内容是用 `github-pages` 在线托管的，HTML 文件是用 [sanstyle-starter](https://github.com/xinetzone/sanstyle-starter) 构建的。要在本地构建和预览这些文档，请安装最新版本的 Jupyter Book：

```
pip install -U git+https://github.com/executablebooks/jupyter-book.git
```

并以以下方式构建这本书：

```
cd path/to/this/repo
jupyter-book build .
```

生成的网站将在 `_build/html` 中，你可以通过打开创建的任何 `.html` 文件来浏览它。
