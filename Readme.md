#归档 OmniFocus 中已完成的任务到 印象笔记/Evernote 
代码主要取自参考文章2，具体设置可以参考这篇文章，我这里主要是汉化了一下，然后调整出我喜欢的格式。

![](http://ww3.sinaimg.cn/large/6763a9e1gw1ez7hwthtptj20ea0bsmye.jpg)

最终在印象笔记中显示的格式：
![](http://ww3.sinaimg.cn/large/6763a9e1gw1ez7hszzdxmj21dm0ygn50.jpg)

注意事项：

- 需要本机安装 OmniFocus和印象笔记/Evernote 这2个App
- 归档后笔记存在印象笔记 inbox 笔记本，笔记名格式为：OmniFocus【2015年12月1日 星期二 => 2015年12月31日 星期四】已完成任务清单

使用方法：

1. 打开 OmniFocus 帮助菜单/打开脚本文件夹
2. 将 scpt 文件放入脚本文件夹
3. OmniFocus工具栏上右键, 在弹出的菜单上选择『自定义工具栏』, 将脚本图标拖到工具栏上
![](http://ww3.sinaimg.cn/large/6763a9e1gw1ez7hvytf14j20r204ogmc.jpg)

后期计划：

1. 准备使用 Mac plist 脚本每天定时运行此脚本，做到自动归档
2. OmniFoucs 中一个任务附注为空时，归档时不显示附注

附上 [github地址](https://github.com/Channe/OmniFocus2Evernote)

> 参考文章：
> 
> 1. [AppleScripting OmniFocus > Send Completed Task Report to Evernote](http://www.engadget.com/2013/02/18/applescripting-omnifocus-send-completed-task-report-to-evernot/)
> 
> 2. [AppleScripting OmniFocus > Send completed task report to Evernote 2](http://www.engadget.com/2013/04/15/applescripting-omnifocus-send-completed-task-report-to-evernot/)
> 
> 3. [OmniFocus的任务执行时间统计脚本](http://www.jeffzhang.cn/omnifocus-script-Lyubishchev/)
