# Perl入学式 2018年度 資料

これは, プログラミング未経験者〜初心者を対象に, Perlを題材にしてプログラミングの基礎を学ぶ勉強会, [Perl入学式](http://perl-entrance.org/)の2018年度用講義資料です.

ソースコードはGitHubの[perl-entrance-org/workshop-2018](https://github.com/perl-entrance-org/workshop-2018)リポジトリにあり, 成果物は[GitBook](https://www.gitbook.com/)を使って公開しています: [https://perl-entrance-org.gitbooks.io/workshop-2018/content/](https://perl-entrance-org.gitbooks.io/workshop-2018/content/)

----

## 資料に貢献する

誤字脱字の指摘や修正, 或いは資料の改善点の提案も, Perl入学式とその資料に対する立派な貢献です.
お気づきの点があれば, 遠慮なくPerl入学式のスタッフまで, 提案や指摘を頂けると助かります.

また, GitHubで公開されているPerl入学式の資料に対するPull Requestは大歓迎です.
以下の手順を参考に資料を修正して, リポジトリにPull Requestを送って下さい.

### 環境構築

gitbookを使っており, npmが必要です. ndenvなどでNode.jsの環境を構築しましょう.

```
$ npm install
```

で環境構築が完了します.

### ビルド

以下のコマンドで資料をビルドします. ビルドされた資料は, `_book`ディレクトリ以下に設置されます.

```
$ npm run build
```

### 資料をブラウザで見る

以下のコマンドを実行したあと, ブラウザで`http://localhost:4000`で資料を見ることができます.

```
$ npm run serve
```

### 資料を更新(公開)する

`workshop-2018`リポジトリの`master`ブランチにpushした内容がGitBookでビルドされ, 自動的に公開されます.
