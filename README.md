# duanju

> **一句话安装：** 先向发布者获取解压密码，把下面文字中的 `【解压密码】` 替换为真实密码，然后整段复制给 Codex 或其他智能体。

```text
请下载 https://raw.githubusercontent.com/zjj231154-droid/duanju/main/duanju-skills.zip，使用密码【解压密码】解压；安装其中 .agents/skills/short-drama、.agents/skills/dreamina-cli 和 .agents/skills/kling-cli 这三个技能。如果支持项目级规则，再把 AGENTS.md 放到当前项目根目录。安装完成后告诉我，并从下一轮开始启用这些技能。
```

面向 Codex 及兼容技能系统智能体的微短剧创作技能包，支持短剧策划、角色设计、分集大纲、单集剧本、质量评审、合规检查，以及即梦 / 可灵辅助生成工作流。

## 下载

[下载加密技能包 duanju-skills.zip](https://raw.githubusercontent.com/zjj231154-droid/duanju/main/duanju-skills.zip)

压缩包使用 AES-256 加密，密码不会保存在公开仓库中，请向发布者索取。若系统自带解压工具不支持 AES，请使用 7-Zip 或其他兼容工具。

## 包含内容

- `short-drama`：微短剧从选题到导出的完整创作流程。
- `dreamina-cli`：即梦图片与视频生成 CLI 的操作指引。
- `kling-cli`：可灵图片与视频生成 CLI 的操作指引。
- `AGENTS.md`：项目级技能触发规则与产物约定。

## 手动安装

1. 下载 `duanju-skills.zip`，使用发布者提供的密码解压。
2. 将 `.agents/skills/` 下的三个技能目录复制到智能体的技能目录。Codex 默认使用 `~/.codex/skills/`。
3. 如需启用项目级规则，将 `AGENTS.md` 复制到目标项目根目录。
4. 重新开始一轮对话，使新技能生效。

短剧创作可使用 `/start`、`/plan`、`/characters`、`/outline`、`/episode`、`/review`、`/compliance`、`/overseas` 和 `/export` 等阶段指令。

## 说明

公开仓库只保存说明文档和加密技能包，不包含明文技能、剧本、角色资料、图片、视频或其他创作产物。即梦与可灵 CLI 需要各自的本地安装及账号授权；登录凭据不会保存在本仓库中。
