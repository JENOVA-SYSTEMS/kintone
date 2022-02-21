# kintone

これはDOM操作でkintoneの通知一括削除をするコマンドです。
DOM操作ですので、個人の責任の上ご利用よろしくおねがいいたします。

kintoneの通知のページでブラウザの開発ツールのconsoleなどで実行してください。

```
//mrkの要素のidを配列に格納

let kidoku_buttun_arr_da = ([].slice.call(document.querySelectorAll('[id$="mrk"]')));

//上記で格納した配列を1要素ずつ読み込み対象の要素をクリックする。

kidoku_buttun_arr_da.forEach(input_elem_da => {
input_elem_da.click();
});
```
 
