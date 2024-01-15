<!-- vscode-markdown-toc -->
* 1. [Shader效果](#Shader)
	* 1.1. [games101笔记](#games101)
	* 1.2. [图形设置](#)
	* 1.3. [扫描效果](#-1)
	* 1.4. [护盾消融](#-1)
	* 1.5. [ 变换](#-1)
	* 1.6. [水纹](#-1)
	* 1.7. [水晶渐变-ase](#-ase)
	* 1.8. [屏幕颜色风格化处理](#-1)
	* 1.9. [屏幕-放射模糊](#-)
	* 1.10. [效果合集](#-1)
* 2. [框架/合集](#-1)
	* 2.1. [融合GF + YooAsset +luban](#GFYooAssetluban)
	* 2.2. [合集](#-1)
	* 2.3. [ReadMe语法](#ReadMe)
	* 2.4. [各种模板教程](#-1)
	* 2.5. [ET中使用的](#ET)
* 3. [序列化](#-1)
	* 3.1. [odin-serializer](#odin-serializer)
	* 3.2. [MessagePack-CSharp](#MessagePack-CSharp)
* 4. [UI解决方案](#UI)
	* 4.1. [1.UI特效优化](#UI-1)
	* 4.2. [2.一个dc绘制所有血条](#dc)
	* 4.3. [3.UI框架](#UI-1)
* 5. [联网](#-1)
	* 5.1. [双重编辑器](#-1)
	* 5.2. [C#服务器框架 国人开发](#C)
	* 5.3. [知名 C#服务器 SuperSocket , 3.7k star](#CSuperSocket3.7kstar)
	* 5.4. [联网-FPS](#-FPS)
	* 5.5. [本地文件服务器](#-1)
* 6. [热更](#-1)
* 7. [快速开发模板](#-1)
	* 7.1. [UI模板](#UI-1)
		* 7.1.1. [背包](#-1)
		* 7.1.2. [tab模板](#tab)
		* 7.1.3. [无尽scroll, 有点东西, 但不多](#scroll)
		* 7.1.4. [ui模板](#ui)
	* 7.2. [Unity商店示例项目](#Unity)
		* 7.2.1. [联网Fps - Multiplayer FPS Template](#Fps-MultiplayerFPSTemplate)
		* 7.2.2. [控制模板](#-1)
		* 7.2.3. [anyrpg模板 (包含ui和音效)](#anyrpgui)
		* 7.2.4. [rpg模板: Warrior Pack Bundle 2 FREE](#rpg:WarriorPackBundle2FREE)
		* 7.2.5. [Game Kit Controller : 付费游戏模板,功能较全](#GameKitController:)
* 8. [工具/神器](#-1)
	* 8.1. [1.编译](#-1)
		* 8.1.1. [1.ILSpy 反编译](#ILSpy)
		* 8.1.2. [2.dll 反编译](#dll)
		* 8.1.3. [3.反编译 加修改](#-1)
	* 8.2. [2.图像识别](#-1)
		* 8.2.1. [IronOcr C#图像识别](#IronOcrC)
		* 8.2.2. [tesseractOCR 开源图像识别, 可cmd执行](#tesseractOCRcmd)
	* 8.3. [3.vpn](#vpn)
		* 8.3.1. [0dcloud 零点云 (推荐)](#dcloud)
		* 8.3.2. [abc加速器](#abc)
	* 8.4. [4.Git工具](#Git)
		* 8.4.1. [Git Extensions](#GitExtensions)
		* 8.4.2. [SmartGit](#SmartGit)
		* 8.4.3. [GitHub Desktop (官方的工具 对网络不好时 有特攻吧)](#GitHubDesktop)
	* 8.5. [5.日常工具推荐](#-1)
		* 8.5.1. [DeskPins 窗口置顶工具](#DeskPins)
		* 8.5.2. [EasyCopy 复制粘贴板](#EasyCopy)
		* 8.5.3. [语雀  在线笔记 多端同步](#-1)
		* 8.5.4. [vscode - MarkDown插件](#vscode-MarkDown)
	* 8.6. [其他](#-1)
* 9. [美术资源](#-1)
	* 9.1. [音效](#-1)
	* 9.2. [模型](#-1)
	* 9.3. [AI绘图](#AI)
	* 9.4. [视频制作素材](#-1)
* 10. [少用但可能用到](#-1)
	* 10.1. [三维软件与Unity的完美协作工具](#Unity-1)
	* 10.2. [可能少用的但又很知名的框架](#-1)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Shader'></a>Shader效果
###  1.1. <a name='games101'></a>games101笔记
[https://zhuanlan.zhihu.com/p/394932478](https://zhuanlan.zhihu.com/p/394932478)
###  1.2. <a name=''></a>图形设置
[https://github.com/insthync/unity-graphic-settings](https://github.com/insthync/unity-graphic-settings)
###  1.3. <a name='-1'></a>扫描效果
[https://zhuanlan.zhihu.com/p/143788955](https://zhuanlan.zhihu.com/p/143788955)
###  1.4. <a name='-1'></a>护盾消融
[https://www.youtube.com/watch?v=jdAbVkre8cw](https://www.youtube.com/watch?v=jdAbVkre8cw)
###  1.5. <a name='-1'></a> 变换
[https://www.youtube.com/watch?v=zksLtFb2wAQ](https://www.youtube.com/watch?v=zksLtFb2wAQ)
###  1.6. <a name='-1'></a>水纹
[https://github.com/dtysky/paradise/tree/master/src/collection/ShaderWaterRipple](https://github.com/dtysky/paradise/tree/master/src/collection/ShaderWaterRipple)
 
###  1.7. <a name='-ase'></a>水晶渐变-ase
[https://www.bilibili.com/video/BV1s54y1e7bv](https://www.bilibili.com/video/BV1s54y1e7bv)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/35554785/1704852613881-a25eaf94-295f-4060-a4d2-480903360a45.png#averageHue=%234f4f59&clientId=u6caf3bf7-1c21-4&from=paste&height=306&id=u6866fd66&originHeight=306&originWidth=342&originalType=binary&ratio=1&rotation=0&showTitle=false&size=164533&status=done&style=none&taskId=u61dfc812-2837-4891-81ed-3d5bd9a612f&title=&width=342)

###  1.8. <a name='-1'></a>屏幕颜色风格化处理
[https://www.bilibili.com/video/BV1wh411U7ZK](https://www.bilibili.com/video/BV1wh411U7ZK)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/35554785/1704959054801-b47522ff-9db3-4556-a735-e4393175d6c4.png#averageHue=%23e90202&clientId=ubb1dee60-5b9f-4&from=paste&height=362&id=u8c685d30&originHeight=598&originWidth=1066&originalType=binary&ratio=1&rotation=0&showTitle=false&size=186795&status=done&style=none&taskId=u908a69f5-5c4a-4f07-ae3f-a9a56f94613&title=&width=646)

###  1.9. <a name='-'></a>屏幕-放射模糊
[https://www.bilibili.com/video/BV1By4y1B7ud](https://www.bilibili.com/video/BV1By4y1B7ud/)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/35554785/1704854240419-1a75c4ca-6604-430c-ab98-1bac997ae313.png#averageHue=%23636a7d&clientId=u6caf3bf7-1c21-4&from=paste&height=364&id=u74169b21&originHeight=608&originWidth=925&originalType=binary&ratio=1&rotation=0&showTitle=false&size=675590&status=done&style=none&taskId=u1da589e6-6a33-406b-a1a3-76a34af1048&title=&width=554)



###  1.10. <a name='-1'></a>效果合集
[https://github.com/csdjk/LearnUnityShader](https://github.com/csdjk/LearnUnityShader)
 描边、溶解、模糊等等，建议直接star了  
![111222.png](https://cdn.nlark.com/yuque/0/2024/png/35554785/1704962286393-826c573b-12c2-48e2-9398-b42532bc9712.png#averageHue=%2380a08d&clientId=ubb1dee60-5b9f-4&from=drop&id=ud24f41f8&originHeight=929&originWidth=478&originalType=binary&ratio=1&rotation=0&showTitle=false&size=702564&status=done&style=none&taskId=ua10a4808-8744-4f8a-952c-648d66c4eef&title=)

##  2. <a name='-1'></a>框架/合集
###  2.1. <a name='GFYooAssetluban'></a>融合GF + YooAsset +luban
[https://github.com/ALEXTANGXIAO/TEngine/tree/main](https://github.com/ALEXTANGXIAO/TEngine/tree/main)
###  2.2. <a name='-1'></a>合集
[https://zhuanlan.zhihu.com/p/591864923](https://zhuanlan.zhihu.com/p/591864923)
###  2.3. <a name='ReadMe'></a>ReadMe语法
[https://github.com/guodongxiaren/README](https://github.com/guodongxiaren/README)
###  2.4. <a name='-1'></a>各种模板教程
[https://deviongames.com/](https://deviongames.com/)
[https://assetstore.unity.com/publishers/955](https://assetstore.unity.com/publishers/955)

 
###  2.5. <a name='ET'></a>ET中使用的
Recast 服务器 C#寻路算法
[https://github.com/recastnavigation/recastnavigation](https://github.com/recastnavigation/recastnavigation)
[https://blog.51cto.com/u_16081664/6229076](https://blog.51cto.com/u_16081664/6229076)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35554785/1701704998290-6896d851-3977-498c-9edb-dfce776970d8.png#averageHue=%233c3c3c&clientId=u3a219914-8890-4&from=paste&height=141&id=u56aa2783&originHeight=194&originWidth=334&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=13095&status=done&style=none&taskId=ufb29f41b-5291-467c-9164-70b77e2fa87&title=&width=242.9090909090909)

##  3. <a name='-1'></a>序列化
###  3.1. <a name='odin-serializer'></a>odin-serializer
[https://github.com/TeamSirenix/odin-serializer](https://github.com/TeamSirenix/odin-serializer)
###  3.2. <a name='MessagePack-CSharp'></a>MessagePack-CSharp
[https://github.com/MessagePack-CSharp/MessagePack-CSharp](https://github.com/MessagePack-CSharp/MessagePack-CSharp)
##  4. <a name='UI'></a>UI解决方案
###  4.1. <a name='UI-1'></a>1.UI特效优化
Particle Effect For UGUI(UI Particle)
性能更好的ui特效解决方案
->Mesh
[https://github.com/mob-sakai/ParticleEffectForUGUI](https://github.com/mob-sakai/ParticleEffectForUGUI)
###  4.2. <a name='dc'></a>2.一个dc绘制所有血条
[https://github.com/sinbad/UnityInstancedHealthBars](https://github.com/sinbad/UnityInstancedHealthBars)

###  4.3. <a name='UI-1'></a>3.UI框架
[https://github.com/Skierhou/UISystem](https://github.com/Skierhou/UISystem)
其中包含
绑定
[https://github.com/Misaka-Mikoto-Tech/UIControlBinding](https://github.com/Misaka-Mikoto-Tech/UIControlBinding)
滚动列表
[https://github.com/qiankanglai/LoopScrollRect](https://github.com/qiankanglai/LoopScrollRect)

简单UI框架 BV1Bz4y1D7rL
[https://gitee.com/friendlyA/XFramework/tree/master](https://gitee.com/friendlyA/XFramework/tree/master)

##  5. <a name='-1'></a>联网
###  5.1. <a name='-1'></a>双重编辑器
[https://assetstore.unity.com/packages/tools/utilities/multiplay-170209](https://assetstore.unity.com/packages/tools/utilities/multiplay-170209)

###  5.2. <a name='C'></a>C#服务器框架 国人开发
[https://github.com/qq362946/Fantasy](https://github.com/qq362946/Fantasy)

[https://www.fantsida.com/fantasy/docs/index.html](https://www.fantsida.com/fantasy/docs/index.html)

###  5.3. <a name='CSuperSocket3.7kstar'></a>知名 C#服务器 SuperSocket , 3.7k star
[https://github.com/kerryjiang/SuperSocket](https://github.com/kerryjiang/SuperSocket)

###  5.4. <a name='-FPS'></a>联网-FPS
[https://www.youtube.com/watch?v=fVotjwJQ5zM](https://www.youtube.com/watch?v=fVotjwJQ5zM)

[https://github.com/tom-weiland](https://github.com/tom-weiland)

###  5.5. <a name='-1'></a>本地文件服务器
EasyWebSvr

##  6. <a name='-1'></a>热更
[https://github.com/Tencent/InjectFix/blob/master/Doc/user_manual.md](https://github.com/Tencent/InjectFix/blob/master/Doc/user_manual.md)
##  7. <a name='-1'></a>快速开发模板
###  7.1. <a name='UI-1'></a>UI模板
####  7.1.1. <a name='-1'></a>背包
[https://github.com/NovaUI-Unity/GridInventorySample](https://github.com/NovaUI-Unity/GridInventorySample)
![b29cz918.bmp](https://cdn.nlark.com/yuque/0/2024/bmp/35554785/1704174939367-0249af73-2450-474c-987c-f239a404a72f.bmp#averageHue=%23595137&clientId=u052ed908-846d-4&from=drop&id=WjQ7t&originHeight=360&originWidth=480&originalType=binary&ratio=1&rotation=0&showTitle=false&size=691254&status=done&style=none&taskId=u48baa891-0cd8-4458-907f-b1afeb898b4&title=)
####  7.1.2. <a name='tab'></a>tab模板
[https://github.com/herbou/Unity_TabsUI](https://github.com/herbou/Unity_TabsUI)
![gr9k4aa0.bmp](https://cdn.nlark.com/yuque/0/2024/bmp/35554785/1704175590316-53e07b9b-5675-4e25-8404-43fdeeea8eb0.bmp#averageHue=%23e6de7b&clientId=u052ed908-846d-4&from=drop&id=Ns7TC&originHeight=360&originWidth=480&originalType=binary&ratio=1&rotation=0&showTitle=false&size=691254&status=done&style=none&taskId=u32cc4c0c-8d2c-4c68-9047-f4392a69914&title=)
####  7.1.3. <a name='scroll'></a>无尽scroll, 有点东西, 但不多
[https://github.com/GabrielReisESilva/UnityUIInfiniteScrollCarouselMenu](https://github.com/GabrielReisESilva/UnityUIInfiniteScrollCarouselMenu)

unity商店

[https://assetstore.unity.com/?free=true&q=ui&orderBy=1](https://assetstore.unity.com/?free=true&q=ui&orderBy=1)

####  7.1.4. <a name='ui'></a>ui模板
[https://assetstore.unity.com/packages/tools/gui/3d-modern-menu-ui-116144](https://assetstore.unity.com/packages/tools/gui/3d-modern-menu-ui-116144)
![wim72cz9.bmp](https://cdn.nlark.com/yuque/0/2024/bmp/35554785/1704176426959-120c6995-d195-4e49-a526-768decf4f40a.bmp#averageHue=%231d1d15&clientId=u052ed908-846d-4&from=drop&id=MK9zV&originHeight=1080&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=8294454&status=done&style=none&taskId=u24166ee2-e702-46fb-be99-9a25e102624&title=)
背包模板 & 角色控制器
[https://assetstore.unity.com/packages/tools/gui/item-inventory-system-45568](https://assetstore.unity.com/packages/tools/gui/item-inventory-system-45568)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/35554785/1704176670511-45d422ac-8137-456d-bb17-e6dd06f0d887.png#averageHue=%23212b35&clientId=u052ed908-846d-4&from=paste&height=325&id=ccLQj&originHeight=325&originWidth=650&originalType=binary&ratio=1&rotation=0&showTitle=false&size=158854&status=done&style=none&taskId=u8501ee6b-d29a-4100-8697-692aa6232a9&title=&width=650)
好思路
![oqnqax6a.bmp](https://cdn.nlark.com/yuque/0/2024/bmp/35554785/1704176923947-87f5a3d7-f523-481c-884e-8912ee68e4a4.bmp#averageHue=%23d4d5db&clientId=u052ed908-846d-4&from=drop&id=Y76rv&originHeight=800&originWidth=1200&originalType=binary&ratio=1&rotation=0&showTitle=false&size=3840054&status=done&style=none&taskId=u5bb8ef6a-a8e6-4789-8f39-65c6da5732a&title=)

###  7.2. <a name='Unity'></a>Unity商店示例项目
####  7.2.1. <a name='Fps-MultiplayerFPSTemplate'></a>联网Fps - Multiplayer FPS Template
[https://assetstore.unity.com/packages/templates/systems/multiplayer-fps-template-259143](https://assetstore.unity.com/packages/templates/systems/multiplayer-fps-template-259143)

####  7.2.2. <a name='-1'></a>控制模板
##### topDown-移动端控制模板
[https://assetstore.unity.com/packages/templates/systems/top-down-mobile-controller-3d-255121](https://assetstore.unity.com/packages/templates/systems/top-down-mobile-controller-3d-255121)

##### 移动端控制-第一人称模板 
[https://assetstore.unity.com/packages/tools/utilities/dynamic-first-person-mobile-controller-kit-221202](https://assetstore.unity.com/packages/tools/utilities/dynamic-first-person-mobile-controller-kit-221202)

##### 移动端输入模板
[https://assetstore.unity.com/packages/tools/input-management/touch-controls-kit-lite-41395](https://assetstore.unity.com/packages/tools/input-management/touch-controls-kit-lite-41395)
##### 移动端输入模板2
[https://assetstore.unity.com/packages/tools/input-management/ujoystick-49186](https://assetstore.unity.com/packages/tools/input-management/ujoystick-49186)

####  7.2.3. <a name='anyrpgui'></a>anyrpg模板 (包含ui和音效)
[https://assetstore.unity.com/packages/templates/systems/anyrpg-core-234361#description](https://assetstore.unity.com/packages/templates/systems/anyrpg-core-234361#description)

####  7.2.4. <a name='rpg:WarriorPackBundle2FREE'></a>rpg模板: Warrior Pack Bundle 2 FREE
[https://assetstore.unity.com/packages/3d/animations/warrior-pack-bundle-2-free-42454](https://assetstore.unity.com/packages/3d/animations/warrior-pack-bundle-2-free-42454)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/35554785/1704215946420-b8424821-6dfb-4123-bcae-e6e54b4457de.png#averageHue=%23484646&clientId=ud75f38b0-7710-4&from=paste&height=460&id=EKVEr&originHeight=633&originWidth=1110&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=401974&status=done&style=none&taskId=u3d335d56-6545-47f1-a3dc-97bd8a93367&title=&width=807.2727272727273)


####  7.2.5. <a name='GameKitController:'></a>Game Kit Controller : 付费游戏模板,功能较全

##  8. <a name='-1'></a>工具/神器
###  8.1. <a name='-1'></a>1.编译
####  8.1.1. <a name='ILSpy'></a>1.ILSpy 反编译
[https://github.com/icsharpcode/ILSpy](https://github.com/icsharpcode/ILSpy)
####  8.1.2. <a name='dll'></a>2.dll 反编译
打开 Developer Command Prompt for vs 2019
dumpbin /exports xxxx.dll
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35554785/1693049828479-99e699bf-daf4-4ccf-950e-539ce9921e07.png#averageHue=%232d2724&clientId=u1de4d3a4-ecd5-4&from=paste&height=131&id=u0049ac5c&originHeight=131&originWidth=286&originalType=binary&ratio=1&rotation=0&showTitle=false&size=9066&status=done&style=none&taskId=u093de0d4-4a0e-41cf-8c0b-f00cb0c6b17&title=&width=286)

####  8.1.3. <a name='-1'></a>3.反编译 加修改
[https://github.com/dnSpy/dnSpy](https://github.com/dnSpy/dnSpy)

###  8.2. <a name='-1'></a>2.图像识别
####  8.2.1. <a name='IronOcrC'></a>IronOcr C#图像识别
[https://ironsoftware.com/csharp/ocr/#trial-license-after-download](https://ironsoftware.com/csharp/ocr/#trial-license-after-download)
####  8.2.2. <a name='tesseractOCRcmd'></a>tesseractOCR 开源图像识别, 可cmd执行
[https://github.com/UB-Mannheim/tesseract](https://github.com/UB-Mannheim/tesseract)

###  8.3. <a name='vpn'></a>3.vpn
####  8.3.1. <a name='dcloud'></a>0dcloud 零点云 (推荐)
[https://www.0dianyun14.xyz/](https://www.0dianyun14.xyz/)
####  8.3.2. <a name='abc'></a>abc加速器

###  8.4. <a name='Git'></a>4.Git工具
####  8.4.1. <a name='GitExtensions'></a>Git Extensions
####  8.4.2. <a name='SmartGit'></a>SmartGit
####  8.4.3. <a name='GitHubDesktop'></a>GitHub Desktop (官方的工具 对网络不好时 有特攻吧)
###  8.5. <a name='-1'></a>5.日常工具推荐
####  8.5.1. <a name='DeskPins'></a>DeskPins 窗口置顶工具
[https://efotinis.neocities.org/deskpins/](https://efotinis.neocities.org/deskpins/)
####  8.5.2. <a name='EasyCopy'></a>EasyCopy 复制粘贴板
[https://github.com/smartgrass/EasyCopy-WinFrom](https://github.com/smartgrass/EasyCopy-WinFrom)
####  8.5.3. <a name='-1'></a>语雀  在线笔记 多端同步

####  8.5.4. <a name='vscode-MarkDown'></a>vscode - MarkDown插件
Markdown Preview Enhanced
MarkDown TOD 自动生成目录
###  8.6. <a name='-1'></a>其他
nuget位置
C:\Users\admin\.nuget\packages

##  9. <a name='-1'></a>美术资源
###  9.1. <a name='-1'></a>音效
搜索royalty free BGM sites

注意版权要求, 有的是禁止商用, 有的是需要注明出处

[https://www.soundsnap.com/](https://www.soundsnap.com/search/audio?query=magic&page=2)

[https://freesound.org/](https://freesound.org/)

[https://www.zapsplat.com/](https://www.zapsplat.com/page/3/?s=sword+hit&post_type=music&sound-effect-category-id)

音效收藏 可爱
[https://freesound.org/people/lemonjolly/](https://freesound.org/people/lemonjolly/)

###  9.2. <a name='-1'></a>模型
角色模型
 [https://hub.vroid.com](https://hub.vroid.com) 
模型
[https://poly.pizza/](https://poly.pizza/)
卡通风模型+ui+音效
[https://kenney.nl/](https://kenney.nl/)

模型,原型都有,但界面简陋
[https://opengameart.org/](https://opengameart.org/)

###  9.3. <a name='AI'></a>AI绘图
midjourney

###  9.4. <a name='-1'></a>视频制作素材
[https://pixabay.com/sound-effects/](https://pixabay.com/sound-effects/)

##  10. <a name='-1'></a>少用但可能用到
###  10.1. <a name='Unity-1'></a>三维软件与Unity的完美协作工具
[https://github.com/Unity-Technologies/MeshSyncDCCPlugins](https://github.com/Unity-Technologies/MeshSyncDCCPlugins)


###  10.2. <a name='-1'></a>可能少用的但又很知名的框架
知名的unity注入框架
[https://github.com/modesttree/Zenject/releases](https://github.com/modesttree/Zenject/releases)

[https://github.com/neuecc/UniRx/releases](https://github.com/neuecc/UniRx/releases)

