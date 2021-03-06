# usmooth 

## !重要提示!

**该工具已不再更新，已整合入 [PerfAssist/PA_Term](https://github.com/PerfAssist/PA_Term)，测试场景见 [PA_Term_DemoScene](https://github.com/PerfAssist/PA_Term_DemoScene)**
 
 
 -------------------------------------
 
- [__Download (v0.2a)__](https://github.com/SeaSunOpenSource/usmooth/releases/tag/0.2a)  
- [__Tutorial__](https://github.com/SeaSunOpenSource/usmooth/wiki/tutorial)
- [Release Notes](/release_notes.md)
- [Roadmap](https://github.com/SeaSunOpenSource/usmooth/issues)

## 设计目标

Unity 已有的性能剖析机制已经比较强大，可是它主要以程序员为目标用户，缺乏对美术和测试等非程序员的支持。而 usmooth 的目的在于帮助__非程序员__提高对游戏实时性能的消耗情况的理解，帮助美术更好地去做场景/角色/特效等资源的规划。

## 功能列表

- (连通性) 可通过 wifi 连接到手机或 Unity Editor 内正在运行的 App 
- (数据分析) 可显示__当前屏幕可见__的 Mesh / Material / Texture 三级信息列表
- (数据统计和排序) 所有列表中的信息都是可排序的，在 Texture 一栏可查到每张贴图的实际内存开销
- (依赖关系) 当双击这三个列表中的任意一项时，所有依赖项和被依赖项都会浅绿色高亮显示
- (编辑器互动) 使用 “定位物件” 功能可在编辑器的场景视图内定位并查看当前选中的物件
- (编辑器互动) 当在编辑器的场景视图内选中物件时，在 usmooth 内所有对应的依赖项都会浅蓝色高亮显示
- __(v0.2-new) 支持 Unity 5.0__
- __(v0.2-new) (游戏互动) 可以点击 Checkbox 来单独显示/隐藏屏幕上指定的物体__
- __(v0.2-new) (游戏互动) 游戏内的所有 Log 输出至 usmooth Log 窗口（提供过滤选项）__

## 运行情况截图

![main_ui](https://github.com/SeaSunOpenSource/usmooth/wiki/images/main_ui.png?raw=true)  

![running_screen](https://github.com/SeaSunOpenSource/usmooth/wiki/images/running_screen.png?raw=true)  


