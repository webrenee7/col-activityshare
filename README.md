## 使用方法
- 加入以下代码
```html
<input class="actitle" type="hidden" value="分享标题" />
<input class="actsummary" type="hidden" value="分享描述！" />
<input class="actlink" type="hidden" value="http://image.kuaikuaidai.com/h5/static/images/lendimgwx.png" />
<input class="linkpage" type="hidden" value="" />
<input id="appId" name="appId" type="hidden" value="${appId}"/>
<input id="timestamp" name="timestamp" type="hidden" value="${timestamp}"/>
<input id="nonceStr" name="nonceStr" type="hidden" value="${nonceStr}"/>
<input id="signature" name="signature" type="hidden" value="${signature}"/>
```

- 引入js
```javascript
<script src="../projectusual/static/js/activityshare.js"></script>
<script src="http://res.wx.qq.com/open/js/jweixin-1.0.0.js"></script>
<script type="text/javascript" src="http://qzonestyle.gtimg.cn/qzone/qzact/common/share/share.js"></script>
```

## 微信分享敏感词汇
目前发现的：
红包、现金、现金红包、福利

之后再做补充

