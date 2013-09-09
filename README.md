# [日本語Markdownユーザー会](http://markdown.jp)

日本語Markdownユーザーのコミュニティ、「日本語Markdownユーザー会」のウェブサイトです。[石橋秀仁](http://ja.ishibashihideto.net/)が制作・運営しています。[http://markdown.jp](http://markdown.jp) をチェックしてください。

このサイトは [Bootstrap](http://getbootstrap.com)（バージョン 3）と [Jekyll](http://jekyllrb.com/) によって作られています。両ソフトウェアの開発者に感謝します。

ディレクトリ構成や Grunt の使い方などは、 GitHub の [twbs/bootstrap](https://github.com/twbs/bootstrap) を参考にしてください。このリポジトリを clone しました。


## サイト制作作業

Terminal を2つ開いて、`jekyll` と `grunt` を watch モードで走らせます：

- `jekyll serve -w` で Jekyll を watch → [http://localhost:9090](http://localhost:9090) をブラウザで開いてプレビューしながらコンテンツを編集
- `grunt watch` で Bootstrap を watch → `less/` を編集すれば自動的に less コンパイル処理が実行される

`grunt` を使うために、最初に `npm install` する必要があります。Jekyll がインストールされていない場合は `gem install jekyll` でインストールしてください。


## 作者

- 石橋秀仁
    - [http://ja.ishibashihideto.net](http://ja.ishibashihideto.net)
    - [https://github.com/zerobase](https://github.com/zerobase)


## 著作権とライセンス

このプロジェクトは [Bootstrap (twbs/bootstrap) の commit 1627905](https://github.com/twbs/bootstrap/commit/16279056ae1b3534f8c54b812492ce222dda6c8d) から派生しました。Bootstrap は Twitter, Inc によって Apache 2.0 ライセンスで提供されます。このプロジェクトも同ライセンスを引き継ぎます。

markdown.jp 固有のコンテンツは、石橋秀仁によって [CC BY 3.0](LICENSE) でライセンスされます。


## Copyright and license

This project is derived from [Bootstrap (twbs/bootstrap) commit 1627905](https://github.com/twbs/bootstrap/commit/16279056ae1b3534f8c54b812492ce222dda6c8d). Bootstrap is licensed under [the Apache 2.0 lisence](https://github.com/twbs/bootstrap/blob/master/LICENSE) by Twitter, Inc. This project inherits the same lisence.

Additional copyright materials of markdown.jp are licensed under [CC BY 3.0](LICENSE) by Ishibashi Hideto.
