# JavaScript-100nocks （随時更新）
- MakeIT 研修用プログラム

## - 目標
HTML、CSS、JavaScriptの基礎が理解でき、扱えること

一例としての回答を[answer](./answer/example)に設置します。自分と相談してから確認して下さい。

[※回答方法は解答手順](./answer/example/回答手順.md)  
[※source treeを使った解答手順](https://qiita.com/ymzk-jp/private/50a912f8d15c5d380ddb)  


---


<details>
<summary>

# `n.1~n.49`

</summary>


1. ## saisyo

    HTMLファイルを作成し、MakeITと表示してください。文字はCSSを使って色を#20D0F0にしてください


    ![saisyo](./img/saisyo.png)




1. ## centerDiv
    300px四方のdivを画面の上部中央に表示してください。色は赤、画面幅が変わっても中心に移動するようにして下さい


    ![centerDiv](./img/centerDiv.gif)


1. ## helloTable 
    3x3の表を画面に表示して下さい。コンテンツはすべて「こんにちは」。一番左の列は縦に３つ結合してください


    ![helloTable](./img/helloTable.png)



1. ## console
    console.logを使ってコンソールに「Hello JavaScript」と出力して下さい


    ![console](./img/console.png)


1. ## bored
    画面中央に表示された「I'm so bored」の文字をクリックすると「AWESOME!」に書き換わるプログラムを作成してください。「AWESOME」は大きさ128px、色黒以外

    ![bored](./img/bored.gif)

1. ## isSame
    ボタンを押すと2つのテキストフォームに入力された文字列を比較し、同一文字列であれば「True」、それ以外であれば「False」とアラート出力するプログラムを作成してください



1. ## sumSequence
    1からnまでの和をコンソール出力するプログラムを作成してください。nはフォームに入力された値である。for文を使用すること




1. ## anchor
    [Yahoo Japan](https://www.yahoo.co.jp/)に遷移するリンクを3つ表示してください  
    1つは同一のタブ上で開くように  
    1つは新しいタブで開くように  
    1つはjavascriptのwindow.open()を使用して開くように




1. ## countUp
    ボタンを押すと画面に表示された数字が1つずつカウントアップされるプログラムを作成してください。カウントが3の倍数の時に表示が変わるようにしてください



1. ## array1
    配列内を順にコンソール出力してください  
    入力:  `const ary = ['a','b','c','d','e','f','g'];`  
    出力: 
    ```js
    a
    b
    c
    d
    e
    f
    g
    ```




1. ## array2
    配列内を順にコンソール出力してください。出力の際に各要素のindex値を足して下さい  
    入力:  `const ary = ['a','b','c','d','e','f','g'];`  
    出力: 
    ```
    a0
    b1
    c2
    d3
    e4
    f5
    g6
    ```


1. ## array3
    宣言された変数が配列かどうか評価してください
    入力
    ```js
    var ary=[]
    var num=1
    var obj={}
    ```
    出力
    ```js
    true
    false
    false
    ```



1. ## typeof
    以下の様に宣言された変数の型を評価して出力してください。  
    入力: 
    ```js
    var num=1; 
    var zero=0;
    var str='1';
    var zs='0';
    ```
    出力
    ```js
    number
    number
    string
    string
    ```




1. ## concat
    2つの配列を結合して出力してください  
    配列1 `ary1=['a','b']`  
    配列2 `ary2=['c','d']`  
    出力
    ```js
    ['a','b','c','d']
    ```




1. ## join
    15 concat で作った配列を出力してください。出力する際、配列内の要素を結合して出力してください  
    配列 `ary=['a','b','c','d']`  
    出力  
    ```js
    abcd
    ```



1. ## rensouhairetu
    連想配列に値を1つ追加し、配列内のすべてのkeyとvalueを出力してください
    連想配列: `ary={'color':'red','size':'100'}`
    追加する要素: `{'count':'5'}`
    ```
    keyは: color valueは: red
    keyは: size valueは: 100
    keyは: count valueは: 5
    ```


1. ## add
    自身が呼び出された数を出力する関数addを作成してください。
    e.g.
    ```js
    add();
    add();
    add();
    ```
    出力
    ```
    1
    2
    3
    ```





1. ## wather
    配列aryの内容をランダムに出力するプログラムを作成してください。  
    配列ary `ary=['晴れ','雨','曇り','槍']`  
    e.g.出力
    ```
    今日の天気は 槍 です
    今日の天気は 晴れ です
    今日の天気は 晴れ です
    今日の天気は 曇り です
    今日の天気は 雨 です
    ```



1. ## addImage
    ボタンを押す事に画像が追加されるようにしてください

    ![addImage](./img/addImage.gif)





1. ## encrypto1
    以下の文字数列`word`を暗号化して出力するプログラムを作成してください  
    暗号のルール: 各数字の後ろに2つ余計な数字を追加する  
    例
    ```js
    var raw='123';
    ～処理～
    console.log(raw); //=>198276354
    ```

    平文はなんでもいいですが例として
    ```js
    114514
    ``` 




1. ## decrypto1
    暗号化した変数`crypto`から不要な文字を削除して出力するプログラムを作成してください  
    hint: 暗号のルールは３文字おき

    ```
    const crypto='やくこみがんきいばていんるよは'
    ```





1. ## tanuki
    入力された文字列に含まれる「た」が連続した場合一文字に置換して、一つ以上の「ふ」が含まれた場合は「ふ」をすべて削除して出力するプログラムを作成してください。  
    入力値
    ```text
    ふわたたしが両手をひろげても、お空はちっとも飛べないが、飛べる小鳥はわたしのように、地面をはやくは走れない。

    わたたしがからだをゆすっても、ふきれいな音は出ないけど、あの鳴る鈴はわたたしのように、たたくさんなうたたは知らないよ。

    鈴と、小鳥と、それからわたたし、みんなふちがって、みんないい。
    ```



1. ## shadow
    hover時box-shadowでハイライトするようにして下さい

    ![shadow](./img/shadow.gif)



1. ## pulldown
    0から200まで選択できるプルダウンメニューを作ってください。javascript:document.createElement()を使うこと








1. ## form
    formタグを使って個人情報送信フォームを作ってください。完成後submitボタンを押して、URLを確認して下さい。入力された情報がURLに正しく追記されているか確認して下さい。  
    フォームの仕様
    ```
    名前: (type="text") 必須項目にすること
    Eメール: (type="email") 
    パスワード: (type="password")
    年齢: (selectタグとoptionタグ) 0~200歳まで選べること
    性別: (type="radio") labelタグも使用すること
    送信ボタン(type="submit")
    formタグの属性にmethod="get"を追加すること
    必須項目が入力されていない場合、入力を促すような仕組みにすること
    ```

    
    ![form](./img/form.gif)



1. ## marquee
    `<marquee scrolldelay="50" truespeed>癒し</marquee>`を設置して下さい。癒されたら完了です




1. ## slider
    設置したスライダーを調整することでmarqueeタグの速度を調整できるようにしてください。
    スライダーは`<input type="range">`で作成できます

    ![slider](./img/slider.gif)


1. ## nav
    横並びのナビゲーションバーを実装してください。    
    仕様
    ```
    コンテンツはの6つ
    マスオーバーした際に色が変わること
    ```

    ![nav](./img/nav.gif)




1. ## onImage
    画面に画像を表示し、その画像の上に一回り縮小させた同じ画像を重ねて表示、その縮小画像の上に「AAAA」と表示してください。一番大きな画像の外下側中央に画像のタイトルを設置してください。画像のタイトルだけかっこいいフォントを使ってください。





1. ## new
    以下のhtmlでnewクラスがついているものだけコンテンツの末尾にnewがつくようにしてください  

    ```html
      <ul>
        <li>ポッポ</li>
        <li>カイオーガ</li>
        <li class="new">ゼラオラ</li>
        <li>ガオガエン</li>
      </ul>
    ```
    出力例  
    ![newContents](./img/new.png)




1. ## createDiv
    100px四方のdivを生成するボタンを作ってください。  
    仕様
    ```
    色は緑
    自動に画面端で折り返すようにする
    ```


1. ## createDiv2
    準備中

    ![constrution](./img/construction.jpg)




1. ## 3sec
    3秒後にalert()を実行するボタンを作ってください

    ![3sec](./img/3sec.gif)


1. ## wTime
    現在の時刻を取得して出力してください。画面は自動で更新するように   

    ![wTime](./img/wTime.gif)


1. ## randomBgColor
    ボタンを押すと背景色がランダムに変わるwebページを作成してください



1. ## toBin
    テキストフォームから入力された10進数を2進数にして出力してください


1. ## toHex
    テキストフォームから入力された10進数を16進数にして出力してください




1. ## duplicate
    1～75までのランダムな整数を重複なく25個格納した配列を出力するプログラムを作成して下さい。
    数字が重複しないよう気をつけて下さい。



1. ## dupSort
    36 duplicate で作成した配列内を昇順でソートして下さい  
    e.g. 入力  
    `ary=['10','3','25','6','5']`  
    出力  
    `ary=['3','5','6','10','25']`


1. ## dupDel
    テキストフォームから指定された数値が、37 dupSort で作成した配列内にある場合削除し、削除後配列の大きさを削除した分だけ縮小した配列を返すプログラムを作成して下さい。指定された数が見つからなかった場合は「error: Can't deleted」と出力して下さい


1. ## partOfTable
    25マスのテーブルを用意し、それぞれのマス目に1～75の数字を割り当ててください。数字は昇順で重複がないようにしてください

    ![partOfTable](./img/partOfTable.PNG)

1. ## whichPlace
    partOfTableで作ったマスをクリックした際にその場所に割り当てられた数をalertするようにしてください



1. ## jquery
    ボタンを押すと「Cosmos」が「Chaos」に書き換わるようにしてください  
    jqueryのCDNを読み込んでjqueryを使って実装してください

    [ノンプログラマーのためのjQuery入門](https://www.slideshare.net/hayatomizuno/jquery-7665168?ref=http://weboook.blog22.fc2.com/blog-entry-349.html)



1. ## incrementHello
    ボタンを押すとボタンの下に 「Hello」 + 押した回数が追加されるプログラムを作成してください  
    jqueryを使って実装してください



1. ## chageColor
    画面に要素を3つ配置しクリックすると背景色が変わるようにしてください  
    それぞれjqueryを使って実装してください  
    やり方は一つとは限りません。それぞれ別の実装方法で実現してみて下さい

    ![changeColor](./img/changeColor.gif)



1. ## addImageJq
    ボタンを押す事に画像が追加されるようにしてください。jQueryを使って実装してください


1. ## hasImage
    addImageJqを改造して、ボタンクリックした時画像がすでにある場合は追加しないようにしてください。jQueryを使って実装してください


1. ## selectImage
    hasImageを改造して、画像の追加上限を3枚にして下さい。jQueryを使って実装してください



1. ## removeImage
    selectImageを改造して、クリックした時クリックされた画像が消去されるようにしてください。jQueryを使って実装してください

---


</details>

</br>


<details>
<summary>

# `n.50~n.100`

</summary>

---

## ・BootStrapを使ってみよう


以下の問題では、CSSはbootstrapを利用して見ましょう。
bootstrapは特定のクラスを与えるとすでに用意されたCSSを適用することができます。
詳しくはwebで  
## [Introduction · Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/)



```html
    <!-- CSS only -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <!-- JS, Popper.js, and jQuery -->
    <script
        src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
        crossorigin="anonymous">
    </script>
    <script
        src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
        crossorigin="anonymous">
    </script>
    <script
        src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous">
    </script>
```


50. ## find関数, closest関数を利用してみよう

    - wrapクラスのdivを用意し、`$(.wrap)`で取得したjQueryオブジェクトを変数wrapperに格納
    - find関数で'link-container'の中のaタグを変数'anchor'に格納しそのhref属性を取得しconsoleに出力してください

        ```html
        <div id="wrap">
            <div class='link-container'>
                <p class='link-text'>これはテキストだよ</p>
                <a href="google.com">yahooo!!!</a>
            </div>
        </div>
        ```

1. ## click関数を使おう

    - buttonをクリックしたらクラスを'btn-default' -> 'btn-warning'に変わる
    - ’ボタンだよ’ -> '押せません'にテキストを変更
    - ボタンを押せないようにする

    ```html
        <div class="container">
            <button type="button" class="js-button-event btn btn-primary">
                これはボタンだよ
            </button>
        </div>
    ```
1. ## fadeを使ってみよう
    - fade in

        'js-fade-in-button' を押したらboxクラスのhiddenになっているオブジェクトをfadeInする
    - fade out 

    現状で表示されているboxクラスのオブジェクトをfadeOutする

    ```css
    <style>
        span { color:red; cursor:pointer; }
        .container > div { margin:3px; width:80px; display:none;
            height:80px; float:left; }
        div#one { background:#f00; }
        div#two { background:#0f0; }
        div#three { background:#00f; }
    </style>
    ```

    ```html
    <div class="container mt-4">
        <div id="one" class="box"></div>
        <div id="two" class="box"></div>
        <div id="three" class="box"></div>
        <div class='d-flex flex-column'>
        <button class='btn btn-lg btn-info js-fade-in-button'>
            fadeIn
        </button>
        <button class='btn btn-lg btn-warning js-fadeout-button'>
            FadeOut
        </button>
        </div>
    </div>
    ```


1. ## ~59までの作業でTodoAppを作成してみよう
    - ディレクトリのなかに以下のファイルを入れてね

    1. package.json
    ```json
    {
        "private": true,
        "dependencies": {
            "director": "~1.2.2",
            "handlebars": "~2.0.0",
            "jquery": "~2.1.1",
            "todomvc-app-css": "^2.1.0",
            "todomvc-common": "~1.0.1"
        }
    }
    ```
    このファイルを作成したらコマンドラインから `npm install`を実行しましょう。
    → node_modulesというフォルダが作成されることを確認して下さい。
    (これは事前に用意したCSSを利用するためです。)

    また `index.html`を以下のように編集してください。
    https://gist.github.com/fumihumi/b34decd2ca92da95e89342ddeb01a85f


1. ## 新規登録の画面からFormを送信しましょう。
    formに送信ボタンを作成し、送信がおされたら入力されている文字を
    ハッシュ形式でAlertするようにしてください。
    形式は以下に準じるものとします

    ```javascript
    {
        text: `${入力された文字}`,
        status: unchecked
        created_at: 作成日時を 'yyyymmdd'の形式で,
    }
    ```

    statusというものは
     - unchecked
     - done
     - deleted

     上記の三つの要素を含んでいます。最初は`unchecked`.
     Todoが完了したらDoneに変化し、
     Todoが削除されたらDeletedに変化します。
     
     また、alertにて表示を完了することができたら、
     以下のようなFormatでHTMLに表示をしましょう。

     ```html
     <div class='content'>
     	<span class='checked'> </spant>
     	<p class='text'>
			...........comming soon
     </div>
     
     ```

1. ## JavascriptでValidationをしましょう
    入力された文字をHTMLとして出力する処理は完了しました。
    しかしながら現状では空文字であってもTodoの新規作成が可能となっています。
    formに文字が入力されていないときは新規登録ができないようにしてください。
    このとき。無断で処理を中断するだけでなく、利用者にもなぜ新規登録ができなかったのか伝えて見ましょう。
    その際、ユーザーフレンドリーとなるように心がけてください。

	また。アプリケーションを作成する際にはセキュリティも意識しなければなりません。
	クロスサイトスクリプティング、SQLインジェクションといったWebの脆弱性について調べ、それらを防ぐための仕組みを作成しましょう。
    セキュリティ対策と行っても何をすれば良いのかわからない場合は相談してください。

1. ## LocalStorageに保存しましょう
	先の操作にてユーザがTodoとして登録するデータは nullではないこと、、安全であることが保証されましたね。
	しかし現状ではブラウザを再読み込みしてしまうとデータが消えてしまいます。
	サーバーを作成したいのですが、今回はサーバーを利用しない方法を使ってみようと思います。
	サーバーの代用手段としてブラウザのLocalStorageを使って見ましょう。
    LocalStorageがなんなのかわからない場合はしらべ、コメントアウトに補足情報として記載してください。
	その後実際に、ユーザが入力したデータをLocalstrageに保存しましょう。	

1. ## LocalStorageから読み出してみよう
	ブラウザを表示したときにLocalstrageにデータがあればそのデータを表示するようにしましょう。

1. ## TodoでState管理をしてみよう
	ここまでで今回の作業としてはメモ帳としてのサービスができました。
	それをさらに本題のTodoアプリに近づけるためにそれぞれのタスクにState管理をしてみましょう。
	現状はすべてのTodoが作成されたばかりになっているのでなので
    `status == unchecked`ですね。
	TodoListの左にあるCheckboxをクリックしたらStatusをCheckedに変更してみましょう。
	また。Todo一覧の上部にあるStatusのタブをくりっくしたらそのStatusだけが絞り込まれるようにしましょう。

1. ## 削除ができるようにしよう
	TodoListのStatusがCheckedでないタスクのみ削除可能です。
	削除ボタンを押せるか押せないかの判断をし削除がおされたら該当Todoを削除しましょう。またLocalStorageからも削除しましょう。

    これにてTodoアプリは終了です。まだまだ機能として不完全な箇所はPRにまとめて見てください！
    お疲れ様でした！


60. ## local file
    ローカルファイルをインプットするために必要なhtml要素を書いてください。インプットできるファイルは、画像ファイルを指定してください。

1. ## reading local file
    問題60の続きです。インプットしたファイルのファイル名とファイルサイズをconsoleに出力してください。

1. ## display local file by base64
    問題61の続きです。
    readAsDataURLというメソッドを使って、取り込んだ画像をブラウザに表示してください。

1. ## display local file by blobURL
    問題61の続きです。
    createObjectURLというメソッドを使って、取り込んだ画像をブラウザに表示してください。

1. ## file download
    問題62,63の続きです。
    アップロードしたファイルを、ブラウザからダウンロードできるようにしてください。
    右クリックのメニューから画像を保存とは違います。
    htmlの要素を使ってください。

1. ## Coming soon...
    ![construction](http://flasco.cocolog-nifty.com/blog/images/maguro.jpg)

1. ## Coming soon...
    ![construction](http://flasco.cocolog-nifty.com/blog/images/maguro.jpg)

1. ## Coming soon...
    ![construction](http://flasco.cocolog-nifty.com/blog/images/maguro.jpg)

1. ## Coming soon...
    ![construction](http://flasco.cocolog-nifty.com/blog/images/maguro.jpg)

1. ## Coming soon...
    ![construction](http://flasco.cocolog-nifty.com/blog/images/maguro.jpg)


70. ## shake
    ボタンを押して文字を揺らして下さい。CSSアニメーションを使って実装すること

    ![shake](./img/shake.gif)


</details>
