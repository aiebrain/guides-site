# guides-site

AI 도구 설치 가이드 모음 사이트.

## 구조
- `index.html` — 메인 페이지 (가이드 목록)
- `antigravity-claude-code.html` — Google Antigravity × Claude Code 설치 가이드
- `openclaw-obsidian.html` — Claude Code × OpenClaw × Obsidian 설치 가이드
- `build.mjs` — Obsidian 마크다운 → HTML 변환 스크립트

## 빌드
```bash
npm install
node build.mjs
```

## 배포
GitHub Pages (main 브랜치 루트)
