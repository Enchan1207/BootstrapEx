# 更新履歴

…という名のただのメモ書きです

## [Add] Initial commit

 - `sass`コマンドをインストール(参考:[Qiita](https://qiita.com/akkisu/items/5287259a0ab3f1cb6faa))
 - VSCodeに[Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) をインストール、`.vscode/settings.json`にcss出力先を設定
 - composerで`Bootstrap-4.3.1`をインストール、`scss/custom.scss`でBootstrapのscssを読み込むよう`@import`文を記述 (参考:[公式](https://getbootstrap.jp/docs/4.3/getting-started/download/))

## [Update] add some components

 - jQuery, bootstrap.min.jsをロード [(index.html: 12-18)](index.html#L12-L18)
 - scssにいくつかカスタム設定を記述(bsの設定をオーバーライドしちゃってるのでまずいかも?)
 - コンポーネントをいくつか追加

## [Add] keep compiled CSS under git management

 - `.gitignore`を修正、コンパイル済みのCSSをgitの管理下におくよくに変更
