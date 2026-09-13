# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
（第7版）
[Michael Hartl](https://www.michaelhartl.com/) 著
  > Railsチュートリアル第7版を使って、サンプルアプリケーションを作っています。第3章では、まず静的なページを作ります。


## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にある
ソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。


## 使い方

 Ruby 3.2.9が使えるMacで、手元にあるsample_appフォルダに移動し、
  必要なgemをインストールします。

  ```sh
  cd ~/repos/rails-learning/sample_app
  bundle install
  ```


次に、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

詳しくは、[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
を参考にしてください。
