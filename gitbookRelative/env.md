# 关于gitbook的安装环境

首先gitbook是npm的一个包，目前安装环境是**node 10.24.1**(目前测试的能正常运行的node版本)，为了方便起见最好还是使用**nvm**管理node版本以方便切换

安装好node之后全局安装gitbook


**执行如下代码:**  
```npm install gitbook-cli -g```  

**初始化gitbook**(不带bookname则是在当前目录下初始化)  

```gitbook init [bookname]```

**预览书籍**(一样会执行一次打包)  

```gitbook serve```

**打包成html**(这个可以打包到指定地方，暂时不写)  

```gitbook build```

**ps**: 以上代码用法未写完全

然后就可以快乐的写自己的笔记了


## VScode方面

安装**Markdown Preview**插件可以直接预览写好的效果，这样就可以暂时不用 **预览命令** 来预览 **(ps:因为预览命令好写并没有起到监听作用)**，写完直接进行打包部署就好了
