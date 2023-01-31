<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# アプリケーション名
* Doc Strage(資料保管庫)

# 開発理由
　私は以前、Vue.js（Nuxt.js）やFirebaseなどを使用して、”ポートフォリオのURLを投稿し公開すること”を目的としたWebアプリを開発し、それを自分のポートフォリオとして企業に就職しました。  
　しかし、恥ずかしながら世の中に公開できるほどのクオリティではなく、自分だけでポートフォリオを量産できるわけでもなかったので、参考にした記事や教材のURLを投稿し簡単にアクセスできるようにしていました。  
　結局、そのアプリは全く使用しない状態になってしまったのですが、Laravelを独学しアウトプットをしたかったため、以前開発したアプリの機能を基に、資料を保管するアプリを開発することにしました。  
　まだ完成ではありませんが、アプリとして最低限の機能を実装できたため、とりあえずデプロイしています。
<br>
 
　「このバグを解決した記事って、Qiitaだったっけ？Zennだったっけ？スタックオーバーフロー？個人ブログ？」など、ネット上のいろんなところにある有用な記事を一か所にまとめられたら便利だと思うので、ぜひ利用されてください。
<br>

　現在追加中の機能として、メール送信機能を考えています。  
　保存している記事をワンタッチでメール送信できると、同僚などがバグで困っている際に便利ではないかと思います。
 
<br>

# 主な使用要領
* 必要と感じたもの
* 開発時に参考にしたもの
* 今後、学習したい教材
* その他忘れたくない、ネット上のすべてのコンテンツ  
のURL保存できます。  
　また、メールアドレスを登録して、保存している記事をメール送信することができます。（機能追加作業中です。）
<br>

1. 新規登録またはテストアカウントでログインしてください
2. Doc Strageページに移動しフォームに自由に入力し、Strage!!ボタンを押してください
3. Docuentボタンをクリックすると別タブで登録したURLのページが表示されます
4. Editボタンを押すと、投稿の内容を編集できます
5. Deleteを押すと、投稿が削除されます
6. ヘッダーの入力欄に任意のワードを入力の上、Searchボタンを押すと、タイトル、カテゴリー、テキストの中で検索し、表示できます。

### どんなアプリか覗きたい方・試しに触ってみたい方・企業の採用担当者様
　「駆け出しエンジニアが作ったアプリに、個人情報を登録するなんてありえない」という方向けにテストアカウントを用意しています。  

> メールアドレス：test@test.com  
> パスワード　　：password123  

でログイン可能です。  
　テストアカウントの投稿には、私がこれまで学習で使用した記事や勉強しながらふと見た記事、ダミーデータで作成した投稿などが保存されています。  
　テストアカウントでも、通常のアカウントどおりのすべての機能が使用できます。  
　※テストアカウントを使用する際は、元々保存されているデータは操作しないで頂けると助かります。  
 <br>

### このアプリ使えるじゃんって思った方
新規登録の上使用していただけると喜びます。
<br>

# 機能一覧
* ログイン機能
* ログアウト機能
* ユーザー登録機能
* フォームのバリデーション機能（検証機能）
* 投稿機能
* 編集機能
* 削除機能（削除フラグを使用しています）
* 検索機能
* ページネーション機能
<br>

# アプリのURL
* https://yamachoki.sakura.ne.jp/Doc_Storage/
<br>

# 使用技術
* Laravel
* MySQL
* Tailwind css
* alpine.js
* JavaScript
<br>
