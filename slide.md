---
transition: "slide"
title: "20220318チューター会"
---

20220318 チューター会

<div style="display:flex;justify-content:space-evenly;background:lightgray;">
<img src="https://duplicate1984.github.io/Portfolio/img/works/iconfinder_AWS_4923041.png" alt="" style="height:150px;">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/985px-Laravel.svg.png" alt="" style="height:150px;">
<img src="https://is4-ssl.mzstatic.com/image/thumb/Purple126/v4/20/91/76/2091769d-32c3-c277-a44c-3a848e1bec0c/electron.png/1200x630bb.png" alt="" style="height:150px;">
</div>

---

もくじ

- AWS の話
- Laravel の話
- Slack bot 開発の話

---

AWS の話

--

Laravel は AWS Cloud9 でやります！

--

講義内容は特に変更なし．

（SNS アプリケーションの実装）

--

実装したプロダクトを GitHub に push

--

デプロイは

- LAB クラスは実施

- DEV クラスは資料で展開

--

AWS アカウントはチューター入る人は発行！

---

Laravel の話

--

Laravel 9 ！！！

--

講義では 9 でいきます！

--

実装は 8 時代と変わりません！

（コマンドの挙動など多少の差あり）

--

！！！注意点！！！

--

マネクラが PHP7.4

（Laravel9 は PHP 8 ↑）

---

Slack bot 開発の話

--

```
＿人人人人人人人人人人人人人人人＿
＞　定型的な投稿がめんどくさい　＜
￣Y^Y^Y^Y^Y^Y^Y^Y^Y^Y^Y^Y^Y￣
```

--

```
＿人人人人人人人人人人人人人人人＿
＞　そうだ，botにやってもらおう　＜
￣Y^Y^Y^Y^Y^Y^Y^Y^Y^Y^Y^Y^Y￣
```

--

講義の案内などは全部 bot にします！

--

1. スプレッドシートに投稿する内容と日時を書いておく．

2. 毎日 node.js でデータ取得して，日時が当日のものを Slack に予約投稿する．

--

![bot図](./img/slack-automator.svg)

---

以上だ( `･ω･)b
