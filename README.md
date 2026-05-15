# 🚀 B2B 内容增长引擎：12步标准化文章生产流程 (SOP)

> **适用场景**：产品型文章集群 / 工程类文章集群 / 认证类文章集群  
> **核心目标**：生产满足 **EEAT** (经验/专业/权威/可信) + **GEO** (AI搜索优化) + **结构化数据** 要求的高转化 B2B 内容。

---

## 📂 第一部分：文章集群架构地图 (Article Cluster Strategy)

| 一级集群类型 | 核心要回答的问题 | 典型标题方向 | 适合覆盖的内容 | 漏斗阶段 | 商业价值 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **认知教育型** | 这是什么？ | What is X, X meaning, X explained, X types, X uses | 定义、分类、基础知识、用途说明 | **TOFU** | 拉新流量、做主题入口 |
| **选型决策型** | 我该怎么选？ | How to choose, buying guide, selection guide, best X for Y | 选购标准、采购要点、适配建议、不同需求推荐 | **MOFU** | 很强，适合导向产品/服务页 |
| **对比替代型** | X 和 Y 区别？ | X vs Y, compare, alternative, pros and cons, which is better | 对比、优缺点、替代方案、适用场景差异 | **MOFU** | 很强，搜索意图明确 |
| **规格标准型** | 参数/标准是什么？| Specifications, dimensions, standards, testing method | 尺寸、参数、测试方法、行业标准、技术要求 | **TOFU/MOFU** | 强，利于建立专业度 |
| **应用场景型** | 它适合谁？ | Best for hotel, for retailers, for contractors, for villas | 人群场景、行业方案、项目适配、客户类型拆分 | **MOFU/BOFU** | 很强，最适合 B2B 转化 |
| **工艺/排查型** | 怎么做/出问题？ | Manufacturing process, quality control, troubleshooting | 工艺流程、质量控制、常见问题、解决方案 | **TOFU/MOFU** | 强，能体现工厂经验 |
| **认证合规型** | 符合什么认证？ | Certification explained, CE/REACH/ASTM/ISO cost | 认证介绍、测试流程、标准解释、合规要求 | **MOFU/BOFU** | 中高，信任价值很强 |
| **供应商评估型**| 怎么合作？ | OEM vs ODM, MOQ, lead time, quotation guide | 合作模式、MOQ、交期、报价、验厂清单 | **MOFU/BOFU** | **最高**，最接近询盘 |

---

## 🛠 第二部分：12 步标准化执行流程

### Step 1：调研文章集群标题
*   **目标**：为上述 8 种集群类型各规划 5-10 篇文章标题。
*   **操作**：使用 `templates/article-cluster-research-template.md`，通过 Google 自动补全、SEMrush Topic Research 挖掘。
*   **评估标准**：必须具备搜索量、明确的商业意图、且与产品强相关。

### Step 2：竞对大纲调研 → 撰写自有大纲
*   **操作步骤**：
    1.  搜索目标关键词，打开前 5 名竞对文章。
    2.  记录：H1/H2/H3 结构、估算字数、是否有 FAQ/表格/案例。
    3.  **超越策略**：覆盖竞对共性模块，加入“工厂视角”和“实操案例”，预留 GEO 摘要位置。
*   **产出物**：自有文章大纲草稿（H1 + H2 + H3 + FAQ）。

### Step 3：SEMrush 关键词挖掘与布局
*   **筛选条件**：意图匹配，搜索量 > 100。
*   **布局策略**：
    *   **主关键词 (Primary)**：1 个，布局在标题、H1、首段。
    *   **次级关键词 (Secondary)**：3-5 个，分布在 H2/H3。
    *   **LSI/长尾词 (Supporting)**：5-10 个，自然融入段落。

### Step 4：生成工厂视角 EEAT 素材 (ChatGPT Prompt)
*   **目标**：增强内容的经验感 (Experience)。
*   **指令**：
    > "请扮演一名在 [行业名称] 工厂有 15 年经验的工程师，基于大纲：[粘贴大纲]，输出：1. 工厂视角的实操经验（300字），描述真实遇到的问题与对策；2. 项目第一人称案例（300字），包含数据和结果。"

### Step 5：确认内链清单 + 准备外链引用
*   **内链**：锁定产品页（核心落地页）、案例页（行业场景）、联系页（CTA）。
*   **外链**：准备权威媒体、行业协会（如 Wikipedia、ISO 官网）的数据或结论段落。

### Step 6：向 AI 输入大纲并确认理解
*   **操作**：在正式生成前，向 AI 发送大纲并要求其确认逻辑、技术深度及 EEAT 插入点。回复“已理解大纲”后再继续。

### Step 7：输入关键词布局与 EEAT 标记指令
*   **指令要求**：
    *   强制关键词出现频次与位置。
    *   明确 [E-Experience]、[E-Expertise]、[A-Authoritativeness]、[T-Trustworthiness] 的具体插入章节。

### Step 8：生成 GEO 文章 (AI 搜索引擎优化)
*   **硬性要求**：
    *   字数不少于 **2500 字**。
    *   **GEO 摘要 (必选 3 种)**：列表摘要 (Bullet points)、答案摘要 (Direct Answer)、表格摘要 (Markdown Table)、步骤摘要 (How-to steps)。
    *   首段 100 字内切入主题，严禁废话。

### Step 9：WordPress 预览与质量质量检查
*   **检查项**：
    - [ ] 字数是否达标？
    - [ ] EEAT 经验内容是否生动？
    - [ ] 关键词是否堆砌？
    - [ ] H 层级是否清晰？
    - [ ] Meta Description 是否 ≤ 160 字符？

### Step 10：视觉化配图与链接部署
*   **配图**：每 500 字一张图（产品/工艺/图表），添加含关键词的 Alt 文本。
*   **链接**：外链设为 `_blank`，内链确保锚文本精准。

### Step 11：添加结构化数据标记 (Schema Markup)
*   **Article Schema**：用于整体文章识别。
*   **FAQ Schema**：提升搜索结果展示面积。
*   **HowTo Schema**：适用于工艺/安装类文章。
*   **ImageObject Schema**：优化图片搜索。

### Step 12：填写关键词词表归档
*   **目标**：形成可复查的内容资产。
*   **操作**：使用 `templates/keyword-record-template.csv` 记录文章 URL、关键词、内链分布、外链来源及收录状态。

---

## 📊 执行流图 (Workflow)

```mermaid
graph LR
    A[调研] --> B[大纲]
    B --> C[素材]
    C --> D[AI生成]
    D --> E[质检]
    E --> F[发布/Schema]
