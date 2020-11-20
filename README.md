# pa-bulma

Partical application of bulma

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Getting Started

1. npmにインストールする

```sh
yarn add pa-bulma
```

2. cssをインポートする

```js
import 'pa-bulma/css/bulma.min.css'
```

3. bulmaを適用したい要素に`.bulma`クラスを付加する

```html
<div class="bulma">
  <button class="button is-primary">Primary</button>
</div>
```

## Why use?

npmからインストールした[bulma](https://www.npmjs.com/package/bulma)をそのまま利用した場合、内部でcss resetを利用している為、他のcssに干渉する場合があります。

pa-bulmaでは`.bulma`クラスを付加したエレメント配下にのみbulmaを適用します。その為、他のcssへの干渉を防ぐことが可能です。

## Acknowledgments

本パッケージの仕組みは [@latica-jp](https://github.com/latica-jp) によって作成されています。心より感謝申し上げます。
