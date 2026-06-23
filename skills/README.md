# Skills

每个直接子目录应是一个可独立安装的 Codex skill。

最低要求：

```text
skills/
└─ skill-name/
   └─ SKILL.md
```

建议使用小写英文和连字符命名，例如 `public-database-mining`。

不要只复制 `SKILL.md`：如果它引用了 `scripts/`、`references/`、`assets/` 或 `agents/`，应保留完整的相对目录结构。
