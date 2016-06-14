# commentfuction
这是仿照人人评论功能的案例
## 这是这个案例中涉及到要点：
* 1.学会JavaScript处理日期和时间。var t=new Date();这样就可以获取当前日期的对象，注意new Date()中不传入参数时获取当前日期的对象，
* 2.掌握Dom操作中的添加/删除子节点方法。appendChild(node)和removeChild(node)
* 3.使用setTimeout设置定时器。设置定时器的目的就是不让输入框失去焦点的时候，立马变小。setTimeout(function(){},定的时间)
* 4.使用clearTimeout清除定时器以及事件代理的运用。事件代理：当我们需要对很多元素添加事件的时候，	可以通过将事件添加到它们的父节点而将事件委托给父节点来触发处理函数。
	这主要得益于浏览器的事件冒泡机制
	事件代理的时候，使用事件对象中的srcElement属性,获取触发元素。
	IE浏览器支持window.event.srcElement，而firefox支持window.event.target。srcElement和target属性里面包含着类class，即各个标签，可以通过判断className，来进行对应的函数操作。
* 5.自定义的属性获取用getAttribute()和自定义的属性用setAttribute(),里面包含两个参数，一个是参数名，一个是值，如commentBox.setAttribute('user','self');
## 这是效果：
http://htmlpreview.github.io/?https://github.com/yanjungan/commentfunction/blob/master/index.html

## 小练习：
* 1.实现删除元素，鼠标移动到一个列表项上，显示删除按钮，点击按钮后，可以将其删除。
* 2.使用JS实现网页投票功能，点击投票按钮，票数加1， 为了防止刷票，每次跳票的间隔为10秒。
* 3.实现网页输入框动态展现和字数计算，获取焦点时，输入框的高度增加， 失去焦点时，输入框的高度减小，在输入的时候，实时计算输入的字数，并显示出来。
* 4.实现网页留言功能，点击确定按钮，把输入框的内容添加到留言列表中。
* 5.实现网页加星功能，点击相应的星星， 实时显示加星结果。
* 6.实现网页留言的编辑功能，每条留言中都会带有一个编辑按钮，点击编辑按钮的时候，可以对相应留言内容进行编辑。
