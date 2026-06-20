# puppyhat.org

`andersonpson.github.io` 是 `puppyhat.org` 的 Jekyll 博客源码仓库。

## 结构

- `_posts/`: 已发布文章与图集内容
- `assets/images/`: 站点与文章使用的图片素材
- `assets/css/main.scss`: 当前站点实际使用的主样式
- `_layouts/`、`_includes/`: 页面布局与公共片段
- `category/`: 分类页模板
- `_config.yml`: 站点配置

## 本地构建

1. 安装依赖：`bundle install`
2. 本地预览：`bundle exec jekyll serve`
3. 生成静态文件：`bundle exec jekyll build`

## 为什么保留这些配置

- 保留 `jekyll-paginate-v2`，因为分类页依赖它生成分页列表和页码跳转。
- 保留 `.github/workflows/deploy.yml`，因为当前站点通过 GitHub Actions 构建并发布到 `gh-pages`。
- 保留 `CNAME`，因为线上站点使用自定义域名 `puppyhat.org`。
