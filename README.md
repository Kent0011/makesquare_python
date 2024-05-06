# 画像正方形化ツール

画像を正方形にリサイズするツールです。

## 使用方法
1. このプログラムと同じディレクトリに'input'および'output'という名称のディレクトリを作成
2. 'input'に正方形化したい画像を入れる
3. 実行 : $ python makesquare.py      
4. 'output'ディレクトリに正方形化された画像ファイルが出力されます

## 出力
入力画像のうち長い辺を基準とし余白が追加されます。


## 使用ライブラリ
`cv2`を用いて画像の読み書き、`numpy`を用いて読み込んだ画像の処理をします。
