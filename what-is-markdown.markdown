---
layout: default
slug: what-is-markdown
title: Markdownとは
desc: "Markdownの概要、記法、HTMLとの関係"
base_url: "../"
---

## Markdownの概要

Markdown（マークダウン）は、**文章の書き方**です。デジタル文書を活用する方法として考案されました。特徴は、

- 手軽に文章構造を明示できること
- 簡単で、覚えやすいこと
- 読み書きに特別なアプリを必要としないこと
- それでいて、対応アプリを使えば快適に読み書きできること

などです。Markdownはジョン・グルーバー（John Gruber）によって2004年に開発され、最初は [Daring Fireball: Markdown](http://daringfireball.net/projects/markdown/) で公開されました。その後、多くの開発者の手を経ながら発展してきました。

## 文章構造

「文章構造」という言葉には馴染みがないかもしれませんが、じつは簡単なことです。文章には「章」や「節」といった「見出し」がありますね。また、本文には「段落」や「箇条書き」があります。こんにちのオンライン文書なら「リンク」も使われるでしょう。文章にはこうした「構造」があり、それを明示することで便利に読み書きできます。

以下の文章では、段落、強調、箇条書き、リンクが使われています：

> Markdown（マークダウン）は、**文章の書き方**です。デジタル文書を活用する方法として考案されました。特徴は、
> 
> - 手軽に文章構造を明示できること
> - 簡単で、覚えやすいこと
> - 読み書きに特別なアプリを必要としないこと
> - それでいて、対応アプリを使えば快適に読み書きできること
> 
> などです。Markdownはジョン・グルーバー（John Gruber）によって2004年に開発され、最初は [Daring Fireball: Markdown](http://daringfireball.net/projects/markdown/) で公開されました。その後、多くの開発者の手を経ながら発展してきました。

## Markdownの書き方

上の文章は、次のようなMarkdown記法で書かれています：

    Markdown（マークダウン）は、**文章の書き方**です。デジタル文書を活用する方法として考案されました。特徴は、

    - 手軽に文章構造を明示できること
    - 簡単で、覚えやすいこと
    - 読み書きに特別なアプリを必要としないこと
    - それでいて、対応アプリを使えば快適に読み書きできること

    などです。Markdownはジョン・グルーバー（John Gruber）によって2004年に開発され、最初は [Daring Fireball: Markdown](http://daringfireball.net/projects/markdown/) で公開されました。その後、多くの開発者の手を経ながら発展してきました。

みなさんが電子メールを書くときの書き方に似ていませんか？

Markdownの代表的なルールには：

- 段落は空行で、一行開ける
- 強調したい部分を `**` で囲む
- 箇条書きは行頭に `- `
- リンクは `[]` でリンクしたい文字を囲って、その直後の `()` の中にURLを書く

などがあります。Markdownとは、こういったルールの体系、つまり**文章の書き方**なのです。このようなルール（記法）に従うことで、私たちはMarkdown対応アプリの恩恵を受けることができます。

## Markdownのはじめかた

Markdownは、ふつうに電子メールを書く感覚で使えます。例えば、あなたが普段の電子メールで「空行で段落を表す」「引用を`> ` で表す」ようにしているなら、すでにあなたはMarkdownの記法を二つ知っていることになります。

おめでとうございます。あなたはもうMarkdownユーザーです。

もし興味があれば、Markdownの記法を調べてみましょう。様々な便利な機能があることが分かるでしょう。[Markdown記法](../syntax/)のページで詳しく紹介しています。しかし、最初は「段落」と「引用」だけでもいいのです。Markdownは「すべての記法を覚えなければ使えない」ようなものではありません。早速いまから「Markdownユーザー」としてMarkdownを活用しましょう。

## MarkdownとHTMLの関係

Markdownは、しばしばHTMLの代わりとして使われます。HTMLを書くのは大変です：

    <p>Markdown（マークダウン）は、<strong>文章の書き方</strong>です。デジタル文書を活用する方法として考案されました。特徴は、</p>

    <ul>
    <li>手軽に文章構造を明示できること</li>
    <li>簡単で、覚えやすいこと</li>
    <li>読み書きに特別なアプリを必要としないこと</li>
    <li>それでいて、対応アプリを使えば快適に読み書きできること</li>
    </ul>

    <p>などです。Markdownはジョン・グルーバー（John Gruber）によって2004年に開発され、最初は <a href="http://daringfireball.net/projects/markdown/">Daring Fireball: Markdown</a> で公開されました。その後、多くの開発者の手を経ながら発展してきました。</p>

HTMLを書くときには、`<p>` や `<li>` といった*HTMLタグ*をたくさん入力する必要があります。タグを打つことに注意が奪われてしまい、本来の文章作成に集中できません。ふだんの文章作成に気軽に使えるとは言いにくいですね。

MarkdownからHTMLに変換するのは簡単です。そのためのアプリが多数あります。「HTMLに出力すること」は、Markdownのもっとも一般的な活用法です。

## Markdownの広がり

Markdownを書くのに特別なソフトウェアは必要ありませんから、アイデア次第で様々な活用法が考えられます。

例えば[Evernote](https://evernote.com/intl/jp/)は人気のノートアプリですが、Markdownに対応していません。それでもMarkdownでノートを書くのに支障はありません。HTMLに変換する必要があれば、Markdown対応アプリにコピー＆ペーストします。ブログやCMS（コンテンツ管理システム）がMarkdownに対応していれば、そのままコピー＆ペーストで投稿できます。

今日も大勢のブロガーがMarkdownでブログを書いています。大勢の企業ウェブ担当者がMarkdownでコンテンツを書いています。大勢の人々がMarkdownで日常的なメモを書いています。

<div class="well well-lg">
  <p class="lead">Markdownの世界へようこそ！</p>
</div>

<div class="btn-group">
  <a href="{{ site.googlegroup_link }}" class="btn btn-primary btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From What-is-markdown', 'To markdown-ja']);" target="_blank">Googleグループ</a>
  <a href="{{ site.trello_link }}" class="btn btn-info btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From What-is-markdown', 'To Trello']);" target="_blank">活動計画</a>
  <a href="/syntax/" class="btn btn-default btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From What-is-markdown', 'To Syntax']);">Markdown記法</a>
  <a href="/apps/" class="btn btn-default btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From What-is-markdown', 'To Apps']);">アプリ</a>
</div>
