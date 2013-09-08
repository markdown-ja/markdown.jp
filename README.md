# [日本語Markdownユーザー会](http://markdown.jp)

日本語Markdownユーザーのコミュニティ、「日本語Markdownユーザー会」のウェブサイトです。[石橋秀仁](http://ja.ishibashihideto.net/)が制作・運営しています。[http://markdown.jp](http://markdown.jp) をチェックしてください。

このサイトは [Bootstrap 3](http://getbootstrap.com) と [Jekyll](http://jekyllrb.com/) によって作られています。両ソフトウェアの開発者に感謝します。

ディレクトリ構成や Grunt の使い方などは、 GitHub の [twbs/bootstrap](https://github.com/twbs/bootstrap) を参考にしてください。このリポジトリを clone しました。

## サイト制作作業

Terminal を2つ開いて、`jekyll` と `grunt` を watch モードで走らせます：

- `jekyll serve -w` で Jekyll を watch → [http://localhost:9090](http://localhost:9090) をブラウザで開いてプレビューしながらコンテンツを編集
- `grunt watch` で Bootstrap を watch → `less/` を編集すれば自動的に less コンパイル処理が実行される

`grunt` を使うために、最初に `npm install` する必要があります。Jekyll がインストールされていない場合は `gem install jekyll` でインストールしてください。

## Authors

**石橋秀仁**

+ [http://twitter.com/zerobase](http://twitter.com/zerobase)
+ [http://github.com/zerobase](http://github.com/zerobase)


## Copyright and license

Copyright 2013 Ishibashi Hideto under [CC BY 3.0](LICENSE).
