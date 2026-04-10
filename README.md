# workflow-skills

将常见的Vibe Coding 工作流整合, 整合进行 `Opencode` + `Omo` 体系中

- `opencode` 作为AI Agent载体, 提供基础vibe coding能力
- `omo` 主打多agent编排,附带一些奇奇怪怪的工具, 深度工作/规划器/执行器等

# skills list

## skill-creator

- 用于创建skill的skill
- 基于交互式评估迭代的方式创建和优化skill
- 可以直接在 `opencode` + `omo` 中使用, 在`Sisyphus`Agent下使用
- 未作任何修改直接来至anthropic skills仓库

## superspowers

- 基于说服心理学构建的日常开发工作流
- 访谈 -> spec -> plan -> execute
- 苏格拉底式提问,整体交互非常友好,个人比较喜欢
- 严格TDD流程,质量保障较高
- 多轮review: spec doc review / plan review / task complete spec review / task complete code review /
  finally-completion-reveiw
- 执行比较慢,可能出现多轮review都不通过,质量反而变差(模型偷懒/上下文膨胀注意力下降)
- 强制加载技能, 无`小打小闹`修正模式
- 无法直接在 `opencode` + `omo` 中使用, 仿造 `skill-creator` 的写作方式, 将整个`superpowers`技能库打包在一个技能中,并且由用户主动控制是否进入
  `superpowers`流程
- 改造兼容`omo`目录结构

## gsd v1

- 待办

## gstack

- 待办