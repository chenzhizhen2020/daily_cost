# 长期主义消费计算器 (Daily Cost Calculator)

一个帮助你计算物品日均成本的网页应用。

## 功能特点

- 计算物品的日均摊销成本
- 管理订阅服务的日均费用
- 实时查看总体每日消费成本
- 新增资产净值界面：分开记录活期资产、固定资产、信用资产
- 支持多张银行卡、美元资产按人民币汇率换算
- 支持多次手动录入历史快照，并按最近两次记录统计日均消费
- 资产变化趋势图：按时间展示活期/固定/信用/净资产四类变化
- 固定资产、信用资产支持自定义新增类型（不限条目）

## 访问应用

本项目已启用 GitHub Pages，可以直接通过以下地址访问：

**https://chenzhizhen2020.github.io/daily_cost/**

## GitHub Pages 部署

本项目使用 GitHub Actions 自动部署到 GitHub Pages。每次推送到 `main` 分支时，都会自动触发部署流程。

### 配置说明

- 部署源：GitHub Actions
- 分支：`main`
- 目录：根目录
- 工作流文件：`.github/workflows/pages.yml`

### 手动触发部署

如果需要手动触发部署，可以在 GitHub Actions 页面找到 "Deploy to GitHub Pages" 工作流，点击 "Run workflow" 按钮。

## 本地使用

直接在浏览器中打开 `index.html` 文件即可使用。
