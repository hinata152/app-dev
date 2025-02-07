
# アジャイル

## アジャイルとは

アジャイル開発手法やアジャイル開発という言葉を聞いたことがあるでしょうか?10年ほど前に比べて日本の開発現場でもよく聞かれるようになったかと思います。

この章ではアジャイルとは何か、アプリケーション開発から見たアジャイルを解説します。

### アジャイルソフトウェア開発宣言

そもそもアジャイルとは何か?と聞かれたら「ソフトウェア開発をよりよく行うために価値がある(と思われる)こと」と答えます。その根拠は[アジャイルマニフェスト](https://agilemanifesto.org/iso/ja/manifesto.html)から来ています。この文章のタイトルは「開発宣言」です。「開発手法」、つまりやり方ではありません。あくまで「経験則からこういう考え方には価値がある(と思われる)」ものの宣言でしかありません。

具体的に中身を見てみましょう。

*私たちは、ソフトウェア開発の実践*
*あるいは実践を手助けをする活動を通じて、*
*よりよい開発方法を見つけだそうとしている。*
*この活動を通して、私たちは以下の価値に至った。*

*プロセスやツールよりも個人と対話を、*
*包括的なドキュメントよりも動くソフトウェアを、*
*契約交渉よりも顧客との協調を、*
*計画に従うことよりも変化への対応を、*
*価値とする。すなわち、左記のことがらに価値があることを*
*認めながらも、私たちは右記のことがらにより価値をおく。 *

*Kent Beck*
*Mike Beedle*
*Arie van Bennekum*
*Alistair Cockburn*
*Ward Cunningham*
*Martin Fowler*
*James Grenning*
*Jim Highsmith*
*Andrew Hunt*
*Ron Jeffries*
*Jon Kern*
*Brian Marick*
*Robert C. Martin*
*Steve Mellor*
*Ken Schwaber*
*Jeff Sutherland*
*Dave Thomas*

*© 2001, 上記の著者たち*
*この宣言は、この注意書きも含めた形で全文を含めることを条件に自由にコピーしてよい。*

ご覧の通り、どこにも開発のやり方については書かれていません。より良い開発方法という意味で価値があると書かれているだけです。そして最初には「プロセスやツールよりも個人と対話を」と書かれています。プロセス（方法）やツールよりも個人と対話することに価値をおいています。つまりアジャイルソフトウェア開発宣言とは開発手法ではなく「開発がより良くなる（と思われる）考え方の羅列」でしかありません。

### アジャイル宣言の背後にある原則

このアジャイルソフトウェア開発宣言には、背景となる原則があります。[「アジャイル宣言の背後にある原則」](https://agilemanifesto.org/iso/ja/principles.html)と呼ばれるものです。

アジャイルソフトウェア開発宣言の詳細なのでここでは取り上げませんが、ぜひとも一読することをオススメします。

![アジャイル宣言の背後にある原則(抜粋)](agile_background)

### アジャイルプラクティス

ここまでアジャイルソフトウェア開発宣言についてみてきました。
しかし、一般的にアジャイルだと言われているカンバンやスプリント、ふりかえりなどのプラクティスはなんなのでしょうか?

これらは開発をより良くするための実践方法となります。あくまでも「より良くするための実践方法」であり、「実践することで良くなる方法」ではありません。プラクティスはそれぞれに目的や背景があり、それらを正しく理解し、実施者が「より良くする」ために行動しないと開発は良くなりません。

たとえば、ふりかえりを例に上げるとただ振り返れば良いと思って問題点を上げ続けたり、ふりかえりに参加するだけで意味があると思っている人がいます。ふりかえりは「過去の行動を見直し、未来の行動を決定する」ために行うものです。どんなに過去を振り返っても未来の行動が決定できなければ価値は半減してしまいます。またその未来の行動も価値がある(と判断した)ものでなければならず、一度決めたならその内容で行動しなければなりません。そうでなければ効果を正確に検証することが出来ないからです。

このようにより良くするために自ら考え行動することが肝要となります。受け身でやっていても良くなることはありません。

プラクティスは先人達がより良くしようと努力した結果に生まれたものであり、プラクティスを用いてより良くしようとしなければ意味がないのです。


### アジャイルが生まれた背景（歴史）

アジャイルの考え方が生まれた背景には、当時まで主流だった開発手法に対するアンチテーゼがきっかけとなっています。アジャイルやそれの元となった開発手法が登場するまでは、厳密に計画、管理され、規制されている開発手法（重量開発手法）が主流でした。この重量開発手法の問題点を解決するため、スクラムやエクストリームプラグラミング（XP）、クリスタルクリア、動的開発システム手法、ユーザー機能駆動開発などの新しい開発手法が発達していきました。

2001年、アメリカのユタ州、スノーバードに集まったこれらの開発手法の発明者たちは重量開発手法に対する軽量開発手法について議論し、アジャイルソフトウェア開発宣言を作成しました。

これがアジャイルが生まれた歴史となります。


## 実際のアジャイル

### 「アジャイルをやっています」

これまで書いてきたとおりアジャイルは「開発がより良くなる（と思われる）考え方の羅列」です。この考え方に従って実際により良い開発を目指している状態がアジャイルであるといえます。このようにアジャイルは状態、手法ではないのです。そのため、手法として「アジャイル開発をやっています」というのは間違った表現であり、アジャイルを正しく理解していないと思われても仕方ありません。

例えば自分たちの現状を正しく把握し、理想とする姿に向かって行動し続けている様をきちんと説明できるでしょうか?開発をより良くするということはチームや組織、サービスやプロダクトによって取るべき行動は変わってきます。一様に実施するプラクティスで良くなることもあるでしょうが、それが本当に「アジャイル」なのかどうか、考えてみましょう。

#### [column] 早い開発=アジャイル

重要なのはより良くしようとしているか?という考え方です。例えば早く開発することはアジャイルが生まれた背景の一つですが、もっとも大事にしているのは早さではありません。最初に挙げた宣言のとおりです。

例えばアジャイルは何かを省略することで早く開発する手法ではありません。必要があればドキュメントを作成しますし、それを顧客に提出することもあるでしょう。当然テストも実施します。ドキュメントを書いたりテストを実施したからといって「アジャイルではない」ということにはなりません。

アジャイルが生まれた背景にも速さに関連するものはひとつかふたつしか登場しません。同時に書かれているのは無駄がない、目的に沿った（お客様のため）、より良くすること、持続可能なということが書かれています。このことからも重要ではあるが、最も重要というわけではないのがわかると思います。

#### [/column]

### 2001年の価値

アジャイルソフトウェア開発宣言は2001年に発表されました。つまり約20年前の価値といっても過言ではないのです。アジャイルの考え方は当時の問題対策のために開発されたものでしかありません。

現在では当たり前であるスマートフォンは10年前の時点だとiPhone 3GSが発売されたぐらいです。日本ではまだ流行っていないか、流行り始めたところだったでしょう。当然20年前には市場には影も形もありませんでした。代わりに日本ではガラケーが市場を席巻していました。システム開発の現場では5年で見ても大きく状況は変わります。

それを踏まえて2019年のいま、20年前の事柄についていまその是非を議論したり、在り方を考えるのはどう思いますか?是非はおいておくにしても少なくとも20年前の話に対してなのだと認識するべきではあります。そのため、いまを生きる我々としては現在は何が問題なのか、これから先どうより良くしていくのか?ということを考えていくべきでしょう。

もちろん考えた結果、アジャイルが最適であるならばそれで良いのです。現状を把握して変化へ対応できるように行動していくのはアジャイルにおいて勝ちがある行動といえます。


## 開発手法との付き合い方

### アジャイルプラクティスとチーム

まずはこちらの画像をごらんください。

![アジャイルプラクティスのマップ](agile_map)

これは海外のブログに掲載された画像[^1]ですが、ここでは元の投稿内容には触れません。ここでは「これだけたくさんのプラクティスがある」ということが主題にとなります。

これだけあるとどれを選択して良いのか判断に非常に迷ってしまいます。そのため、まずは自分達（自分・チーム・組織）にあったものを選択するのが重要となってきます。そのためにも自分たちの現状を正しく把握する必要があるわけです。

そして正しく選択するにはプラクティスについて学び、試し、理解する必要があります。チームで実施するにはチームで学ぶ必要がありますし、試し理解するにもチームで行う必要があります。そのためチームビルディングは非常に重要な要素となります。

たくさんのプラクティスから自分たちにあったものを、自分たちで選ぶことができると良い状態であると言えます。そのためにもチームについても考えることもアジャイルにとって大事となります。

[^1]:引用元 https://medium.com/tech-sojourna/7-things-wrong-with-deloittes-agile-tube-map-641192e20068

#### [column] 最初に導入するプラクティスのススメ

いくつかの書籍やアジャイルコーチの話を聞くと最初は定期的な「ふりかえり」から導入すると良いそうです。これはふりかえりによって現状を把握できたり、カイゼンしている実感が得られて良い循環を回しやすくなったりするためだと言われています。

注意すべきなのは決してふりかえりが簡単だからというわけではないということです。ふりかえりと言っても数多くの型があり、それぞれに適した場面があります。なんとなくKPTが有名だから、KPTをチームで出せばふりかえりになると思っているなどのようにその手法について勉強せずに利用してもうまく行かない事が多いでしょう。

そこでチームでふりかえりについて学びつつ、ふりかえりから始めることをおすすめします。その際はふりかえり読本シリーズ[^2]がおすすめです。ぜひチームでふりかえりから始めてより良い開発を目指してみてください。

[^2]:ふりかえり読本シリーズ https://hurikaeri.booth.pm/
#### [/column]


### 開発手法

現在はスクラム、XP、ウォーターフォールなど様々な開発手法が存在しています。このうち、どれかが最高!というわけではありません。状況（人・リソース・状況・目的など）によって「そのときに最適な手法」は変わってきます。そのため、そのときの自分達に最適なものを選べるように備えておくのが変化に対する備えといえます。

いずれの手法も極めようとすると時間がかかってしまいます。どれかひとつを極めるよりも広く浅く勉強しつつ、現状に適応できる手法を一部(あるいすべて)適用するのがより現実的な解となります。実際に業務で開発する場合は様々なしがらみによって自由に手法を選べません。与えられた状況の中で最大限の成果を出しつつ、より良い方向に向いて進んでいけるとアジャイルの価値を体現しているといえます。

実際に多くのしがらみがある旧態依然とした現場で働いているエンジニアも、アジャイルな考え方を工夫して導入しています。そこでは古いものを頭ごなしに否定するのではなく、対話によって何故そうなっているのか?を解きほぐし、現状に合わせて認識をアップデートをし、カイゼンする試みが泥臭く行われています。Podcastでそのエンジニアの話を聞いた際も大変ではあるが楽しそうでした。

このことからもあまり深刻にならず、社内外に仲間を求め、より良い開発を求めて楽しくやっていくことが肝要だと感じます。この本を通してそういった活動が広がったらこんなにうれしいことはありません。ぜひ楽しく開発をして、それを発信していきましょう。

<!--

アジャイルプラクティスは、ここ以外の章にも、モノによってはしれっと入れていいかも

-->
