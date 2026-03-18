# ウエストパーク社労士事務所 ウェブサイト

## 開発原則
- **KISS** (Keep It Simple, Stupid) - シンプルで理解しやすいコード
- **YAGNI** (You Aren't Gonna Need It) - 必要な機能のみ実装
- **DRY** (Don't Repeat Yourself) - 重複を避ける

## プロジェクト概要
福岡・北九州エリアの社労士事務所「ウエストパーク社労士事務所」の公式ウェブサイト
ポジショニング：「賃上げ×生産性向上の両立を実現する社労士」「助成金×DXのワンストップ窓口」

## 技術構成
- **フロントエンド**: HTML5, Tailwind CSS (CDN), JavaScript
- **デザイン**: サイドバーレイアウト、レスポンシブ対応
- **フォーム**: EmailJS
- **ホスティング**: Cloudflare Pages

## ファイル構成
- `docs/` - 公開用HTMLファイル群（Cloudflare Pages用）
  - `index.html` - トップページ（LP型）
  - `services.html` - 助成金申請サポート
  - `subsidies.html` - DX導入支援
  - `about.html` - 代表紹介
  - `pricing.html` - 料金案内
  - `faq.html` - よくある質問
  - `contact.html` - 無料相談・お問い合わせ
  - `diagnosis.html` - 助成金簡易診断（準備中）
  - `blog.html` - コラム・最新情報（準備中）
  - `images/` - 画像ファイル
- `20260318_NEW/` - HPコンテンツ設計書・営業資料
- `Design.md` - ウェブサイト設計書
- `01-05-*.md` - コンテンツファイル（分割済み）

## EmailJS設定
以下の値を実際のEmailJS設定に変更：
- `YOUR_EMAILJS_USER_ID`
- `YOUR_SERVICE_ID`
- `YOUR_TEMPLATE_ID`

## コミット規則
- 絵文字を使用（📝 ✨ 🐛 🎨 等）

## 連絡先
- **代表**: 野口 聡（のぐち さとる）（特定社会保険労務士）
- **電話**: 080-3948-2324
- **メール**: westpark-sr@gmail.com

## 設計方針（2026年3月リニューアル）
- ターゲット: 中小企業経営者 / 士業 / 建設・不動産業界
- FP資格: HP非表示（保有資格欄のみ）
- 労働局勤務: HP非掲載（対面の隠し玉）
- 労務顧問: 積極的に推さない（メニューに存在する程度）
- 地域: 北九州・福岡広域 + オンライン全国
