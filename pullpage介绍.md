###API介绍
1. sectionsColor：可以为每一个section设置背景颜色；
2. controlArrows：箭头来控制slide幻灯片，默认是true，在M端不需要设置为false，通过滑动操作；
3. verticalCentered：用来控制每一页的内容是否垂直居中，默认是true，一般保持默认值就行；
4. resize：字体---是否随着窗口的缩放而缩放，默认为false；
5. scrollingSpeed：滚动速度，默认是700；
6. anchors：定义锚链接，默认值为[],有了锚链接，用户就可以快速定位到要打开的某一页面，注意定义锚链接时，值不要和页面的任意id和name相同，尤其在ie浏览器下，定义时不需要加#；
7. lockAnchors：锁定锚链接，默认为false，如果设置为true，那么anchors定义的则没有效果；
8. easing：easeInOutCubic 如果修改此项需要引入，jquery.easings或者jquery ui
9. css3：true，是否支持css3 transforms来实现滚动，默认是true，浏览器若不支持用jq来代替css3
10. loopTop:true,//滚动到顶部后是否连续滚动到底部，默认是false
11. loopBottom:true,//滚动到底部后是否连续滚动回顶部，默认是false
12. loopHorizontal:true,//横向slider幻灯片是否循环滚动，默认是true
13. autoScrolling:true,//是否使用插件的滚动方式，默认是true，如果是false，则会出现浏览器自带的滚动条，不会按页滚动，而是按照滚动条的默认行为来滚动
14. scrollBar:false,//是否包含滚动条，默认是false，如果设置为true，则会出现浏览器自带的滚动条，页面滚动还是按页滚动，但是滚动条的默认行为也是有效。
15. paddingTop/paddingBotttom: 设置每一个section的顶部和底部的padding，默认都是0，一般需要设置一个固定在顶部或者底部的菜单、导航、元素等
16. fixedElements: 固定元素，默认为null，需要配置一个jq选择器，在页面滚动的时候，fixedElements设置的元素固定不动
17. keyboardScrolling: 是否可以使用键盘的导航键,默认true
18. touchSensitivity： 在移动设备中滑动页面的敏感性，默认为5，是按着百分比来衡量，最高为100，越大则越难滑动
19. continuousVertical：是否循环滚动，默认为false，若为true，页面会循环滚动，而不像loopTop或者loopBottom那样出现跳动，这个属性和loopTop、loopBottom不兼容，不要同时设置
20. animateAnchor：锚链接是否控制滚动动画，默认是true，如果设置为false，则不会又动画
21. recordHistory:true,//是否记录历史，默认为true，可以记录页面滚动的历史，通过浏览器的前进后退来导航，注意如果设置了autoScrolling：false。那么这个配置也将关闭，即设置为false
22. menu:"#fullpageMenu",//绑定菜单，设定相关属性与anchors的值对应后，菜单可以控制滚动，默认为false，可以设置为菜单的jquery选择器
23. navigation:false,//是否显示导航，默认为false，如果设置为true，会显示小圆点，作为导航
24. navigationPosition:'left',//导航小圆点的位置，可以设置为left或者right
25. navigationTooltips:,//导航小圆点的tooltips设置，默认为[],注意按照顺序设置
				
				
				
				

				
				
				
				







知识点：

1. 在section后边假如加上active，打开页面直接就是那页

	
