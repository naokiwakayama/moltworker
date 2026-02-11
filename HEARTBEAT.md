# HEARTBEAT.md

# Keep this file empty (or with only comments) to skip heartbeat API calls.
# Add tasks below when you want the agent to check something periodically.

## 設定ファイル変更時のルール
- SOUL.md, MEMORY.md, TOOLS.md, HEARTBEAT.md, AGENTS.md を編集したら
  ~/moltworker-repo 内の該当ファイルにも同じ変更を反映し、
  git commit & push すること
- コミットメッセージは変更内容を簡潔に記述する
  （例: "update TOOLS.md: add GitHub integration config"）

## 起動時チェック
- git config (user.name, user.email) が設定されてるか確認し、なければ設定する
- ~/moltworker-repo が存在するか確認し、なければcloneする
- git credential.helper が設定されてるか確認
- ~/.git-credentials が存在するか確認
- なければ再設定する（PATは環境変数 or 記憶から復元）
