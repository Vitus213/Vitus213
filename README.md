# agent-usage

由 nix-config 的 `agent-usage-report`（home-manager 定时任务）自动生成，分支只保留一个提交。

- `data/<host>.json`：每台主机的每日统计历史（Claude Code / Codex / omp）
- `agent-usage-compact.svg` / `agent-usage.svg`：活跃时长 + token + 折算成本（有额度，400×190 / 810 宽）
- `agent-time-compact.svg` / `agent-time.svg`：仅活跃时长（无额度，400×190 / 810 宽）
- `summary.json`：汇总结果
