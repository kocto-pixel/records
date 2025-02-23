以下是我在scrachblocks里复刻的所有中文scratch积木，
你可以在`scratchblocks`里粘贴它们：
~~~
移动(10)步::motion
右转@turnRight(15)度::motion
左转@turnLeft(15)度::motion

移到(随机位置 v)::motion
移到x:(0) y:(0)::motion
在(1)秒内滑行到(随机位置 v)::motion
在(1)秒内滑行到x:(0) y:(0)::motion

面向(90)方向::motion
面向(鼠标指针 v)::motion

将x坐标增加(10)::motion
将x坐标设为(10)::motion
将y坐标增加(10)::motion
将y坐标设为(10)::motion

碰到边缘就反弹::motion

x坐标::motion reporter
y坐标::motion reporter
方向::motion reporter

将旋转方式设为[左右翻转 v]::motion

说[你好！](2)秒::looks
说[你好！]::looks
思考[嗯......](2)秒::looks
思考[嗯......]::looks

换成(造型1 v)造型::looks
下一个造型::looks
换成(背景1 v)背景::looks
下一个背景::looks

将大小增加(10)::looks
将大小设为(100)::looks

将[颜色 v]特效增加(25)::looks
将[颜色 v]特效设定为(0)::looks
清除图形特效::looks

显示::looks
隐藏::looks

移到最[前面 v]::looks
[前移 v](1)层::looks
造型[编号 v]::looks reporter
背景[编号 v]::looks reporter
大小::looks reporter

播放声音( v)等待播完::sound
播放声音( v)::sound
停止所有声音::sound

将[音调 v]音效增加(10)::sound
将[音调 v]音效设为(100)::sound
清除音效::sound

将音量增加(-10)::sound
将音量设为(100)%::sound
音量::sound reporter

当@greenFlag被点击::events hat
当按下[空格 v]键::events hat
当角色被点击::events hat
当背景换成[背景1 v]::events hat
当[响度 v]>(10)::events hat
当接收到[消息1 v]::events hat
广播(消息1 v)::events
广播(消息1 v)并等待::events

等待(1)秒::control
重复执行(10)次{
}@loopArrow::control

重复执行{
}@loopArrow::control

如果<>那么{
}::control
如果<>那么{
}{
}::control
等待<>::control
重复执行直到<>{
}@loopArrow::control
当<>重复执行{
}@loopArrow::control

停止[全部脚本 v]::control cap

当作为克隆体启动时::control hat
克隆(自己 v)::control
删除此克隆体::control cap
~~~
