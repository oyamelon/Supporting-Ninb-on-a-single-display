NinjaBrain Botをシングルディスプレイでも使用しやすくするため、簡易画像をオーバーレイ表示させます。
![20220525083101](https://user-images.githubusercontent.com/97399080/170148332-415374b4-9593-4292-a98e-6bac4101e87b.png)
例：ディスプレイの左上に、座標の候補を2つまで表示。
# 設定
NinjaBrain Botの設定として、View typeをDetailed、Window sizeをSmall、Show direction to strongholdをオフにします。

次にAHKの設定を変更します。自身の環境に沿って変更してください。
NinbX = 表示させるX座標。
NinbY = 表示させるY座標。
ViewCoord = 表示させる座標の候補数（1～5）。
NinbPic = OBSオーバーレイ用の画像のパス。

表示させるキーと、非表示にさせるキーは、65行目と66行目で変更できます。
# 使い方
F3+Cで通常通りNinjaBrain Botを使用し、座標の候補が表示されたらAHK側も簡易画像を表示させます。
NinjaBrain Botをリセットすると、自動的にAHK側も簡易画像が消されます。
また、NinjaBrain Botに座標の候補が表示されている間は、JキーとKキー（デフォルト）で、AHK側の表示/非表示ができます。
