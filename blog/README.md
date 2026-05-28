# 博客资源

这里存放 Hexo 博客专用的静态资源。

## 目录结构

```text
img/covers/default/        全站默认文章封面池
img/posts/<post-slug>/     单篇文章专属图片
img/pages/about/           关于页图片资源
img/screenshots/           博客截图和预览图
js/pages/                  页面级脚本
```

文章专属封面和文章正文图放在同一个文章目录：

```text
img/posts/<post-slug>/cover.webp
```

新文件名优先使用小写英文、数字和短横线。

## PicGo 建议

文章图片推荐的 GitHub 基础路径：

```text
blog/img/posts/
```

如果使用按本地目录生成云端路径的 PicGo 插件，应让本地文章 slug 目录参与生成路径，使上传结果落到：

```text
blog/img/posts/<post-slug>/
```
