# Soldier76

PUBG - G502鼠标宏自动压枪脚本使用说明

*(务必...务必...务必...认真看完，使用说明写的很详细了)*

---

### 下载脚本
* 选择<a href="https://github.com/kiccer/Soldier76/releases" target="_blank">下载</a>版本
* 版本号由**a.b.c**三个部分组成
* **a**是大版本号，此版本号改动时，将可能会造成操作方式上的改变
* **b**是次版本号，通常表示有新功能上线
* **c**是修订号，通常表示修复了BUG，或是正在测试新的功能，通常不够稳定
* 下载时请尽量选择**a.b**形式的版本号，例如**v3.3**

### 安装教程
1. **以管理员方式**启动罗技驱动
2. 扫描游戏
3. 开启 **自动游戏检测**
4. 右键配置文件左侧 **PUBG** 图标 -> **编写脚本**
5. 将 **Soldier76.lua** 中包含的所有代码完全复制进去，保存(Ctrl + S)
6. 右键 **PUBG配置** 和 **默认配置** 中的 **G6**, **G7**, **G8**, **G9**, **G10**, **G11** 按钮 -> **取消分配**

### 使用本鼠标宏需要对游戏内设置做出一定改动：
* 将**开镜**设置为**按住右键**，**必需设置** (注意，这里说的是**按住**，不是单击)
* 如果使用腰射压枪功能，需要把腰射键改为**左ctrl**键，可选，推荐
* 如果使用自动连发功能，需要把开火键改为键盘按键（例如：~键），可选，不推荐

### G键功能 - 默认 (部分支持自定义)
G键 | 功能
:--: | ---
**G6** | 切换至 **5.56** 枪械配置文件表，并使用**第一个**配置，可自定义
**G7** | 切换至 **9mm** 枪械配置文件表，并使用**第一个**配置，可自定义
**G8** | 切换至 **7.62** 枪械配置文件表，并使用**第一个**配置，可自定义
**G9** | 切换至 **.45** 枪械配置文件表，并使用**第一个**配置，可自定义
**G10** | 切换至**最后一个**配置 (滚轮右偏)
**G11** | 切换至**下一个**配置 (滚轮左偏)

### 模式控制
按键 | 功能
:--: | ---
**CapsLock** | 开启大写字母键，启动宏，关闭则锁定宏(宏将暂时不可用，但配置记录保留)
**ScrollLock** | 开启开发者调试模式，准星自动向右拉(开启后尝试修改 `InGameSightingSensitivity` 的值，使弹道变成一字)

### 使用方法
* 在右键(按住开镜)按住的情况下，点击左键启动压枪宏
* 在左Ctrl键(腰射)按住的情况下，点击左键启动压枪宏
* 开镜并按住左Alt键的情况下，点击左键启动4倍压枪宏

### 硬件条件
* 一只 G502 鼠标
* 游戏画面不卡顿，不频繁掉帧，必要时可以锁定帧数保证稳定性

### 免责声明
* **该脚本程序仅供学习交流，严禁使用于任何商业用途，若产生利益纠纷，概不负责。**

### 关于宏
* 宏就像是一个心灵手巧的瞎子，它可以帮你做更复杂细腻的操作，但无法根据实时情况进行变通。
* 宏不是外挂，宏只是辅助工具。工具能发挥出多大的作用取决于使用者的能力。
* 该脚本只是将复杂的操作化繁为简，能让使用者从压枪操作中解放出更多精力。

~~Ps: 如果认为游戏体验有提升的话，请给我一颗小星星:)~~
