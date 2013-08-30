# tab

---

标签切换组件。建议和 `arale.switchable` 进行配合。

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/tab.css">
<style>
a { color:#08c; }
a:hover { color:#0fa; }
a:active { color:#f60; }
a:visited { color:#000; }
</style>

````html
<div class="ui-tab">
    <ul class="ui-tab-items">
        <li class="ui-tab-item ui-tab-item-current">
            <a href="javascript:;">全部交易</a>
        </li>
        <li class="ui-tab-item">
            <a href="javascript:;">进行中的交易</a>
        </li>
        <li class="ui-tab-item">
            <a href="javascript:;">等待发货的交易</a>
        </li>
        <li class="ui-tab-item">
            <a href="javascript:;">未确认收获的交易</a>
        </li>
    </ul>
</div>
````
