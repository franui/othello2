# 説明
2015年の4月頃にプログラミングの練習を目的として作った、GUIのオセロのブラウザゲームです。  
主にJavaScriptで書かれています。

# インストール
リポジトリごとダウンロードして適当な場所で解凍して頂き、  
直下のselectmenu.htmlをダブルクリックすると始まります。

# 遊び方
一人で遊ぶ（コンピュータと対戦する）か二人で遊ぶかを選ぶことができ、  
一人で遊ぶを選んだ場合は白と黒のどちらを使うか、二人で遊ぶを選んだ場合は白と黒のどちらが先行かを選びます。    

二人で遊ぶを選んだ場合はそのままGame Startを押せばゲームが始まります。  
一人で遊ぶを選んだ場合は先行か後攻かランダムで決まり、Game Startを押せばゲームが始まります。

# 仕様など
ターンプレイヤーは「待った」をすることや、ゲームを初めからやり直すことができます。  
現在の互いの駒の数と、ターンプレイヤーが置くことができる場所が表示されます。    

また、コンピュータと対戦する場合は、参考として評価関数による評価値のリストを表示しています。  
これは3手先までの全ての可能な盤面の推移を計算し、それぞれの場合について評価関数による盤面の評価値を与えており  
点数が高いほどその盤面は自分にとって有利ということになります。  
コンピュータも毎回同様の計算を行い、3手先の点数が最大になるような手を打ちます。
