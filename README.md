# ROHAN4600：大規模日本語テキストコーパス（仮）です．

## ROHAN4600とは
コーパス文の課題生成システムが提示した条件を満たす文章を人間が作ることで，ある程度クオリティが統一した文章を作ろうという試みです．システムは常用漢字と読みを全て含み，出現頻度の低いモーラもカバーするように各文章の条件を設定します．その条件を満足するように作文を続けていけば，いずれ良いコーパスが出来上がるはずです．

## 文章のフォーマット
- 漢字は半角括弧で読みを入れること（例えば「勝(か)つ」）
- 作成した文章後，半角「,」を入れて全角カタカナで文章を入れてください．
- カタカナ部分は「を」は「お」とし，「〇〇へ」は「〇〇え」と読みに忠実に入力してください．
- 文章は一度朗読し，読みやすいかを評価してから確定しましょう．
- 同じ名詞を多用するのは控えましょう．
- ポリコレには配慮し炎上を避ける文章にしよう．

## 200文章毎のコンセプト（似たような文章とならないようにする工夫）
- 0001～0200: 作業に慣れるため読みやすさ重視で条件無し
- 0201～0400: 四字熟語を入れる努力
- 0401～0600: 日本のメジャーな苗字
- 0601～0800: 外来語由来の動詞・名詞
- 0801～1000: 山手線の駅名
- 1001～1200: 世界の国名をカタカナ名で
- 1201～1400: 47都道府県
- 1401～1600: 数詞１（〇時間，〇個，〇枚，〇本，〇冊を一～十まで＋何△（例えば「何時間」））
- 1601～1800: 数詞２（〇台，〇杯，〇人，〇匹，〇階を一～十まで＋何△）
- 1801～2000: 数詞３（〇回，〇円，〇歳，〇番，〇拍を一～十まで＋何△）
- 2001～2200: 数詞４（〇票，〇発，〇品，〇粒，〇句を一～十まで＋何△）
- 2201～2400: 数詞５（〇位，〇席，〇秒，〇分，〇時を一～十まで＋何△）
- 2401～2600: 数詞６（〇つを一～九まで＋「とお」と「いくつ」）
- 2601～2800: 古風な単語・表現
- 2801～3000: 動物等の名前（カタカナをたくさん使う）
- 3001～3200: 常用以外の漢字と読みを中心に

## 作文の妥協
出現頻度の低いモーラを入れることは後半キツイと思います．「くぅ」「ぐぅ」「でぇ」は特に難しいと思うので，最悪妥協しても構いません．

## 文章リストの評価
これまで作った文章リストから，エントロピーと平均モーラで評価できます．100文章単位で評価し，一定の水準に達していなければ作り直しましょう．

## 質の高いコーパスにするために
- 常用漢字はシステムがカバーしているので，常用漢字以外も積極的に入れる
- 日本語以外のカタカナ名称を入れると，エントロピー的に有利になる

## ライセンス
パブリックドメインです．

## 協力者
クレジットさせて頂くので，パブリックドメインという条件で良ければ名乗り出て頂けたら嬉しいなぁ（希望的観測）．200文章（「です・ます」100文と「だ・である」100文のセット）作って頂いたら，平均モーラとエントロピーを評価してランキングを作ろうと思っています．
