# 👋 Hi, I'm 杨爵锋 (Yang Juefeng)

> 🎓 2026届本科毕业生 | 土木工程转码 Python 开发  
> 🎯 专注 **爬虫工程** 与 **数据分析** 方向  
> 📍 目标城市：深圳、东莞、珠海
> 📧 3608872992@qq.com

---

## 🛠 技术栈

### 爬虫与数据采集
<p align="left">
  <img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scrapy-框架-663399?style=for-the-badge&logo=scrapy&logoColor=white" />
  <img src="https://img.shields.io/badge/DrissionPage-浏览器自动化-009688?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Playwright-自动化-2E7D32?style=for-the-badge" />
  <img src="https://img.shields.io/badge/requests-HTTP客户端-FF6F00?style=for-the-badge" />
</p>

### 反爬与逆向
<p align="left">
  <img src="https://img.shields.io/badge/验证码OCR-ddddocr-E91E63?style=for-the-badge" />
  <img src="https://img.shields.io/badge/浏览器指纹-反检测-9C27B0?style=for-the-badge" />
  <img src="https://img.shields.io/badge/WAF绕过-阿里云盾-F44336?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MD5签名-参数加密-3F51B5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JS逆向-入门-FF5722?style=for-the-badge" />
</p>

### 数据分析与可视化
<p align="left">
  <img src="https://img.shields.io/badge/pandas-数据处理-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/matplotlib-可视化-11557C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Streamlit-仪表盘-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-商业智能-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
</p>

### 数据库与存储
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-关系型-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-文档型-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-缓存-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
</p>

### 工具与部署
<p align="left">
  <img src="https://img.shields.io/badge/Git-版本控制-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-容器化-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-服务器-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/APScheduler-定时任务-0099CC?style=for-the-badge" />
</p>

---

## 🚀 项目经历

### 🔥 数据采集与监控系统

<details>
<summary><b>📱 抖音装修获客工具</b> - 已上架闲鱼商业化</summary>

- **技术栈**：Python / requests / 反爬绕过 / 数据清洗
- **功能**：自动化采集抖音装修行业潜在客户信息
- **亮点**：
  - 掌握请求头/Cookie/动态Token/MD5签名四类主流反爬绕过
  - 已商业化上架闲鱼，验证了产品市场匹配度
- **状态**：✅ 已上线运营

</details>

<details>
<summary><b>🏠 房天下房价监控系统</b> - Scrapy + MongoDB 增量采集</summary>

- **技术栈**：Scrapy / MongoDB / APScheduler / 增量爬取
- **功能**：
  - 自动爬取房天下二手房列表页数据
  - MongoDB 增量存储，避免重复抓取
  - 定时任务自动运行，持续监控房价变化
- **亮点**：
  - 完整的 Scrapy 工程化实践
  - 增量采集策略，高效去重
  - 支持多城市、多区域数据采集

</details>

<details>
<summary><b>📈 雪球网股价监控系统</b> - WAF绕过 + API采集</summary>

- **技术栈**：DrissionPage / 阿里云WAF绕过 / MongoDB / pandas
- **功能**：
  - 绕过阿里云WAF反爬，获取实时股票行情
  - MongoDB 增量存储历史数据
  - 数据清洗与可视化分析
- **亮点**：
  - 掌握 SSR 服务端渲染数据采集
  - 理解 WAF 控制流混淆与绕过原理
  - 全链路打通：反爬绕过 → API采集 → 数据存储

</details>

<details>
<summary><b>📚 古文岛混合采集系统</b> - Scrapy 工程化实践</summary>

- **技术栈**：Scrapy / CrawlSpider / FilesPipeline / 自定义中间件
- **功能**：
  - 混合采集：文本内容 + 文件附件同步下载
  - CrawlSpider 规则化爬取，自动跟踪链接
  - FilesPipeline 文件下载与去重
- **亮点**：
  - 深入掌握 Scrapy 框架核心组件
  - 自定义中间件实现请求/响应处理
  - 工程化项目结构，可复用性强

</details>

<details>
<summary><b>🎬 Pexels 多媒体采集系统</b> - API 调用 + 批量下载</summary>

- **技术栈**：Python / Pexels API / 异步下载 / 文件管理
- **功能**：
  - 调用 Pexels API 搜索图片/视频
  - 多线程异步下载，提升采集效率
  - 自动分类存储，元数据管理
- **亮点**：
  - API 接口调用与分页处理
  - 异步 IO 提升下载性能
  - 完整的文件管理与错误处理

</details>

<details>
<summary><b>⭐ GitHub Trending 监控系统</b> - 星级项目追踪与打分</summary>

- **技术栈**：Python / requests / MongoDB / 数据分析
- **功能**：
  - 自动爬取 GitHub Trending 热门项目
  - 项目质量评分算法（Star增长、活跃度、文档完整度）
  - 每日更新，生成推荐报告
- **亮点**：
  - 自定义评分模型，筛选高质量项目
  - 增量更新策略，避免重复抓取
  - 数据可视化展示趋势

</details>

### 📊 数据分析项目

<details>
<summary><b>🏘️ 链家二手房分析仪表盘</b> - Streamlit + Power BI</summary>

- **技术栈**：pandas / matplotlib / Streamlit / Power BI
- **功能**：
  - 二手房数据清洗与特征工程
  - 交互式数据探索仪表盘
  - 房价影响因素分析
- **亮点**：
  - 双平台展示：Streamlit（交互式）+ Power BI（商业智能）
  - 多维度数据可视化

</details>

---

## 🛡️ 爬虫攻防靶场

独立完成 **6 层爬虫攻防靶场**，系统化掌握反爬对抗技能：

| 层级 | 防御机制 | 攻击方法 |
|------|----------|----------|
| 1 | Session 登录验证 | Session 维持 + Cookie 管理 |
| 2 | Token 签名校验 | MD5 签名算法复现 |
| 3 | 时间戳过期（30秒） | 实时生成时间戳 |
| 4 | 参数签名防篡改 | sorted params + MD5 |
| 5 | 验证码（5分钟过期 + 一次性使用 + IP锁定） | ddddocr OCR 识别 |
| 6 | 浏览器指纹检测 | add_init_script 反检测 |

**核心成果**：
- ✅ 掌握 `navigator.webdriver` / `plugins` / `languages` 指纹伪装
- ✅ 理解纵深防御思维，多层防线互为补充
- ✅ 实战验证：普通 Playwright vs 反检测 Playwright 指纹对比

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yjfyyds2333&show_icons=true&theme=radical" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yjfyyds2333&theme=radical" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yjfyyds2333&layout=compact&theme=radical" alt="Top Languages" />
</p>

---

## 🎯 当前状态

- 📚 **正在学习**：JS 逆向（断点调试 / 加密算法 / 代码混淆）
- 💼 **求职中**：Python 爬虫 / 数据采集 / 数据分析岗位
- 🔧 **持续迭代**：各项目功能优化与工程化重构
- 📝 **LeetCode**：累计 47 题，持续刷题中

---

## 📬 联系我

- 📧 **Email**：3608872992@qq.com
- 💼 **求职意向**：Python 爬虫工程师 / 数据采集工程师 / 数据分析师
---

<p align="center">
  <i>土木工程转码er | 用代码解决实际问题 | 持续学习中 🚀</i>
</p>
