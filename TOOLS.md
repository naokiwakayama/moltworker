# TOOLS.md - Local Notes

Skills define *how* tools work. This file is for *your* specifics — the stuff that's unique to your setup.

---

## Oura Ring API

環境変数 `ouraring_API_KEY` でAPIアクセス可能。

### ジム通知対応
- **トリガー:** Macrodroidからジム退出時に自動通知が飛んでくる
- **対応:** Oura APIから最新の健康データ（readiness/sleep/activity）を取得し、励ましの言葉をかける
- **注意:** 毎回違う言葉で、やる気が出るメッセージを送る

### ユーザーのジムルーティン
- **タイミング:** 平日朝
- **持ち物:** プロテイン、クレアチン
- **ジム後:** コメダで1時間弱作業
- **帰宅後:** リモートワーク本格始業

---

## GitHub連携

- リポジトリ: https://github.com/naokiwakayama/moltworker
- ローカルパス: ~/moltworker-repo
- push手順: `cd ~/moltworker-repo && git add -A && git commit -m "説明" && git push`
- 認証: 環境変数 `GITHUB_PAT` を使用

---

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.
