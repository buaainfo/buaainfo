# 本文档编写规则

## 开始

### Fork仓库

首先，您应当从我们的 [Github](https://github.com/buaainfo/buaainfo "仓库") fork我们的仓库至您的账号，这样方便您在本地调试文档，以及保障本文档的质量。

### 安装必要依赖

开始之前，我们认为您已经懂得一定的 [python](https://www.python.org/) 语言以及 [markdown](https://www.markdownguide.org/) 语言，并且在您的电脑上安装 [python 3.x](https://www.python.org/downloads/) 版本。

对于本文档，需要您安装必要的库。

```py
pip install \
              mkdocs-material \
              mkdocs-awesome-pages-plugin \
              jieba \
              mkdocs-glightbox \
              mkdocs-git-revision-date-localized-plugin \
              mkdocs-git-authors-plugin \
```

## 编写

### 了解本文档的结构

在编写开始时，您应当了解此文档的结构，这样有利于您的push被我们接受。

您可以查看本项目下的 [tree.txt](https://github.com/buaainfo/buaainfo/blob/main/docs/tree.txt) 文档，或者 [mkdocs.yml](https://github.com/buaainfo/buaainfo/blob/main/mkdocs.yml) 的 nav 部分，这样方便您了解我们的大致框架，您可以发现我们更推荐创立单个的md文件，我们建议通过**关键词**来进行命名。

### 编写文档

本文档使用 [markdown](https://www.markdownguide.org/) 语言，请按照 [markdown](https://www.markdownguide.org/) 语言规范进行编写。

除此之外，您可以通过本框架官方的 [docs](https://squidfunk.github.io/mkdocs-material/reference/) 文档，通过调用非官方markdown语言来进行美化或者更直观的表达。

此外，您应当了解您有权利和义务编写的内容：

* **在目录下创建新的md文件进行编写**
* **在 [mkdocs.yml](https://github.com/buaainfo/buaainfo/blob/main/mkdocs.yml) 中的nav部分添加您的文档的名称及位置**

### 本地浏览

mkdocs允许您在编写文档的同时进行本地预览，这样能帮助您避免BUG的产生。

```
mkdocs serve
```

### 图片

在使用该项目的同时，我们希望您上传图片到长期维护的图床中，或者上传到[此项目中](images)。为了保证此文档的质量和长期使用性，请不要在本文档中引用不可靠的图床链接。

## 提交

请注意，在提交之前检查您的文档编写是否出错（尽管我们还会再检查一次），此外，您还应当检查是否有修改我们的配置文件，我们不接受修改配置文件的pr（当然您可以[联系我们](mailto:buaainfo@proton.me)进行建议）。

一般来说，我们会尽量在当天对您的pr进行审核。

## 最后

此文档是一份公益性文档，对于每一位贡献于此文档的朋友，我们代表所有使用该文档的师生朋友感谢您的无私付出。
