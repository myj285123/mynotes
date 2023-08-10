# 虚幻引擎的环境搭建

首先说明一下，虚幻的运行依赖于C++，构建则依赖于\.net，因此要搭建运行环境必须二者都装。  

1. 我们需要从[epic的官网: https://store.epicgames.com/zh-CN/](https://store.epicgames.com/zh-CN/)上下载epicgame的运行程序。  
2. 然后通过epicgame的运行程序装好虚幻以后，开始搭建代码运行环境  
    (1) 从 [**visual studio**](https://visualstudio.microsoft.com/zh-hans/vs/ "https://visualstudio.microsoft.com/zh-hans/vs/") 或着 [**visual studio code**](https://code.visualstudio.com/) 的官网下载对应的软件
    (2) 配置环境  
     如果你下载的是 **visual studio**，参考链接：[https://docs.unrealengine.com/5.2/zh-CN/setting-up-visual-studio-development-environment-for-cplusplus-projects-in-unreal-engine/](https://docs.unrealengine.com/5.2/zh-CN/setting-up-visual-studio-development-environment-for-cplusplus-projects-in-unreal-engine/)
        如果你下的是 **visual studio code** ，参考链接： [https://docs.unrealengine.com/5.2/zh-CN/setting-up-visual-studio-code-for-unreal-engine/](https://docs.unrealengine.com/5.2/zh-CN/setting-up-visual-studio-code-for-unreal-engine/)
    使用**visual studio code**还要下载 **C++** 和 **C#** 的扩展才能有正常的代码提示，还需要在虚幻引擎内部的编辑器配置丽的sourcecode去配置编辑器，然后再重新构建一下，下次就可以直接使用了。(虽然 **visual studio code** 启动很快，很轻量化，但是使用C++插件的时候还是有点消耗资源的)