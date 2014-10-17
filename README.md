# HTML5 Site Template

新規でHTML5サイトを作成する際の雛形です。

[GitHub Repository](https://github.com/yuta-kanayama/html5-site-template)  
[Author Blog](http://yuta-k.net/)


## 仕様技術
* HTML5
* Sass + Compass
* JavaScript(jQuery)
* gulp
* git


## HTMLとCSS
CSS設計に[BEM](http://bem.info/)と[SMACSS](http://smacss.com/)を取り入れています。  
メタ言語として[Sass](http://sass-lang.com/)と[Compass](http://compass-style.org/)を使用しています。

### カテゴライズ

* base - サイト全体に関わるスタイル
* image - base64エンコードした画像の定義
* layout - レイアウトを定義するスタイル
* module - 独立した構成要素
* state - 状態の定義
* theme - テーマの定義
* tools - 変数やMixin
* unique - サイト特有のスタイル


### 命名規則

```
.block__element  
.block--modifier  
.block__element--modifier  

✗ .block__element__element  
✗ .block__element--modifier__element
```
