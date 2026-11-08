# 👋 Hi, I'm 张凡 (Zhang Fan)

**2027 届本科 · 数据科学与大数据技术（班级学习委员） | 华为 ICT 大赛省级一等奖**  
🎯 **核心方向**：`AI 应用全栈开发` · `大模型与 Agent 工程开发` · `Agent 平台测试开发与评测 (QA)`

[![Portfolio Cloudflare](https://img.shields.io/badge/⚡_作品集_(Cloudflare_加速)-steep--bird--36af-FFD43B?style=for-the-badge&labelColor=2C221E)](https://steep-bird-36af.wufi3456.workers.dev)
[![Portfolio GitHub](https://img.shields.io/badge/🌐_作品集_(GitHub_Pages)-zhangzhangwudi2--creator.github.io-FF922B?style=for-the-badge&labelColor=2C221E)](https://zhangzhangwudi2-creator.github.io)
[![Feishu Portfolio](https://img.shields.io/badge/📘_飞书云文档作品集-lcn240mx3b00.feishu.cn-2B8A3E?style=for-the-badge&labelColor=2C221E)](https://lcn240mx3b00.feishu.cn)
[![PDF Resume](https://img.shields.io/badge/📄_PDF_简历直达-Resume.pdf-3B82F6?style=for-the-badge&labelColor=2C221E)](https://zhangzhangwudi2-creator.github.io/resume.pdf)

---

### ⚡ 核心工程量化指标 (Engineering Telemetry)

| 核心维度 | 量化指标 | 工程实现摘要 |
| :--- | :---: | :--- |
| **数学建模与回归** | **`R² > 0.96`** | 基于 Trust Region Reflective 算法求解 Bass 创新扩散常微分方程，远超静态线性均值流速 (`R² = 0.41`) |
| **高可用模型网关** | **`10 Channels / 75 RPM`** | 多渠道权重轮询 + 429 自动熔断降级 + Cloudflare 边缘隧道 (`175~190ms` 优选握手) |
| **桌面端极致瘦身** | **`13.7 MB / 50 MB RAM`** | Python Bottle + Edge WebView2 单文件免安装封装，搭配状态机 JSON 容错提取引擎（`0%` 解析崩溃率） |
| **系统级自动化测试** | **`169 Passed (100%)`** | 覆盖 11 个子模块的 pytest 契约测试、Mock 回放与异常注入，搭配 Pydantic `Claims Gate` 规则级前置阻断 |
| **金融大模型对齐评测** | **`25+ Rubrics / 200+ 公式`** | 使用 `openpyxl` 构建含 200+ 动态公式的 Ground Truth，制定正交原子级评测准则与 `±1%` 科学容差 |

---

### 🏆 精选开源仓库 (Featured Repositories)

| 仓库名称 | 定位与技术栈 | 核心亮点 |
| :--- | :--- | :--- |
| 📊 [**xianyu-lifecycle-llm**](https://github.com/zhangzhangwudi2-creator/xianyu-lifecycle-llm) | **本科毕设 · 算法与全栈系统**<br/>`Python` `SciPy NLS` `Streamlit` `Pydantic` | 融合 Bass 扩散动力学微分方程、CR4/HHI 寡占度计量与 DeepSeek/Qwen 结构化语义抽取的二手数字商品分析系统 |
| 💼 [**aiqiuzhizhe**](https://github.com/zhangzhangwudi2-creator/aiqiuzhizhe) | **AI 求职助手桌面端系统**<br/>`Python` `WebView2` `PyInstaller` `SQLite` | `13.7MB` 单文件免安装桌面应用，内置基于状态机与栈平衡匹配的 JSON 容错解析引擎，彻底消除 Markdown 截断崩溃 |
| 🎨 [**zhangzhangwudi2-creator.github.io**](https://github.com/zhangzhangwudi2-creator/zhangzhangwudi2-creator.github.io) | **个人交互式作品集网站**<br/>`React 18` `TypeScript` `Vite` `Tailwind` | Cozy Neo-Brutalism 极客贴纸风，支持「🧠 咕咕嘎嘎 / 👔 正经面试」双态切换、Bento 微型图表与系统架构流水线 |
| 🛠️ [**contentops-lab**](https://github.com/zhangzhangwudi2-creator/contentops-lab) | **多平台 AI 内容工程工作台**<br/>`Workflow` `Prompt Engineering` `Eval` | 面向多平台内容生产、痛点挖掘、标题生成与自动化质量复盘的 AI 工程实验库 |

---

### 🛠️ 技术栈矩阵 (Tech Stack)

- **AI 应用与全栈开发**：Python (`FastAPI` / `Bottle` / `Streamlit` / `Asyncio`), TypeScript / React, Edge WebView2, PyInstaller, SQLite (WAL)
- **大模型与边缘基建**：OpenAI / Gemini / DeepSeek / Qwen SDK, New API 多渠道网关与 429 熔断, Cloudflare Tunnel (`cloudflared`) & Zero Trust
- **Agent 评测与质量保障**：`pytest` 系统级自动化测试, Playwright (CDP 旁路监听), Pydantic v2 `Claims Gate`, `openpyxl` 动态公式 Ground Truth, 25+ Rubrics 设计
