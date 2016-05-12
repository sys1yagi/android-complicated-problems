# android-complicated-problems

origin : http://konifar-zatsu.hatenadiary.jp/entry/2016/05/05/002128

# What is this

本リポジトリではAndroidアプリケーションを開発している時に遭遇する複雑な問題に対してどのようなアプローチをするべきかを考察していきます。

# Why

Androidアプリケーション開発における複雑な問題を統合的に解くためです。多くの議論が個別の問題にフォーカスしており問題同士の相互作用に言及していません。あるいはアーキテクチャやライブラリが主体の議論となり本質的な問題が何なのかが曖昧であるケースが多いです。

# How do it

まず複雑さをもたらしている問題を列挙しそれらすべてを含んだアプリケーションの仕様を策定します。そこから各問題を個別に解くケースと全体を全て満たすケースの実装を考えていきます。実装に対する制約はありません。さまざまな言語、プラットフォーム、ライブラリ、アーキテクチャの実装を集めようと考えています。

# Complicated problems

[en](README.md)

1. 一覧のロード中に画面の向きが変更された時にそのままロードと表示させたい。
1. 一覧のロード中に画面が閉じられた時にロードを中止したい。
1. 一覧でいいねを押してからタップして詳細を開いた。
1. 一覧でロードエラーが発生した時にリトライしたい。
1. オフライン状態で一覧画面を開いた。
1. 一覧のデータが0件の時は大きなレクタングル広告を表示、1件以上の時はフッタにバナー広告を表示したい。
1. 一覧の上部に特集一覧を表示する時、2つのロードをいい感じにしたい。
1. 一覧の2つ目と8つ目にネイティブ広告を表示したい。表示の速度も考慮してプリロードもしておきたい。
1. メッセージ画面でメッセージを送信する時、リクエストが成功する前に画面に表示させたい。
1. メッセージ画面でメッセージを送信失敗した時、リトライしたい。
1. 低ネットワーク環境下では低画質の画像を表示したい。
1. wi-fiにつないでいる場合のみ、プリロードして表示を高速化したい。
1. いいねボタンを含む一覧があり、そこから詳細画面に遷移しいいねを押す。一覧に復帰した時にいいねの状態が反映されている。
1. 画面に復帰したとき最初のロードから5分以上経過していたら再ロードしたい

# App specification

TODO : 上記の問題を全て含むアプリケーションの仕様を定義する


# LICENSE

```
The MIT License (MIT)

Copyright (c) 2016 Toshihiro Yagi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```