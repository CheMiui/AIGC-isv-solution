# AI 漫剧赛道 ISV 渠道合作方案实战复盘 (含交互式作品集源码)

🌐 **[在线预览 (Live Demo)](https://chemiui.github.io/portfolio_Michelle/)** （请替换为实际链接）

## 📖 项目简介
本项目包含两个层面的交付成果：
1. **业务层面：** 完整记录了百度智能云针对某 AI 漫剧赛道技术集成商（ISV）的完整售前拓展与落地方案。拆解了如何通过“API 聚合 + IAM 企业级管控体系”解决渠道商在并发限制、账单结算及渠道防撬单保护等方面的核心商业痛点。
2. **工程层面：** 本仓库包含了该复盘报告的**交互式前端展示单页 (SPA)** 源码。摒弃了臃肿的框架，采用原生 Web 技术构建了具有极客感与高级商业感的高保真作品集页面。

## 🎯 业务解决方案架构
* **多模型 API 聚合：** 统一接入 Vidu（主体库）、可灵、Gemini、DeepSeek 等头部多模态模型，赋能渠道商以低成本获取全栈调用能力。
* **企业级权限与分发体系 (IAM)：** 采用“主账号统付 + 子账号隔离分发 API Key”机制，解决下游数百家工作室的账单与权限隔离问题。
* **高并发调度与渠道保护：** 推动 30-50 专属高并发通道打通，并确立明确的客户报备机制，从底层机制上保障了 ISV 的商业安全感。

## 🛠️ 前端技术栈与 UI 实现 (Frontend Tech Stack)
本项目前端展示页（`index.html`）完全由原生代码手写实现，未依赖 React/Vue 等重量级框架，极致优化了加载速度与跨端兼容性：

* **核心技术 (Core)：** HTML5, CSS3, Vanilla JavaScript (原生 JS)
* **设计规范 (Design System)：**
  * **Bento Box (便当盒网格)：** 利用高度灵活的 CSS Grid 布局构建信息模块，信息呈现密度高且极具结构美感。
  * **动态双主题 (Theme Switch)：** 基于 CSS Custom Properties (变量) 实现 Light / Dark Mode 无缝切换。
  * **纯 CSS 国际化 (i18n)：** 利用 `[data-lang]` 属性控制中英双语的瞬间切换。
* **高级数据可视化 (Advanced Visualizations)：**
  * **交互式系统架构图：** 采用原生 `<svg>` 绘制复杂的业务流向与系统层级，并配合 JavaScript 实现基于坐标动态计算的悬停信息气泡 (Tooltip)。
  * **动态雷达图 (Radar Chart)：** 放弃 ECharts 等第三方图表库，直接使用 HTML5 `<canvas>` API 辅以三角函数（Math.sin/cos）手搓绘制能力雷达图，支持极度丝滑的 Hover 交互交互。
* **微交互与排版 (Micro-interactions & Typography)：**
  * **横向拖拽时间轴 (Drag-to-scroll Timeline)：** 利用原生 JS 监听鼠标事件，实现无滚动条的沉浸式横向拖拽体验。
  * **高级字体映射：** 采用 `DM Serif Display` 渲染优雅的大标题，`DM Sans` 保证正文可读性，`JetBrains Mono` 增强标签的极客代码感。

## 🚀 项目成果
* **售前闭环：** 推动客户完成账号体系搭建、API 接口文档发放及测试环境打通。
* **资产沉淀：** 将单次拜访的碎片化经验提取为《XXXX项目深度分析文档》，成为团队内可复用的 ISV 渠道商拓展框架。

---
*Designed & Developed for Professional Portfolio Purposes.*
