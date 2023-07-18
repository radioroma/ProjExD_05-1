# ゲーム のタイトル
へボリス
（おそらくへぼいテトリスのようなゲームが出来上がるから）
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
形の違うカラフルなブロックが落下し、横一列に揃えると消えるパズルゲーム
テトリスのようなもの

## ゲームの実装
###共通基本機能
* ランダムで4つのつながったブロックが枠内で落下し、積みあがる機能
### 担当追加機能
* 経過時間（経過した時間を表示する機能）
* 回転（キーを押すと、落ちてきたブロックが落下しながら時計回りや反時計回りに回転する機能）
* 高速落下(下キーを押すと落下中のブロックの落下速度が速くなる機能)
* 列消去, スコア（横一列にブロックが隙間なく並んだ場合、その列が消えて上に積まれているブロックが消えた列分下に落下する機能, 消すことのできたブロックの数や、積み上げたブロックの数などの点数を表示する機能）
* ゲームオーバー（積みあがったブロックが画面外に出た時に、ゲームが強制終了される機能）
### ToDo
- 経過時間(担当：須長)
- 回転(担当：小玉)
- 高速落下(担当：石田)
- 列消去, スコア(担当：佐々木)
- ゲームオーバー(担当：川西)
### メモ
経過時間について
recは時間を測る変数
121行目で計算


