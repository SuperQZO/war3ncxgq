# War3Trainer(WarCraft III Trainer)

**终止更新**

这是我原先blog文章（[魔兽3内存修改器](http://tctianchi.duapp.com/archives/tag/%E9%AD%94%E5%85%BD3)）对应的代码。如今这个blog已经下线，彻底断绝了我更新的动力。十多年前我上学期间因不满当时的工具而写了这款修改器，但自己早就不玩魔兽所以一直对更新之事兴味索然。虽感谢十年来网友们的精神支持，只得跟进一下聊表寸心。然则暴雪的耐心还是超人意料，真是令人敬佩。

![Screenshot](https://raw.githubusercontent.com/tctianchi/War3Trainer/master/Screenshot.png)

## 下载

请移步[release](https://github.com/tctianchi/War3Trainer/releases)页。

## 修改器简介

这款修改器可以读写魔兽争霸3游戏中的游戏资源、单位攻击力、英雄属性等，帮助你在单机游戏中获得更好的娱乐体验。但不能：
* 修改器不是作弊器，只能在单机上使用
* 不适用于网络对战，更无法在战网上胡闹
* 没有向网络发送过任何欺骗信息
* 想在宿舍里联机打RPG地图的话需要在每台电脑上做相同的修改动作才不会掉线，游戏平衡性不受影响
* 我懒得与国内某平台做修改对抗，请网友们不要再发一些诸如“我的账号被封了该怎么办”之类的消息

## 支持的游戏版本
* 1.20e（1.20.4.6074）
* 1.21a（1.21.0.6263）
* 1.21b（1.21.1.6300）
* 1.22（1.22.0.6328）
* 1.23（1.23.0.6352）
* 1.24a（1.24.0.6372）
* 1.24b（1.24.1.6374）
* 1.24c（1.24.2.6378）
* 1.24d（1.24.3.6384）
* 1.24e（1.24.4.6387）
* 1.25b（1.25.1.6397）
* 1.26（1.26.0.6401）
* 1.27a（1.27.0.52240）
* 1.28（1.28.0.7205）
* 1.28f（1.28.5.7680）

## 历史程序版本

### [V15](https://github.com/tctianchi/War3Trainer/releases/tag/v15)

2017.8.27
* 对.net Framework的依赖由2.0改为4.6.1，因为win 10已不再默认安装2.0
* 支持1.28f
* 撤销对网易的兼容

### [V14](https://github.com/tctianchi/War3Trainer/releases/tag/v14)

2017.4.22
* 主动获得管理员权限
* 兼容网易对战平台（dz.163.com）
* 支持1.28

### [V13](https://github.com/tctianchi/War3Trainer/releases/tag/v13)

2016.8.12
* 支持1.27a

### [V12](https://github.com/tctianchi/War3Trainer/releases/tag/v12)

2014.1.4
* 支持1.26

### [V11](https://github.com/tctianchi/War3Trainer/releases/tag/v11)

2011.4.6
* 新增对win7 x64的支持
* 修正了修改列表焦点与选择项不一致的Bug

### [V10](https://github.com/tctianchi/War3Trainer/releases/tag/v10)

2011.3.12
* 支持1.25b

### V9.3

2011.3.3
* 修正了一处不必要的throw Exception，汗-_-b

### V9.2

2011.3.3
* 修正了功能列表未选择时更新修改列表会崩溃的Bug

### V9.1

2011.3.3
* 新增HP、MP回复的修改

### [V9](https://github.com/tctianchi/War3Trainer/releases/tag/v9)

2011.3.2
* 新增武器射程的修改
* 支持1.20.4.6074、1.21.0.6263、1.21.1.6300、1.22.0.6328、1.23.0.6352、1.24.0.6372、1.24.1.6374、1.24.2.6378、1.24.3.6384、1.24.4.6387（大部分是离不开电脑同学提供的）
* 改为根据Game.dll判断版本（由eflay同学提供）

### [V8](https://github.com/tctianchi/War3Trainer/releases/tag/v8)

2009.8.15
* 改用C#重写所有代码
* 允许修改的游戏金钱从10家改为12家
* 允许修改物品种类和使用次数
* 支持1.20.4.6074、1.21.0.6263、1.21.1.6300、1.22.0.6328、1.23.0.6352、1.24.0.6372

### [V7](https://github.com/tctianchi/War3Trainer/releases/tag/v7)

2008.11.5
* 为Dota修正选中单位列表的获取
* 界面

### [V6](https://github.com/tctianchi/War3Trainer/releases/tag/v6)

2008.10.26
* 无注入（当然也不是内存搜索）的新思路
* 又可以改单位（含建筑和金矿）了
* 支持1.20e、1.21、1.22.0.6328三个版本
* 允许修改单位的坐标
* 可以改一点英雄技能

### [V5](https://github.com/tctianchi/War3Trainer/releases/tag/v5)

2008.10.8
* 针对魔兽3 1.22.0.6328
* 金钱不再需要注入，可以即刻完成刷新
* 单位只需注入一次，其他地址可以推算
* 新增HP、MP修改
* 限制了TextBox长度

### [V4](https://github.com/tctianchi/War3Trainer/releases/tag/v4)

2007.3.17
* 下面的修改遵循“贴补丁”的方式修改程序
* 追加攻击相关
* 追加防御相关
* 追加金钱相关

### [V3](https://github.com/tctianchi/War3Trainer/releases/tag/v3)

2007.2.4
* 针对1.21a重新修改

### [V2](https://github.com/tctianchi/War3Trainer/releases/tag/v2)

2007.1.31
* 增加了“智力”的修改
* 去除了界面上不必要的元素
