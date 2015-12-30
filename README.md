### 立体轮播小插件

**用法：**

```javascript
var yourConfig = {
    num: 3, //要显示的数量，应该是个奇数
    maxWidth: 250, //代表中央图片的宽度
    maxHeight: 150, //中央图片的高度
    autoPlay: true, //是否自动滚动播放
    showTime: 1000, //autoPlay为true时这个属性才有用
    animationTime: 300, //
    scale: 0.8,
    distance: 50
};
$(selector).lunbo(yourConfig);
```
**注意：**
selector应该是个容器，下面的html结构应该是ul li img的形式：

```html
<div class='container'>
	<ul>
		<li> <img src=''></li>
		<li> <img src=''></li>
	</ul>
</div>
```
