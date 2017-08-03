# cdda-mod-Daizu
[Cataclysm: Dark Days Ahead](http://www.cataclysmdda.com/) に大豆を追加するmodです。
これはオリジナルからのフォークです。

## インストール
data/modsフォルダの中に、Daizu_modフォルダをコピーして下さい。
また、[植木鉢mod](https://github.com/hirmiura/cdda-mod-Uekibati)もインストールする必要があります。

## 追加されるもの
- 大豆とその種、そうして大豆から作られる諸々の食品 (味噌、醤油、豆乳、豆腐、おから、納豆)
- 追加された食品から作られる料理 (卯の花、味噌汁、干し納豆、豆腐ハンバーグなど)

大豆とその種はトマトと同じ確率で、同じような場所に在ります。

## 必要な熟成期間

対象 | 熟成時間 | 備考
:----|---------:|:----
味噌 |      8日 |
醤油 |   70時間 | 要醗酵桶。季節長による補正あり。
納豆 |      1日 |


**2015-12-16 更新**

麹の追加により、味噌と醤油のレシピに麹を必要としました。米やら大豆やらと木灰を混ぜることで麹(培養中)ができます。
私は専門家ではないので麹の生産法については異論も在りましょうが平安時代にはこの方法でやっていたんだと思います。

対象 | 熟成時間 | 備考
:----|---------:|:----
麹   |      2日 |
味醂 |   70時間 | 要醗酵桶。季節長による補正あり。

## 必要な生育時間

植木鉢を使用することによって枝豆が収穫できます。

**植木鉢を使用した場合**

対象 | 生育時間
:----|--------:
枝豆 |      4日
大豆 |      9日

**土に直に植えた場合(大豆しか取れません)**

対象 | 生育時間
:----|--------:
大豆 |      9日


# 更新履歴

## [3.0.2](https://github.com/hirmiura/cdda-mod-Daizu/tree/3.0.2) (2017-08-03)
[Full Changelog](https://github.com/hirmiura/cdda-mod-Daizu/compare/3.0.1...3.0.2)

- 醤油が醗酵しないバグの修正
- 味噌周りをいろいろ修正

## [3.0.1](https://github.com/hirmiura/cdda-mod-Daizu/tree/3.0.1) (2017-08-01)
[Full Changelog](https://github.com/hirmiura/cdda-mod-Daizu/compare/3.0.0...3.0.1)

- 豆乳作成レシピに食用酢を追加

## [3.0.0](https://github.com/hirmiura/cdda-mod-Daizu/tree/3.0.0) (2017-07-22)

- フォーク後の初リリース
- modinfoの作者が表示されていなかったのを修正
- cdda#6603で確認

## 2.00 (2016-05-11)

- 大豆製品が食べられなくなっていたので、material.jsonの大豆を変更、野菜と同じ栄養価を設定。
- comestibles.jsonの納豆パン・豆乳シチュー・肉じゃが・豆腐ハンバーグパテ・納豆汁・味噌汁（全部密閉側）
- 納豆（未発酵）・麹（培養中）のtarget_chargesを削除。
- 納豆をうまく取り出せないので、containers.jsonに藁パックという収納物を追加。藁パックは納豆作りに再利用可能。
- 麹の分類を粉末から麹に変更、material.jsonに追加。レシピにビニール袋を追加。
- なお、修正者は作者様ではありません。

## 1.30 (2015-12-20)

- 植木鉢modのミスをこちらも修正。
- ついでに枝豆と大豆を製作の時点で分けるようにしました。

## 1.20 (2015-12-17)

- mod情報の基本的な変更。
- 幾つかのミスを修正。
- 幾つかの料理の追加と、豆乳チーズを全てのチーズ料理に使用可能に。

## 1.10 (2015-12-16)

- 幾つかのミスを修正。
- 枝豆、豆乳チーズ、麹、ずんだ、きな粉のレシピを追加。
- ついでに麹ができたので味醂と肉じゃがも追加。

## 1.00 (2015-12-15)
- 完成
