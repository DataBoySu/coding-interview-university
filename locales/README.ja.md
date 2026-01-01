<!--START_SECTION:navbar-->
<div align="center">
  <a href="../README.md">🇺🇸 English</a> | <a href="README.de.md">🇩🇪 Deutsch</a> | <a href="README.es.md">🇪🇸 Español</a> | <a href="README.fr.md">🇫🇷 Français</a> | <a href="README.ja.md">🇯🇵 日本語</a> | <a href="README.ko.md">🇰🇷 한국어</a> | <a href="README.pt.md">🇵🇹 Português</a> | <a href="README.ru.md">🇷🇺 Русский</a> | <a href="README.zh.md">🇨🇳 中文</a>
</div>
<!--END_SECTION:navbar-->

# コーディング面接大学

> 元々これはソフトウェアエンジニアになるための短期間の学習トピックリストとして作成したが、
> それが今日あなたが見る大規模なリストに成長した。この学習計画を経て、[アマゾンのソフトウェア開発エンジニアとして採用された](https://startupnextdoor.com/ive-been-acquired-by-amazon/?src=ciu)！
> あなたは私がしたようにそれほど多く学ばなければならないわけではないだろう。いずれにせよ、必要なすべての情報はここにある。
>
> 私は数か月間、1日8〜12時間ほど学習した。私の物語はここにある：[なぜ私はグーグルの面接のために8か月間フルタイムで勉強したのか](https://medium.freecodecamp.org/why-i-studied-full-time-for-8-months-for-a-google-interview-cc662ce9bb13)
>
> **ご注意ください：** 私がしたようにそれほど多く学ばなければならないわけではない。私は多くの時間を必要でないことに費やした。その詳細については下記に記載している。私はあなたの貴重な時間を無駄にすることなくそこまで導くお手伝いをします。
>
> ここに記載されている項目は、アマゾン、フェイスブック、グーグル、マイクロソフトなどの巨大企業を含む、ほぼすべてのソフトウェア会社の技術面接に十分に対応する準備を整えるでしょう。
>
> *あなたが良い運を祈っています！*

<details>
<summary>Translations:</summary>

- [Bahasa Indonesia](../translations/README-id.md)
- [Bulgarian](../translations/README-bg.md)
- [Español](../translations/README-es.md)
- [German](../translations/README-de.md)
- [Japanese (日本語)](../translations/README-ja.md)
- [Marathi](../translations/README-mr.md)
- [Polish](../translations/README-pl.md)
- [Português Brasileiro](../translations/README-ptbr.md)
- [Russian](../translations/README-ru.md)
- [Tiếng Việt - Vietnamese](../translations/README-vi.md)
- [Urdu - اردو](../translations/README-ur.md)
- [Uzbek](../translations/README-uz.md)
- [বাংলা - Bangla](../translations/README-bn.md)
- [ខ្មែរ - Khmer](../translations/README-kh.md)
- [简体中文](../translations/README-cn.md)
- [繁體中文](../translations/README-tw.md)
</details>

<details>
<summary>Translations in progress:</summary>

- [Afrikaans](https://github.com/jwasham/coding-interview-university/issues/1164)
- [Arabic](https://github.com/jwasham/coding-interview-university/issues/98)
- [French](https://github.com/jwasham/coding-interview-university/issues/89)
- [Greek](https://github.com/jwasham/coding-interview-university/issues/166)
- [Italian](https://github.com/jwasham/coding-interview-university/issues/1030)
- [Korean(한국어)](https://github.com/jwasham/coding-interview-university/issues/118)
- [Malayalam](https://github.com/jwasham/coding-interview-university/issues/239)
- [Persian - Farsi](https://github.com/jwasham/coding-interview-university/issues/186)
- [Telugu](https://github.com/jwasham/coding-interview-university/issues/117)
- [Thai](https://github.com/jwasham/coding-interview-university/issues/156)
- [Turkish](https://github.com/jwasham/coding-interview-university/issues/90)
- [Українська](https://github.com/jwasham/coding-interview-university/issues/106)
- [עברית](https://github.com/jwasham/coding-interview-university/issues/82)
- [हिन्दी](https://github.com/jwasham/coding-interview-university/issues/81)
</details>

## これは何ですか？

![Coding at the whiteboard - from HBO's Silicon Valley](https://d3j2pkmjtin6ou.cloudfront.net/coding-at-the-whiteboard-silicon-valley.png)

This is my multi-month study plan for becoming a software engineer for a large company.

**Required:**
* A little experience with coding (variables, loops, methods/functions, etc)
* Patience
* Time

Note this is a study plan for **software engineering**, not frontend engineering or full-stack development. There are really
super roadmaps and coursework for those career paths elsewhere (see https://roadmap.sh/ for more info).

There is a lot to learn in a university Computer Science program, but only knowing about 75% is good enough for an interview, so that's what I cover here.
For a complete CS self-taught program, the resources for my study plan have been included in Kamran Ahmed's Computer Science Roadmap: https://roadmap.sh/computer-science

---

## 目次

### 学習計画

- [これは何ですか？](#what-is-it)
- [なぜ使うべきですか？](#why-use-it)
- [どうやって使うか](#how-to-use-it)
- [自分は十分に賢くないと思うな](#dont-feel-you-arent-smart-enough)
- [動画リソースに関する注意点](#a-note-about-video-resources)
- [プログラミング言語の選択](#choose-a-programming-language)
- [データ構造とアルゴリズムのための書籍](#books-for-data-structures-and-algorithms)
- [面接準備のための書籍](#interview-prep-books)
- [私の間違いを繰り返さないで](#dont-make-my-mistakes)
- [見られない内容について](#what-you-wont-see-covered)
- [日々の計画](#the-daily-plan)
- [コーディング問題の練習](#coding-question-practice)
- [コーディング問題](#coding-problems)

### 学習トピック

- [アルゴリズムの複雑性 / Big-O / 非常に近似分析](#algorithmic-complexity--big-o--asymptotic-analysis)
- [データ構造](#data-structures)
    - [配列](#arrays)
    - [リンクリスト](#linked-lists)
    - [スタック](#stack)
    - [キュー](#queue)
    - [ハッシュテーブル](#hash-table)
- [さらに知識](#more-knowledge)
    - [二分探索](#binary-search)
    - [ビット演算](#bitwise-operations)
- [木構造](#trees)
    - [木構造 - はじめに](#trees---intro)
    - [二分探索木: BSTs](#binary-search-trees-bsts)
    - [ヒープ / 優先キュー / 二分ヒープ](#heap--priority-queue--binary-heap)
    - 平衡探索木 (一般的な概念、詳細はなし)
    - トレーバーサル: preorder, inorder, postorder, BFS, DFS
- [ソート](#sorting)
    - 選択ソート
    - 挿入ソート
    - ヒープソート
    - クイックソート
    - マージソート
- [グラフ](#graphs)
    - 有向グラフ
    - 無向グラフ
    - 隣接行列
    - 隣接リスト
    - トレーバーサル: BFS, DFS
- [さらにさらに知識](#even-more-knowledge)
    - [再帰](#recursion)
    - [動的計画法](#dynamic-programming)
    - [デザインパターン](#design-patterns)
    - [組み合わせ論 (n choose k) & 確率](#combinatorics-n-choose-k--probability)
    - [NP, NP-Complete および近似アルゴリズム](#np-np-complete-and-approximation-algorithms)
    - [コンピュータがプログラムを処理する方法](#how-computers-process-a-program)
    - [キャッシュ](#caches)
    - [プロセスとスレッド](#processes-and-threads)
    - [テスト](#testing)
    - [文字列検索 & 操作](#string-searching--manipulations)
    - [トライ](#tries)
    - [浮動小数点数](#floating-point-numbers)
    - [ユニコード](#unicode)
    - [エンディアン](#endianness)
    - [ネットワーキング](#networking)
- [最終確認](#final-review)

### ジョブの獲得

- [履歴書の更新](#update-your-resume)
- [求人情報の確認](#find-a-job)
- [面接プロセスおよび一般的な面接準備](#interview-process--general-interview-prep)
- [面接が来る際の準備](#be-thinking-of-for-when-the-interview-comes)
- [面接官に質問する](#have-questions-for-the-interviewer)
- [就職後](#once-youve-got-the-job)

**---------------- 以下の内容はすべて任意です ----------------**

### オプショナルな追加トピックとリソース

- [追加の本](#additional-books)
- [システム設計、スケーラビリティ、データ処理](#system-design-scalability-data-handling) (4年以上の経験がある場合)
- [追加の学習](#additional-learning)
    - [コンパイラ](#compilers)
    - [Emacsとvi(m)](#emacs-and-vim)
    - [Unixコマンドラインツール](#unix-command-line-tools)
    - [情報理論](#information-theory-videos)
    - [パリティとハミング符号](#parity--hamming-code-videos)
    - [エントロピー](#entropy)
    - [暗号技術](#cryptography)
    - [圧縮](#compression)
    - [コンピュータセキュリティ](#computer-security)
    - [ガベージコレクション](#garbage-collection)
    - [並列プログラミング](#parallel-programming)
    - [メッセージング、シリアライズ、キューイングシステム](#messaging-serialization-and-queueing-systems)
    - [A*](#a)
    - [高速フーリエ変換](#fast-fourier-transform)
    - [ブロームフィルタ](#bloom-filter)
    - [ハイパーコログログ](#hyperloglog)
    - [ローカリティセンシティブハッシュ](#locality-sensitive-hashing)
    - [van Emde Boas木](#van-emde-boas-trees)
    - [拡張データ構造](#augmented-data-structures)
    - [バランス付き検索木](#balanced-search-trees)
        - AVL木
        - スプレイ木
        - 赤黒木
        - 2-3検索木
        - 2-3-4木 (2-4木とも呼ばれる)
        - N-ary (K-ary, M-ary)木
        - B木
    - [k-D木](#k-d-trees)
    - [スキップリスト](#skip-lists)
    - [ネットワークフロー](#network-flows)
    - [離散集合とユニオンファインド](#disjoint-sets--union-find)
    - [高速処理のための数学](#math-for-fast-processing)
    - [トレープ](#treap)
    - [線形計画法](#linear-programming-videos)
    - [幾何学、凸包](#geometry-convex-hull-videos)
    - [離散数学](#discrete-math)
- [いくつかのトピックに関する追加の詳細](#additional-detail-on-some-subjects)
- [動画シリーズ](#video-series)
- [コンピュータ科学コース](#computer-science-courses)
- [論文](#papers)

---

## なぜこれを使用するのか？

大規模な会社でソフトウェアエンジニアとして働きたいのであれば、これらのことについて知っておく必要があります。

コンピュータ科学の学位を取得できなかった場合（私はそうでした）、この資料で補ってもらい、4年間の時間を節約できます。

このプロジェクトを始めた当初、スタックとヒープの違いすらわからず、ビッグ・オー（Big-O）に関する知識も、木構造やグラフのトラバース方法についても何も知りませんでした。ソートアルゴリズムを自分で書かなければいけたとしたら、それは非常に酷いものだったでしょう。これまでに使ったすべてのデータ構造は言語に組み込まれており、その内部の仕組みについては全く理解していませんでした。メモリを管理する必要があったのは、実行しているプロセスが「メモリ不足」のエラーを出すときだけでした。そのときは、代替案を探さなければなりませんでした。人生のどこかで多次元配列や数千の連想配列を使用したことはありますが、データ構造をゼロから作成したことは一度もありません。

これは長期的な計画です。あなたにとって何カ月かかるかはわかりません。すでにこれらの大半を理解しているのであれば、かかる時間ははるかに短くなります。

**[⬆ トップに戻る](#table-of-contents)**

## 使い方

以下は概要であり、上から順に項目を処理する必要があります。

私はGitHubの特別なマーカダウンの形式を使用しており、進行状況を追跡するためにタスクリストを含んでいます。
  - [GitHub風マーカダウンについての詳細](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

### gitを使用したくない場合

このページで、上部にあるCodeボタンをクリックし、「Download ZIP」をクリックしてください。ファイルを解凍すると、テキストファイルを使用できます。

Markdownを理解するコードエディタで開いている場合、すべてが整った形式で表示されます。

![ZIPファイルとしてリポジトリをダウンロードする方法](https://d3j2pkmjtin6ou.cloudfront.net/how-to-download-as-zip.png)

### gitに慣れている場合

新しいブランチを作成して、このような項目を確認できます。括弧内にxを入力してください: [x]

1. ***GitHubリポジトリをフォークしてください:*** `https://github.com/jwasham/coding-interview-university` にフォークボタンをクリックしてください。

    ![GitHubリポジトリをフォーク](https://d3j2pkmjtin6ou.cloudfront.net/fork-button.png)

1. ローカルリポジトリにクローンしてください:

```bash
    git clone https://github.com/<YOUR_GITHUB_USERNAME>/coding-interview-university.git
    cd coding-interview-university
    git remote add upstream https://github.com/jwasham/coding-interview-university.git
    git remote set-url --push upstream DISABLE  # so that you don't push your personal progress back to the original repo
    ```

1. 変更を完了した後、すべてのボックスにXを記入してください:

```bash
    git commit -am "Marked personal progress"
    git pull upstream main  # keep your fork up-to-date with changes from the original repo

    git push # just pushes to your fork
    ```

**[⬆ トップに戻る](#table-of-contents)**

## 頭が良くないと感じている必要はありません

- 成功したソフトウェアエンジニアは頭が良いですが、多くの人は自分が十分に頭が良いとは思っていません。
- 以下の動画は、この不安を克服するのに役立つかもしれません：
    - [The myth of the Genius Programmer](https://www.youtube.com/watch?v=0SARbwvhupQ)
    - [It's Dangerous to Go Alone: Battling the Invisible Monsters in Tech](https://www.youtube.com/watch?v=1i8ylq4j_EY)

**[⬆ back to top](#table-of-contents)**

## ビデオリソースに関する注意点

一部のビデオは、CourseraまたはEdXのクラスに登録しないとアクセスできません。これらはMOOCと呼ばれます。
時折、クラスが開講されていないため、数か月間待たなければならない場合があり、アクセスができないこともあります。

オンラインコースのリソースを、常に利用可能な無料の公開ソース（できれば大学の講義）に置き換えることができれば理想的です。
これにより、特定のオンラインコースが開講されているときに限らず、いつでも学習できるようになります。

**[⬆ トップへ戻る](#table-of-contents)**

## プログラミング言語の選択

コーディング面接を行うためにプログラミング言語を選択する必要がありますが、コンピューターサイエンスの概念を学ぶためにも使用できる言語である必要があります。

理想的には、同じ言語を使用するようにするべきです。これにより、1つの言語にのみ熟練すれば済みます。

### この学習計画について

この学習計画を作成する際、ほとんどの部分で2つの言語を使用しました：C言語とPython

* C: 非常に低レベルの言語です。ポインタやメモリの確保/解放を扱うことができ、データ構造やアルゴリズムを体感できます。PythonやJavaなどの高レベル言語では、これらは隠されています。日常的な作業では、これは非常に便利ですが、これらの低レベルのデータ構造がどのように構築されているかを学ぶ際には、金属に近い感覚を持つことは非常に良いです。
    - Cは至る所に存在します。本や講義、動画など、学習中にあらゆる場所で例を見つけることができます。
    - [The C Programming Language, 2nd Edition](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
        - これは短い本ですが、C言語に対する良い理解を提供し、少し練習すればすぐに熟練することができます。Cを理解することで、プログラムやメモリの動作を理解する助けになります。
        - 本を非常に深く読む必要はありません（あるいは、読了する必要もありません）。C言語で読み書きできるようになるまでに達成すれば十分です。
* Python: 現代的で非常に表現力が豊かです。私はPythonを学んだのは、非常に使いやすく、面接の際にコードを書く量を減らすことができるからです。

これは私の好みです。もちろん、あなたが好きなようにしてください。

必要でないかもしれませんが、新しい言語を学ぶためのサイトをいくつか紹介します：
- [Exercism](https://exercism.org/tracks)
- [Codewars](http://www.codewars.com)
- [HackerEarth](https://www.hackerearth.com/for-developers/)
- [Scaler Topics (Java, C++)](https://www.scaler.com/topics/)
- [Programiz PRO Community Challenges)](https://programiz.pro/)

### インタビュー用のコーディング

インタビューのコーディング部分では、ご自身が使い慣れている言語を使用できますが、大規模な企業では以下の選択肢が確実です：

- C++
- Java
- Python

以下の言語も使用できますが、使用する前に情報を確認してください。いくつかの注意点があるかもしれません：

- JavaScript
- Ruby

私がインタビュー用の言語選択について書いた記事はこちら：
[Pick One Language for the Coding Interview](https://startupnextdoor.com/important-pick-one-language-for-the-coding-interview/).
私が記事を書いた元の記事はこちら：[Choosing a Programming Language for Interviews](https://web.archive.org/web/20210516054124/http://blog.codingforinterviews.com/best-programming-language-jobs/)

選んだ言語に非常に精通し、知識がある必要があります。

選択肢についてさらに詳しく読むには：
- [Choose the Right Language for Your Coding Interview](http://www.byte-by-byte.com/choose-the-right-language-for-your-coding-interview/)

[言語固有のリソースはこちら](../programming-language-resources.md)

**[⬆ トップへ戻る](#table-of-contents)**

## データ構造とアルゴリズムのための書籍

この本は、コンピュータ科学の基礎になります。

1つ選んでください。あなたが使い慣れている言語で構いません。多くの読書とコーディングを行います。

### Python

- [Coding Interview Patterns: Nail Your Next Coding Interview](https://geni.us/q7svoz) (**主な推奨**)
    - 面接官が本当に求めていることとその理由についての内部者視点。
    - 詳細な解説付きの101の実際のコーディング面接問題。
    - 実際にライブ面接で解いているかのように、各問題を解決するための直感的な説明。
    - キーの概念とパターンを示す1000以上の図解。

- [Algorithms in C, Parts 1-5 (Bundle), 3rd Edition](https://www.amazon.com/Algorithms-Parts-1-5-Bundle-Fundamentals/dp/0201756080)
    - 基本、データ構造、ソート、検索、およびグラフアルゴリズム

### Java

ご選択肢:

- Goodrich, Tamassia, Goldwasser
    - [Javaにおけるデータ構造とアルゴリズム](https://www.amazon.com/Data-Structures-Algorithms-Michael-Goodrich/dp/1118771338/)
- Sedgewick and Wayne:
    - [アルゴリズム](https://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X/)
    - 本の内容をカバーする無料のCourseraコース（著者が講義！）:
        - [アルゴリズムI](https://www.coursera.org/learn/algorithms-part1)
        - [アルゴリズムII](https://www.coursera.org/learn/algorithms-part2)

### C++

ご選択肢:

- Goodrich, Tamassia, and Mount
    - [Data Structures and Algorithms in C++, 2nd Edition](https://www.amazon.com/Data-Structures-Algorithms-Michael-Goodrich/dp/0470383275)
- Sedgewick and Wayne
    - [Algorithms in C++, Parts 1-4: Fundamentals, Data Structure, Sorting, Searching](https://www.amazon.com/Algorithms-Parts-1-4-Fundamentals-Structure/dp/0201350882/)
    - [Algorithms in C++ Part 5: Graph Algorithms](https://www.amazon.com/Algorithms-Part-Graph-3rd-Pt-5/dp/0201361183/)

**[⬆ back to top](#table-of-contents)**

## Interview Prep Books

ここに、学習を補完するために推奨される本を紹介します。

- [Coding Interview Patterns: Nail Your Next Coding Interview](https://geni.us/q7svoz)

- [Programming Interviews Exposed: Coding Your Way Through the Interview, 4th Edition](https://www.amazon.com/Programming-Interviews-Exposed-Through-Interview/dp/111941847X/)
    - C++およびJavaでの解答
    - Cracking the Coding Interviewのための良いウォームアップ
    - 難しすぎない。大多数の問題は、インタビューで見る問題よりも簡単かもしれない（私が読んだ限り）

- [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - Javaでの解答

### 余裕がある場合は:

1つ選んでください:

- [Elements of Programming Interviews (C++ version)](https://www.amazon.com/Elements-Programming-Interviews-Insiders-Guide/dp/1479274836)
- [Elements of Programming Interviews in Python](https://www.amazon.com/Elements-Programming-Interviews-Python-Insiders/dp/1537713949/)
- [Elements of Programming Interviews (Java version)](https://www.amazon.com/Elements-Programming-Interviews-Java-Insiders/dp/1517435803/)
        - [Companion Project - Method Stub and Test Cases for Every Problem in the Book](https://github.com/gardncl/elements-of-programming-interviews)

**[⬆ back to top](#table-of-contents)**

## Don't Make My Mistakes

このリストは多くの月にわたり成長し、はい、手がかりがなくなった。

ここにいくつかの間違いを挙げますので、より良い体験を得るために、そして数カ月の時間を節約するために。

### 1. すべてを覚えることはできない

私は何時間もの動画を視聴し、詳細なメモを取りましたが、数カ月後には多くのことを覚えていませんでした。私は3日間かけてメモを確認し、フラッシュカードを作成して復習しました。すべての知識が必要だったわけではありません。

どうか、私の間違いを繰り返さないために読んでください:

[コンピュータ科学の知識の保持](https://startupnextdoor.com/retaining-computer-science-knowledge/)。

### 2. フラッシュカードの使用

この問題を解決するために、2つのタイプのフラッシュカード（一般とコード）を追加できる小さなフラッシュカードサイトを作成しました。各カードは異なるフォーマットを持っています。私はモバイルファーストのウェブサイトを作成したので、どこにいてもスマートフォンやタブレットで確認できます。

無料で作成できます：

- [フラッシュカードサイトのリポジトリ](https://github.com/jwasham/computer-science-flash-cards)

**私は自分のフラッシュカードの使用を推奨しません。** カードが多すぎるため、多くは必要としないトリビアです。

でも、私の言うことを聞かずに使いたい場合は、こちらをご覧ください：
- [私のフラッシュカードデータベース（1200枚）](https://github.com/jwasham/computer-science-flash-cards/blob/main/cards-jwasham.db):
- [私のフラッシュカードデータベース（極限 - 1800枚）](https://github.com/jwasham/computer-science-flash-cards/blob/main/cards-jwasham-extreme.db):

ただし、私は過剰にカードを作成しており、アセンブリ言語やPythonのトリビアから機械学習や統計まで、あらゆるトピックをカバーしています。これは必要なものよりはるかに多いです。

**フラッシュカードに関する注意点:** 最初に答えを認識したときに「既知」とマークしないでください。本当に覚えるには、同じカードを見て正しく答えられる回数を繰り返す必要があります。繰り返しはその知識をあなたの脳に深く刻み込みます。

私のフラッシュカードサイトの代替として、[Anki](http://ankisrs.net/)を使用することを何度も推奨されてきました。それはあなたの記憶を助けるために繰り返しシステムを使用しています。使いやすく、すべてのプラットフォームで利用可能で、クラウド同期システムも備えています。iOSでは25ドルかかりますが、他のプラットフォームでは無料です。

Anki形式の私のフラッシュカードデータベース: https://ankiweb.net/shared/info/25173560（[@xiewenya](https://github.com/xiewenya) ありがとうございます）。

一部の学生は、空白のフォーマットに関する問題を報告しており、これを修正するには次の手順を実行してください：デッキを開き、カードを編集し、カードを選択し、「スタイル」のラジオボタンを選択し、「white-space: pre;」というメンバーをカードクラスに追加してください。

### 3. 学習しながらコーディング面接の質問を行う

これは非常に重要です。

データ構造とアルゴリズムを学習している間に、コーディング面接の質問を始めてください。

学んだことを問題解決に応用しないと、忘れてしまいます。私はこの間違いを犯しました。

あるトピックを学習し、ある程度理解できたと感じたとき、例えば**連結リスト**の場合:
1. [コーディング面接の本](#interview-prep-books)のいずれか（または以下のコーディング問題のウェブサイト）を開きます。
1. 連結リストに関する質問を2つまたは3つ解きます。
1. 次の学習トピックに進みます。
1. 後で戻って、もう2つまたは3つの連結リストの問題を解きます。
1. 新しいトピックを学ぶたびにこれを繰り返します。

**すべての学習中に問題を解き続けることが重要です。学習の後ではなく、学習の間に。**

知識があるかどうかではなく、知識をどのように応用するかが採用の基準です。

これに関するリソースは以下にたくさん掲載されています。続けてください。

### 4. 集中

多くの注意散漫な要因があり、貴重な時間を浪費してしまうことがあります。集中と注意は難しいものです。歌詞のない音楽を再生すると、ある程度は集中できるようになります。

**[⬆ トップへ戻る](#table-of-contents)**

## What you won't see covered

These are prevalent technologies but not part of this study plan:

- JavaScript
- HTML, CSS, and other front-end technologies
- SQL

**[⬆ back to top](#table-of-contents)**

## 毎日の計画

このコースでは、多くのトピックを扱います。それぞれのトピックは、数日かかるかもしれません。あるいは、1週間以上かかるかもしれません。それはあなたのスケジュールに依存します。

毎日、リストの次のトピックを取り上げ、そのトピックに関する動画を視聴し、その後、このコースで選んだ言語を使って、そのデータ構造またはアルゴリズムの実装を書くようにしてください。

私のコードはここにあります:
 - [C](https://github.com/jwasham/practice-c)
 - [C++](https://github.com/jwasham/practice-cpp)
 - [Python](https://github.com/jwasham/practice-python)

すべてのアルゴリズムを暗記する必要はありません。ただ、それを理解するだけです。そして、それを使って、自分の実装を書けるようにするだけです。

**[⬆ トップに戻る](#table-of-contents)**

## コーディング質問の練習

なぜここにあるのか？面接の準備はまだしていない。

[戻ってこれを読んでください。](#3-do-coding-interview-questions-while-youre-learning)

プログラミング問題の練習が必要な理由:
- 問題の認識と、正しいデータ構造やアルゴリズムがどの場所に適しているか
- 問題の要件を収集する
- 面接で行うように、問題を話し合う
- コンピュータではなく、ホワイトボードや紙を使ってコーディングする
- 解決策の時間と空間の複雑性を考え出す（以下にBig-Oを参照）
- 解決策をテストする

面接で体系的でコミュニケーション能力のある問題解決方法についての素晴らしい紹介があります。プログラミング面接の本からもこの方法を学ぶことができますが、私はこの素晴らしいリソースを見つけました：
[アルゴリズム設計キャンバス](http://www.hiredintech.com/algorithm-design/)

コンピュータではなく、ホワイトボードや紙を使ってコードを書く。いくつかのサンプル入力を使ってテストする。その後、コンピュータでタイプし、テストする。

自宅にホワイトボードがない場合は、アートストアから大きな描画パッドを購入してください。ソファに座って練習できます。
これは私の「ソファホワイトボード」です。写真にペンを追加したのはスケールのためだけです。ペンを使うと消したいと思うでしょう。
すぐに汚れてしまいます。**私は鉛筆と消しゴムを使います。**

![私のソファホワイトボード](https://d3j2pkmjtin6ou.cloudfront.net/art_board_sm_2.jpg)

**コーディング質問の練習は、プログラミング問題の答えを覚えることではありません。**

**[⬆ トップに戻る](#table-of-contents)**

## コーディング問題

インタビュー準備書籍は[ここ](#interview-prep-books)に忘れずに。

問題解決:
- [解決策の見つけ方](https://www.topcoder.com/thrive/articles/How%20To%20Find%20a%20Solution)
- [Topcoder問題文の解読方法](https://www.topcoder.com/thrive/articles/How%20To%20Dissect%20a%20Topcoder%20Problem%20Statement%20Content)

コーディングインタビュー問題動画:
- [IDeserve (88動画)](https://www.youtube.com/playlist?list=PLamzFoFxwoNjPfxzaWqs7cZGsPYy0x_gI)
- [Tushar Roy (5プレイリスト)](https://www.youtube.com/user/tusharroy2525/playlists?shelf_id=2&view=50&sort=dd)
    - 問題解決のウォークスルーに最適
- [Nick White - LeetCodeソリューション (187動画)](https://www.youtube.com/playlist?list=PLU_sdQYzUj2keVENTP0a5rdykRSgg9Wp-)
    - 解決策とコードの説明が良い
    - 短時間でいくつか視聴可能
- [FisherCoder - LeetCodeソリューション](https://youtube.com/FisherCoder)

挑戦/練習サイト:
- [LeetCode](https://leetcode.com/)
    - 私のお気に入りのコーディング問題サイト。準備期間が1〜2か月続くことを考えると、サブスクリプション料は価値があります。
    - 上記のNick WhiteおよびFisherCoderの動画でコードウォークスルーをご覧ください。
- [HackerRank](https://www.hackerrank.com/)
- [TopCoder](https://www.topcoder.com/)
- [Codeforces](https://codeforces.com/)
- [Codility](https://codility.com/programmers/)
- [Geeks for Geeks](https://practice.geeksforgeeks.org/explore/?page=1)
- [AlgoExpert](https://www.algoexpert.io/product)
    - Googleエンジニアによって作成され、スキルを磨くための優れたリソースでもあります。
- [Project Euler](https://projecteuler.net/)
    - 数学に強く焦点を当てており、コーディングインタビューにはあまり適していません

**[⬆ トップへ戻る](#table-of-contents)**

## さっそく始めましょう

では、十分な説明はこれで終わりにしましょう。学び始めましょう！

ただし、学びながら上記のコーディング問題にも取り組むのを忘れないでください！

## アルゴリズムの複雑性 / Big-O / 非常に近い分析

- ここでは実装するものはありません。動画を見てメモを取るだけです。やったね！
- ここにはたくさんの動画があります。理解できるまで十分に見ればいいです。いつでも戻って復習できます。
- すべての数学が理解できないと心配する必要はありません。
- あなたが理解する必要があるのは、Big-Oを使ってアルゴリズムの複雑性を表現する方法だけです。
- [ ] [ハーバード CS50 - 非常に近い記法 (動画)](https://www.youtube.com/watch?v=iOq5kSKqeR4)
- [ ] [Big O 記法 (一般のクイックチュートリアル) (動画)](https://www.youtube.com/watch?v=V6mKVRU1evU)
- [ ] [Big O 記法 (およびオメガとシータ) - 最も数学的な説明 (動画)](https://www.youtube.com/watch?v=ei-A_wy5Yxw&index=2&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
- [ ] [スカイナ (動画)](https://www.youtube.com/watch?v=z1mkCe3kVUA)
- [ ] [UCバークレー Big O (動画)](https://archive.org/details/ucberkeley_webcast_VIS4YDpuP98)
- [ ] [償却分析 (動画)](https://www.youtube.com/watch?v=B3SpQZaAZP4&index=10&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
- [ ] TopCoder (再帰関係式とマスター定理を含む):
    - [計算複雑性: 第1章](https://www.topcoder.com/thrive/articles/Computational%20Complexity%20part%20one)
    - [計算複雑性: 第2章](https://www.topcoder.com/thrive/articles/Computational%20Complexity%20part%20two)
- [ ] [チートシート](http://bigocheatsheet.com/)
- [ ] [[レビュー] アルゴリズムの分析 (プレイリスト) 18分で (動画)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZMxejjIyFHWa-4nKg6sdoIv)

まあ、これくらいで十分でしょう。

「Cracking the Coding Interview」を通読するとき、この章に章があります。最後にはクイズがあり、さまざまなアルゴリズムの実行時間複雑性を識別できるか確認できます。これは非常に良い復習とテストです。

**[⬆ トップに戻る](#table-of-contents)**

## データ構造

- ### 配列
    - [ ] 配列について:
    	- [Arrays CS50 Harvard University](https://www.youtube.com/watch?v=tI_tIZFyKBw&t=3009s)
        - [Arrays (video)](https://www.coursera.org/lecture/data-structures/arrays-OsBSF)
        - [UC Berkeley CS61B - Linear and Multi-Dim Arrays (video)](https://archive.org/details/ucberkeley_webcast_Wp8oiO_CZZE) (15分32秒から視聴を開始)
        - [Dynamic Arrays (video)](https://www.coursera.org/lecture/data-structures/dynamic-arrays-EwbnV)
        - [Jagged Arrays (video)](https://www.youtube.com/watch?v=1jtrQqYpt7g)
    - [ ] ベクトルを実装（自動拡張可能な変更可能な配列）:
        - [ ] 配列とポインタ、ポインタ演算を使用してインデックスにジャンプする代わりにインデクシングを使用するコード実践
        - [ ] 新しい生のデータ配列と割り当てられたメモリ
            - 仮にint配列を内部で割り当てても、その機能は使用しない
            - 16から開始、または開始番号が大きい場合は、2のべき乗 - 16, 32, 64, 128を使用
        - [ ] size() - アイテムの数
        - [ ] capacity() - 容納可能なアイテム数
        - [ ] is_empty()
        - [ ] at(index) - 指定されたインデックスのアイテムを返す。インデックスが範囲外の場合、エラーを発生させる
        - [ ] push(item)
        - [ ] insert(index, item) - 指定されたインデックスにアイテムを挿入し、そのインデックスの値とトレーリング要素を右にシフト
        - [ ] prepend(item) - 上記のinsertをインデックス0で使用可能
        - [ ] pop() - 終端から削除し、値を返す
        - [ ] delete(index) - 指定されたインデックスのアイテムを削除し、トレーリング要素を左にシフト
        - [ ] remove(item) - 値を検索し、その値を持つインデックスを削除（複数の場所にある場合でも）
        - [ ] find(item) - 値を検索し、最初のインデックスを返す。見つからない場合は-1
        - [ ] resize(new_capacity) // プライベート関数
            - 容量に達した場合、サイズを倍に拡張
            - アイテムをポップした場合、サイズが容量の1/4であれば、サイズを半分に縮小
    - [ ] 時間
        - 終端（追加/削除、アロケーションのためのアモルティズド）インデックス、または更新にO(1)
        - 他の場所での挿入/削除にO(n)
    - [ ] 空間
        - メモリ内で連続しているため、近接性はパフォーマンスに有利
        - 必要空間 = (配列容量、これはn以上) * アイテムのサイズ、2nでもO(n)

- ### リンクドリスト
    - [ ] 説明:
    	- [ ] [Linked Lists CS50 Harvard University](https://www.youtube.com/watch?v=2T-A_GFuoTo&t=650s) - これは直感を構築します。
        - [ ] [Singly Linked Lists (video)](https://www.coursera.org/lecture/data-structures/singly-linked-lists-kHhgK)
        - [ ] [CS 61B - Linked Lists 1 (video)](https://archive.org/details/ucberkeley_webcast_htzJdKoEmO0)
        - [ ] [CS 61B - Linked Lists 2 (video)](https://archive.org/details/ucberkeley_webcast_-c4I3gFYe3w)
        - [ ] [[Review] Linked lists in 4 minutes (video)](https://youtu.be/F8AbOfQwl1c)
    - [ ] [C Code (video)](https://www.youtube.com/watch?v=QN6FPiD0Gzo)
            - ビデオ全体ではなく、Node構造体とメモリ割り当てに関する部分
    - [ ] リンクドリスト vs 配列:
        - [Core Linked Lists Vs Arrays (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-linked-lists-vs-arrays-rjBs9)
        - [In The Real World Linked Lists Vs Arrays (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/in-the-real-world-lists-vs-arrays-QUaUd)
    - [ ] [Why you should avoid linked lists (video)](https://www.youtube.com/watch?v=YQs6IC-vgmo)
    - [ ] 注意点: ポインタへのポインタの知識が必要:
        (関数がポインタのアドレスを変更する可能性がある場合にポインタを関数に渡すとき)
        このページはptr to ptrの理解を得るためにあるだけです。このリストのトラバーサルスタイルはお勧めしません。賢さのための可読性と保守性が損なわれます。
        - [Pointers to Pointers](https://www.eskimo.com/~scs/cclass/int/sx8.html)
    - [ ] 実装（tailポインタを使用しておよび使用しないで）:
        - [ ] size() - リスト内のデータ要素の数を返す
        - [ ] empty() - リストが空の場合trueを返す
        - [ ] value_at(index) - 0から始まるnthアイテムの値を返す
        - [ ] push_front(value) - リストの先頭にアイテムを追加
        - [ ] pop_front() - 先頭のアイテムを削除し、その値を返す
        - [ ] push_back(value) - リストの末尾にアイテムを追加
        - [ ] pop_back() - 末尾のアイテムを削除し、その値を返す
        - [ ] front() - 先頭アイテムの値を取得
        - [ ] back() - 末尾アイテムの値を取得
        - [ ] insert(index, value) - 指定されたインデックスに値を挿入し、そのインデックスの現在のアイテムは新しいアイテムによって指される
        - [ ] erase(index) - 指定されたインデックスのノードを削除
        - [ ] value_n_from_end(n) - リストの末尾からnth位置のノードの値を返す
        - [ ] reverse() - リストを逆順に
        - [ ] remove_value(value) - この値を持つリスト内の最初のアイテムを削除
    - [ ] 二重リンクドリスト
        - [説明 (video)](https://www.coursera.org/lecture/data-structures/doubly-linked-lists-jpGKD)
        - 実装は不要

- ### スタック
    - [ ] [Stacks (video)](https://www.coursera.org/lecture/data-structures/stacks-UdKzQ)
    - [ ] [[Review] Stacks in 3 minutes (video)](https://youtu.be/KcT3aVgrrpU)
    - [ ] 実装はしない。配列を使用して実装するのは簡単

- ### キュー
    - [ ] [Queue (video)](https://www.coursera.org/lecture/data-structures/queues-EShpq)
    - [ ] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
    - [ ] [[Review] Queues in 3 minutes (video)](https://youtu.be/D6gu-_tmEpQ)
    - [ ] リンクドリストを使用して、tailポインタで実装:
        - enqueue(value) - 尾に値を追加
        - dequeue() - 値を返し、最も最近に追加された要素（先頭）を削除
        - empty()
    - [ ] 固定サイズの配列を使用して実装:
        - enqueue(value) - 有効なストレージの末尾にアイテムを追加
        - dequeue() - 値を返し、最も最近に追加された要素を削除
        - empty()
        - full()
    - [ ] コスト:
        - 頭にenqueueし、尾にdequeueするような悪いリンクリストの実装では、O(n)となる
            なぜなら、最後の要素が必要になるため、各dequeueでフルトラバースが必要になるから
        - enqueue: O(1) (アモルティズド、リンクリストと配列 [プロービング])
        - dequeue: O(1) (リンクリストと配列)
        - empty: O(1) (リンクリストと配列)

- ### ハッシュテーブル
    - [ ] ビデオ:
        - [ ] [Hashing with Chaining (video)](https://www.youtube.com/watch?v=0M_kIqhwbFo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=8)
        - [ ] [Table Doubling, Karp-Rabin (video)](https://www.youtube.com/watch?v=BRO7mVIFt08&index=9&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [Open Addressing, Cryptographic Hashing (video)](https://www.youtube.com/watch?v=rvdJDijO2Ro&index=10&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [PyCon 2010: The Mighty Dictionary (video)](https://www.youtube.com/watch?v=C4Kc8xzcA68)
        - [ ] [PyCon 2017: The Dictionary Even Mightier (video)](https://www.youtube.com/watch?v=66P5FMkWoVU)
        - [ ] [(Advanced) Randomization: Universal & Perfect Hashing (video)](https://www.youtube.com/watch?v=z0lJ2k0sl1g&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=11)
        - [ ] [(Advanced) Perfect hashing (video)](https://www.youtube.com/watch?v=N0COwN14gt0&list=PL2B4EEwhKD-NbwZ4ezj7gyc_3yNrojKM9&index=4)
        - [ ] [[Review] Hash tables in 4 minutes (video)](https://youtu.be/knV86FlSXJ8)

    - [ ] オンラインコース:
        - [ ] [Core Hash Tables (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-hash-tables-m7UuP)
        - [ ] [Data Structures (video)](https://www.coursera.org/learn/data-structures/home/week/4)
        - [ ] [Phone Book Problem (video)](https://www.coursera.org/lecture/data-structures/phone-book-problem-NYZZP)
        - [ ] 分散ハッシュテーブル:
            - [Instant Uploads And Storage Optimization In Dropbox (video)](https://www.coursera.org/lecture/data-structures/instant-uploads-and-storage-optimization-in-dropbox-DvaIb)
            - [Distributed Hash Tables (video)](https://www.coursera.org/lecture/data-structures/distributed-hash-tables-tvH8H)

    - [ ] 配列を使用して線形プロービングで実装
        - hash(k, m) - mはハッシュテーブルのサイズ
        - add(key, value) - キーが既に存在する場合、値を更新
        - exists(key)
        - get(key)
        - remove(key)

**[⬆ back to top](#table-of-contents)**

## More Knowledge

- ### バイナリ検索
    - [ ] [バイナリ検索 (動画)](https://www.youtube.com/watch?v=D5SrAga1pno)
    - [ ] [バイナリ検索 (動画)](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)
    - [ ] [詳細](https://www.topcoder.com/thrive/articles/Binary%20Search)
    - [ ] [ブループリント](https://leetcode.com/discuss/general-discussion/786126/python-powerful-ultimate-binary-search-template-solved-many-problems)
    - [ ] [[レビュー] 4分でバイナリ検索 (動画)](https://youtu.be/fDKIpRe8GW4)
    - [ ] 実装:
        - バイナリ検索 (整数の並べられた配列上)
        - 再帰を使用したバイナリ検索

- ### ビット演算
    - [ ] [ビットのチートシート](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/bits-cheat-sheet.pdf)
        - 2^1 から 2^16 および 2^32 までの 2 のべき乗を多く知っておく必要があります
    - [ ] &、|、^、~、>>、<< を使用してビットを操作する方法を本当に良く理解してください
        - [ ] [ワード](https://en.wikipedia.org/wiki/Word_(computer_architecture))
        - [ ] 良い導入:
            [ビット操作 (動画)](https://www.youtube.com/watch?v=7jkIUgLC29I)
        - [ ] [Cプログラミングチュートリアル 2-10: ビット演算子 (動画)](https://www.youtube.com/watch?v=d0AwjSpNXR0)
        - [ ] [ビット操作](https://en.wikipedia.org/wiki/Bit_manipulation)
        - [ ] [ビット演算](https://en.wikipedia.org/wiki/Bitwise_operation)
        - [ ] [ビットハック](https://graphics.stanford.edu/~seander/bithacks.html)
        - [ ] [ビットツィッダラー](https://bits.stephan-brumme.com/)
        - [ ] [ビットツィッダラーインタラクティブ](https://bits.stephan-brumme.com/interactive.html)
        - [ ] [ビットハック (動画)](https://www.youtube.com/watch?v=ZusiKXcz_ac)
		- [ ] [演算の練習](https://pconrad.github.io/old_pconrad_cs16/topics/bitOps/)
    - [ ] 2の補数と1の補数
        - [バイナリ: プラスとマイナス (なぜ2の補数を使用するのか) (動画)](https://www.youtube.com/watch?v=lKTsv6iVxV4)
        - [1の補数](https://en.wikipedia.org/wiki/Ones%27_complement)
        - [2の補数](https://en.wikipedia.org/wiki/Two%27s_complement)
    - [ ] 設定されたビットの数を数える
        - [1バイト内のビットを数える4つの方法 (動画)](https://youtu.be/Hzuzo9NJrlc)
        - [ビット数を数える](https://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan)
        - [32ビット整数内の設定されたビットの数を数える方法](http://stackoverflow.com/questions/109023/how-to-count-the-number-of-set-bits-in-a-32-bit-integer)
    - [ ] 値の交換:
        - [交換](https://bits.stephan-brumme.com/swap.html)
    - [ ] 絶対値:
        - [絶対値整数](https://bits.stephan-brumme.com/absInteger.html)

**[⬆ トップに戻る](#table-of-contents)**

## ツリー

- ### ツリー - はじめに
    - [ ] [ツリーの紹介 (動画)](https://www.coursera.org/lecture/data-structures/trees-95qda)
    - [ ] [ツリーのトラバーサル (動画)](https://www.coursera.org/lecture/data-structures/tree-traversal-fr51b)
    - [ ] [BFS(幅優先探索)とDFS(深さ優先探索) (動画)](https://www.youtube.com/watch?v=uWL6FJhq5fM)
        - BFSのメモ:
           - レベル順 (BFS, キューを使用)
           - 時間複雑度: O(n)
           - 空間複雑度: 最良: O(1), 最悪: O(n/2)=O(n)
        - DFSのメモ:
            - 時間複雑度: O(n)
            - 空間複雑度:
                最良: O(log n) - ツリーの平均高さ
                最悪: O(n)
            - inorder (DFS: 左, 自分, 右)
            - postorder (DFS: 左, 右, 自分)
            - preorder (DFS: 自分, 左, 右)
    - [ ] [[レビュー] 幅優先探索を4分で (動画)](https://youtu.be/HZ5YTanv5QE)
    - [ ] [[レビュー] 深さ優先探索を4分で (動画)](https://youtu.be/Urx87-NMm6c)
    - [ ] [[レビュー] ツリーのトラバーサル (プレイリスト)を11分で (動画)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZO1JC2RgEi04nLy6D-rKk6b)

- ### 二分探索木: BSTs
    - [ ] [二分探索木のレビュー (動画)](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
    - [ ] [紹介 (動画)](https://www.coursera.org/learn/data-structures/lecture/E7cXP/introduction)
    - [ ] [MIT (動画)](https://www.youtube.com/watch?v=76dhtgZt38A&ab_channel=MITOpenCourseWare)
    - C/C++:
        - [ ] [二分探索木 - C/C++での実装 (動画)](https://www.youtube.com/watch?v=COZK7NATh4k&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=28)
        - [ ] [BSTの実装 - スタックとヒープでのメモリ確保 (動画)](https://www.youtube.com/watch?v=hWokyBoo0aI&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=29)
        - [ ] [二分探索木内の最小値と最大値の検出 (動画)](https://www.youtube.com/watch?v=Ut90klNN264&index=30&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [二分木の高さの検出 (動画)](https://www.youtube.com/watch?v=_pnqMz5nrRs&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=31)
        - [ ] [二分木のトラバーサル - 幅優先と深さ優先戦略 (動画)](https://www.youtube.com/watch?v=9RHO6jU--GU&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=32)
        - [ ] [二分木: レベル順トラバーサル (動画)](https://www.youtube.com/watch?v=86g8jAQug04&index=33&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [二分木のトラバーサル: Preorder, Inorder, Postorder (動画)](https://www.youtube.com/watch?v=gm8DUJJhmY4&index=34&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [二分木が二分探索木かどうかの確認 (動画)](https://www.youtube.com/watch?v=yEwSGhSsT0U&index=35&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [二分探索木からノードの削除 (動画)](https://www.youtube.com/watch?v=gcULXE7ViZw&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=36)
        - [ ] [二分探索木でのInorder Successor (動画)](https://www.youtube.com/watch?v=5cPbNCrdotA&index=37&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
    - [ ] 実装:
        - [ ] [insert    // ツリーに値を挿入](https://leetcode.com/problems/insert-into-a-binary-search-tree/submissions/987660183/)
        - [ ] get_node_count // 格納された値の数を取得
        - [ ] print_values // ツリー内の値を最小から最大まで出力
        - [ ] delete_tree
        - [ ] is_in_tree // 与えられた値がツリー内にある場合trueを返す
        - [ ] [get_height // ノード数で高さを返す (単一ノードの高さは1)](https://www.geeksforgeeks.org/find-the-maximum-depth-or-height-of-a-tree/)
        - [ ] get_min   // ツリー内で格納された最小値を返す
        - [ ] get_max   // ツリー内で格納された最大値を返す
        - [ ] [is_binary_search_tree](https://leetcode.com/problems/validate-binary-search-tree/)
        - [ ] delete_value
        - [ ] get_successor // 与えられた値の次に高い値を返す。存在しない場合は-1を返す

- ### ヒープ / 優先キュー / 二分ヒープ
    - ツリーとして視覚化されるが、通常は線形で保存される (配列、リンクリスト)
    - [ ] [ヒープ](https://en.wikipedia.org/wiki/Heap_(data_structure))
    - [ ] [紹介 (動画)](https://www.coursera.org/lecture/data-structures/introduction-2OpTs)
    - [ ] [二分木 (動画)](https://www.coursera.org/learn/data-structures/lecture/GRV2q/binary-trees)
    - [ ] [ツリーの高さに関するコメント (動画)](https://www.coursera.org/learn/data-structures/supplement/S5xxz/tree-height-remark)
    - [ ] [基本操作 (動画)](https://www.coursera.org/learn/data-structures/lecture/0g1dl/basic-operations)
    - [ ] [完全二分木 (動画)](https://www.coursera.org/learn/data-structures/lecture/gl5Ni/complete-binary-trees)
    - [ ] [疑似コード (動画)](https://www.coursera.org/learn/data-structures/lecture/HxQo9/pseudocode)
    - [ ] [ヒープソート - 開始位置へジャンプ (動画)](https://youtu.be/odNJmw5TOEE?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3291)
    - [ ] [ヒープソート (動画)](https://www.coursera.org/lecture/data-structures/heap-sort-hSzMO)
    - [ ] [ヒープの構築 (動画)](https://www.coursera.org/lecture/data-structures/building-a-heap-dwrOS)
    - [ ] [MIT 6.006 アルゴリズム入門: 二分ヒープ](https://www.youtube.com/watch?v=Xnpo1atN-Iw&list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY&index=12)
    - [ ] [CS 61B 講義24: 優先キュー (動画)](https://archive.org/details/ucberkeley_webcast_yIUFT6AKBGE)
    - [ ] [線形時間でのBuildHeap (max-heap)](https://www.youtube.com/watch?v=MiyLo8adrWw)
    - [ ] [[レビュー] ヒープ (プレイリスト)を13分で (動画)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZNsyqgPW-DNwUeT8F8uhWc6)
    - [ ] max-heapの実装:
        - [ ] insert
        - [ ] sift_up - insertに必要
        - [ ] get_max - 最大のアイテムを返すが、削除しない
        - [ ] get_size() - 格納された要素数を返す
        - [ ] is_empty() - ヒープに要素が存在しない場合trueを返す
        - [ ] extract_max - 最大のアイテムを返し、削除する
        - [ ] sift_down - extract_maxに必要
        - [ ] remove(x) - インデックスxのアイテムを削除
        - [ ] heapify - 配列からヒープを作成、heap_sortに必要
        - [ ] heap_sort() - 未整列の配列をmax heapまたはmin heapを使用して場所を変更しながら整列配列に変換

## ソート

- [ ] メモ:
    - ソートを実装し、各アルゴリズムの最良ケース/最悪ケース、平均複雑度を把握する:
        - バブルソートは最悪 - O(n^2)、n <= 16 の場合を除く
    - [ ] ソートアルゴリズムの安定性 ("クイックソートは安定ですか？")
        - [Sorting Algorithm Stability](https://en.wikipedia.org/wiki/Sorting_algorithm#Stability)
        - [Stability In Sorting Algorithms](http://stackoverflow.com/questions/1517793/stability-in-sorting-algorithms)
        - [Stability In Sorting Algorithms](http://www.geeksforgeeks.org/stability-in-sorting-algorithms/)
        - [Sorting Algorithms - Stability](http://homepages.math.uic.edu/~leon/cs-mcs401-s08/handouts/stability.pdf)
    - [ ] どのアルゴリズムがリンクリストで使用可能ですか？配列では？どちらでも？
        - リンクリストをソートすることをおすすめしませんが、マージソートは可能。
        - [Merge Sort For Linked List](http://www.geeksforgeeks.org/merge-sort-for-linked-list/)

- ヒープソートについては上のヒープデータ構造を参照してください。ヒープソートは良いですが、安定ではありません。

- [ ] [Sedgewick - マージソート (5動画)](https://www.coursera.org/learn/algorithms-part1/home/week/3)
    - [ ] [1. マージソート](https://www.coursera.org/lecture/algorithms-part1/mergesort-ARWDq)
    - [ ] [2. ボトムアップマージソート](https://www.coursera.org/learn/algorithms-part1/lecture/PWNEl/bottom-up-mergesort)
    - [ ] [3. ソート複雑度](https://www.coursera.org/lecture/algorithms-part1/sorting-complexity-xAltF)
    - [ ] [4. 比較子](https://www.coursera.org/lecture/algorithms-part1/comparators-9FYhS)
    - [ ] [5. 安定性](https://www.coursera.org/learn/algorithms-part1/lecture/pvvLZ/stability)

- [ ] [Sedgewick - クイックソート (4動画)](https://www.coursera.org/learn/algorithms-part1/home/week/3)
    - [ ] [1. クイックソート](https://www.coursera.org/lecture/algorithms-part1/quicksort-vjvnC)
    - [ ] [2. 選択](https://www.coursera.org/lecture/algorithms-part1/selection-UQxFT)
    - [ ] [3. 重複キー](https://www.coursera.org/lecture/algorithms-part1/duplicate-keys-XvjPd)
    - [ ] [4. システムソート](https://www.coursera.org/lecture/algorithms-part1/system-sorts-QBNZ7)

- [ ] UC Berkeley:
    - [ ] [CS 61B Lecture 29: Sorting I (動画)](https://archive.org/details/ucberkeley_webcast_EiUvYS2DT6I)
    - [ ] [CS 61B Lecture 30: Sorting II (動画)](https://archive.org/details/ucberkeley_webcast_2hTY3t80Qsk)
    - [ ] [CS 61B Lecture 32: Sorting III (動画)](https://archive.org/details/ucberkeley_webcast_Y6LOLpxg6Dc)
    - [ ] [CS 61B Lecture 33: Sorting V (動画)](https://archive.org/details/ucberkeley_webcast_qNMQ4ly43p4)
    - [ ] [CS 61B 2014-04-21: レディックスソート(動画)](https://archive.org/details/ucberkeley_webcast_pvbBMd-3NoI)

- [ ] [バブルソート (動画)](https://www.youtube.com/watch?v=P00xJgWzz2c&index=1&list=PL89B61F78B552C1AB)
- [ ] [バブルソートの分析 (動画)](https://www.youtube.com/watch?v=ni_zk257Nqo&index=7&list=PL89B61F78B552C1AB)
- [ ] [挿入ソート、マージソート (動画)](https://www.youtube.com/watch?v=Kg4bqzAqRBM&index=3&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
- [ ] [挿入ソート (動画)](https://www.youtube.com/watch?v=c4BRHC7kTaQ&index=2&list=PL89B61F78B552C1AB)
- [ ] [マージソート (動画)](https://www.youtube.com/watch?v=GCae1WNvnZM&index=3&list=PL89B61F78B552C1AB)
- [ ] [クイックソート (動画)](https://www.youtube.com/watch?v=y_G9BkAm6B8&index=4&list=PL89B61F78B552C1AB)
- [ ] [選択ソート (動画)](https://www.youtube.com/watch?v=6nDMgr0-Yyo&index=8&list=PL89B61F78B552C1AB)

- [ ] マージソートコード:
    - [ ] [出力配列を使用 (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/sorting/mergesort.c)
    - [ ] [出力配列を使用 (Python)](https://github.com/jwasham/practice-python/blob/master/merge_sort/merge_sort.py)
    - [ ] [インプレース (C++)](https://github.com/jwasham/practice-cpp/blob/master/merge_sort/merge_sort.cc)
- [ ] クイックソートコード:
    - [ ] [実装 (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/randomization/quick.c)
    - [ ] [実装 (C)](https://github.com/jwasham/practice-c/blob/master/quick_sort/quick_sort.c)
    - [ ] [実装 (Python)](https://github.com/jwasham/practice-python/blob/master/quick_sort/quick_sort.py)

- [ ] [[レビュー] ソート (プレイリスト) 18分](https://www.youtube.com/playlist?list=PL9xmBV_5YoZOZSbGAXAPIq1BeUf4j20pl)
    - [ ] [クイックソート 4分 (動画)](https://youtu.be/Hoixgm4-P4M)
    - [ ] [ヒープソート 4分 (動画)](https://youtu.be/2DmK_H7IdTo)
    - [ ] [マージソート 3分 (動画)](https://youtu.be/4VqmGXwpLqc)
    - [ ] [バブルソート 2分 (動画)](https://youtu.be/xli_FI7CuzA)
    - [ ] [選択ソート 3分 (動画)](https://youtu.be/g-PGLbMth_g)
    - [ ] [挿入ソート 2分 (動画)](https://youtu.be/JU767SDMDvA)

- [ ] 実装:
    - [ ] マージソート: 平均および最悪ケースで O(n log n)
    - [ ] クイックソート: 平均ケースで O(n log n)
    - 選択ソートおよび挿入ソートは、平均および最悪ケースでどちらも O(n^2)
    - ヒープソートについては上のヒープデータ構造を参照してください

- [ ] 必須ではありませんが、おすすめします:
    - [ ] [Sedgewick - レディックスソート (6動画)](https://www.coursera.org/learn/algorithms-part2/home/week/3)
        - [ ] [1. Javaでの文字列](https://www.coursera.org/learn/algorithms-part2/lecture/vGHvb/strings-in-java)
        - [ ] [2. キーインデックスカウント](https://www.coursera.org/lecture/algorithms-part2/key-indexed-counting-2pi1Z)
        - [ ] [3. 最も重要な桁から文字列レディックスソート](https://www.coursera.org/learn/algorithms-part2/lecture/c1U7L/lsd-radix-sort)
        - [ ] [4. 最も重要な桁から文字列レディックスソート](https://www.coursera.org/learn/algorithms-part2/lecture/gFxwG/msd-radix-sort)
        - [ ] [5. 3ウェイレディックスクイックソート](https://www.coursera.org/learn/algorithms-part2/lecture/crkD5/3-way-radix-quicksort)
        - [ ] [6. サフィックス配列](https://www.coursera.org/learn/algorithms-part2/lecture/TH18W/suffix-arrays)
    - [ ] [レディックスソート](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#radixSort)
    - [ ] [レディックスソート (動画)](https://www.youtube.com/watch?v=xhr26ia4k38)
    - [ ] [レディックスソート、カウントソート (制約がある場合線形時間) (動画)](https://www.youtube.com/watch?v=Nz1KZXbghj8&index=7&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [ランダム化: 行列乗算、クイックソート、フライバルズアルゴリズム (動画)](https://www.youtube.com/watch?v=cNB2lADK3_s&index=8&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [線形時間でのソート (動画)](https://www.youtube.com/watch?v=pOKy3RZbSws&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=14)

要約すると、[15種類のソートアルゴリズム](https://www.youtube.com/watch?v=kPRA0W1kECg)の視覚的な表現があります。
この話題についてさらに詳しく知りたい場合は、[Some Subjectsの追加詳細](#additional-detail-on-some-subjects)の「ソート」セクションを参照してください。

**[⬆ トップに戻る](#table-of-contents)**

## グラフ

グラフはコンピュータ科学における多くの問題を表すために使用できますので、このセクションは木構造やソートと同様に長くなります。

- メモ:
    - メモリ内にグラフを表す基本的な方法は4つあります:
        - オブジェクトとポインタ
        - 隣接行列
        - 隣接リスト
        - 隣接マップ
    - 各表現方法とその利点・欠点に精通してください
    - BFSとDFS - 計算複雑性、トレードオフ、そして実際のコードでの実装方法を知ってください
    - 質問が提示されたら、まずグラフに基づいた解決策を検討し、それがなければ他の方法を検討してください

- [ ] MIT(videos):
    - [ ] [幅優先探索](https://www.youtube.com/watch?v=oFVYVzlvk9c&t=14s&ab_channel=MITOpenCourseWare)
    - [ ] [深さ優先探索](https://www.youtube.com/watch?v=IBfWDYSffUU&t=32s&ab_channel=MITOpenCourseWare)

- [ ] Skiena レクチャ - とても良い導入:
    - [ ] [CSE373 2020 - レクチャ10 - グラフデータ構造 (動画)](https://www.youtube.com/watch?v=Sjk0xqWWPCc&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=10)
    - [ ] [CSE373 2020 - レクチャ11 - グラフトラバーサル (動画)](https://www.youtube.com/watch?v=ZTwjXj81NVY&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=11)
    - [ ] [CSE373 2020 - レクチャ12 - 深さ優先探索 (動画)](https://www.youtube.com/watch?v=KyordYB3BOs&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=12)
    - [ ] [CSE373 2020 - レクチャ13 - 最小全域木 (動画)](https://www.youtube.com/watch?v=oolm2VnJUKw&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=13)
    - [ ] [CSE373 2020 - レクチャ14 - 最小全域木 (続き) (動画)](https://www.youtube.com/watch?v=RktgPx0MarY&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=14)
    - [ ] [CSE373 2020 - レクチャ15 - グラフアルゴリズム (続き2) (動画)](https://www.youtube.com/watch?v=MUe5DXRhyAo&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=15)

- [ ] グラフ (復習とさらに):

    - [ ] [6.006 単一始点最短経路問題 (動画)](https://www.youtube.com/watch?v=Aa2sqUhIn-E&index=15&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.006 ダイクストラ (動画)](https://www.youtube.com/watch?v=NSHizBK9JD8&t=1731s&ab_channel=MITOpenCourseWare)
    - [ ] [6.006 ベルマン-フォード (動画)](https://www.youtube.com/watch?v=f9cVS_URPc0&ab_channel=MITOpenCourseWare)
    - [ ] [6.006 ダイクストラの高速化 (動画)](https://www.youtube.com/watch?v=CHvQ3q_gJ7E&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=18)
    - [ ] [Aduni: グラフアルゴリズムI - トポロジカルソート、最小全域木、プライムアルゴリズム - レクチャ6 (動画)](../ https://www.youtube.com/watch?v=i_AQT_XfvD8&index=6&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [ ] [Aduni: グラフアルゴリズムII - DFS、BFS、クルスカルアルゴリズム、Union-Findデータ構造 - レクチャ7 (動画)](../ https://www.youtube.com/watch?v=ufj5_bppBsA&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=7)
    - [ ] [Aduni: グラフアルゴリズムIII: 最短経路 - レクチャ8 (動画)](https://www.youtube.com/watch?v=DiedsPsMKXc&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=8)
    - [ ] [Aduni: グラフアルゴリズムIV: 幾何アルゴリズムへの導入 - レクチャ9 (動画)](https://www.youtube.com/watch?v=XIAQRlNkJAw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=9)
    - [ ] [CS 61B 2014: 重み付きグラフ (動画)](https://archive.org/details/ucberkeley_webcast_zFbq8vOZ_0k)
    - [ ] [貪欲アルゴリズム: 最小全域木 (動画)](https://www.youtube.com/watch?v=tKwnms5iRBU&index=16&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [強連結成分 コサラジュアルゴリズム グラフアルゴリズム (動画)](https://www.youtube.com/watch?v=RpgcYiky7uw)
    - [ ] [[復習] 最短経路アルゴリズム (プレイリスト) 16分間 (動画)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZO-Y-H3xIC9DGSfVYJng9Yw)
    - [ ] [[復習] 最小全域木 (プレイリスト) 4分間 (動画)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZObEi3Hf6lmyW-CBfs7nkOV)

- 完全なCourseraコース:
    - [ ] [グラフ上のアルゴリズム (動画)](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome)

- 実装する予定:
    - [ ] 隣接リストによるDFS (再帰的)
    - [ ] 隣接リストによるDFS (スタックによる反復的)
    - [ ] 隣接行列によるDFS (再帰的)
    - [ ] 隣接行列によるDFS (スタックによる反復的)
    - [ ] 隣接リストによるBFS
    - [ ] 隣接行列によるBFS
    - [ ] 単一始点最短経路 (ダイクストラ)
    - [ ] 最小全域木
    - DFSに基づくアルゴリズム (上記のAduni動画を参照):
        - [ ] サイクルの確認 (トポロジカルソートが必要なため、開始前にサイクルを確認する必要があります)
        - [ ] トポロジカルソート
        - [ ] グラフ内の接続成分の数をカウント
        - [ ] 強連結成分のリスト
        - [ ] 二部グラフの確認

**[⬆ トップに戻る](#table-of-contents)**

## より詳しい知識

- ### 再帰
    - [ ] スタンフォードの再帰とバックトラッキングに関する講義:
        - [ ] [講義8 | プログラミング抽象化 (動画)](https://www.youtube.com/watch?v=gl3emqCuueQ&list=PLFE6E58F856038C69&index=8)
        - [ ] [講義9 | プログラミング抽象化 (動画)](https://www.youtube.com/watch?v=uFJhEPrbycQ&list=PLFE6E58F856038C69&index=9)
        - [ ] [講義10 | プログラミング抽象化 (動画)](https://www.youtube.com/watch?v=NdF1QDTRkck&index=10&list=PLFE6E58F856038C69)
        - [ ] [講義11 | プログラミング抽象化 (動画)](https://www.youtube.com/watch?v=p-gpaIGRCQI&list=PLFE6E58F856038C69&index=11)
    - いつ使用すべきか？
    - テール再帰はなぜ良いのか？
        - [ ] [テール再帰とは？なぜ悪いのか？](https://www.quora.com/What-is-tail-recursion-Why-is-it-so-bad)
        - [ ] [テール再帰 (動画)](https://www.coursera.org/lecture/programming-languages/tail-recursion-YZic1)
    - [ ] [再帰問題を解くための5つの簡単なステップ (動画)](https://youtu.be/ngCos392W4w)

	バックトラッキングのブループリント: [Java](https://leetcode.com/problems/combination-sum/discuss/16502/A-general-approach-to-backtracking-questions-in-Java-(Subsets-Permutations-Combination-Sum-Palindrome-Partitioning))
	[Python](https://leetcode.com/problems/combination-sum/discuss/429538/General-Backtracking-questions-solutions-in-Python-for-reference-%3A)
- ### 動的計画法
    - 面接では動的計画法の問題を見ることはないかもしれませんが、動的計画法が適切な問題であることを認識できるようになることは価値があります。
    - このテーマは結構難しいです。それぞれのDPで解ける問題は再帰関係として定義されなければならないため、それを見つけるのは難しいです。
    - DPの問題の例をたくさん見て、パターンをしっかり理解するのをおすすめします。
    - [ ] 動画:
        - [ ] [スカイナ: CSE373 2020 - 講義19 - 動的計画法の導入 (動画)](https://www.youtube.com/watch?v=wAA0AMfcJHQ&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=18)
        - [ ] [スカイナ: CSE373 2020 - 講義20 - 編集距離 (動画)](https://www.youtube.com/watch?v=T3A4jlHlhtA&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=19)
        - [ ] [スカイナ: CSE373 2020 - 講義20 - 編集距離（続き） (動画)](https://www.youtube.com/watch?v=iPnPVcZmRbE&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=20)
        - [ ] [スカイナ: CSE373 2020 - 講義21 - 動的計画法 (動画)](https://www.youtube.com

## 最終確認

このセクションには、重要な概念の多くを確認するために、比較的短いビデオが含まれています。
頻繁にリフレッシャーが必要な場合に便利です。

- [ ] 2〜3分間の短いトピックビデオのシリーズ（23ビデオ）
    - [ビデオ](https://www.youtube.com/watch?v=r4r1DZcx1cM&list=PLmVb1OknmNJuC5POdcDv5oCS7_OUkDgpj&index=22)
- [ ] 2〜5分間の短いトピックビデオのシリーズ - マイケル・サンボル（48ビデオ）:
    - [ビデオ](https://www.youtube.com/@MichaelSambol)
    - [コード例](https://github.com/msambol/dsa)
- [ ] [セドウィック ビデオ - アルゴリズム I](https://www.coursera.org/learn/algorithms-part1)
- [ ] [セドウィック ビデオ - アルゴリズム II](https://www.coursera.org/learn/algorithms-part2)

---

**[⬆ トップに戻る](#table-of-contents)**

## リジュメを更新してください

- 本「Cracking The Coding Interview」および「Programming Interviews Exposed」にリジュメの準備に関する情報を確認してください
- ["This Is What A GOOD Resume Should Look Like" by Gayle McDowell (author of Cracking the Coding Interview)](https://www.careercup.com/resume),
    - 著者の注意書き: "これは米国向けのリジュメです。インドやその他の国での履歴書（CV）は異なる期待がありますが、多くのポイントは同じです。"
- ["Step-by-step resume guide" by Tech Interview Handbook](https://www.techinterviewhandbook.org/resume/guide)
    - から始めてリジュメを作成する方法、効果的なリジュメの内容の書き方、最適化方法、リジュメのテスト方法についての詳細なガイド

**[⬆ back to top](#table-of-contents)**

## 面接プロセスと一般的な面接準備

- [ ] [2021年のエンジニア面接を突破する方法](https://davidbyttow.medium.com/how-to-pass-the-engineering-interview-in-2021-45f1b389a1)
- [ ] [テック採用の謎を解く](https://www.youtube.com/watch?v=N233T0epWTs)
- [ ] 大手4社への就職方法:
    - [ ] [大手4社への就職方法 - Amazon, Facebook, Google & Microsoft (動画)](https://www.youtube.com/watch?v=YJZCUhxNCv8)
    - [ ] [大手4社への就職方法 1 (フォローアップ動画)](https://www.youtube.com/watch?v=6790FVXWBw8&feature=youtu.be)
- [ ] コーディング面接対策セット1:
    - [ ] [Gayle L McDowell - コーディング面接を突破する (動画)](https://www.youtube.com/watch?v=rEJzOhC5ZtQ)
    - [ ] [Gayle Laakmann McDowell著『コーディング面接を突破する』(動画)](https://www.youtube.com/watch?v=aClxtDcdpsQ)
- [ ] Facebookのコーディング面接対策:
    - [ ] [アプローチ](https://www.youtube.com/watch?v=wCl9kvQGHPI)
    - [ ] [問題のウォークスルー](https://www.youtube.com/watch?v=4UWDyJq8jZg)
- 準備コース:
    - [データ構造、アルゴリズム、および面接向けPython (有料コース)](https://www.udemy.com/python-for-data-structures-algorithms-and-interviews/):
        - Pythonに焦点を当てた面接準備コースで、データ構造、アルゴリズム、模擬面接、その他多くの内容をカバー。
    - [Pythonを使用したデータ構造とアルゴリズム入門 (Udacity無料コース)](https://www.udacity.com/course/data-structures-and-algorithms-in-python--ud513):
        - Pythonに焦点を当てたデータ構造とアルゴリズムの無料コース。
    - [データ構造とアルゴリズムナノディグリー! (Udacity有料ナノディグリー)](https://www.udacity.com/course/data-structures-and-algorithms-nanodegree--nd256):
        - 100以上のデータ構造とアルゴリズムの演習問題に手を動かして実践し、専任のメンターから指導を受け、面接や実務のシナリオに備える。
    - [行動面接を突破する (Educative無料コース)](https://www.educative.io/courses/grokking-the-behavioral-interview):
        - 夢の仕事に就けない理由は、技術的な能力ではなく、行動面接でのパフォーマンスが原因であることが多い。
    - [AlgoMonster (有料コースと無料コンテンツ)](https://algo.monster/?utm_campaign=jwasham&utm_medium=referral&utm_content=coding-interview-university&utm_source=github):
      - LeetCodeの短期集中コース。数千の質問から抽出されたすべてのパターンをカバー。

模擬面接:
- [Gainlo.co: 大手企業の模擬面接官](http://www.gainlo.co/#!/) - このサービスを利用し、電話面接と対面面接でリラックスすることができた。
- [Pramp: ピアによる模擬面接](https://www.pramp.com/) - ピア間で面接を練習するモデル。
- [interviewing.io: シニアエンジニアによる模擬面接練習](https://interviewing.io) - FAANGのシニアエンジニアと匿名でアルゴリズムやシステム設計の面接を実施。
- [Meetapro: FAANGの面接官による模擬面接](https://meetapro.com/?utm_source=ciu) - Airbnbスタイルの模擬面接/コーチングプラットフォーム。
- [Hello Interview: 専門のコーチやAIによる模擬面接](https://www.hellointerview.com/?utm_source=ciu) - AIまたはFAANGのスタッフエンジニアやマネージャーと直接面接。
- [Codemia: AIまたはコミュニティの解決策とフィードバックを使用してシステム設計問題を練習](https://codemia.io/?utm_source=ciu) - AI練習ツールを使用してシステム設計問題を練習。コミュニティに解決策を共有し、人間からのフィードバックも得られる。

**[⬆ トップへ戻る](#table-of-contents)**

## 面接が来るときに考えておくこと

面接で質問されるであろう約20の質問を考えておくこと。以下の項目のラインに沿って、それぞれ少なくとも1つの回答を用意しておくこと。データではなく、何かを成し遂げたという物語を用意すること。

- この仕事に応募した理由は?
- 過去に解決した難しい問題は?
- 面臨した最大の課題は?
- 見たことのある最高の/最悪のデザインは?
- 既存の製品を改善するためのアイデアは?
- 個人として、チームの一員として、最もよく働ける方法は?
- あなたのスキルや経験のうち、この役割において資産となるものは何か、なぜか?
- [仕事x / プロジェクトy]で最も楽しんだことは?
- [仕事x / プロジェクトy]で直面した最大の課題は?
- [仕事x / プロジェクトy]で直面した最も難しいバグは?
- [仕事x / プロジェクトy]で学んだことは?
- [仕事x / プロジェクトy]では、もっとよくできていたと思うことは?

**[⬆ トップへ戻る](#table-of-contents)**

## 面接官に質問したいこと

以下が私の質問です（すでに答えを知っているかもしれませんが、彼らの意見やチームの視点が知りたいです）：

- あなたのチームの規模はどのくらいですか？
- 開発サイクルはどのようですか？ウォーターフォール/スプリント/アジャイルを行っていますか？
- デッドラインに追われることが多いですか？それとも柔軟性がありますか？
- チームではどのように決定を下していますか？
- 週に何回会議がありますか？
- あなたの作業環境は集中力を高めるのに役立っていますか？
- 今、何をしていますか？
- 何が好きですか？
- 仕事と生活の様子はどのようですか？
- 仕事と生活のバランスはどのようですか？

**[⬆ トップに戻る](#table-of-contents)**

## Once You've Got The Job

Congratulations!

Keep learning.

You're never really done.

---

   *************************************
   *************************************

    Everything below this point is optional. It is NOT needed for an entry-level interview.
    However, by studying these, you'll get greater exposure to more CS concepts and will be better prepared for
    any software engineering job. You'll be a much more well-rounded software engineer.

   *************************************
   *************************************

---

**[⬆ back to top](#table-of-contents)**

## その他の書籍

これらは、興味のあるトピックについてさらに深く学ぶために用意されています。

- [The Unix Programming Environment](https://www.amazon.com/dp/013937681X)
    - 古いが非常に良い本
- [The Linux Command Line: A Complete Introduction](https://www.amazon.com/dp/1593273894/)
    - 現代的な選択肢
- [TCP/IP Illustrated Series](https://en.wikipedia.org/wiki/TCP/IP_Illustrated)
- [Head First Design Patterns](https://www.amazon.com/gp/product/0596007124/)
    - デザインパターンへの優しい導入
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)
    - 通称「Gang Of Four」の本またはGOF
    - デザインパターンの標準的な本
- [Algorithm Design Manual](http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202) (Skiena)
    - 見直しと問題認識のために
    - アルゴリズムカタログの部分は、面接で得られる難易度を超えており、非常に難解です
    - この本は2つの部分から構成されています：
        - データ構造とアルゴリズムに関するクラスの教科書
            - 長所：
                - どのアルゴリズムの教科書でも良い見直しになります
                - 産業界や学術界で問題を解決する経験から得たエピソードが含まれています
                - C言語でのコード例が含まれています
            - 短所：
                - CLRSと同様に、密で理解が難しい場合があります。一部のトピックではCLRSがより良い選択肢である場合もあります
                - 第7章、第8章、第9章は、説明が不十分であったり、頭を使う必要があるため、読むのが非常に困難です
                - 間違いなく、Skienaの本や彼の授業スタイル、マナーは好きですが、私はStony Brookの材料にはなり得ないかもしれません
        - アルゴリズムカタログ：
            - この本を購入する本当の理由です。
            - この本はアルゴリズムの参考書として非常に優れており、一から最後まで読むものではありません。
    - Kindleで借りることができます
    - 解答：
        - [解答](https://web.archive.org/web/20150404194210/http://www.algorithm.cs.sunysb.edu/algowiki/index.php/The_Algorithms_Design_Manual_(Second_Edition))
    - [誤植](http://www3.cs.stonybrook.edu/~skiena/algorist/book/errata)
- [Algorithm](http://jeffe.cs.illinois.edu/teaching/algorithms/) (Jeff Erickson)
- [Write Great Code: Volume 1: Understanding the Machine](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
    - この本は2004年に出版され、やや古くなっていますが、コンピュータを簡単に理解するための非常に良いリソースです
    - 著者は[HLA](https://en.wikipedia.org/wiki/High_Level_Assembly)を考案したため、HLAに関する記述や例は、一粒の砂に注意して読む必要があります。HLAは広く使われていませんが、アセンブリ言語の見た目を示す良い例です
    - 以下の章は、良い基礎を築くために読む価値があります：
        - 第2章 - 数値表現
        - 第3章 - 二進数の算術とビット演算
        - 第4章 - 浮動小数点表現
        - 第5章 - 文字の表現
        - 第6章 - メモリの構成とアクセス
        - 第7章 - 複合データ型とメモリオブジェクト
        - 第9章 - CPUアーキテクチャ
        - 第10章 - 指令セットアーキテクチャ
        - 第11章 - メモリアーキテクチャと構成
- [Introduction to Algorithms](https://www.amazon.com/Introduction-Algorithms-fourth-Thomas-Cormen/dp/026204630X)
    - **重要:** この本を読んでも限られた価値しか得られません。この本はアルゴリズムとデータ構造の良い見直しになりますが、良いコードを書く方法を教えることはありません。効率的に良いソリューションを書ける能力が必要です
    - 通称CLR、時折CLRSと呼ばれるのは、Steinが遅れて参加したからです
- [Computer Architecture, Sixth Edition: A Quantitative Approach](https://www.amazon.com/dp/0128119055)
    - より豊かで、最新の（2017年）、しかし長く詳細な解説が含まれています

**[⬆ トップに戻る](#table-of-contents)**

## システム設計、スケーラビリティ、データ処理

**4年以上の経験がある場合、システム設計に関する質問が予想されます。**

- スケーラビリティとシステム設計は非常に広範なトピックであり、多くのトピックとリソースがあります。なぜなら、スケール可能なソフトウェア/ハードウェアシステムを設計する際には、多くのことを考慮する必要があるからです。
      これはかなりの時間を要するでしょう。
- 考え方:
    - スケーラビリティ
        - 大規模なデータセットを単一の値に凝縮する
        - 1つのデータセットを別のデータセットに変換する
        - 非常に大量のデータを処理する
    - システム設計
        - 機能セット
        - インターフェース
        - クラス階層
        - 一定の制約下でのシステム設計
        - 簡潔さと堅牢性
        - 費用対効果
        - パフォーマンス分析と最適化
- [ ] **ここから開始**: [The System Design Primer](https://github.com/donnemartin/system-design-primer)
- [ ] [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
- [ ] [How Do I Prepare To Answer Design Questions In A Technical Interview?](https://www.quora.com/How-do-I-prepare-to-answer-design-questions-in-a-technical-interview?redirected_qid=1500023)
- [ ] [8 steps guide to ace your system design interview](https://javascript.plainenglish.io/8-steps-guide-to-ace-a-system-design-interview-7a5a797f4d7d)
- [ ] [Database Normalization - 1NF, 2NF, 3NF and 4NF (video)](https://www.youtube.com/watch?v=UrYLYV7WSHM)
- [ ] [System Design Interview](https://github.com/checkcheckzz/system-design-interview) - この中に多くのリソースがあります。記事や例を確認してください。以下にいくつか掲載しています。
- [ ] [How to ace a systems design interview](https://web.archive.org/web/20120716060051/http://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
- [ ] [Numbers Everyone Should Know](http://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
- [ ] [How long does it take to make a context switch?](http://blog.tsunanet.net/2010/11/how-long-does-it-take-to-make-context.html)
- [ ] [Transactions Across Datacenters (video)](https://www.youtube.com/watch?v=srOgpXECblk)
- [ ] [A plain English introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
- [ ] [MIT 6.824: Distributed Systems, Spring 2020 (20 videos)](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)
- [ ] コンセンサスアルゴリズム:
    - [ ] Paxos - [Paxos Agreement - Computerphile (video)](https://www.youtube.com/watch?v=s8JqcZtvnsM)
    - [ ] Raft - [An Introduction to the Raft Distributed Consensus Algorithm (video)](https://www.youtube.com/watch?v=P9Ydif5_qvE)
        - [ ] [読みやすい論文](https://raft.github.io/)
        - [ ] [インフォグラフィック](http://thesecretlivesofdata.com/raft/)
- [ ] [Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html)
- [ ] [NoSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
- [ ] スケーラビリティ:
    - これらすべてが必要ではありません。興味のあるものをいくつか選んでください。
    - [ ] [概要 (video)](https://www.youtube.com/watch?v=-W9F__D3oY4)
    - [ ] 短いシリーズ:
        - [クローン](http://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
        - [データベース](http://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
        - [キャッシュ](http://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
        - [非同期処理](http://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)
    - [ ] [スケーラブルなウェブアーキテクチャと分散システム](http://www.aosabook.org/en/distsys.html)
    - [ ] [分散コンピューティングの誤謬の説明](https://pages.cs.wisc.edu/~zuyu/files/fallacies.pdf)
    - [ ] [ジェフ・ディーン - Googleでのソフトウェアシステムの構築と学んだこと (video)](https://www.youtube.com/watch?v=modXC5IWTJI)
    - [ ] [スケールに耐えるシステム設計の紹介](http://lethain.com/introduction-to-architecting-systems-for-scale/)
    - [ ] [App EngineとCloud Datastoreを使用してグローバルなオーディエンスに向けたモバイルゲームのスケーリング (video)](https://www.youtube.com/watch?v=9nWyWwY2Onc)
    - [ ] [Googleがグローバルなインフラに向けたスケールエンジニアリングを行う方法 (video)](https://www.youtube.com/watch?v=H4vMcD7zKM0)
    - [ ] [アルゴリズムの重要性](https://www.topcoder.com/thrive/articles/The%20Importance%20of%20Algorithms)
    - [ ] [シャーディング](http://highscalability.com/blog/2009/8/6/an-unorthodox-approach-to-database-design-the-coming-of-the.html)
    - [ ] [長期的なエンジニアリング - Astrid Atkinsonのキーノート (video)](https://www.youtube.com/watch?v=p0jGmgIrf_M&list=PLRXxvay_m8gqVlExPC5DG3TGWJTaBgqSA&index=4)
    - [ ] [7年間のYouTubeスケーラビリティの教訓を30分で](http://highscalability.com/blog/2012/3/26/7-years-of-youtube-scalability-lessons-in-30-minutes.html)
        - [video](https://www.youtube.com/watch?v=G-lGCC4KKok)
    - [ ] [PayPalが8VMで毎日数十億のトランザクションを処理する方法](http://highscalability.com/blog/2016/8/15/how-paypal-scaled-to-billions-of-transactions-daily-using-ju.html)
    - [ ] [大規模なデータセットから重複を除去する方法](https://blog.clevertap.com/how-to-remove-duplicates-in-large-datasets/)
    - [ ] [Etsyのスケールとエンジニアリング文化の見解 (video)](https://www.youtube.com/watch?v=3vV4YiqKm1o)
    - [ ] [Amazonが独自のマイクロサービスアーキテクチャに至った経緯](http://thenewstack.io/led-amazon-microservices-architecture/)
    - [ ] [圧縮するかしないか、Uberの選択](https://eng.uber.com/trip-data-squeeze/)
    - [ ] [近似クエリ処理をいつ使用すべきか](http://highscalability.com/blog/2016/2/25/when-should-approximate-query-processing-be-used.html)
    - [ ] [Googleが単一データセンターからフェールオーバー、ネイティブマルチホームアーキテクチャへの移行](../ http://highscalability.com/blog/2016/2/23/googles-transition-from-single-datacenter-to-failover-to-a-n.html)
    - [ ] [毎日数百万のリクエストを処理する画像最適化技術](http://highscalability.com/blog/2016/6/15/the-image-optimization-technology-that-serves-millions-of-re.html)
    - [ ] [Patreonのアーキテクチャの短い紹介](http://highscalability.com/blog/2016/2/1/a-patreon-architecture-short.html)
    - [ ] [Tinder: 最大のレコメンドエンジンの1つが次にあなたに誰を表示するかをどう決めるのか](http://highscalability.com/blog/2016/1/27/tinder-how-does-one-of-the-largest-recommendation-engines-de.html)
    - [ ] [現代的なキャッシュの設計](http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)
    - [ ] [Facebookスケールでのライブ動画ストリーミング](http://highscalability.com/blog/2016/1/13/live-video-streaming-at-facebook-scale.html)
    - [ ] [Amazon AWS上で1100万以上のユーザーにスケールするための入門ガイド](http://highscalability.com/blog/2016/1/11/a-beginners-guide-to-scaling-to-11-million-users-on-amazons.html)
    - [ ] [Netflixスタック全体の360度ビュー](http://highscalability.com/blog/2015/11/9/a-360-degree-view-of-the-entire-netflix-stack.html)
    - [ ] [遅延は至る所に存在し、売上に影響を与える - どう対処するか](http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it)
    - [ ] [Instagramを支えるもの: 数百のインスタンス、数十の技術](http://instagram-engineering.tumblr.com/post/13649370142/what-powers-instagram-hundreds-of-instances)
    - [ ] [Salesforceアーキテクチャ - 毎日13億のトランザクションをどう処理するか](http://highscalability.com/blog/2013/9/23/salesforce-architecture-how-they-handle-13-billion-transacti.html)
    - [ ] [ESPNのスケールでのアーキテクチャ - 100,000のDuh Nuh Nuhs/秒で運用](http://highscalability.com/blog/2013/11/4/espns-architecture-at-scale-operating-at-100000-duh-nuh-nuhs.html)
    - [ ] 以下で「メッセージング、シリアライズ、キューイングシステム」を参照して、サービスをつなぐ技術に関する情報が掲載されています。
    - [ ] Twitter:
        - [O'Reilly MySQL CE 2011: Jeremy Cole, "Big and Small Data at @Twitter" (video)](https://www.youtube.com/watch?v=5cKTP36HVgI)
        - [スケールでのタイムライン](https://www.infoq.com/presentations/Twitter-Timeline-Scalability)
    - より多くの情報については、[Video Series](#video-series)セクションにある「Mining Massive Datasets」の動画シリーズを参照してください。
- [ ] システム設計プロセスの実践: 以下は、紙に書きながら試してみるためのアイデアです。それぞれに、現実世界でどのように処理されたかのドキュメントが含まれています。
    - 見直し: [The System Design Primer](https://github.com/donnemartin/system-design-primer)
    - [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
    - [チートシート](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/system-design.pdf)
    - フロー:
        1. 問題と範囲を理解する:
            - 面接官の助けを借りて、ユースケースを定義する
            - 他の機能を提案する
            - 面接官が範囲外と判断した項目を削除する
            - 高可用性が必要であることを仮定し、ユースケースとして追加する
        2. 制約について考える:
            - 月間リクエスト数を尋ねる
            - 秒間リクエスト数を尋ねる（彼らが自発的に提供するか、計算させるか）
            - 読み取りと書き込みの比率を推定する
            - 推定する際には80/20ルールを考慮する
            - 秒間の書き込みデータ量
            - 5年間の総ストレージ容量
            - 秒間の読み取りデータ量
        3. 抽象設計:
            - レイヤー（サービス、データ、キャッシュ）
            - インフラストラクチャ: ロードバランシング、メッセージング
            - サービスを駆動する主要なアルゴリズムの概要
            - ボトルネックを考慮し、解決策を決定する
    - 練習:
        - [ランダムなユニークID生成システムを設計する](https://blog.twitter.com/2010/announcing-snowflake)
        - [キーバリューデータベースを設計する](http://www.slideshare.net/dvirsky/introduction-to-redis)
        - [画像共有システムを設計する](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
        - [レコメンドシステムを設計する](http://ijcai13.org/files/tutorial_slides/td3.pdf)
        - [URL短縮システムを設計する: 上記からコピー](http://www.hiredintech.com/system-design/the-system-design-process/)
        - [キャッシュシステムを設計する](https://web.archive.org/web/20220217064329/https://adayinthelifeof.nl/2011/02/06/memcache-internals/)

**[⬆ トップに戻る](#table-of-contents)**

## その他の学習

それらを追加したのは、あなたがバランスの取れたソフトウェアエンジニアになるのを助ける

## いくつかのテーマに関する追加の詳細

これらを追加した理由は、上記で既に提示したアイデアを強化するためですが、上記に含めなかったのは、内容が多すぎるからです。テーマについて過剰に語りすぎるのは簡単です。
この世紀に採用されるためにも、したいですよね？

- **SOLID**
    - [ ] [Bob Martin SOLID Principles of Object Oriented and Agile Design (video)](https://www.youtube.com/watch?v=TMuno5RZNeE)
    - [ ] S - [Single Responsibility Principle](http://www.oodesign.com/single-responsibility-principle.html) | [Single responsibility to each Object](http://www.javacodegeeks.com/2011/11/solid-single-responsibility-principle.html)
        - [more flavor](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
    - [ ] O - [Open/Closed Principle](http://www.oodesign.com/open-close-principle.html)  | [On production level Objects are ready for extension but not for modification](https://en.wikipedia.org/wiki/Open/closed_principle)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
    - [ ] L - [Liskov Substitution Principle](http://www.oodesign.com/liskov-s-substitution-principle.html) | [Base Class and Derived class follow ‘IS A’ Principle](http://stackoverflow.com/questions/56860/what-is-the-liskov-substitution-principle)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
    - [ ] I - [Interface segregation principle](http://www.oodesign.com/interface-segregation-principle.html) | Clients should not be forced to implement interfaces they don't use
        - [Interface Segregation Principle in 5 minutes (video)](https://www.youtube.com/watch?v=3CtAfl7aXAQ)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
    - [ ] D -[Dependency Inversion principle](http://www.oodesign.com/dependency-inversion-principle.html) | Reduce the dependency In composition of objects.
        - [Why Is The Dependency Inversion Principle And Why Is It Important](http://stackoverflow.com/questions/62539/what-is-the-dependency-inversion-principle-and-why-is-it-important)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)

- **Union-Find**
    - [Overview](https://www.coursera.org/learn/data-structures/lecture/JssSY/overview)
    - [Naive Implementation](https://www.coursera.org/learn/data-structures/lecture/EM5D0/naive-implementations)
    - [Trees](https://www.coursera.org/learn/data-structures/lecture/Mxu0w/trees)
    - [Union By Rank](https://www.coursera.org/learn/data-structures/lecture/qb4c2/union-by-rank)
    - [Path Compression](https://www.coursera.org/learn/data-structures/lecture/Q9CVI/path-compression)
    - [Analysis Options](https://www.coursera.org/learn/data-structures/lecture/GQQLN/analysis-optional)

- **More Dynamic Programming** (videos)
    - [6.006: Dynamic Programming I: Fibonacci, Shortest Paths](https://www.youtube.com/watch?v=r4-cftqTcdI&ab_channel=MITOpenCourseWare)
    - [6.006: Dynamic Programming II: Text Justification, Blackjack](https://www.youtube.com/watch?v=KLBCUx1is2c&ab_channel=MITOpenCourseWare)
    - [6.006: DP III: Parenthesization, Edit Distance, Knapsack](https://www.youtube.com/watch?v=TDo3r5M1LNo&ab_channel=MITOpenCourseWare)
    - [6.006: DP IV: Guitar Fingering, Tetris, Super Mario Bros.](https://www.youtube.com/watch?v=i9OAOk0CUQE&ab_channel=MITOpenCourseWare)
    - [6.046: Dynamic Programming & Advanced DP](https://www.youtube.com/watch?v=Tw1k46ywN6E&index=14&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [6.046: Dynamic Programming: All-Pairs Shortest Paths](https://www.youtube.com/watch?v=NzgFUwOaoIw&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=15)
    - [6.046: Dynamic Programming (student recitation)](https://www.youtube.com/watch?v=krZI60lKPek&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=12)

- **Advanced Graph Processing** (videos)
    - [Synchronous Distributed Algorithms: Symmetry-Breaking. Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=mUBmcbbJNf4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=27)
    - [Asynchronous Distributed Algorithms: Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=kQ-UQAzcnzA&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=28)

- MIT **Probability** (mathy, and go slowly, which is good for mathy things) (videos):
    - [MIT 6.042J - Probability Introduction](https://www.youtube.com/watch?v=SmFwFdESMHI&index=18&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Conditional Probability](https://www.youtube.com/watch?v=E6FbvM-FGZ8&index=19&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Independence](https://www.youtube.com/watch?v=l1BCv3qqW4A&index=20&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Random Variables](https://www.youtube.com/watch?v=MOfhhFaQdjw&list=PLB7540DEDD482705B&index=21)
    - [MIT 6.042J - Expectation I](https://www.youtube.com/watch?v=gGlMSe7uEkA&index=22&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Expectation II](https://www.youtube.com/watch?v=oI9fMUqgfxY&index=23&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Large Deviations](https://www.youtube.com/watch?v=q4mwO2qS2z4&index=24&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Random Walks](https://www.youtube.com/watch?v=56iFMY8QW2k&list=PLB7540DEDD482705B&index=25)

- [Simonson: Approximation Algorithms (video)](https://www.youtube.com/watch?v=oDniZCmNmNw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=19)

- **String Matching**
    - Rabin-Karp (videos):
        - [Rabin Karps Algorithm](https://www.coursera.org/lecture/data-structures/rabin-karps-algorithm-c0Qkw)
        - [Precomputing](https://www.coursera.org/learn/data-structures/lecture/nYrc8/optimization-precomputation)
        - [Optimization: Implementation and Analysis](https://www.coursera.org/learn/data-structures/lecture/h4ZLc/optimization-implementation-and-analysis)
        - [Table Doubling, Karp-Rabin](https://www.youtube.com/watch?v=BRO7mVIFt08&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=9)
        - [Rolling Hashes, Amortized Analysis](https://www.youtube.com/watch?v=w6nuXg0BISo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=32)
    - Knuth-Morris-Pratt (KMP):
        - [TThe Knuth-Morris-Pratt (KMP) String Matching Algorithm](https://www.youtube.com/watch?v=5i7oKodCRJo)
    - Boyer–Moore string search algorithm
        - [Boyer-Moore String Search Algorithm](https://en.wikipedia.org/wiki/Boyer%E2%80%93Moore_string_search_algorithm)
        - [Advanced String Searching Boyer-Moore-Horspool Algorithms (video)](https://www.youtube.com/watch?v=QDZpzctPf10)
    - [Coursera: Algorithms on Strings](https://www.coursera.org/learn/algorithms-on-strings/home/week/1)
        - starts off great, but by the time it gets past KMP it gets more complicated than it needs to be
        - nice explanation of tries
        - can be skipped

- **Sorting**

    - Stanford lectures on sorting:
        - [Lecture 15 | Programming Abstractions (video)](https://www.youtube.com/watch?v=ENp00xylP7c&index=15&list=PLFE6E58F856038C69)
        - [Lecture 16 | Programming Abstractions (video)](https://www.youtube.com/watch?v=y4M9IVgrVKo&index=16&list=PLFE6E58F856038C69)
    - Shai Simonson:
        - [Algorithms - Sorting - Lecture 2 (video)](https://www.youtube.com/watch?v=odNJmw5TOEE&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=2)
        - [Algorithms - Sorting II - Lecture 3 (video)](https://www.youtube.com/watch?v=hj8YKFTFKEE&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=3)
    - Steven Skiena lectures on sorting:
        - [CSE373 2020 - Mergesort/Quicksort (video)](https://www.youtube.com/watch?v=jUf-UQ3a0kg&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=8)
        - [CSE373 2020 - Linear Sorting (video)](https://www.youtube.com/watch?v=0ksyQKmre84&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=9)

- NAND To Tetris: [Build a Modern Computer from First Principles](https://www.coursera.org/learn/build-a-computer)

**[⬆ back to top](#table-of-contents)**

## ビデオシリーズ

リラックスして楽しんでください。

- [動的計画法の個別の問題リスト（すべて短い）](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)

- [x86アーキテクチャ、アセンブリ、アプリケーション（11ビデオ）](https://www.youtube.com/playlist?list=PL038BE01D3BAEFDB0)

- [MIT 18.06 線形代数、2005年春学期（35ビデオ）](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8)

- [優れた講義 - MIT 微分積分学の再訪：単変数微分積分学](https://www.youtube.com/playlist?list=PL3B08AE665AB9002A)

- [Skienaによるアルゴリズム設計マニュアルの講義 - CSE373 2020 - アルゴリズムの分析（26ビデオ）](https://www.youtube.com/watch?v=22hwcnXIGgk&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=1)

- [UC Berkeley 61B（2014年春学期）：データ構造（25ビデオ）](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd)

- [UC Berkeley 61B（2006年秋学期）：データ構造（39ビデオ）](https://archive.org/details/ucberkeley-webcast-PL4BBB74C7D2A1049C)

- [UC Berkeley 61C：マシン構造（26ビデオ）](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_)

- [OOSE：UMLとJavaを使用したソフトウェア開発（21ビデオ）](https://www.youtube.com/playlist?list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO)

- [MIT 6.004：コンピューテーション構造（49ビデオ）](https://www.youtube.com/playlist?list=PLDSlqjcPpoL64CJdF0Qee5oWqGS6we_Yu)

- [カーネギー・メロン大学 - コンピュータアーキテクチャ講義（39ビデオ）](https://www.youtube.com/playlist?list=PL5PHm2jkkXmi5CxxI7b3JCL1TWybTDtKq)

- [MIT 6.006：アルゴリズム入門（47ビデオ）](https://www.youtube.com/watch?v=HtSuA80QTyo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&nohtml5=False)

- [MIT 6.033：コンピュータシステム工学（22ビデオ）](https://www.youtube.com/watch?v=zm2VP0kHl1M&list=PL6535748F59DCA484)

- [MIT 6.034 人工知能、2010年秋学期（30ビデオ）](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)

- [MIT 6.042J：コンピュータ科学のための数学、2010年秋学期（25ビデオ）](https://www.youtube.com/watch?v=L3LMbpZIKhQ&list=PLB7540DEDD482705B)

- [MIT 6.046：アルゴリズムの設計と分析（34ビデオ）](https://www.youtube.com/watch?v=2P-yW7LQr08&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

- [MIT 6.824：分散システム、2020年春学期（20ビデオ）](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)

- [MIT 6.851：高度なデータ構造（22ビデオ）](https://www.youtube.com/watch?v=T0yzrZL1py0&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=1)

- [MIT 6.854：高度なアルゴリズム、2016年春学期（24ビデオ）](https://www.youtube.com/playlist?list=PL6ogFv-ieghdoGKGg2Bik3Gl1glBTEu8c)

- [ハーバード大学 COMPSCI 224：高度なアルゴリズム（25ビデオ）](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uP4rJgf5ayhHWgw7akUWSf)

- [MIT 6.858 コンピュータシステムセキュリティ、2014年秋学期](https://www.youtube.com/watch?v=GqmQg-cszw4&index=1&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)

- [スタンフォード大学：プログラミングパラダイム（27ビデオ）](https://www.youtube.com/playlist?list=PL9D558D49CA734A02)

- [クリストフ・パアールによる暗号入門](https://www.youtube.com/playlist?list=PL6N5qY2nvvJE8X75VkXglSrVhLv1tVcfy)
    - [コースウェブサイトおよびスライドと問題セット](http://www.crypto-textbook.com/)

- [大規模データのマイニング - スタンフォード大学（94ビデオ）](https://www.youtube.com/playlist?list=PLLssT5z_DsK9JDLcT8T62VtzwyW9LNepV)

- [グラフ理論 - サラダ・ハーケ（67ビデオ）](https://www.youtube.com/user/DrSaradaHerke/playlists?shelf_id=5&view=50&sort=dd)

**[⬆ トップに戻る](#table-of-contents)**

## コンピュータサイエンスコース

- [オンラインCSコースのディレクトリ](https://github.com/open-source-society/computer-science)
- [CSコースのディレクトリ（多くのコースにオンライン講義あり）](https://github.com/prakhar1989/awesome-courses)

**[⬆ トップに戻る](#table-of-contents)**

## アルゴリズムの実装

- [プリンストン大学による複数のアルゴリズムの実装](https://algs4.cs.princeton.edu/code)

**[⬆ 上へ戻る](#table-of-contents)**

## Papers

- [Love classic papers?](https://www.cs.cmu.edu/~crary/819-f09/)
- [1978: Communicating Sequential Processes](http://spinroot.com/courses/summer/Papers/hoare_1978.pdf)
    - [implemented in Go](https://godoc.org/github.com/thomas11/csp)
- [2003: The Google File System](http://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
    - replaced by Colossus in 2012
- [2004: MapReduce: Simplified Data Processing on Large Clusters](../ http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
    - mostly replaced by Cloud Dataflow?
- [2006: Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [2006: The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby-osdi06.pdf)
- [2007: Dynamo: Amazon’s Highly Available Key-value Store](http://s3.amazonaws.com/AllThingsDistributed/sosp/amazon-dynamo-sosp2007.pdf)
    - The Dynamo paper kicked off the NoSQL revolution
- [2007: What Every Programmer Should Know About Memory (very long, and the author encourages skipping of some sections)](https://www.akkadia.org/drepper/cpumemory.pdf)
- 2012: AddressSanitizer: A Fast Address Sanity Checker:
    - [paper](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37752.pdf)
    - [video](https://www.usenix.org/conference/atc12/technical-sessions/presentation/serebryany)
- 2013: Spanner: Google’s Globally-Distributed Database:
    - [paper](http://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)
    - [video](https://www.usenix.org/node/170855)
- [2015: Continuous Pipelines at Google](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43790.pdf)
- [2015: High-Availability at Massive Scale: Building Google’s Data Infrastructure for Ads](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44686.pdf)
- [2015: How Developers Search for Code: A Case Study](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43835.pdf)
- More papers: [1,000 papers](https://github.com/0voice/computer_expert_paper)

**[⬆ back to top](#table-of-contents)**

## LICENSE

[CC-BY-SA-4.0](.././LICENSE.txt)

