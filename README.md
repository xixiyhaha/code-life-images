# code-life-images

用于存放博客中的图片。

## 目录结构

```
images/
├── posts/    # 博客文章内容配图
├── cover/    # 博客文章封面图
└── common/   # 通用图片（如 logo、头像、背景等）
```

## 使用方式

将图片上传到对应目录后，可通过以下格式在博客中引用：

```markdown
![图片描述](https://raw.githubusercontent.com/xixiyhaha/code-life-images/main/images/posts/图片文件名)
```

## 命名规范

- 文件名使用小写字母、数字和连字符（`-`），不使用空格
- 建议按文章或日期归类，例如：`2024-01-post-title-image.png`
- 支持 `.png`、`.jpg`、`.jpeg`、`.gif`、`.webp` 等常见图片格式
