# commentfuction
这是仿照人人评论功能的案例
## 这是这个案例中涉及到要点：
* 1.学会JavaScript处理日期和时间。var t=new Date();这样就可以获取当前日期的对象，注意new Date()中不传入参数时获取当前日期的对象，
* 2.掌握Dom操作中的添加/删除子节点方法。appendChild(node)和removeChild(node)
* 3.使用setTimeout设置定时器。设置定时器的目的就是不让输入框失去焦点的时候，立马变小。setTimeout(function(){},定的时间)
* 4.使用clearTimeout清除定时器以及事件代理的运用。事件代理：当我们需要对很多元素添加事件的时候，	可以通过将事件添加到它们的父节点而将事件委托给父节点来触发处理函数。
	这主要得益于浏览器的事件冒泡机制
	事件代理的时候，使用事件对象中的srcElement属性,获取触发元素。
	IE浏览器支持window.event.srcElement，而firefox支持window.event.target。srcElement和target属性里面包含着类class，即各个标签，可以通过判断classNam，来进行对应的函数操作。
* 5.自定义的属性获取用getAttribute()和自定义的属性用setAttribute(),里面包含两个参数，一个是参数名，一个是值，如commentBox.setAttribute('user','self');
## 这是效果：

