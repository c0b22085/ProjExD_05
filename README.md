# ゲーム のタイトル
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
ぱっちぃを倒す

## ゲームの実装
###共通基本機能
敵を倒し
スコアが追加される

### 担当追加機能
* 画像差し替え
* 敵パワーアップ
* 敵追加 c0a22159 諫山隼汰
* 味方パワーアップ c0a22123 廣田俊介
* アイテム実装
### ToDo
- [ ] ほげほげ機能
- [ ] ふがふが関数内の変数名の統一
### メモ
* Escapeボタンを押すとゲーム終了
* ←→　ボタンで移動
* Spease ボタンでビーム発射
* 敵に当たるか爆弾にあたるとゲームオーバ
* 敵にビームが当たるとScore１UP

**追加機能　敵追加**
* SCOREが20の倍数になると敵を1体追加する
* 出現する敵は通常の敵よりも小さく、速く、得点が高い(10点)

* 追加機能　味方パワーアップ
* TABボタンでSUPERMODEに変更
* SUPERMODE中は敵にビームをあてると自分からビームを打つ


