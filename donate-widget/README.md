# Donate-widget

#### 需要修改以下内容为你的账户

	/script.js:4-6 对应账户的二维码路径

	/index.html:28 PayPal.me 改为现在收款页面，这样可以删除原来的按钮方式了。

	/index.html:37 `<input id="btc-key" type="text" value="比特币账号" readonly="readonly">`

#### 使用 `iframe` 嵌入页面的代码，高度至少 `240px`，宽度至少 `310px`！

```
<iframe src="https://yoursite.com/donate-page/" style="overflow-x:hidden;overflow-y:hidden; border:0xp none #fff; min-height:240px; width:100%;"  frameborder="0" scrolling="no"></iframe>
```

### License

Released under the MIT license.
