# loto7loto6Generator
ロト7、ロト6、ミニロトの番号予想をするパッチです。

基本的に年末ジャンボも買わないですし、呑む打つ買うは呑む以外はやらない僕の数少ない趣味の一つに「計算でロト6やロト7を当てたい」というのがあります(苦笑)。いままでの戦歴ではまぁ年に１度とかたまーーーに900円あたった(笑)事があります。殆どあたりません。でロトの抽選の機械の画像を見たところ(ググると出てきます)「これはいままでのやり方ではだめだ!!」となり、共通の趣味を持つ人の力を借りてトライしたい、と思いまして秘伝のタレを公開します(酷いなーこれ・笑)。

## パッチについて
起動時に[loadbang]をつかってUnix timeを生成したあとに、それをRandamに突っ込んでそこから出た数字(桁すうが多い)で、その数字をつかって[Uzi]でbangを出力しそれぞれの種別事に乱数を回してますので、起動するとレインボーカーソルになります(笑)。大丈夫、暫くまっていれば出力されます。UnixtimeをMaxで取る方法が意外と見付からなくてJSで取ってます。探した中ではこれが一番楽なのかなと。

ここについてFacebookで「cpuclockが使えるのでは?」という指摘をいただきましたが、cpuclockはあくまでMaxが起動してからの経過時間をUnix timeの形式で出力してるだけなので、先に書いた「ロトの抽選の機械」の自然現象をつかった抽選、には凡そ力及ばないだろう、という認識の元、Unix timeという1970年1月1日午前0時0分0秒から現在までの悠久の時の流れ(笑)、をrandamにブチこんでいる、というわけです。

## スクショ(パッチが重くて開きずらいので)
<img width="1561" alt="Screen Shot 2019-05-29 at 9 55 57" src="https://user-images.githubusercontent.com/265457/58521720-605b9d00-81f8-11e9-8235-94ff764f23f4.png">

## ライセンスについて
MITライセンスですが、もしこれでロトが当ったらクリエーターに向けてなにか貢献する事業でも始めてください(笑・エンジェル投資家になるとか、シェアスペース作るとか、なんか夢のあることをやってくれる人が出たらいいなぁ)。もちろん自分のお金ですから自分の為に半分くらいは使ってしまっていいですよ、いやそもそもダメとか始めから言えないんだけど。でもまぁこいういうのはノリが重要なので、当った誰かがそんな夢のあることをやってくれるといいなぁ、しかもMaxのコミュニティの中で。痛快じゃないですか? そんなことが起こったら??? もちろん僕が当ったときは必ずなにかやります!!

というわけで皆で夢をみましょう(笑)。
