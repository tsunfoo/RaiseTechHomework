# 第3回課題： 
![start up success bin_cloud9_dev](https://github.com/tsunfoo/RaiseTechHomework/assets/147902768/f5ca709a-07d8-411a-b3fb-5d320d952e54)
![fruit created successfully](https://github.com/tsunfoo/RaiseTechHomework/assets/147902768/7f0d572e-153e-429c-b4a5-fb6e396905ea)

##   課題の確認項目：

1. AP サーバーとは：
  - APサーバ（アプリケーションサーバ）とは、プログラムを動作させるサーバのことです。APサーバはWebブラウザからのリクエストを処理するWebサーバからの要求　を受けてプログラムを実行したり、必要に応じてDBサーバへの問い合わせや書き込み処理をし、処理結果をWebサーバへ提供する役割を担っています。

  - 本課題のAP名前とバージョン：　Puma (version: 5.6.5) 。AP切断した場合、ページアクセス不可。
![exiting puma](https://github.com/tsunfoo/RaiseTechHomework/assets/147902768/56c0cee1-326c-4dba-9c4a-aa3a47e55450)


2. DB サーバーとは：
  - データベース（Database）は、情報を効果的に管理し、検索、更新、挿入、削除などの操作を行うためのデータの組織化された集合体で
    す。データベースは、データの永続的な保存と効率的な取り扱いを可能にするために使用されます。

  - 本課題のDB サーバーとバージョン：MySQL (Server version: 8.0.35)。DB サーバーを終了させた場合、ページアクセル不可。
    ![stop sql read lock](https://github.com/tsunfoo/RaiseTechHomework/assets/147902768/108ac79b-655f-456d-9002-f4eba8b6fe8e)

3.Rails の構成管理ツール:　Bundler (version 2.3.14)


## 今回の課題の学び：
1.　基礎知識： サーバー、データーベース、アプリケーションの役割と関係性。

2.　Railsの事前設定に関して：
- データベースへの接続は講義通りにコマンドを実行しても何度も失敗したので、railsの事前設定に関する知識不足を痛感しました。 最終的接続成功したが、イレギュラーへの対処力を身に着けるために、引き続き自主的な学習が必要。

3. MySQLのトラブル：
- ”sudo service mysql stop”　コマンドでデーターベースを止めようとしたが "Failed to stop mysql.service: Unit mysql.service not loaded."というエラーメッセージが表示され、結局MySQLにログインし、READ LOCKコマンドでデーターバースへの接続で止めましたが、”sudo service mysql stop”　コマンドの失敗原因が不明,現在調べ中。
![sudo stop sql fail](https://github.com/tsunfoo/RaiseTechHomework/assets/147902768/923f7af5-4a16-4f80-adaf-e844d71ff945)


