<p align="center">
  <a href="https://github.com/itcoffee66/githubweekly">
    <img src="asset/it-coffee-circle.png" alt="IT咖啡馆" width="128" />
  </a>
</p>

## githubweekly

GitHub一周热点汇总，每周分享热门项目，B站、YouTube发布视频版本，搜：IT咖啡馆   

> 🏗️ 本站基于 [Jekyll](https://jekyllrb.com/) + [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 主题构建，通过 GitHub Actions 自动部署。

### 往期内容

- 第103期：[4000行代码的openclaw能用吗](post/103.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/103.html)
- 第102期：[全球爆火的AI助理真的那么好用吗？](post/102.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/102.html)
- 第101期：[IT咖啡馆的Github一周热点上线了](post/101.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/101.html)
- 第100期：[火爆的AI编程代理](post/100.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/100.html)
- 第99期：[提升Claude code效率10倍的工具？](post/99.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/99.html)
- 第98期：[AI文档检索框架](post/98.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/98.html)
- 第97期：[自动操作手机的智能助手](post/97.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/97.html)
- 第96期：[FLUX发布了新一代，但似乎没那么惊艳了](post/96.md) | [在线阅读](https://itcoffee66.github.io/githubweekly/asset/html/96.html)

## RSS 订阅

使用 RSS 订阅软件可以快速知道本周 GitHub 热点项目

订阅地址：[https://itcoffee66.github.io/githubweekly/rss.xml](https://itcoffee66.github.io/githubweekly/rss.xml)

## 项目结构

```
├── _weekly/         # Jekyll 集合源文件（保留原始文件名：96.md, 97.md, ...）
├── _config.yml      # Jekyll 站点配置
├── _tabs/           # Chirpy 主题导航页（关于、归档、分类、标签）
├── _data/           # 站点数据文件（联系方式、分享按钮等）
├── asset/           # 静态资源（图片、Logo 等）
├── post/            # 原始 Markdown 源文件（供 GitHub 浏览）
├── scripts/         # 旧版 Python 脚本（已停用）
├── Gemfile          # Ruby 依赖声明
└── .github/workflows/
    └── pages-deploy.yml  # GitHub Actions 自动部署工作流
```

## 本地开发

```bash
# 安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve

# 访问 http://127.0.0.1:4000/githubweekly/
```

## 新增文章

在 `_weekly/` 目录下创建新文件，文件名即期号，如 `104.md`：

```yaml
---
title: "GitHub一周热点第NNN期"
date: "YYYY-MM-DD"
description: "本期摘要"
---

正文内容...
```
