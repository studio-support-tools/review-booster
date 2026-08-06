Heeeeat!口コミ作成サポート｜公開手順

1. ZIPを解凍する
2. Netlifyへログインする
3. 解凍したフォルダをNetlify Dropへドラッグ＆ドロップする
4. 発行されたURLをスマホで開いて確認する
5. そのURLをLINEで送る

【正式なGoogle口コミURLへ変更】
index.htmlを開き、以下を検索してください。
const GOOGLE_REVIEW_URL=

現在はテスト用のGoogle検索URLです。
正式導入時に、管理者発行の「クチコミを依頼」URLへ差し替えます。

例：
const GOOGLE_REVIEW_URL="https://g.page/r/XXXXXXXXXXXX/review";

【特徴】
・APIなし
・スプレッドシート連携なし
・入力内容の保存なし
・Googleログイン不要でページ閲覧可能
・文章生成はお客様の端末内だけで実行
