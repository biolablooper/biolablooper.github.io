# public/game/ — 第3の売り（HTML クエスト）

**このフォルダは公開の売り物。アプリの付録ではない。移動禁止。**

| | |
|--|--|
| 本番 | https://protocol-site-c7duz2ygeq-an.a.run.app/game/ |
| 配信 | Cloud Run `protocol-site`（`VITE_PUBLIC_SURFACE=app` の静的配信） |
| セーブ | ブラウザ `localStorage` |
| AI | **Gemini なし**（手順検索 API も呼ばない） |

## ルール

- ゲームコード・アセットは **ここだけ**（別ツリーや Roblox をリポに足さない）
- Pages 側の `/game/` は本 URL への **リダイレクト**
- 育て方: クエスト内容 · オンボーディング · **開始/終了 CTA は `/tools/protocol-search` と `/tools/protocol-check` へ**（`/product` に戻さない）
- nginx は `/game/` だけ CSP を緩和（`nginx.site.conf`）

正本: [../../../CLAUDE.md](../../../CLAUDE.md) · [../../../docs/pillars/README.md](../../../docs/pillars/README.md) · [../../../DIRECTORY.md](../../../DIRECTORY.md)
