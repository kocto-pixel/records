### ScratchBlocks中文积木样式代码分享
我在scrachblocks里复刻了中文scratch积木，如有错误请予以反馈~  
**相关链接**：  
积木图片生成网站：[`scratchblocks.github.io`](scratchblocks.github.io "点击跳转")  
用法教程（英文页面，请自行翻译）[`en.scratch-wiki.info/...`](en.scratch-wiki.info/wiki/Block_Plugin/Syntax "点击跳转：.../wiki/Block_Plugin/Syntax") 

**说明**：  
`//`开头的是注释，这里用来展示积木盒分区，`{`开头的是ring样式积木，这里用来展示控制按钮  
以下是代码，你可以在`scratchblocks`里粘贴它们：
~~~
//运动
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

//外观
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

//声音
播放声音( v)等待播完::sound
播放声音( v)::sound
停止所有声音::sound

将[音调 v]音效增加(10)::sound
将[音调 v]音效设为(100)::sound
清除音效::sound

将音量增加(-10)::sound
将音量设为(100)%::sound
音量::sound reporter

//事件
当@greenFlag被点击::events hat
当按下[空格 v]键::events hat
当角色被点击::events hat
当背景换成[背景1 v]::events hat
当[响度 v]>(10)::events hat
当接收到[消息1 v]::events hat
广播(消息1 v)::events
广播(消息1 v)并等待::events

//控制
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

//侦测
碰到(鼠标指针 v)::sensing boolean
碰到颜色(#7e004c)?::sensing boolean
颜色(#88ec3c)碰到(#30d186)?::sensing boolean
到(鼠标指针 v)的距离::sensing reporter

询问[你叫什么名字]并等待::sensing
回答::sensing reporter

按下(空格 v)键?::sensing boolean
按下鼠标?::sensing boolean
鼠标的x坐标::sensing reporter
鼠标的y坐标::sensing reporter
将拖动模式设为[可拖动 v]::sensing

响度::sensing reporter
计时器::sensing reporter
计时器归零::sensing

(舞台 v)的[背景编号 v]::sensing reporter

当前时间的[年]::sensing reporter
2000年至今的天数::sensing reporter

用户名::sensing reporter

//运算
()+()::operators reporter
()-()::operators reporter
()*()::operators reporter
()/()::operators reporter
在(1)和(10)之间取随机数::operators
<>与<>::operators boolean
<>或<>::operators boolean
<>不成立::operators boolean

连接[苹果]和[香蕉]::operators reporter
[苹果]的第(1)个字符::operators reporter
[苹果]的字符数::operators reporter
[苹果]包含[果]?::operators boolean

()除以()的余数::operators boolean
四舍五入()::operators boolean
[绝对值 v]()::operators reporter

//变量
{建立一个变量:: grey ring}:: grey ring
我的变量::variables reporter
将[我的变量 v]设为[0]::variables
将[我的变量 v]增加[1]::variables
显示变量[我的变量 v]::variables
隐藏变量[我的变量 v]::variables

{建立一个列表:: grey ring}:: grey ring

//自制积木
{制作新的积木:: grey ring}:: grey ring
~~~
