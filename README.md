# jerry-fage-static

Jerry-FaGe 的静态资源仓库。

## 目录约定

```text
blog/     博客专用资源，对应 blog.jerryfage.top / Jerry-FaGe.github.io
shared/   多个项目可复用的通用资源
img/      旧版博客图片路径，迁移完成前暂时保留
js/       旧版博客脚本路径，迁移完成前暂时保留
```

后续新增项目资源时，优先建立独立的顶层目录，避免继续把文件直接堆在仓库根目录下。

## 访问地址

```text
https://cdn.jsdelivr.net/gh/Jerry-FaGe/jerry-fage-static@master/<path>
```

已经发布并被引用的文件尽量视为不可变资源。如果资源内容需要替换，优先使用新文件名或新路径，避免 CDN 缓存导致旧内容继续生效。

## 迁移说明

当前 `blog/` 下的新结构是博客资源的新归档位置；旧 `img/`、`js/` 路径会在博客引用全部替换并验证无误后再删除。
