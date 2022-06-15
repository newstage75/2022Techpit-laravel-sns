## 本プロジェクトの意味


**2022/06/14 再勉強が始まる！**

[Laravel(+Vue.js)でSNS風Webサービスを作ろう！](https://www.techpit.jp/courses/11)

Laravelを用いて、一通りプロジェクトを作成するに至った[参考URL](https://tugi-ichi.com)自分ではあるが、
再度この教材を学習することにより、Laravelに対する理解をより深める狙い

前回は飛ばし飛ばし＆コピペが多かったが、丁寧に進めて行きたい。

さらに、この教材は最終的に「Heroku」へのデプロイがある。

自身のサイトをHerokuに移せないか？と考えていた矢先のため、その辺りも含めて確認できたらと思う。


### 自分用メモ〜プロジェクトの立ち上げ方〜

[こちらを参照](https://www.techpit.jp/courses/11/curriculums/12/sections/103/parts/356)

laradockディレクトリ（編集しているlaravelフォルダと同階層に存在）にて
```
docker-compose up -d workspace php-fpm nginx postgres
```
```
#終了
docker-compose stop
```


### GitHubの活用指針

[こちらを参照](https://qiita.com/tkmd35/items/9612c03dc60b1c516969)