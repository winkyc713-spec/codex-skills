# codex-skills

这是 winkyc713-spec 的个人 Codex skills 仓库，用于集中整理、审核、版本化和安装自建或经授权引用的 skills。

## 目录结构

```text
codex-skills/
├─ skills/                 # 每个子目录是一个可独立安装的 skill
│  └─ <skill-name>/
│     ├─ SKILL.md          # 必需
│     ├─ scripts/          # 可选：辅助脚本
│     ├─ references/       # 可选：按需加载的参考资料
│     ├─ assets/           # 可选：模板或静态资源
│     └─ agents/           # 可选：界面元数据
├─ templates/              # 新 skill 模板
├─ SOURCES.md              # 第三方来源、版本和许可证登记
└─ .gitignore
```

## 收录原则

1. 每个 skill 必须位于 `skills/<skill-name>/`，并包含完整的 `SKILL.md`。
2. 第三方 skill 在收录前应检查许可证、来源、脚本行为和外部依赖。
3. 在 `SOURCES.md` 记录上游仓库、固定版本或 commit、许可证与本地修改。
4. 不提交论文全文、数据集、密钥、令牌、账号信息或未获授权的材料。
5. 对外部脚本保持最小权限，并在安装前人工复核。

## 安装

可使用 Codex 的 skill installer 从本仓库安装单个 skill：

```powershell
python install-skill-from-github.py `
  --repo winkyc713-spec/codex-skills `
  --path skills/<skill-name>
```

也可以直接告诉 Codex：

> 使用 skill-installer，从 winkyc713-spec/codex-skills 安装 skills/<skill-name>。

安装完成后重启 Codex，使新 skill 被加载。
