# jsDelivrCDN

使用jsDelivr CDN教程
https://cloud.tencent.com/developer/article/1615048?from=information.detail.%E5%9B%BD%E5%86%85%20%E5%85%8D%E8%B4%B9cdn

示例：
https://cdn.jsdelivr.net/gh/muxinzi/jsDelivrCDN@1.0/images/logo.png

也可以不使用版本，比如：https://cdn.jsdelivr.net/gh/muxinzi/jsDelivrCDN/images/logo.png

注意：版本号不是必需的，是为了区分新旧资源，如果不使用版本号，将会直接引用最新资源。

参考资料：https://www.liuyao-blog.cn/posts/ee35.html

刷新缓存：在原先的url中，将“https://cdn.jsdelivr.net/…” 替换为 “https://purge.jsdelivr.net/…” 即可刷新
