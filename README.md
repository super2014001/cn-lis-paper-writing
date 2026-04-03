# cn-lis-paper-writing

一个面向**中文图书情报领域学术论文**的最小可运行 skill 包。

## 当前包含
- `SKILL.md`：总控规则
- `references/abstract.md`：摘要写作与改写规则
- `references/introduction.md`：引言写作与改写规则
- `references/literature-review.md`：文献综述组织规则
- `references/methods.md`：方法部分写作规则
- `references/results-discussion.md`：结果与讨论写作规则
- `references/conclusion.md`：结论写作规则
- `references/reply-to-reviewers.md`：回复审稿意见规则
- `references/examples.md`：结构型示例
- `references/reviewer-checklist.md`：投稿前自检清单
- `agents/openai.yaml`：最简元信息

## 当前定位
- 不包含学位论文专项写作
- 强化实践启示
- 适合做 v0.3 起步版

## 建议使用方式
1. 先根据用户任务定位到对应章节文件
2. 先诊断问题，再给结构提纲，再给改写文本
3. 通篇修改后用 `reviewer-checklist.md` 做一次自检
4. 面对返修意见时，用 `reply-to-reviewers.md` 生成逐条回应草稿

## 建议下一步
1. 增补 `references/examples.md` 中的正反例数量
2. 加入 `references/concept-definition.md` 或 `references/title-keywords.md`
3. 用 5—10 篇真实图情论文片段回测并继续补规则
