# shutup

压缩和精简 AI 面向的 prompt、plan、outline、handoff。

## 什么时候用

- 给另一个 AI 写 prompt/plan/outline/handoff
- 压缩已有的 AI 生成内容
- 去除冗余、套话、过度规划
- 防止 prompt 膨胀

## 默认行为

如果没有指定压缩比例，默认压缩到原文的 30%-50%。

## 核心原则

1. 先删后改
2. 保留意图，不加新需求
3. 把读者当成熟 AI，不需要手把手教
4. Plan 只列检查点，不模拟未来细节
5. 最好的输出是能正确引导下一个 actor 的最短版本

## 安装

将 `SKILL.md` 放到你的 Hermes skills 目录下：

```
~/.hermes/skills/shutup/SKILL.md
```

或通过 Hermes CLI 安装：

```bash
hermes skill install shutup
```
