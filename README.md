# good-ui

一个中文 Codex Skill，用于设计、实现和评审 Web、App 与小程序的交互控件。适合处理这样的需求：“卡片短拖时回到原位，拖过阈值才切换”“编辑时可以反悔”“保存失败后能直接重试”。

## 安装与使用

将仓库克隆到个人 Codex 技能目录。默认路径如下，使用自定义 `CODEX_HOME` 时，将目标改为该目录下的 `skills/good-ui`。

```shell
git clone https://github.com/margenal02/good-ui.git ~/.codex/skills/good-ui
```

Windows PowerShell 中可使用下面的命令。

```powershell
git clone https://github.com/margenal02/good-ui.git (Join-Path $env:USERPROFILE '.codex/skills/good-ui')
```

新开一次对话后，可以这样调用。

> 用 $good-ui 改进这张行程卡。点开底部抽屉后可以调整天数，确认才回填。请验证取消、确认和键盘关闭后的结果。

## 仓库内容

- [Skill 入口](SKILL.md)包含控件选择、行为描述和验收方法。
- [交互模式参考](references/patterns.md)涵盖反馈、手势、输入、容器、导航、数据联动和视觉动效。
- [交互练习册](assets/interaction-lab.html)是可离线运行的单文件网页。克隆后用浏览器打开，可体验手势卡片、底部抽屉、温控旋钮、提交重试、预算区间和删除撤销。点击“回看本例教程”可查看对应的原作。
