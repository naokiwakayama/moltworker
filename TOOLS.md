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

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

## GitHub連携
- リポジトリ: https://github.com/naokiwakayama/moltworker
- ローカルパス: ~/moltworker-repo
- push手順: `cd ~/moltworker-repo && git add -A && git commit -m "説明" && git push`
- 認証: 環境変数 `GITHUB_PAT` を使用

---

Add whatever helps you do your job. This is your cheat sheet.
