# 💰 长期主义消费计算器 (Long-termism Cost Calculator)

> **“买得贵不一定代表浪费，买得便宜也不一定就是节约。”**

这是一个帮助你通过**日均持有成本 (Daily Cost)** 视角重新审视消费习惯的网页应用。通过计算物品分摊到每一天的真实开销，助你做出更理性的购买决策，并记录个人资产净值的增长趋势。

👉 **在线使用**: [https://chenzhizhen.github.io/save_money/](https://chenzhizhen.github.io/save_money/)

---

## ✨ 核心功能

### 1. 🛍️ 物品日均成本计算 (Daily Cost)
不仅看标价，更看**拥有的时间**。
- **动态摊销**：输入物品价格与购买日期，自动计算自持有以来的**日均成本**。
- **回血机制**：支持记录二手卖出价格，锁定最终的使用成本。
- **订阅管理**：统一管理 Netflix、Spotify 等订阅服务，自动将月费/年费转换为日费。
- **总日均开销**：实时显示你目前拥有的所有物品加起来，每天即使躺着不动也需要消耗的金额。

### 2. 📈 资产净值追踪 (Asset Tracker)
不仅记流水，更看**存量的积累**。
- **全资产管理**：
    - **活期资产**：微信、支付宝、银行卡余额。
    - **固定/投资资产**：股票、基金、美元资产（支持自定义汇率）。
    - **信用/负债**：花呗、白条、信用卡欠款。
- **智能趋势分析**：
    - **历史快照**：支持随时录入资产快照，对比最近两次记录，反推真实的日均消费/储蓄速度。
    - **可视化图表**：直观展示活期、固定、负债及净资产的时间变化曲线。
- **灵活扩展**：支持自定义添加任意数量的资产账户或负债项目。

---

## 🔒 隐私与安全
本应用为纯静态网页（Serverless），**所有数据仅存储在你浏览器的本地缓存 (LocalStorage) 中**，不会上传至任何服务器。你的财务数据完全由你自己掌握。

---

## 🛠️ 技术栈
- **核心框架**: Vue 3 (Composition API)
- **样式库**: Tailwind CSS
- **图表库**: Chart.js
- **部署**: GitHub Actions 自动构建部署至 GitHub Pages

## 🚀 本地开发

如果你想在本地运行或修改代码：

1. 克隆项目到本地：
   ```bash
   git clone https://github.com/chenzhizhen/save_money.git
   ```

2. 安装依赖：
   ```bash
   npm install
   ```

3. 启动开发服务器：
   ```bash
   npm run dev
   ```

4. 打包生产版本：
   ```bash
   npm run build
   ```
## 🌐 访问应用

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
