# ChiMi #
MIUI扩展插件（EdXposed/TaiChi/LSPosed）

修改MIUI系统的一款MIUI增强插件


最新版本只支持MIUI12.5

失效的可以尝试：
▲①用LSPosed/EdXposed/太极优化应用（如状态栏功能部分失效，，LSPosed作用域中长按系统界面选择优化，Edxposed用Speed模式优化系统界面，太极优化系统界面） 

②重新添加应用和重新勾选模块！

③清除ChiMi数据或者重装ChiMi

④太极阳用户要仔细看适配的版本，还没适配就会失效，适配后要更新太极阳引擎

⑤停用可能起冲突的Xposed模块和Magisk模块（比如修改系统或者系统界面的Xposed/Magisk模块；停用/删除magisk模块后需要删除/data/system/package-cache/里对应文件）

更多细节写在使用说明中

如果按照软件内说明的操作过后还是不行的可以提交issue。

更新后最好重新勾选并重启，避免出现未知bug。


已知bug：
- 锁屏时间样式选择第四个，添加闹钟失效
- 状态栏网络类型变大且移动位置至信号右边，双卡用户会出现留白现象
- 因MIUI12.5状态栏的信号和状态栏系统图标（蓝牙、静音等）布局是动态布局，所以时间居中+信号居左会把系统图标也居左；
切换横屏时挖孔屏时间居中，状态栏左边会留白一部分，且再切回竖屏时状态栏布局会乱，需要下拉刷新一下状态栏。



功能如下图：
![image](img/1.jpg)
![image](img/2.png)
![image](img/3.jpg)
![image](img/4.jpg)
![image](img/5.png)
![image](img/6.jpg)
