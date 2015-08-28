#droiReverse

###这是一个android逆向工程工具的合集
+ [apktool](): 转成smali，以及反编译res资源
+ [dex2jar](https://github.com/pxb1988/dex2jar): dex转为jar工具
+ [jd-gui](http://jd.benow.ca/):
  + 用来查看.class文件
  + 有漂亮的gui界面
  
    ![](http://jd.benow.ca/img/screenshot17.png)

+ [jadx-gui](https://github.com/skylot/jadx/tree/master/jadx-gui/src/main/java/jadx/gui):     
    + 方便的jadx工具，可以直接反编译apk
    + 使用方法`jadx-gui x.apk`
+ [androguard](https://github.com/androguard/androguard): 
   + 可用python配置的反编译工具
   + 反编译DEX
   + 反编译资源
+ [enjarfy](https://github.com/google/enjarify)：
   + google的反编译工具
   + 可以将dalvik bytecode转化为java bytecode
   + 比dex2jar支持case更多
+ [jeb](https://www.pnfsoftware.com/)
   + 商业反编译软件(有demo版本免费)
   + 强大的将bytecode转为java代码的能力，对于循环等处理的很好
   + 支持动态编辑，重命名，添加新packag等
   + 支持python的api扩展
  
###TODO
1. 添加脚本，将所有工具加入到系统变量中
2. 使用git submodule
3. 英语翻译
   

##This project contain multiple tools for android reverse engineering
1. apktool: https://code.google.com/p/android-apktool
2. dex2jar: code.google.com/p/dex2jar
3. jd-gui : jd.benow.ca/



