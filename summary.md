·day01：
简历HTML基本结构与响应写法，利用flex布局做响应

待研究问题：
    通过before伪元素实现背景动画，且不覆盖；
待研究实践方式：
    写死整个resume-main的背景图片url，不通过main-left添加背景图;

----------------------------------------

·day02：
头像使用DIV、IMG标签的动画展现
总结：分别用DIV、IMG标签做动画，各有长处，HTML结构方面可能相对删减压缩力度过大，模块归类比较杂，作为头像又带动画

*此处希望老师提供个结构方式作为参考；

昨日问题解决：
    尝试后发现缩小屏幕宽度或相应，图片的位置会比较谜，不采用

----------------------------------------

·day03：
普通的写代码，更改CSS，优化CSS，调整HTML结构与模块结构
总结：继昨天的问题，最后还是决定模块区分好，并将整个简历的思路由静态页面更改为可增删改查页面，后期可反复调用简历模板的形式去制作

今日身体处于歇菜状态，代码量较少，去趴了

----------------------------------------

·day04：
右侧两栏结构也做自适应，同时用群里同学的问题写出一段work实现左边框渐变，带识别第一和最后渐变的代码，用的是border-image
总结：由于浏览器兼容问题，弃用这段border-imgae的渐变实现方式

独眼大侠的第二天，_(:зゝ∠)_

----------------------------------------

·day06：
根据参考而制作的简历项目自此算是完结，day05~day06的两天从05开始的CSS结构松散（打算放弃重写，，，）到今日06重振旗鼓，继续修改项目，已经算是成功结束（不能说圆满）
总结：最后总结下项目的思路已经制作经历过程

- 项目最开始的思路是做一套根据项目参考而制作的简历项目
- 第二天遇上了结构与功能结构的问题，思考模块的独立性与可维护性
- 写到第三天就萌生一个模板的思路，竟然是适应的东西，为啥不就能直接适应到底呢，于是全套内容适应之路开启
- 第四天算是利用其它同学想实现的属性写法去思考，期间利用了border-iamge的属性完美解决该同学的问题，最后的测试也是由于兼容性问题，选择放弃（弃用的CSS都会有独立的CSS文件去存放），接下来就是用其他方式实现咯
- 第五天也是由于个人的不够严谨，中途改了视窗大小的问题，导致后面的内容在相应后直接塌陷
- 第六天吗，重振旗鼓了，修复BUG就是玩文字游戏，中途多利用好调试工具（感谢调试工具），改变结构高度思路，最后也是解决了问题，当然，在内容的相应于适应上也是下了一番思考的功夫，无论内容多或少，都会让模板自己去响应适应，最后测试上还是有个小缺陷，就是当流浪器默认的视图大小缩小时，里面的内容较为空旷，内容列表与其子内容列表不能去做一个响应，一但内容多了，里面的所有内容也塌陷，不够也没啥人会去缩小得特别小吧

///代码总结嘛，中途的思路不能说乱，但是摇摆不定，最后也是这里打打补丁，那边打打补丁，整套代码之间看起来还是有点小乱


独眼大侠黑五赶车，漏写一天总结_(:зゝ∠)_
1