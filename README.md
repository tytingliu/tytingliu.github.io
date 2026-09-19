# 个人博客
基于 Jekyll + GitHub Pages 搭建的个人博客。

## 使用方式
1. 在 `_posts` 目录新建文章，文件名格式：`YYYY-MM-DD-文章标题.md`
2. 图片放到 `assets/images/`，文章引用：`![描述]({{ site.baseurl }}/assets/images/xxx.png)`
3. 提交代码 push 到 GitHub，自动部署到 GitHub Pages

## 本地预览
```bash
jekyll serve
