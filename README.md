# scomb-shibaura-ichiba
このアプリケーションは，Chromeの拡張機能である．  

## 機能
このアプリケーションの機能は，ScombのLMSページ (https://scombz.shibaura-it.ac.jp/lms/timetable) に「クリップボードに時間割情報をコピー」ボタンを追加し，そのボタンを押した後，規約に同意を得たうえでクリップボードに時間割情報をコピーする機能である．  
芝浦生以外はアクセスできない．
出力形式は，  
授業名, 教員名1, 教員名2, ...である．   
例は，   
高度情報演習1B, 福田　浩章, 中島　毅  
である．これがすべての授業に対して改行されて羅列される．  
注意として，教員名に休講のようなものが出力されることである．  

## 目的
芝浦市場の教科書のサジェストにユーザがペーストをすることを目的としている．  
この機能を使うことで，自分が取っている授業の教科書がサジェストされ，簡単に購入することができる．  

## セキュリティ
この拡張機能は，https://scombz.shibaura-it.ac.jp/lms/timetable* 上でしか動かない．  
この拡張機能は，余計な機能を一切積んでいない．  
この拡張機能は，余計な通信を一切しない．  
この拡張機能は，芝浦工業大学情報イノベーション科の許可を得て作成されている．  

## 使用方法
1. ファイルをダウンロードする．
2. Google Chromeの拡張機能を設定ページへ飛ぶ． (chrome://extensions/)
3. パッケージ化されていない拡張機能を読み込む で，ダウンロードしたファイルを選択する．
4. 拡張機能が有効化されていない場合，有効化する．
5. Scombのlmsタブにとび，右上に表示される青いボタンをクリックする．
6. 規約に同意する．
7. 芝浦市場のホームページ（商品一覧ページ）で，"Scomb-Shibura-Ichibaからペースト"と書いてあるテキストボックスにペーストする．

