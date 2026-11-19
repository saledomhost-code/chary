# 好品出海 Skills（Codex）

本仓库包含三个可用于 Codex 的外贸工作流 Skill：

- **企业出海规划生成器**：生成企业出海规划与市场分析。
- **视频文案批量生成器**：批量生成海外 B2B 视频文案与拍摄分镜。
- **好品客户背调**：分析海外客户真实性、跟进价值与成交可能性。

## 安装

将本仓库的 `skills/` 目录中需要的 Skill 文件夹复制到 Codex 用户级目录：

- Windows：`%USERPROFILE%\.agents\skills\`
- macOS/Linux：`~/.agents/skills/`

例如 Windows PowerShell：

```powershell
git clone https://github.com/saledomhost-code/chary.git
Copy-Item -Recurse .\chary\skills\* "$HOME\.agents\skills\"
```

安装后重新启动 Codex 或开启新会话。在对话中可以直接点名 Skill，例如：“使用「好品客户背调」分析这家客户”。

## 依赖说明

Skill 提供工作流程与输出规范。联网检索、读取表格、生成 Word/Excel/PDF 等能力取决于 Codex 当前可用的工具与环境。使用者应核对 Skill 中的外部工具和路径依赖。

## 授权

请查看 [LICENSE](LICENSE)。仓库公开可见不代表内容采用开源许可，也不自动授予复制或再分发权。
