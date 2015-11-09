---
layout: page
title: 微信公众号
permalink: /wechat/
---

我们的自由岌岌可危。关注广蓝微信公众号<span id="wechat-id">cantonres</span>获取最新资讯（点击二维码复制微信号）：

<div id="note-copied" class="note" style="display: none;">
复制成功！现在打开微信，点击右上角的搜索按钮，粘贴我们的微信号来关注我们吧！
</div>

<div id="note-manual" class="note" style="display: none;">
轻点复制键，打开微信，粘贴搜索我们的微信号来关注我们吧！
</div>

<div id="qr" data-clipboard-target="#wechat-id">

![二维码](/assets/wechat.qr.png){: .center .medium}

</div>

<script src="/assets/clipboard.min.js"></script>
<script>
var clipboard = new Clipboard( '#qr' );
clipboard.on( "success", function( e ) {
	document.getElementById( "note-copied" ).style.display = "";
} );
clipboard.on( "error", function( e ) {
	document.getElementById( "note-manual" ).style.display = "";
} );

</script>
