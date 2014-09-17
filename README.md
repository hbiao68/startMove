startMove
=========

原生JS运动库，支持匀速和缓冲两种运动方式

startMove(obj, { width: 480, opacity: 100 }, "linear", 20, function() {});
参数说明
=========
obj: 要运动的元素<br>
json: 要改变的属性<br>
effect: 运动方式：linear匀速，easeOut缓冲，默认为linear<br>
iSpeed: 每次运动的步长，默认为10<br>
fn: 运动完成的回调
