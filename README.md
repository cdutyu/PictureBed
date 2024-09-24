---
​---
vlook-chp-autonum: h1{{第#zh#章}},h2{{###}},h3{{###}},h4{{###}},h5{{###}}
​---

---

[TOC]

---

## 创建仓库

1. 在[GitHub](https://github.com/)创建一个公有仓库

2. 在仓库添加一个文件夹作为图片保存位置

---

## 配置PicGo

1. [下载PicGo](https://mirrors.sdu.edu.cn/github-release/1712122460/github-release/Molunerfinn_PicGo/v2.3.1/)
2. 安装[PicGo](https://picgo.github.io/PicGo-Doc/zh/)
3. 打开`PicGo`>>`PicGo设置`>>`开启时间戳重命名`选项
4. 打开`PicGo`>>`图床设置`>>`GitHub图床`
5. 填写`GitHub设置`

* 设定仓库名:`GitHub用户名/仓库名`
* 设定分支名:`分支名`，一般填`main`
* 设定Token:在[GitHub的开发者设置](https://github.com/settings/tokens)中选择`Generate new token (classic)`：有效期设置为`无有效期`，`设置作用域(Select scopes)`仅勾选`repo`。复制token并填入该`设定Token`位置
* 指定存储路径:`仓库中图片保存位置对应文件夹路径`
* 设定自定义域名:`https://cdn.jsdelivr.net/gh/GitHub用户名/仓库名/`

6. 点击`设置为默认图床`和`确定`


---

## Typora自动上传图片

上述操作已经完成图床搭建，Typora用户可以按以下步骤实现Typora插入图片时自动上传图床

1. 打开`Typora`>>`偏好设置`>>`图像`

2. 按下面内容更改设置,其中`PicGo`路径改为`PicGo.exe`的安装位置

![](https://cdn.jsdelivr.net/gh/sername531/PictureBed/image/202409231903142.png)

---

## 声明

### 作者

- [CSDN@智科不编程](https://blog.csdn.net/qq_74251965?type=blog)
