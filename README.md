# zeess

[Demo](http://zacanger.github.io/zeess)

A really pretty small CSS sorta-framework.

To use: download, clone, or `npm i -S zeess`, and link to it.

Docs will show up eventually, I promise.

## grid

### not flex based
`.split` is a half a column.
use like: `<div class="split">this stuff is half of its parent's size</div>`

### flex based

```html
<div class="row">
  <div class="col">Col</div>
  <div class="col">Col</div>
</div>
```

* `row` is a row
* `col` is a column
* `col-tenth` is `10%` width
* `col-fifth` is `20%` width
* `col-quarter` is `25%` width
* `col-third` is `33.3333334%` width
* `col-half` is `50%` width
