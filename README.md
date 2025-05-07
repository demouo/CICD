# CI/CD示例项目

这是一个用于学习CI/CD流程的示例项目。该项目演示了如何使用GitHub Actions自动部署静态网站到GitHub Pages。

## 项目结构

- `index.html`: 示例网站的主页
- `.github/workflows/deploy.yml`: GitHub Actions工作流配置文件

## 如何使用

1. Fork这个仓库到你的GitHub账户
2. 在仓库设置中启用GitHub Pages（Settings > Pages）
3. 选择gh-pages分支作为部署源
4. 推送更改到main分支，GitHub Actions将自动部署网站

## CI/CD流程说明

1. 当你推送代码到main分支时，GitHub Actions工作流会自动触发
2. 工作流会检出代码并部署到gh-pages分支
3. GitHub Pages会自动从gh-pages分支构建和部署网站

## 查看部署结果

部署完成后，你的网站将可以通过以下地址访问：
`https://[你的GitHub用户名].github.io/[仓库名]` 