# Daily‑Track

个人训练打卡记录工具，纯前端单页应用，数据存储于浏览器 localStorage。

## 功能

- 凯格尔盆底肌训练（循环计时器 + 组数打卡）
- 停‑动计时训练（掐段计时 + 分段记录）
- 历史记录管理（删除 / JSON 导出备份）
- 统计图表 & 本地分析总结（Chart.js）

## 访问

部署后访问：`https://<用户名>.github.io/daily-track/`

## 部署（GitHub Actions）

1. 推送代码到 `main` 分支
2. 仓库 **Settings → Pages → Source** 选择 **GitHub Actions**
3. `deploy.yml` 会在每次 push 到 main 时自动构建并发布

## 技术栈

HTML + TailwindCSS v3 CDN + Chart.js CDN + 原生 JavaScript
