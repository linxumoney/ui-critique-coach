# UI Critique Coach：别再只说“页面不够高级”

好的 UI 评审不是换一种渐变、把圆角调大，也不是凭审美给分。它要回答：用户能不能看懂下一步、关键状态有没有覆盖、手机上会不会崩、键盘和读屏用户能不能完成任务。

`ui-critique-coach` 是一个面向设计师、前端和产品团队的开源 Agent Skill。它按用户任务、信息层级、交互状态、可访问性和响应式行为检查界面，并输出按严重度排序的修改清单。

## 使用示例

```text
用 $ui-critique-coach 评审这个页面截图和对应代码。
用户的核心任务是完成退款申请，请先找阻断问题，再谈视觉优化。
```

## 默认输出

- 核心任务完成度
- P0-P3 问题清单
- 每个问题的证据、影响和建议
- 缺失状态与移动端风险
- 最值得先改的三件事

## 安装

```bash
cp -R skills/ui-critique-coach ~/.codex/skills/
```

## 方法参考

本项目独立实现。AI 辅助界面设计问题域参考了 [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)，该项目采用 MIT License。本项目没有复用其数据库、设计规则、命令、脚本或提示词。

## License

MIT License。
