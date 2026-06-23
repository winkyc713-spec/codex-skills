# Skill 来源登记

添加或更新第三方 skill 时，请填写一行。固定到具体 commit，便于审计和复现。

| Skill | 本仓库路径 | 上游仓库 | 上游路径 | 固定版本/Commit | 许可证 | 本地修改 | 最近核对 |
|---|---|---|---|---|---|---|---|
| Superpowers v6.0.3 | 独立 Fork：`winkyc713-spec/superpowers` | `obra/superpowers` | `skills/` | `896224c4b1879920ab573417e68fd51d2ccc9072` | MIT | 无 | 2026-06-23 |
| frontend-design | `skills/frontend-design` | `anthropics/skills` | `skills/frontend-design/` | `57546260929473d4e0d1c1bb75297be2fdfa1949` | Apache-2.0 | 无 | 2026-06-23 |
| Impeccable | 独立 Fork：`winkyc713-spec/impeccable` | `pbakaus/impeccable` | `.agents/skills/impeccable/` | `d2ab4ddee6fa63002fae680652b5fbd31735e280` | Apache-2.0 | 无 | 2026-06-23 |
| Nature Skills | 独立 Fork：`winkyc713-spec/nature-skills` | `Yuan1z0825/nature-skills` | `skills/nature-*` + `skills/_shared` | `5d2ba1dee1c087be6de8f4a8aad4b27f04974be9` | Apache-2.0 | 无 | 2026-06-23 |

## 核对清单

- 上游许可证允许复制、修改和再发布。
- `SKILL.md` 不包含越权、隐藏或与用途无关的指令。
- `scripts/` 不读取或上传密钥、私人文件及无关数据。
- 外部命令、网络访问和写入路径均与 skill 用途相符。
- 未提交受版权限制的论文全文、数据库导出或敏感信息。
