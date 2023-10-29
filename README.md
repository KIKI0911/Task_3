# URL(Uniform Resource Locator)とは
ホームページの**住所の情報**であり、ホームページの置いてる**場所**や**ファイル名**をなどを表す情報。
# クエリ文字列とは
サーバーへ送りたいデータを指定し、そのデータを送るためにURLの末尾に付け足す文字列のこと。
クエリ文字列には２種類あり、『パッシブパラメータ』と『アクティブパラメータ』がある。
1. パッシブパラメータ
> Webサイトのアクセス分析をするために、固有のパラメータをつけてユーザがどこから自分の
> Webサイトへ辿り着いたかを知るためのもの。
> また、パッシブパラメータは表示されるコンテンツには影響はない。
2. アクティブパラメータ
> パッシブパラメータと異なり、パラメータを付け加えることで、Webサイトの表示内容を変更することができる。
# パス変数(パスパラメーター)とは
ファイル・システム上のロケーションを指定するもの。
# クエリ文字列とパス変数の違いとは
**クエリ文字列**は、URLの末尾に追加され、追加の情報、プログラムや関数に渡される値、または情報を含むことができます。それに対して**パス変数**はURL先のウェブサイト内でのリソースの場所を指定します。
例えば、
`URL:https://instance.com/list?userId=monkey`
   この場合、?の後ろにある"userId=monkey"がクエリ文字列になります。
また、パス変数は上記のURLでは"list"になります。
# HTTPメソッドとは何か
