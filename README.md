# カクカク移動.trascript
コマ落ち的な移動をするAviUtlトラックバー変化スクリプト

![image](https://user-images.githubusercontent.com/99536641/232079080-6433f898-9e39-42bc-bfea-b7a4fe4a9044.png)


# 導入方法
[Release](../../releases/) などの Source code (zip) などからダウンロードします。
カクカク移動.traをscriptフォルダあたりにいれます（他のトラックバー変化スクリプト.traと同じように導入します）

# パラメータに関して
トラックバー設定値（移動フレーム間隔）にマイクロ秒で更新間隔を指定します（初期値:133333）

![image](https://user-images.githubusercontent.com/99536641/232074387-37ebf849-0db1-4f74-bc6b-381dbd1b67d6.png)

コマ落ち計算例
- 30fpsで1コマ落ち→2/30秒に1回描画する→1000000×2/30≒66667
- 60fpsで5コマ落ち→6/60秒に1回描画する→1000000×6/60＝100000
