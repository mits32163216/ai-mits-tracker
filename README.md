# AI-MITS 実装トラッカー v2

**🔒 これは AI-MITS プロジェクト実装手順書の唯一の正本（Source of Truth）です。**（2026-06-14 Mits確定）

公開URL：**https://mits32163216.github.io/ai-mits-tracker/**

裏（バックヤード）と表（インターフェース）を並列でチェック管理。localStorage 永続化（端末内のみ）。

---

## 正本ルール

- AI-MITS の **進捗・タスク・手順** はすべてこの tracker を正本として管理する
- 過去Notionページ（旧手順書・旧マッピング・旧計画）は **参照のみ**・正本扱い禁止
- 新しい進捗・手順は Notion ではなく tracker の HTML に追記して git push で反映

## 旧資料（参照のみ・正本扱い禁止）

| Notion ID | タイトル | 状態 |
|---|---|---|
| `35400782d90a8167b94bed3e08b0c8f5` | Corpus2Skill 実装手順書（AI-MITS）2026-05-09 | 旧版 |
| `35800782d90a8174827eceb4368fe6cb` | Branch × 教材マッピング v1.1（2026-05-06） | 旧版（v2.0 は tracker 管理） |
| `35800782d90a8183a4a2e7daf95ed932` | Branch × 教材マッピング v1.0 | 旧版 |

## 更新フロー

1. ローカル原本HTML を編集：
   `/Users/nishidamitsuhiro/My Drive/claude-nishida/経営プロジェクト/02_AI-MITS/_wip/aimits_implementation_tracker_v2_20260614.html`
2. `cp <ローカル原本> /tmp/ai-mits-tracker/index.html && cd /tmp/ai-mits-tracker && git add -A && git commit -m "..." && git push`
3. GitHub Pages で 30秒〜2分で本番反映

## 改訂履歴

- 2026-06-14 v2.0：裏／表 並列・チェック式・GitHub Pages 移行（旧 Notion 手順書を全面リライト）
- 2026-05-09 v1.0：旧 Notion 手順書（`35400782...`）
