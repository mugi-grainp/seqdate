# 概要

指定された期間の日付文字列を、改行区切りで出力する

## 入力と出力

- 引数1: 開始日
- 引数2: 終了日

```
$ seqdate 2019-06-25 2019-07-05
```
v1.0.0 時点での仕様として、開始日よりも終了日は後でなければならない。
また、開始日、終了日の年月日区切り記号は何でもよく、なくても構わない。

上記入力の時、出力は以下の通り。

```
2019-06-25
2019-06-26
2019-06-27
2019-06-28
2019-06-29
2019-06-30
2019-07-01
2019-07-02
2019-07-03
2019-07-04
2019-07-05
```

v1.0.0時点での仕様として、区切り記号は変更できない。
