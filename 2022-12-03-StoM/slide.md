---

theme: "white"
transition: "Slide"
title: "2022-12-03"

---

# Using OSM on Web application first step.

---

## アジェンダ

- 自己紹介
- 各種ライブラリの紹介
- 福岡トピックス
- おまけ

---

![image](https://event.ospn.jp/event_images/sessions/efc_%E7%94%B0%E4%B8%AD.png)

---

福岡市エンジニアカフェから来ました。

---

<iframe src="https://duckduckgo.com/?q=%E8%B5%A4%E7%85%89%E7%93%A6%E6%96%87%E5%8C%96%E9%A4%A8&atb=v315-1&iax=images&ia=images"></iframe>

---

## 赤煉瓦文化館(重要指定文化財)

![image](https://bunkazai.city.fukuoka.lg.jp/getImage.php?src=files/CulturalPropertyImage110imageja.jpg&width=340)


---

![image](https://engineercafe.jp/assets/img/img-main_pc.4802559a.jpg)

---

コミュニティ活動の拠点、ものづくり、ハッカスペースとして活用されている。

---

大学院で地図を使った手法開発などしていた。
(地理空間分析)

↓

福岡市エンジニアカフェでものづくり全般に従事

↓

Web系に寄り道

---


OSMどうやって活用している？

---


近年はwebでの地図表現が多く見られるようになってきている

---

こんなときどうする？

---

「OpenStreetMapをWebページに載せたい」


---

## Leaflet


---

### 単に表示してみる

https://alt9800.github.io/sample-maps/simple/

---

### geojsonを重ねてみる

https://alt9800.github.io/sample-maps/import-json/

---

### DeckGLを使ってみる

https://alt9800.github.io/sample-maps/deck-sample


(補足 : MapLibre GL JSなどの方が厳密にはOSMを使っている！という感じがする)

---

Leafletを使っているときの困りごとをいくつか解決してくれる。



---


- データの読み込み周りが冗長になりやすい(shpとかjsonなどを適宜読みたかったり、データベースを活用したい)

- 宣言的UIとして利用したい(データと描画の分割をしたい)

---

## 福岡市での地図の盛り上がり

---

### その1 : 

「天神ビッグバン」(大規模再開発)のために急いだ更新が必要→町中でマッピングし放題

<iframe width="425" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.openstreetmap.org/export/embed.html?bbox=130.3735971450806%2C33.580946541729524%2C130.42466640472415%2C33.60261013809972&amp;layer=mapnik" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/#map=15/33.5918/130.3991">大きな地図を表示</a></small>

---

<iframe src="https://tenjinbc.jp/"></iframe>

https://wiki.openstreetmap.org/wiki/Indoor_Mapping

---

Code for FukuokaやUrbanDataChallengeの福岡拠点と連携してマッピング

---

### その2 : 

Project Plataeuがそろそろ来るぞ！！


---

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">国土交通省の三次元都市モデル Project <a href="https://twitter.com/hashtag/PLATEAU?src=hash&amp;ref_src=twsrc%5Etfw">#PLATEAU</a> データを <a href="https://twitter.com/hashtag/OpenStreetMap?src=hash&amp;ref_src=twsrc%5Etfw">#OpenStreetMap</a> にインポートする手順書改良作業を学生と行いつつ、東京都 <a href="https://twitter.com/hashtag/%E6%9D%B1%E6%9D%91%E5%B1%B1%E5%B8%82?src=hash&amp;ref_src=twsrc%5Etfw">#東村山市</a> の建物LOD1データをインポート実施いたしました。各プラットフォームに PLATEAU データが展開進んでいます。 <a href="https://t.co/Kq9ODS2rp6">https://t.co/Kq9ODS2rp6</a><a href="https://twitter.com/hashtag/%E5%8F%A4%E6%A9%8B%E7%A0%94%E7%A9%B6%E5%AE%A4?src=hash&amp;ref_src=twsrc%5Etfw">#古橋研究室</a> <a href="https://twitter.com/hashtag/OSMjp?src=hash&amp;ref_src=twsrc%5Etfw">#OSMjp</a> <a href="https://t.co/zKMHIEgtXY">pic.twitter.com/zKMHIEgtXY</a></p>&mdash; Taichi Furuhashi 🇺🇦 (@mapconcierge) <a href="https://twitter.com/mapconcierge/status/1587571275953627137?ref_src=twsrc%5Etfw">November 1, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

---

都市にらくがきできるアプリ・ゾンビから逃げる防災ゲームが入賞。福岡開催PLATEAUハッカソン (1/3) : - ASCII STARTUP
https://ascii.jp/elem/000/004/110/4110382/

---

Coming soon...

---

最後に最近リリースされたOSMを用いたおすすめアプリのご紹介。

---



誰でも撮影地Map
https://railbus.fan/

MySQL8.0以降の機能を利用しつつ、OSM上に撮影Mapをだれでも追加できるすばらしきコンテンツ

---

地図って楽しいね。


---