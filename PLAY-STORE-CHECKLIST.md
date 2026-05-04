# Google Play Store 提出チェックリスト

## 📋 完了済みアイテム

- [x] PWA 構築（HTML / manifest / service worker）
- [x] PNG アイコン（192 / 512）
- [x] プライバシーポリシー（`privacy.html`）
- [x] PWABuilder で Android パッケージ生成
- [x] `signing.keystore` 安全な場所に保管 ※必須
- [x] `assetlinks.json` を `koya800.github.io/.well-known/` に配置
- [x] Digital Asset Links 配信確認
- [x] Google Play Console アカウント作成

## 🎯 これからやること

### 本人確認（Google 側）
- [ ] パスポート or 運転免許証 or マイナンバーカードのアップロード
- [ ] 顔写真撮影
- [ ] 2〜3日待つ

### Play Console 内のアプリ作成
- [ ] 「アプリを作成」をクリック
- [ ] アプリ名: `タマゴクリッカー`
- [ ] デフォルト言語: 日本語
- [ ] アプリ・ゲーム: ゲーム
- [ ] 無料 / 有料: 無料
- [ ] ポリシー同意

### ストア掲載情報
- [ ] **アプリ名**: タマゴクリッカー
- [ ] **短い説明** (80字): `store-descriptions.txt` 参照
- [ ] **詳細な説明** (4000字): `store-descriptions.txt` 参照
- [ ] **アプリアイコン** (512×512 PNG): `icon-512.png` を使用
- [ ] **フィーチャーグラフィック** (1024×500 PNG): `gen-feature-graphic.html` で生成
- [ ] **スクリーンショット** (2〜8枚): スマホで撮影
- [ ] **アプリのカテゴリ**: ゲーム > カジュアル
- [ ] **タグ**: クリッカー、放置、コレクション、癒し
- [ ] **連絡先メール**: あなたのメール
- [ ] **ウェブサイト**: `https://koya800.github.io/tamago-clicker/`
- [ ] **プライバシーポリシー**: `https://koya800.github.io/tamago-clicker/privacy.html`

### スクリーンショット（必須2枚〜推奨5〜8枚）
スマホで撮影してください：
- [ ] メイン画面（卵タップ中）
- [ ] 図鑑（数キャラ集まった状態）
- [ ] 強化ショップ
- [ ] 実績画面
- [ ] 転生画面
- [ ] （任意）シナジー表示
- [ ] （任意）かけら大量獲得時の演出

撮影方法（Android）: 電源ボタン + 音量↓ 同時押し

### アプリのコンテンツ
- [ ] **広告**: 「いいえ、広告は含まれていません」
- [ ] **アプリのアクセス権**: 「全機能を制限なく利用できる」
- [ ] **コンテンツのレーティング**: アンケート回答
  - 暴力: なし
  - 性的表現: なし
  - 露骨な表現: なし
  - 賭博・カジノ: なし
  - 薬物・アルコール: なし
  → 結果: IARC 3+ または 全年齢
- [ ] **対象ユーザー**: 全年齢対象
- [ ] **ニュースアプリ**: いいえ
- [ ] **政府関連アプリ**: いいえ
- [ ] **金融機関のアプリ**: いいえ
- [ ] **データセーフティ**:
  - データを収集または共有する: **いいえ**
  - データは端末上で暗号化されて転送される: 該当なし（外部送信なし）
  - データの削除をユーザーが要求できる: アプリのアンインストールで全データ削除

### リリースの作成（本人確認完了後）
- [ ] 製品版 (Production) または 内部テスト (Internal testing) を選択
- [ ] **AAB ファイルをアップロード**: `app-release-bundle.aab`
- [ ] リリースノート: `初回リリース。卵をタップして生き物を集める癒し系クリッカーゲームです。`
- [ ] **アプリの整合性 (App signing)**: Google が管理する署名鍵を使用 (推奨)
- [ ] 国・地域の選択: 日本 (or 全世界)

### 公開申請
- [ ] すべての必須項目に ✓ が付いているか確認
- [ ] 「公開を開始」または「審査リクエスト」をクリック
- [ ] **審査期間: 通常 3〜7日**

---

## 📦 ファイルの場所

- AAB ファイル: `C:\Users\hukud\Desktop\タマゴ - Google Play package\app-release-bundle.aab`
- アイコン 512: `C:\Users\hukud\Documents\GitHub\tamago-clicker\icon-512.png`
- 説明文: `C:\Users\hukud\Documents\GitHub\tamago-clicker\store-descriptions.txt`
- Feature Graphic 生成: `C:\Users\hukud\Documents\GitHub\tamago-clicker\gen-feature-graphic.html` をブラウザで開く
- プライバシーポリシー URL: `https://koya800.github.io/tamago-clicker/privacy.html`

---

## 🔐 紛失厳禁

- `signing.keystore`
- `signing-key-info.txt`
- これらが無いと将来のアップデートが出せません！
- 推奨: Google Drive / OneDrive にバックアップ
