# templates/ の使い方

ここには **参考用のプロンプトファイル** を置きます。

## 追加方法（UIでOK）
1. GitHub で `Add file` → `Create new file`
2. `docs/prompts/templates/<ファイル名>.md` を入力
3. 本文にプロンプトを **そのままコピペ**（機微は `[MASKED]`）
4. `Commit directly to the main branch` で保存（自分のリポの場合）

## 命名ルール（例）
- ベース: `chat_to_gh_issue_backup_prompt_v1.2.md`
- 派生: `chat_to_gh_issue_backup_prompt_<variant>.md`（例: `_gpt.md`, `_claude.md`, `_gemini.md`）

## 注意
- **SOP（運用手順）**は本文/コメントに混在させない（`SECURITY.md`、`docs/OPERATIONS.md` を参照）
- 長文対策: 1コメント ≤30KB、≥10秒、1バッチ ≤5（失敗時はコメント代替）
- PREPEND前提: Indexはアンカー直下に **GFM（半角 `|`）** で1行追加
