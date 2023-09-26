# アルゴリズム学習まとめ

## 使えるテクニックメモ

[桁分離](http://logos.yumenogotoshi.com/tkool2_script_sepa.html)

## 詰まったところ

### [いい整数](https://atcoder.jp/contests/abc079/tasks/abc079_a)

4桁の整数で、同じ数字が3つ以上並んだもの
if文までの知識
**2,3桁目が違ったらfalse**
↑の考え方でいけた(桁分離を使った)

### [Hina Arare](https://atcoder.jp/contests/abc089/tasks/abc089_b)

とにかく、n文字の半角スペース区切りの標準入力の方法がわからない。
本当にそれまでの知識で解けるのかってハナシ。
[Shift Only](https://atcoder.jp/contests/abc081/tasks/abc081_b)も

### [Collecting Balls(Easy)](https://atcoder.jp/contests/abc074/tasks/abc074_b)

半角スペース区切りのn個の標準入力の仕方不明  
x,y座標の話が理解ムズイ

### [回文数のやつ](https://atcoder.jp/contests/abc090/tasks/abc090_b)

全探索しか浮かばないが、めちゃいい方法ありそう
とりあえず、回文数になるまで探索して、見つかったら100（中心の数）をインクリメントする。ただ、2の位が9のときは10にしないとだめ。（他にいい方法がありそう。）

### [minesweeper](https://atcoder.jp/contests/abc075/tasks/abc075_b)

リスト使えば余裕そうだが、stringだけの知識だと難しそう。