# 一、创建仓库

1. 在 [GitHub](https://github.com/) 创建一个公有仓库

2. 在仓库添加一个文件夹作为图片保存位置

---

# 二、配置 PicGo

1. [下载 PicGo](https://mirrors.sdu.edu.cn/github-release/1712122460/github-release/Molunerfinn_PicGo/v2.3.1/)
2. 安装 [PicGo](https://picgo.github.io/PicGo-Doc/zh/)
3. 打开 `PicGo` >> `PicGo设置` >> `开启时间戳重命名` 选项

---

# 三、配置图床

## （一）GitHub 图床

1. 打开 `PicGo` >> `图床设置` >> `GitHub图床`
2. 填写 `GitHub设置`

* 设定仓库名: `GitHub用户名/仓库名`
* 设定分支名: `分支名`，一般填 `main`
* 设定 Token: 在 [GitHub 的开发者设置](https://github.com/settings/tokens) 中选择 `Generate new token (classic)`：有效期设置为 `无有效期`，`设置作用域(Select scopes)` 仅勾选 `repo`。复制 token 并填入该 `设定Token` 位置
* 指定存储路径: `仓库中图片保存位置对应文件夹路径`，例如`image/`
* 设定自定义域名: `https://cdn.jsdelivr.net/gh/GitHub用户名/仓库名/`

3. 点击 `设置为默认图床` 和 `确定`

---

# 四、Typora 自动上传图片

上述操作已经完成图床搭建，Typora 用户可以按以下步骤实现 Typora 插入图片时自动上传图床

1. 打开 `Typora` >> `偏好设置` >> `图像`

2. 按下面内容更改设置, 其中 `PicGo` 路径改为 `PicGo.exe` 的安装位置

![](https://cdn.jsdelivr.net/gh/sername531/imgur//image/202404031505522.png)

---

# 五、声明

## （一）作者

- [CSDN@智科不编程](https://blog.csdn.net/qq_74251965?type=blog)
