
# 正誤訂正


#### 第1版第1刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|---|---|---|---|---|
|1章|p.64|コード1-6-2 1行目<br>(誤)``ns1 = '文字列のサンプル'``<br>(正)``s1 = '文字列のサンプル'``|紙面のみ誤りでNotebook上は問題ありません|2023-01-12|
|1章|p.67|コード1-6-5 4行目<br>(誤)``# 文字列'pen'の場所をfindメソッドで探す``<br>(正)``# 文字列'apple'の場所をfindメソッドで探す``||2023-02-02|
|1章|p.67|コード1-6-5 8行目<br>(誤)``# 結果の10は先頭を0としたときの文字'p'の位置を示す``<br>(正)``# 結果の10は先頭を0としたときの文字'a'の位置を示す``||2023-02-02|
|1章|p.108|問題 2行目<br>(誤)関数div_chaperを定義して<br>(正)関数div_titleを定義して||2023-02-02|
|2章|p.144|コード2-2-14 1行目<br>(誤)0行目と2行目、すべての列<br>(正)0行目と1行目、すべての列||2023-02-25|
|2章|p.255|コード3-4-2 2行目<br>(誤) ``!head -5 bank.csv`` <br>(正) ``!head -5 bank-full.csv`` ||2023-02-25|
|2章|p.255|コード3-4-2 4-7行目<br>(誤)<br>30;"unemployed";"married";"primary";"no";1787;"no";"no";"cellular";19;"oct";79;1;-1;0;"unknown";"no<br>33;"services";"married";"secondary";"no";4789;"yes";"yes";"cellular";11;"may";220;1;339;4;"failure";"no<br>35;"management";"single";"tertiary";"no";1350;"yes";"no";"cellular";16;"apr";185;1;330;1;"failure";"no<br>30;"management";"married";"tertiary";"no";1476;"yes";"yes";"unknown";3;"jun";199;4;-1;0;"unknown";"no"<br>(正)<br>58;"management";"married";"tertiary";"no";2143;"yes";"no";"unknown";5;"may";261;1;-1;0;"unknown";"no<br>44;"technician";"single";"secondary";"no";29;"yes";"no";"unknown";5;"may";151;1;-1;0;"unknown";"no<br>33;"entrepreneur";"married";"secondary";"no";2;"yes";"yes";"unknown";5;"may";76;1;-1;0;"unknown";"no<br>47;"bluecollar";"married";"unknown";"no";1506;"yes";"no";"unknown";5;"may";92;1;-1;0;"unknown";"no"||2023-02-25|
|3章|p.267|コード3-4-14<br>(正) 一番下に次の行を追加 All, 0.1574, 0.5355, 0.3070 ||2023-02-25|
|3章|p.300|コード3-6-4 表中の項目「貸出日時」のデータ書式<br>(誤) .000<br>(正)  小数部分なし||2023-02-25|
|3章|p.301|コード3-6-5 表中の項目「貸出日時」のデータ書式<br>(誤) .000<br>(正)  小数部分なし||2023-02-25|
|3章 | p.304 |コード3-6-8 下から9行目と一番下の一番右のデータ形式<br>(誤) .000<br>(正) 小数部分なし||2023-02-25|
|3章 | p.305 |コード3-6-9 下から9行目の一番右のデータ形式<br>(誤) .000<br>(正) 小数部分なし||2023-02-25|
|3章|p.307|コード3-6-10 下から5行目-一番下の一番右の項目のデータ書式<br>(誤) .000<br>(正)  小数部分なし||2023-02-25|
|3章|p.315|コード3-6-15 表中の項目「貸出日時」のデータ書式<br>(誤) .000<br>(正)  小数部分なし||2023-02-25|
|3章|p.316|コード3-6-16 表中の項目「貸出日時」のデータ書式<br>(誤) .000<br>(正)  小数部分なし||2023-02-25|
|3章|p.324|コード3-7-1 2行目<br>(誤)``url1 = 'https://github.com/makaishi2/samples/raw/main/data/rental3-jp.csv'``<br>(正)``url1 = 'https://github.com/makaishi2/samples/raw/main/data/rental5-jp.csv'``|紙面のみ誤りでNotebook上は問題ありません|2023-02-02|
|3章|p.336|一番上の行<br>Notebook上にある「# 顧客情報」で始まるセルの実装を補ってください|紙面のみ誤りでNotebook上は問題ありません|2023-02-02|
|4章|p.353|コード4-10 一番下の行<br>(誤)``df.head(1)``<br>(正)``df.head(2)``||2023-02-25|
|4章|p.358|コード4-15 2行目<br>(出版時)<br>``df.groupby('客室クラス').mean()``<br>(現在)<br>``df.groupby('客室クラス').mean(numeric_only=True)``|pandasのバージョンアップに伴い修正が必要|2024-04-26|
|4章|p.364|コード4-21 5,6行目<br>(出版時)<br>``x='客室クラス', y='運賃', data=df,``<br>``palette=['blue', 'cyan', 'grey'])``<br>(現在)<br>``x='客室クラス', y='運賃', hue='客室クラス', data=df,``<br>``palette=['blue', 'cyan', 'grey'], legend=False)``|pandasのバージョンアップに伴い修正が必要|2024-04-26|
|4章|p.365|コード4-22 5,6行目<br>(出版時)<br>``x='客室クラス', y='運賃', data=df,``<br>``palette=['blue', 'cyan', 'grey'])``<br>(現在)<br>``x='客室クラス', y='運賃', hue='客室クラス', data=df,``<br>``palette=['blue', 'cyan', 'grey'], legend=False)``|pandasのバージョンアップに伴い修正が必要|2024-04-26|

<hr>

[メインページに戻る](../README.md)

