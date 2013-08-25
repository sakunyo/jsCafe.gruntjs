

# Grunt + Proxy を使ったサンプル

grunt-connect-proxy と grunt-contrib-connect の middleware を使って

localhost:3000/api ディレクトリを localhost:8888/api に中継するサンプルです。

1. npm install を実行します。


		$ npm install


2. MAMPなどの別のWebサーバーを 8888 ポートで起動しましょう。
その中に api ディレクトリを作り、任意のファイルを置きましょう。


3. grunt を実行します。


		$ grunt


4. ブラウザで http://localhost:3000/api を開きます。
任意のファイルが表示されましたか？

Grunt の Proxy タスクでバックグラウンドに
Ruby や Perl や Apache、Nginx などの Node 以外のWebサーバーが使えます。

