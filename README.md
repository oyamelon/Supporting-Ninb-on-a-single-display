NinjaBrain Botをシングルディスプレイでも使用しやすくするため、簡易画像をオーバーレイ表示させます。
![20220525032947](https://user-images.githubusercontent.com/97399080/170106879-c0c53895-fadf-4ce1-b43d-b7fd3c7e263b.png)
例：ディスプレイの左上に、座標の候補を2つまで表示。
# 設定
NinjaBrain Botの設定として、View typeをDetailed、Window sizeをSmall、Show direction to strongholdをオフにします。

次にAHKの設定を変更します。自身の環境に沿って変更してください。
NinbX = 表示させるX座標。
NinbY = 表示させるY座標。
ViewCoord = 表示させる座標の候補数（1～5）。
NinbPic = OBSオーバーレイ用の画像のパス。

表示させるキーと、非表示にさせるキーは、58行目と59行目で変更できます。
# 使い方
F3+Cで通常通りNinjaBrain Botを使用し、候補が表示されたらJキー（デフォルト）で簡易画像を表示及び更新。
Uキー（デフォルト）で表示させた簡易画像を非表示。

非表示のキーは、NinjaBrain BotのResetキーにするのがオススメです。
