# TabCoffer

日本語 | [English](../README.md) | [中文](README_zh.md) | [Deutsch](README_de.md) | [Español](README_es.md) | [Français](README_fr.md)

ローカル優先のタブセッション管理。開いているタブを名前付き保管庫に収め、ワンクリックで取り戻せます。

> Chrome · Edge · Firefox · Manifest V3 · Local-first · No account · No tracking

---

## Free vs Pro

| 機能 | 無料 | Pro |
|------|------|------|
| 保存できるセッション | **3** | 100 |
| 1 セッションのタブ数 | **20** | 200 |
| ワンクリック保存・復元 | ✅ | ✅ |
| 改名・削除・並び替え | ✅ | ✅ |
| JSON 書き出し | ✅ | ✅ |
| セッションとタブの検索 | — | ✅ |
| JSON 読み込み（統合・重複除外） | — | ✅ |
| 復元時の重複スキップ／未オープンのみ | — | ✅ |

**保存・復元・書き出しは無料で、機能は制限されません。上限は 3 セッション × 20 タブのみです。** Pro は上限を引き上げ、検索・読み込み・2 つの精细な復元オプションを追加します。ライセンスは任意で、無料版では要求されません。

---

## How to use

1. まとめたいタブを開きます。
2. TabCoffer アイコンをクリックし、名前を入力して**セッションを保存**します。
3. タブを閉じてもセッションは保管庫に残ります。
4. 後でポップアップを開き、**新しいウィンドウで開く**か**このウィンドウに追加**を選びます。

---

## Privacy

セッション、タイトル、URL、アイコンはこの端末の `chrome.storage.local` にのみ保存されます。ページ本文は読まず、解析も送信しません。唯一のネットワーク要求は Pro 有効化時のライセンス確認で、`api.annmax1983.com` にライセンスキー・ランダムなインストール ID・ブラウザー情報のみを送り、セッションは送りません。

---

## Source

> このリポジトリはプロジェクト紹介用で、完全なソースコードは公開していません。公式ストアからインストールしてください。

---

## Licence

Get a licence: `https://annmax1983.com/checkout?plugin=tabcoffer`

Activate it: TabCoffer popup → ⚙ → enter the key.

Copyright © 2026 TabCoffer. All rights reserved. Closed source.
