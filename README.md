# Auto_GirlsFrontline
少女前线的中国特色社会主义现代化：全自动拖尸、后勤、打捞、捡垃圾

# 更新公告
7.11更新：特别致谢@railannad指出的问题，战斗中断时和无战斗时主菜单的UI位置是不一样的，之前考虑不周，现已完善程序。另外听说不同版本的MuMu可能界面有细微的差别，导致关闭游戏的“x”的位置不一样，这个只能请各位自己调一下CLOSE_GAME_CLICK_BOX的位置了

# 责任声明
本人编写并分享本程序的目的有且仅有学习参考一用，使用者若因上述目的之外的任何行为造成的任何后果均与本人无关，任何人在查看、下载、使用本程序时即代表你已同意上述声明并且愿意承担一切后果。

# 功能介绍
当前上传了四个功能：
1. auto0_2: 自动0-2拖尸
2. autoLSupport：自动收后勤
3. auto4_6: 自动4-6捡垃圾
4. auto8_1n: 自动8-1n炸狗
>至于打捞，太精污了，不想做


# 使用说明
1. 此项目中的所有程序仅能在**电脑**端配合**模拟器**使用 
2. 运行时请务必以**管理员**身份运行，否则运行时会报错
3. 本程序是.py脚本，不是.exe可执行文件的，需要你懂python编程基础才能使用，需要安装**opencv(4.2.0)、skimage(0.16.2)库**
4. 如果你没有看我的程序，不清楚运行原理，请务必使用"MuMu模拟器"，自定义分辨率为750x500,DPI为166,系统的缩放为100%
5. 如果你看了并且理解了程序，那么你只需要重新设置好所有box，重新预存好所有图片，就可以使用任意模拟器，任意分辨率
6. 本程序是在pc端模拟鼠标操作模拟器，且所有的点击动作都是在一个矩形区域内**随机**选点，点击后有**随机**的等待间隔，最大程度避免被发现


# 原理概括
基本逻辑和数电里的有限状态机差不多，不断地截取游戏界面并判断所处的状态，然后不同的状态对应于不同的操作。所谓“状态”，就是当前在哪个界面，比如说在主菜单界面，那么状态就是“主菜单”，假如是要自动0-2，那么对应的操作就是点击“作战”；如果在作战选择菜单，那么状态就是“作战选择”，对应的操作就是点击“作战任务”，拖动点击“第零战役”，点击“普通”。
>> 我说得再多再详细也不如自己看看程序，注释我写得比较详细，整体逻辑也比较简单易懂，搞懂了原理你就可以自己改功能了（hxd，给颗⭐行不）

# 碎碎念念
奇迹和魔法是存在的！...那么代价是什么呢？
这毕竟是违反规则的，虽然我做了充分的预防措施，而且从2020年1月底入坑，2月初制作使用此程序，到现在也确实安然无事(出事了我自然会删除该项目的)，但是我也不能保证不会被官方发现。我相信各位也是珍惜自己的账号的，所以请务必小心谨慎，莫要自负,莫要招摇，自己玩得开心才最重要。

祝疫情早日结束，祝各位开心健康，叶~！
