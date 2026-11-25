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
- [交互练习册](assets/interaction-lab.html)包含 14 个可操作案例。下载后用浏览器打开即可离线练习。每例都有操作提示、观察要点和对应的原视频链接。

| 想练习的交互 | 可以打开的案例 |
| --- | --- |
| 手势与数值 | 手势卡片、温控旋钮、范围选择 |
| 容器与导航 | 底部抽屉、日程展开、分段视图 |
| 列表与输入 | 删除与撤销、站点排序、搜索多选、中文输入 |
| 状态与数据 | 提交按钮、骨架加载、清单进度、月度看板 |
