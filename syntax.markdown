---
layout: default
slug: syntax
title: Markdown記法
desc: "Markdownの書き方（記法）の紹介"
base_url: "../"
---

## Markdown記法とは

Markdownには「書き方のルール」（記法）があります。

Markdownで書いたテキストと、そのHTML出力例のペアで紹介していきます。

## 段落

段落どうしは空行で分けます。

Markdown:

    日本国民は、正当に選挙された国会における代表者を通じて行動し（略）この憲法は、かかる原理に基くものである。われらは、これに反する一切の憲法、法令及び詔勅を排除する。
    
    日本国民は、恒久の平和を念願し、（略）平和のうちに生存する権利を有することを確認する。
    
    われらは、いづれの国家も、自国のことのみに専念して他国を無視してはならないのであつて、政治道徳の法則は、普遍的なものであり、この法則に従ふことは、自国の主権を維持し、他国と対等関係に立たうとする各国の責務であると信ずる。
    
    日本国民は、国家の名誉にかけ、全力をあげてこの崇高な理想と目的を達成することを誓ふ。

このMarkdownが以下のようになります：

> 日本国民は、正当に選挙された国会における代表者を通じて行動し（略）この憲法は、かかる原理に基くものである。われらは、これに反する一切の憲法、法令及び詔勅を排除する。
> 
> 日本国民は、恒久の平和を念願し、（略）平和のうちに生存する権利を有することを確認する。
> 
> われらは、いづれの国家も、自国のことのみに専念して他国を無視してはならないのであつて、政治道徳の法則は、普遍的なものであり、この法則に従ふことは、自国の主権を維持し、他国と対等関係に立たうとする各国の責務であると信ずる。
> 
> 日本国民は、国家の名誉にかけ、全力をあげてこの崇高な理想と目的を達成することを誓ふ。


## 箇条書き

箇条書きは、行頭に半角ハイフン＋スペース (`- `) を置きます。スペースを忘れがちなので気をつけましょう。

Markdown:

    天皇は、内閣の助言と承認により、国民のために、左の国事に関する行為を行ふ。

    - 憲法改正、法律、政令及び条約を公布すること。
    - 国会を召集すること。
    - （略）
    - 儀式を行ふこと。

このMarkdownが以下のようになります：

> 天皇は、内閣の助言と承認により、国民のために、左の国事に関する行為を行ふ。
> 
> - 憲法改正、法律、政令及び条約を公布すること。
> - 国会を召集すること。
> - （略）
> - 儀式を行ふこと。


## 引用

引用は、行頭に半角不等号 (`>`) を置きます。

Markdown:

    新聞をひろげてみて次のような三面記事が出ていない日はほとんどあるまい。

    > 水曜日から木曜日にかけての深更、某街四十番地所在の家屋に住む者は連続的に二発放たれた銃声に夢を破られた。（略）
    > 
    > 某氏（五七）はかなり楽な生活をしていた人で、幸福であるために必要であるものはすべて具っていたのである。*何が*氏をしてかかる不幸な決意をなすに到らしめたのか、原因は全く不明である。

このMarkdownが以下のようになります：

> 新聞をひろげてみて次のような三面記事が出ていない日はほとんどあるまい。
> 
> > 水曜日から木曜日にかけての深更、某街四十番地所在の家屋に住む者は連続的に二発放たれた銃声に夢を破られた。（略）
> > 
> > 某氏（五七）はかなり楽な生活をしていた人で、幸福であるために必要であるものはすべて具っていたのである。*何が*氏をしてかかる不幸な決意をなすに到らしめたのか、原因は全く不明である。


## リンク

リンクしたいテキストを半角 `[]` で囲み、それに続く半角 `()` にリンク先URLを書きます。

Markdown:

    ウェブ関連技術の標準化は [World Wide Web Consortium (W3C)](http://www.w3.org/) などによって行われています。

このMarkdownが以下のようになります：

> ウェブ関連技術の標準化は [World Wide Web Consortium (W3C)](http://www.w3.org/) などによって行われています。

アプリによっては `[` の直前や `)` の直後に空白 (` `) が必須ですので、お気をつけ下さい。[^foreign_apps]

URLを段落外に出す方法もあります。

Markdown:

    [W3C] のほか、[Internet Engineering Task Force (IETF)] という団体もあります。

    [W3C]: http://www.w3.org/
    [Internet Engineering Task Force (IETF)]: http://www.ietf.org/

このMarkdownが以下のようになります：

> [W3C] のほか、[Internet Engineering Task Force (IETF)] という団体もあります。
> 
> [W3C]: http://www.w3.org/
> [Internet Engineering Task Force (IETF)]: http://www.ietf.org/

## 強調

強調したい文字を半角 `*` で囲むと、強調になります：

Markdown:

    彼*が*支払ったのではなく、彼*に*私が支払ったのです。

このMarkdownが以下のようになります：

> 彼*が*支払ったのではなく、彼*に*私が支払ったのです。

`*` はHTMLの `<em>` タグに対応しており、ふつうは <span style="font-style: italic;">斜体</span> で表示されます。ですから日本語の文章では使いにくいかもしれません。 [^visual]

さらに強い強調は、半角 `*` を片側2個ずつにします：

Markdown:

    彼女はコーヒーで口の中のパンを嚥み下してからじっと僕の顔を見た。
    
    **「嘘つき！」**
    
    と彼女は言った。

このMarkdownが以下のようになります：

> 彼女はコーヒーで口の中のパンを嚥み下してからじっと僕の顔を見た。
> 
> **「嘘つき！」**
> 
> と彼女は言った。

`**` はHTMLの `<strong>` タグに対応しており、ふつうは <span style="font-style: bold; font-weight: 800;">太字</span> で表示されます。

<div class="well well-lg">
  <p class="lead">Markdown記法は簡単ですね！</p>
</div>

<div class="btn-group">
  <a href="{{ site.googlegroup_link }}" class="btn btn-primary btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From Syntax', 'Next markdown-ja']);" target="_blank">Googleグループ</a>
  <a href="{{ site.trello_link }}" class="btn btn-info btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From Syntax', 'To Trello']);" target="_blank">活動計画</a>
  <a href="/what-is-markdown/" class="btn btn-default btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From Syntax', 'Next What-is-markdown']);">Markdownとは</a>
  <a href="/apps/" class="btn btn-default btn-lg" onclick="_gaq.push(['_trackEvent', 'Next actions', 'From Syntax', 'To Apps']);">アプリ</a>
</div>

[^foreign_apps]: 日本語の処理を考慮していないアプリ、とくに海外で開発されたアプリで顕著です。日本語Markdownユーザー会は、外国製アプリの日本語対応を推進します。

[^visual]: 見た目のついての注意点です。HTML出力の見た目は、環境によって変わります。具体的には、HTMLに適用されるスタイルシート(CSS)や、ブラウザによって。ですから、このページとは異なる見た目になることもあります。
