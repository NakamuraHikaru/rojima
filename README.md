# Rojima HP

## Rojimaの現状
- 出店希望申込はメール
- 出店希望の度にメールをしている
- 出店確認メールを送っている
- 出店者リストは現在なし
- Facebookで出店者紹介
- お越しの方へのページがない
- 最新情報は基本的にFacebookで更新している

## 要望
- ホームページから出店希望の申し込み
- 出店者の情報をDBで保持
- 出店者情報をCSVで出力
- メールアドレスとパスワードの認証により前回の入力情報が表示される
- 出店者リスト
- 簡単なブログ機能

## メニュー
### TOP
- 最新記事
- 次回開催日時

### Rojimaとは[静的]
- Rojima詳細

### ブログ
- 一覧表示
- 詳細ページ
### 出店者リスト
- 一覧
- 今月、前月、翌月で表示
- 出店者詳細はポップアップ表示

### 出店者の方へ
- 申し込みについて[静的]
	- 申し込みについての詳細
- 出店申し込み
	- 申込みフォーム
	- 自身の店の前回の情報を表示（メアド・パスによる認証？）
- Q&A[静的]

### お越しの方へ
- アクセス[静的]
	- Googleマップ
	- 詳細は画像で表示
- Q&A[静的]

### お問い合わせ
- 総合お問い合わせフォーム

## 各メニューの現在状況
### TOP(https://rojima.sakura.ne.jp/)
- ページの生成のみ

### Rojimaとは(https://rojima.sakura.ne.jp/about/)
- 以前に作ってあったままの状態

### 出店者リスト(https://rojima.sakura.ne.jp/出店者)
- 回ごとに出店者を掲載することは可能
- "記事"として扱われてしまっているため、ブログ記事との棲み分けができていない

### ブログ(https://rojima.sakura.ne.jp/ブログ記事一覧)
- 記事一覧表示
- 記事詳細ページ

### 出店者の方へ
- 「出店者申し込みについて」のページの生成のみ
- 「出店申し込み」のページの生成のみ
- 「出店申し込み」ページはGoogleフォームを使用する可能性あり

### お越しの方へ(https://rojima.sakura.ne.jp/wp-admin/post.php?post=208&action=edit)
- ページの生成のみ
- アクセスの掲載
- Q&Aの掲載

### お問い合わせ
- 未着手

## 機能の現状
### 認証による前回出店情報の表示
### 出店者のCSV出力
- どのように出力するか要検討
### データベース
- 出店者テーブル
	- 出店者の情報
- 出店履歴
	- 開催日程
	- 出店者
### https
実装



