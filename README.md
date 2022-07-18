# plot-time-series

csv形式の時系列データを簡易にグラフ化して確認するツール

## 使い方

1. plot_time_series.htmlをブラウザで開きます。
2. csv形式の時系列データを
<img src="imgs\ドラッグアンドドロップの枠.png" alt="ドラッグアンドドロップの枠">
へドラッグアンドドロップします。

3. Plotlyでグラフが描画されます。
   1. CDNでPlotlyを利用するため、インターネットに接続できる環境で使用してください。
   2. 列見出しの行や列見出しそのもの、グラフ化するデータを選択したい場合はplot_time_series.html内のjavascriptをテキストエディタで直接編集してください。

## サンプルデータ

sample.csv
(Shift JIS,CRLF 形式)

<img src="imgs\サンプルのcsvデータの内容.png" alt="サンプルcsvデータ">

を枠内へドラッグアンドドロップすると以下のようなグラフが表示されます。

<img src="imgs\サンプルのグラフ.png" alt="サンプルのグラフ">

## 動作確認

以下の環境で動作確認しています。

* Microsoft Edge
バージョン 103.0.1264.62 (公式ビルド) (64 ビット)
