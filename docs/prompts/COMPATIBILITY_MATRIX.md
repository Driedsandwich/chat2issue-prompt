# Prompt Compatibility Matrix

> 目的: 
> - "1セッション=1 Issue" バックアップ用プロンプトの**対応状況を一覧化**
> - まずは代表的クライアントから開始し、**PRで派生を収集**

| クライアント | ステータス | 備考 |
|---|---|---|
| ChatGPT (Web/Apps) | **Available** | `templates/chat_to_gh_issue_backup_prompt_v1.2.md` を利用
| Claude | **Placeholder** | `templates/claude/chat_to_gh_issue_backup_prompt_claude.md` にコピペで追加してください
| Cursor | **Placeholder** | `templates/cursor/chat_to_gh_issue_backup_prompt_cursor.md` にコピペで追加してください
| VS Code（拡張/エージェント等） | **Placeholder** | `templates/vscode/chat_to_gh_issue_backup_prompt_vscode.md` にコピペで追加してください
| Claude Code | **Placeholder** | `templates/claude-code/chat_to_gh_issue_backup_prompt_claude_code.md` にコピペで追加してください
| Codex（レガシ） | **Placeholder** | 廃止・非推奨の可能性があります。必要であれば `templates/codex/...` に追加し、注意書きを明記してください
| その他（MCP対応クライアント） | **PR Welcome** | `templates/<client>/...` で提案してください

## 追加の仕方（誰でもできます）
- **Issue で相談**："このクライアント用を追加したい"と書くだけでOK（非エンジニア歓迎）
- **直接 PR**：`docs/prompts/templates/<client>/...` に **UIでコピペ**→保存→PR。
  - 参考: `CONTRIBUTING.md`（チェック項目・命名ルール） / `.github/PULL_REQUEST_TEMPLATE.md`（チェックリスト）

> 注：各クライアント固有の挙動（投稿サイズ上限・レート・UIの差）は、プロンプト内に**注意書き**として記してください。
