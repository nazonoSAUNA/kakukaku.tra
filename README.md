# カクカク移動.trascript
コマ落ち的な移動をするAviUtlトラックバー変化スクリプト

# 導入方法
Source Code.zipなどからダウンロードします。
カクカク移動.traをscriptフォルダあたりにいれます（他のトラックバー変化スクリプト.traと同じように導入します）

# パラメータに関して
トラックバー設定値（移動フレーム間隔）にマイクロ秒で更新間隔を指定します（初期値:133333）


コマ落ち計算例
- 30fpsで1コマ落ち→2/30秒に1回描画する→1000000×2/30≒66667
- 60fpsで5コマ落ち→6/60秒に1回描画する→1000000×6/60＝100000
