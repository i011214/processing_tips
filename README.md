# processing_tips

# 目次
* [概要](#anchor1)
* [PC操作のTips](#anchor2)
* [Processing操作のTips](#anchor3)
* [VSCode操作のTips](#anchor4)
* [Chrome操作のTips](#anchor5)
* [おわりに](#anchor6)

<a id="anchor1"></a>

* **概要**

    コーディングという慣れない作業をすると、ひっかかる事がいくつかあると思います。<br>
    キーボードとマウスを持ち替えている間に、やるべきことを忘れてしまったり<br>
    メニュー内のボタンを探している間に、どこを読んでいたのか分からなくなったり…<br>
    プログラミングのことに集中したいのに、PCやソフトの操作で手間取ってしまい、<br>
    学習効率が上がらないなという経験はありませんでしょうか。<br>
    ここではちょっとした工夫で、コーディングの効率を上げ、プログラミングに集中するための<br>
    コツを紹介していきたいと思います。
<br>
<br>
<a id="anchor2"></a>

* **PC操作のTips**
    - 画面切り替え　:　**Alt+Tab**<br>
    コーディング作業中、画面を切り替えたいシチュエーションは多いと思います。
    例えば、テキストエディタと参考書のpdfや、Webブラウザなどです。
    逆方向に切り替えたい場合には、Alt+Shift+Tabとします。
    
    - 保存　:　**ctrl+s**<br>
    ソースコードや、テキストエディタで編集を行う際には、こまめに保存する習慣をつけましょう。
    
    - コピー　:　**ctrl+c**<br>
    コピーしたい部分を選択してからctrl+cで選択された内容がクリップボードにコピーされます。
    
    - ペースト　:　**ctrl+v**<br>
    クリップボードにコピーされた内容を貼り付けます。
    
    - 切り取り　:　**ctrl+x**<br>
    切り取りたい部分を選択してからctrl+xで選択範囲が切り取られクリップボードにコピーされます。
    
    - 元に戻す　:　**ctrl+z**<br>
    加えた変更を元に戻すことができます。何度も押すとさらに戻すことができます。
    
    - やり直す　:　**ctrl+y**<br>
    元に戻した処理をやり直すことができます。何度も押すとさらにやり直すことができます。
    
    - 半角英数字に変換する　:　**F10**<br>
    かな入力時に一部分だけ半角英数字に変換することができます。
    コメントを記述している時などに役に立ちます。
    
    - 検索　:　**ctrl+f**<br>
    現在開いているウィンドウ内で、テキストを検索することができます。
    
    - すべて選択　:　**ctrl+a**<br>
    現在開いているウィンドウ内の全てのテキストを選択します。
    
    - カーソルでの文字選択　:　**shift+←/→**<br>
    現在のカーソル位置から←/→キーで移動した範囲を選択します。

    - 単語単位でのカーソル移動　:　**ctrl+←/→**<br>
    現在のカーソル位置から←/→キー押下により、単語単位で移動します。
    どの部分を単語とみなされるかは、アプリケーションに依存します。
    
    - 単語単位の選択　:　**ctrl+shift+←/→**<br>
    先述のカーソルの選択と、単語単位での移動の組み合わせです。
    現在のカーソル位置から←/→キー押下により、単語単位で移動し、その範囲を選択します。
    
    - 単語単位の選択(マウス)　:　**ダブルクリック**<br>
    ダブルクリックした単語を選択します。
    どの部分を単語とみなされるかは、アプリケーションに依存します。
    
    - ボタンの移動　:　**Tab**<br>
    ポップアップ内の"OK"、"CANCEL"など、フォーカスしているオブジェクト(ボタンやリンクなど)を
    切り替えることができます。
    "shift+tab"で後ろ方向に移動もできます。
    
<br>
<br>
<a id="anchor3"></a>

* **Processing操作のTips**
    - インデントを増やす　:　**ctrl+]** もしくは 行の先頭で**Tab**<br>
    カーソルのある行のインデントを増やします。

    - インデントを減らす　:　**ctrl+[** もしくは 行の先頭で**Shift+Tab**<br>
    カーソルのある行のインデントを減らします。
    
    - コメントアウトする　:　**ctrl+/**<br>
    カーソルのある行をコメントアウトします。
    コメントアウトされている行で行うと、コメントアウトを解除します。
    
    - 単語を補完する　:　**ctrl+space**<br>
    単語を途中まで入力した状態で"ctrl+space"を押下すると、単語を補完もしくは補完候補を表示します。
    初期設定では機能オフになっているので、
    「ファイル」メニューから、「設定」の"コード補完"にチェックを入れてください。
    ※残念ながら、pythonモードでは正しく動作しません
    
    - 整形する　:　**ctrl+t**<br>
    インデントなど、ソースコードをきれいに整えてくれます。
    ※残念ながら、pythonモードでは正しく動作しません
    
    - 実行する　:　**ctrl+r**<br>
    プログラムを実行します。
    画面左上の再生ボタンと同様の動作をします。
    
    - メニューを開く　:　**Alt**<br>
    画面上方のメニューにフォーカスします。
    上下左右キー、Enterキーでメニューを実行できます。

<br>
<br>
<a id="anchor4"></a>

* **VSCode操作のTips**
    - テキストエディタを分割する　:　**ctrl+￥** もしくは **ctrl+k,ctrl+￥**<br>
    テキストエディタを分割し、複数のファイルを同時に表示することができます。
    他のソースコードを参照しながらコーディングする際に役立ちます。
    初期設定では"ctrl+￥"で左右に分割、"ctrl+k"を押してから"ctrl+￥"を押すと上下に分割します。
    メニューの「表示」-「エディターレイアウト」からも同様に分割することができます。
    
    - テキストエディタを移動する　:　**ctrl+PageUp** もしくは **ctrl+PageDown**<br>
    分割したテキストエディタを移動します。
    
    

<br>
<br>
<a id="anchor5"></a>

* **Chrome操作のTips**
    - 新しいタブを開く　:　**ctrl+t**<br>

    - ページを更新する　:　**ctrl+r** もしくは **f5**<br>
    
    - 開発者ツールを開く　:　**ctrl+shift+i** もしくは **f12**<br>
    
    - 次のタブに切り替える　:　**ctrl+Tab**<br>
    
    - 前のタブに切り替える　:　**ctrl+shift+Tab**<br>
    
    - タブを閉じる　:　**ctrl+w**<br>
    
    - URL入力窓にフォーカスする　:　**ctrl+l** もしくは **f6**<br>
    
<br>
<br>
<a id="anchor6"></a>

* **おわりに**

    VSCode、eclipse、XcodeなどのIDE(統合開発環境)では、ショートカットを編集することができます。<br>
    残念ながらProcessingではショートカットの編集は出来ないようです。<br>
    マウスとキーボードを持ち替えることなくコーディングしていると、凄腕プログラマーになった気分になれます笑<br>
