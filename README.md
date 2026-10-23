<a href="https://reachrich.ai/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://reachrich.ai/icons/riqi-dark-180.png">
    <img align="right" src="https://reachrich.ai/icons/riqi-light-180.png" alt="ReachRich" width="64" height="64">
  </picture>
</a>

# ReachRich

**A 股市场与量化研究平台**

[打开平台](https://reachrich.ai/) · [使用手册](https://docs.reachrich.ai/) · [RiQi](https://riqi.ai/) · [English](README.en.md)

ReachRich 为个人研究者和机构投研团队提供行情、资讯与股票筛选工具。先了解市场，再形成候选清单，围绕具体公司继续研究。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://reachrich.ai/product/reachrich-market-overview.jpg">
  <img src="https://reachrich.ai/product/reachrich-market-overview-light.jpg" alt="ReachRich 市场概览：主要指数、涨跌分布与价格图" width="640">
</picture>

<sub>市场概览，采用官网已公开的历史收盘快照。</sub>

## 平台功能

### 行情与市场观察

查看主要指数、市场涨跌分布和个股价格走势。在个股研究中切换日、周、月周期，结合成交量比较不同时间尺度的变化。

[查询个股日 K](https://docs.reachrich.ai/reachrich/daily-k.html) · [切换日、周、月周期](https://docs.reachrich.ai/reachrich/weekly-monthly.html)

### 资讯与事件研究

按关键词、来源和分类查找资讯。将报道作为研究线索，再回到公司公告和原始资料核对日期、金额与事件背景。

[搜索资讯与选择来源](https://docs.reachrich.ai/reachrich/news.html)

### 股票筛选

使用筛选模板建立候选清单，记录所用条件和数据日期。再从候选中选择需要深入研究的公司，不把候选清单与个人持仓混在一起。

[使用筛选模板](https://docs.reachrich.ai/reachrich/screener.html)

### RiQi 投研助手

[RiQi](https://github.com/reachrich-ai/riqi) 是同一产品体系中的对话式研究工作区。带着问题和资料讨论一家公司的经营变化，对回答中的依据继续追问，并在原会话中补充后续材料。

[了解 RiQi](https://reachrich.ai/riqi) · [完成一家公司研究](https://docs.reachrich.ai/workflows/company-study.html)

## 快速开始

以一条公司新闻为起点：

1. **找到原始信息。** 在 ReachRich 检索相关资讯，记下报道日期，并找到对应公告。先分清报道发生的时间和事件发生的时间。
2. **查看市场背景。** 查询公司价格与成交情况，选择与事件相符的观察区间；需要建立对照组时，再使用筛选工具。
3. **带着问题进入 RiQi。** 提供相关资料，说明要讨论的公司、报告期与问题，例如“这次订单变化会怎样影响交付与收入确认”。阅读回答后，围绕出处和假设继续核对。

完整操作见[完成你的第一次 A 股研究](https://docs.reachrich.ai/start/quickstart.html)。

## 研究资料

### [A 股回测：交易成本与复权口径](https://reachrich.ai/research/a-share-backtest-costs.html)

怎样比较两份回测结果：从价格口径、成交假设与换手定义入手，再检查费用和样本外区间。

### [A 股新闻事件研究：从资讯线索到公司公告](https://reachrich.ai/research/a-share-news-event-study.html)

怎样把一条新闻变成可继续研究的问题：对齐报道与事件日期，核对原始披露，留下证据和后续观察点。

### [A 股因子验证：识别过拟合与样本外失效](https://reachrich.ai/research/a-share-factor-validation.html)

怎样判断一个因子是否依赖已知样本：记录定义与参数尝试，固定验证区间，再检查成本和成交约束。

公司研究案例：[用 RiQi 做 A 股公司研究](https://riqi.ai/research/a-share-company-research.html)。

## 文档与支持

- [平台介绍](https://reachrich.ai/about)：ReachRich 与 RiQi 的产品分工。
- [完整使用手册](https://docs.reachrich.ai/)：按研究任务和操作步骤查找说明。
- [账号与功能访问](https://docs.reachrich.ai/help/access.html)：登录与可用功能说明。
- [帮助与反馈](https://reachrich.ai/support)：使用问题与机构需求。

当前面向中国大陆 A 股研究，功能与数据按账号权限提供；港股与美股仍在研发。

本仓库维护产品介绍与公开指南，不包含产品核心代码、私有策略或密钥。
