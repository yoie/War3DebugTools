# 兼容说明 (测试版)
* 目前只支持 124,126版本，storm 109版本
* 暂时不支持JAPI的解析，附加YDWE编译后的图可能存在崩溃或者闪退
* 如部分功能无内容或者无反应可能是暂未完成功能
# 项目计划 Project Plan 
* Jass执行断点，支持单步执行调试
* 游戏崩溃后定位脚本执行点
* 支持127版本兼容

# 介绍 Introduce
## 1、静态分析 Static Analysis
* 地图文件浏览器 Map files browser
  * 有(listfile)情况下，可直接查看资源文件内容
  * 无(listfile)情况下，支持通过未知文件解析其格式，同时支持查看内存
* 脚本分析器 Jass script analysis
  * 自动解析代码结构，归档全局变量，触发器，函数
  * 代码支持高亮显示方便阅读
  
## 2、动态调试 Dynamic Analysis
* 地图资源浏览器 Map file resources browser
  * 可以监测游戏读条时地图所有加载资源的记录
  * 通过刷新可以显示游戏内所有已经加载的资源列表
* 游戏内存描述表查看 Game memory description table viewer
  * 可以查看游戏所有申请的内存块描述和大小
  * 支持查看内存块内详细数据内容
* Jass脚本调试器 Jass script debugging
  * 可以查看Jass内存执行编码，支持解析，同时解析整理代码结构
  * 支持动态下断，下断后可以查看当前脚本引擎内寄存器、堆栈、变量(全局、局部)的值
  * 可以监测脚本函数执行的记录，并且统计调用次数，以及内存消耗，可用来查内存泄漏
* 地图单位浏览器 Map units browser
  * 可以查看当前地图内所有单位对象的属性
  * 支持单位对象资源导出
  
## 3、动态监测记录 Game Monitor
* 游戏内存申请记录 Monitor game alloc memory record
  * ~~可以监控游戏内所有内存申请操作，可用来查内存泄漏~~
* 游戏崩溃记录扩展
  * 可以监控游戏当前脚本执行位置，寄存器、堆栈、变量数据，以及当前游戏环境内所有单位信息
  
## 4、其他工具 Other Tools
* MDX查看器 MDX files viewer
* BLP查看器 BLP files viewer
* 内存监测记录查看  Memory record log viewer
  * 用来查看内存监控数据日志

# 界面截图 Tools Screenshot
![Image text](https://github.com/yoie/War3DebugTools/blob/main/Images/1.png)
![Image text](https://github.com/yoie/War3DebugTools/blob/main/Images/2.png)
![Image text](https://github.com/yoie/War3DebugTools/blob/main/Images/3.png)
![Image text](https://github.com/yoie/War3DebugTools/blob/main/Images/4.png)
# 更新 Update
* 2022-03-22 MD5:006F2F1BCF39735BDF77AD1CD988AE5A Version:Build 20220322 Bate

# 联系作者 Contact
* Email : yoie_studio@163.com
