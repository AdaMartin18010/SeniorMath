# 贡献指南 | Contributing

感谢您愿意为 SeniorMath 贡献！本项目专注于高中数学知识梳理与教育资源建设（非编程）。

## 内容风格

- 结构：每文档包含“概述/核心概念/方法/应用/学习要点/常见错误/扩展思考”。
- 语言：简明、准确、可教学落地；必要时中英双语小标题。
- 记号：统一使用标准数学符号（ℝ, ℤ, ℕ, ∀, ∃, ⇒），函数与集合写法一致。
- 图示：Mermaid 概念图放于 `mindmaps/concept-maps/`。

## 锚点与导航

- 小节标题即锚点（避免重复命名）。
- 每文档顶部添加“导航 | Navigation”（前置/后续/并列）。
- 跨文档索引在 `documentation/references/Cross-Links-Index.md` 维护。

## 标准映射流程

1. 确认条款（CCSS/AP/A-Level）
2. 定位文档小节：`docs/...#小节标题`
3. 指向练习：`exercises/...`（题号或关键词段）
4. 更新映射表：
   - 宏观：`standards/STANDARDS_ALIGNMENT_MATRIX.md`
   - CCSS细粒度：`standards/CCSS_MAPPING_FULL.md` 与 CSV
   - AP/A-Level：`standards/AP_MAPPING_FULL.md`，`standards/ALEVEL_MAPPING_FULL.md` 与 CSV

## 质量保障

- 提交前自检：使用 `documentation/references/Quality-Assurance-Checklist.md`
- 公式与叙述双检；例题与答案（或提纲）可核验。
- 与“常见错误/误区”相互呼应。

## 提交流程

- 新增内容：置于相应目录（docs/exercises/standards/mindmaps 等）。
- 小而清晰的提交，配合简要说明：目的/涉及条款/受影响文档。
- 遵循版本规范：见 `VERSIONING.md`；发布说明更新 `CHANGELOG.md`。

## 许可与署名

- 采用 Apache-2.0 许可证。
- 欢迎在提交信息中保留署名与致谢。

---
> 贡献前建议先阅读索引与发布说明：`documentation/references/INDEX.md`，`RELEASE_NOTES.md`。
