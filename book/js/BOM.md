## window

- 全局变量不能通过 delete 操作符删除，而直接在 window 对象上的定义的属性可以。
```
var age = 29;
window.color = "red";

delete window.age; // false
delete window.color; // true
```

- 窗口
	- window
	- self
	- top
	- parent

- 除非最高层窗口是通过 window.open() 打开的，否则其 window 对象的 name 属性不会包含任何值

