# AI 产品经理每周学习简报 Skill

这个 Codex Skill 面向想转向 AI 产品经理的非技术背景读者。它先查看近七天 Hugging Face Daily Papers、GitHub Trending 和 Hacker News 的榜单，分析反复出现的主题，再挑选重要材料精读。输出重点是事实、证据边界和产品决策含义。

## 周报包含什么

1. 调查范围、日期和无法取得的榜单页面。
2. 三个来源的整体趋势，以及这些趋势可以和不能说明什么。
3. 约 6–8 条重要材料的排序表：优先级、材料链接、材料是什么、值得看的原因。
4. 最重要的 2–3 条深入分析，以及其余材料的要点。
5. 按优先级排列的阅读路径。

选题数量随证据质量调整。论文结果、项目作者的功能描述、社区讨论和周报作者的推断会明确区分。

## 使用

将本仓库的 `SKILL.md` 放到 Codex 可发现的 skill 目录，然后在 Codex 中提出类似请求：

> 使用 ai-pm-weekly-brief，分析过去一周 Hugging Face Daily Papers、GitHub Trending 和 Hacker News 的整体趋势，并生成本周 AI 产品经理学习周报。

需要定期推送时，可另行在 Codex 中创建每周自动化任务，让它调用该 Skill。仓库本身不包含自动化配置。

## 数据来源

- [Hugging Face Daily Papers](https://huggingface.co/papers)
- [GitHub Trending](https://github.com/trending)
- [Hacker News](https://news.ycombinator.com/)

这三个榜单反映各自社区的关注点，不能直接代表整个行业的需求或技术成熟度。

