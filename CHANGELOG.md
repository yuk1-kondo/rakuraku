# 更新履歴 (CHANGELOG)

## [v2.1.0] - 2025-06-18

### 🎨 ブランドリニューアル
- **サービス名変更**: 「らくらく転送」→「シェアっと」
- **UI表示名更新**: 全画面でサービス名を統一
- **ドキュメント更新**: README、技術仕様書などを更新

## [v2.0.0] - 2025-06-17

### 🎉 主要機能の追加・改善
- **URL共有機能を追加**: スマホからPCへのURL共有が可能に
- **Firebase Realtime Database**: リアルタイムデータ同期を実装
- **認証システム**: アクセスコード認証とQRコード自動認証
- **タブ切り替え**: ファイルアップロードとURL共有のタブUIを実装

### 🔧 技術的改善
- **重複スクリプト問題を解決**: 複数の`<script>`タグによる変数衝突を解消
- **HTML構造の修正**: 正しいDOM構造に修正
- **エラーハンドリング強化**: try-catch文とデバッグ情報を追加
- **CSS最適化**: タブ切り替えとレスポンシブデザインを改善

### 🐛 修正されたバグ
- **画面が真っ白になる問題**: JSエラーによる初期化失敗を解決
- **URL共有ボタンが動作しない問題**: イベントリスナーとDOM取得の問題を修正
- **タブ切り替えの不具合**: CSSスタイルの不備を修正
- **文字化け問題**: PC側タイトルの文字化け記号を除去

### 🚀 デプロイメント
- **Firebase Hosting**: 本番環境への自動デプロイを実装
- **Firebase Realtime Database**: データベースルールの設定完了
- **本番URL**: https://rakupic-19e91.web.app

### 📱 動作確認済み機能
- PC→スマホ: QRコード生成とアクセス
- スマホ→PC: ファイルアップロード（リアルタイム受信）
- スマホ→PC: URL共有（リアルタイム受信）
- 認証システム: アクセスコード認証
- 自動認証: QRコードアクセス時の認証スキップ

---

## [v1.0.0] - 2025-06-16

### 🎉 初回リリース
- **基本的なファイル転送機能**: スマホからPCへのファイル転送
- **QRコード生成**: PC側でQRコード生成
- **シンプルなUI**: 基本的なアップロード画面

### 📋 技術スタック
- **Frontend**: HTML5, CSS3, JavaScript (ES6 Modules)
- **Backend**: Firebase Realtime Database
- **Hosting**: Firebase Hosting
- **QR Code**: QRious.js
- **Authentication**: カスタム認証システム

---

## 今後の予定
- [ ] ファイルタイプの制限機能
- [ ] アップロード履歴の表示
- [ ] 複数ファイルの同時アップロード
- [ ] ダークモード対応
- [ ] PWA対応
