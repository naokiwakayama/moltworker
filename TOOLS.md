# TOOLS.md - Local Notes

Skills define *how* tools work. This file is for *your* specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:
- Camera names and locations
- SSH hosts and aliases  
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Examples

```markdown
### Cameras
- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH
- home-server → 192.168.1.100, user: admin

### TTS
- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Slack行動ルール
- メッセージを受け取ったらまずスタンプ（リアクション）を付ける
- メンションなしでも反応する
- **返信は必ずスレッド形式で行う**（元のメッセージに対してスレッドで返信）
- チャンネル: C052GSRK97C

## GitHub連携
- リポジトリ: https://github.com/naokiwakayama/moltworker
- ローカルパス: ~/moltworker-repo
- push手順: `cd ~/moltworker-repo && git add -A && git commit -m "説明" && git push`
- 認証: 環境変数 `GITHUB_PAT` を使用

## Slackスレッドメモリ
- `memory/slack-threads/` にスレッドごとの記憶を保存
- ファイル名: `{thread_ts}_{トピック名}.md`
- Slackメッセージ受信時、同一スレッドのファイルがあれば読み込む
- トピック名は最初の数メッセージから自動推測
- 会話の区切りでファイルを更新する

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.
