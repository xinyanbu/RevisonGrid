# 🐙 RevisonGrid
🐙 RevisonGrid is an personal planning system that turns goals into actionable daily execution.  Beyond priority management, habit tracking, and drag-and-drop scheduling, it features a smart auto-planning engine: for quantifiable goals, users simply choose working days per week, and the system automatically distributes tasks across the calendar.

> 告别繁琐的日历应用和涣散的备考计划。这是一款专为「多线程硬核备考」与「复杂项目推进」打造的极简前端追踪系统。毕业季，考公、论文、找工作八手抓👋，仍然有条不紊地掌控你的每一项任务。


## ✨ 项目亮点 (Key Features)

* 📅 **一键智能排期引擎 (Smart Scheduling)** 只需设定总量（如 20 套卷子）和逢周几安排，系统会自动在日历中生成 `项目 01` 到 `项目 20` 的序列，并自动跨越休息日，精准填入矩阵。
* 🐙 **极致高密度视图 (High-Density Matrix)**
  抛弃了传统日历留白过多的弊端，采用 Excel 级别的数据宽表排版。支持 ISO 标准周数（W24）自动计算，全局进度一目了然。
* 🎯 **进度双向联动机制 (Interactive Progress)**
  目标卡片内置 `+1`、`+5`、`+10` 步进引擎。支持自定义项目专属色彩，选定的颜色将自动渲染到下方追踪日历的对应文本中。
* 🖐️ **丝滑拖拽调休 (Drag & Drop)**
  计划赶不上变化？鼠标悬浮任务即可唤出拖拽手柄，将任务自由拖拽至本月的任意空位，无缝应对突发的调休与改期。
* 📊 **CSV 标准化导出 (Data Export)**
  一键将矩阵数据导出为长表格式（Long Format CSV）。完美衔接 SAS、R 语言等统计分析工具，供你进行长期的执行力复盘与时间序列建模。
* 🔒 **100% 纯本地隐私 (Privacy First)**
  无需注册，零服务器交互。所有数据实时保存在浏览器 LocalStorage 中，你的数据完全只属于你自己。

## 🎯 适用场景 (Use Cases)

本系统特别适合需要**长周期、高专注度、多项目并行**的场景：
1. **硬核升学与考公备考**：例如将行测 600 题、资料分析网课拆解到每日。
2. **雅思学习**：雅思听说读写四维度全方面排期与复盘，每日进度直观展示。
3. **日常自律与微习惯**：内置横向微习惯打卡矩阵（如健身有氧、专业软件操作练习），每日纯点击即可完成状态切换（✅ / ❌）。

## 🛠️ 如何使用 (How to Use)

1. **直接运行**：点击上方的 Live Demo 链接，直接在浏览器中开始规划你的当月目标。
2. **本地部署**：克隆本仓库，直接双击打开 `index.html` 即可使用，无需任何依赖环境配置。
3. **数据管理**：若需更换电脑，可先点击「导出 CSV」备份数据。

## 🎨 技术栈 (Tech Stack)

* 纯原生 HTML5 / JavaScript / CSS3
* **Tailwind CSS** (通过 CDN 引入，实现极简现代的 UI 响应式布局)
* **LocalStorage API** (实现轻量级本地状态管理)
