# Prompts

`docs/prompts/templates/` に**参考用テンプレート**を置きます。
- 目的：あなたのLLM/用途に合わせて**派生**しやすくする
- セキュリティ：機微は `[MASKED]`、SOPは本文/コメントに混在させない（`SECURITY.md` 参照）
- 派生の投稿（PR）は `CONTRIBUTING.md` を参照

## 互換マトリクス
- `docs/prompts/COMPATIBILITY_MATRIX.md` を参照（ChatGPT=Available、Claude/Cursor/VSCode/Claude Code/Codex=Placeholder）

## 参考テンプレート
- ChatGPT: `docs/prompts/templates/chat_to_gh_issue_backup_prompt_v1.2.md`
- Claude: `docs/prompts/templates/claude/chat_to_gh_issue_backup_prompt_claude.md`（受け皿）
- Cursor: `docs/prompts/templates/cursor/chat_to_gh_issue_backup_prompt_cursor.md`（受け皿）
- VS Code: `docs/prompts/templates/vscode/chat_to_gh_issue_backup_prompt_vscode.md`（受け皿）
- Claude Code: `docs/prompts/templates/claude-code/chat_to_gh_issue_backup_prompt_claude_code.md`（受け皿）
- Codex（レガシ）: `docs/prompts/templates/codex/chat_to_gh_issue_backup_prompt_codex.md`（受け皿）

> 注意：利用時は**あなたの環境に合わせて**見直してください（リポ名／Indexタイトルなど）。
