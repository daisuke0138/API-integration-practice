# API-integration-practice
# ①課題番号-プロダクト名

福岡県企業の取得特許の表示と
カテゴリ別のニュースを表示
表示情報について
Chatgptのテキスト検索が可能

## ②課題内容（どんな作品か）
特許やニュースを表示させるアプリを作成しています。

①福岡県企業の取得特許の表示は
resas-apiから、福岡県企業の特許のみを表示させる。
9つの技術分野別の特許を見ることができます。

②カテゴリ別のニュースは、
news-apiから世界中のネットニュースを
4つのカテゴリから５件ずつ表示させます。

↓6/15AM追加↓
①、②で得た情報から、気になる点を
生成AIchat-gpt3.5で検索ができます。

## ③DEMO

## ④作ったアプリケーション用のIDまたはPasswordがある場合
なし
## ⑤工夫した点・こだわった点
データを取得するだけで精一杯でした。


## ⑥難しかった点・次回トライしたいこと(又は機能)
resas-apiからデータ取得するパラメータとして
技術分野のカテゴリーを選択できるはずだが、
公式ドキュメントでは理解不能で時間を使い過ぎました。

次回トライしたいこととして
データ表示だけでなく、疑問点を生成aiやネットでの検索、
応答をさせたい。
→ai検索は6/15追加済

また検索した内容をメモ(txt,pdf,pptxなど)を作成し
fire base storage等のデータベースに保存できるものを作りたい。

## ⑦質問・疑問・感想、シェアしたいこと等なんでも
公式ドキュメントが理解不能だったので
力技で進めるアドバイスをいただきました。
その判断や力技の手法を考えるのも大事なのかなと思いました。

resas公式ドキュメントの
https://opendata.resas-portal.go.jp/docs/api/v1/industry/patent/list.html

このaddTecが理解不能。sanmple通りにするとエラーになる。
parameters：addTec