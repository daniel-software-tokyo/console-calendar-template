# 課題6:今までの機能をコマンドで選択できるようにしてほしい

イメージ: 
`実行可能なコマンド`
`1: 現在日時の表示`
`2: 月ごとの日数表示`
`3: カレンダー表示(1月分)`
`4: カレンダー表示(期間)`
`コマンドを入力してください: `

で、`1`が入力されたら現在日時を表示して、待機して処理を終わらせる。

(動作イメージ)
カーソルの待機場所は、`コマンドを入力してください: `

`4: カレンダー表示(期間)`
`コマンドを入力してください: `　ここでカーソルが点滅
ここの次の行から結果表示(見やすいようにちゃんと１行空ける事)

また、コマンドにない入力がされたら`対応するコマンドがありませんでした`でまた再表示させる。
当然、コマンド入力を求める行と一覧両方。