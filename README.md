# CSVヒートマップ
緯度経度データ(CSV形式)をGoogleマップ上にヒートマップ表示するツールです

![キャプチャー](https://raw.githubusercontent.com/wiki/qaz-s/google-csv-heatmap/Heatmap.png)

## 使用方法
1. http://qaz-s.github.io/heatmap/ にアクセス
2. 右下の+ボタンを選択し、CSVファイルをドラッグアンドドロップ
3. CSVファイル読み込み後、IMPORTボタンを選択すればOK

## CSVのフォーマットについて

CSVは下記の形式で用意してください。

    lat,lng
    37.09636,139.81002
    37.08346,139.82983
    37.14576,136.23256
    ...

緯度経度は、度数形式とミリ秒形式に対応しています。

## 参考
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/)
- [Material Design Lite](http://www.getmdl.io/)
- [HTML5 File API](http://www.w3.org/TR/file-upload/)
