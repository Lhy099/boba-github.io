# Lhy099 博客

基于 Hugo + GitHub Pages 的个人博客。

## 访问地址

- GitHub Pages: https://lhy099.github.io/

## 本地开发

```bash
# 安装 Hugo
# 启动开发服务器
hugo server -D

# 新建文章
hugo new content posts/文章标题.md
```

## 发布流程

1. 编辑 `content/posts/` 下的文章
2. 提交到 main 分支
3. GitHub Actions 自动部署

## 技术栈

- [Hugo](https://gohugo.io/) - 静态网站生成器
- [Ananke Theme](https://github.com/theNewDynamic/gohugo-theme-ananke) - 主题
- GitHub Pages - 托管
