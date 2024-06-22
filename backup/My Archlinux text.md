# 我在Archlinux下的使用感受
首先录屏软件OBS,免费且开源，非常适合录制做视频
媒体播放工具我在linux下推荐vlc和mpv,终端下配合使用cvlc和mpv,
mpv可能更适合我，在终端下一目了然
文本编辑器我有neovim,vscode,nano（个人不太喜欢）vi,非常推荐
neovim,高度自定义我还是好好学习vimshell和lua自己在写配置吧用的icevim,linux好用的安卓模拟器有genymotion,其他例如anbox,xdroid等都用过了，对了，还有一个waydroid,感觉这些都缺乏优化或Arm转译，剪辑我一直用的达芬奇，kdenlive,画图gimp,资源监视fastfetch htop,文件资源管理器一直用的Dolphin和ranger,终端我不喜欢konsole,以前用过iwm和dwm之后就特别喜欢alalcritty,kitty之类的
网络方面我装了dhcpcd,Watt-toolkit,以及大家都知道的霍格沃兹，浏览器首推Firefox,真的，他应该是我在linux wayland下运行的最好的浏览器了，记得force webrender, chromium浏览器在我这里显得特别臃肿，我也不喜欢，对wayland支持一般
## 游戏方面：
我在linux下的游戏有：hmcl,大名鼎鼎的mc启动器，建议Java运行环境找优化好的JDK,加上linux调度一直很好，所以不出意外的话应该比Windows下要流畅（不能保证一定）
2,wine（红酒）我用它玩过gtavc,gtasa,gta4,植物大战僵尸玩的也比较多，有beta,95未名，杂交，年度英文等，在我的机器上杂交版要全屏玩，并且勾选3D加速，我也不太懂为什么Kwin窗口会时不时冻结，一些加了Pak包的植物大战僵尸打了补丁也开不了，GTA4要玩加不了snt和汉化补丁，推荐设置窗口锁帧，加DXVK补丁，只能说Vulkan Yes！！！
也有运行的比较好的，例如CE修改器，ms excel等
3 genymotion,我用它来玩Eclise beta&alpha,shuttle,pvz2国际版等，一直很不错，调用OpenGL很流畅，保存模拟器要关机，否则你的pp.dat文件丢失，不要x掉窗口，找电源选项长按关机。
### 开发体验上
我首选vscode,neovim在某些场景下也并不高效，我个人感觉一般般（个人观点vim大佬勿喷）
Jetbrains家族体验过pycharm,idea,clion,rustrover,感觉还行，但很臃肿，之后我都卸了
我在linux下学习的语言有Rust,C,C++,Lua,（我没有语言歧视，只是觉得Rust在linux下运行的更好，C++配合cmake还可以，java,python,asm都试过，挺折腾的，用到的图形渲染接口Vulkan,Opengl,Vulkan跟着大佬也没学明白（能力有限），但Vulkan性能确实顶！
彩蛋：<iframe 
src="https://www.bilibili.com/video/BV17wVsedEwv/?spm_id_from=333.999.0.0&vd_source=36dcef7152e02daacd8b22d9ba8b5ea2" 
scrolling="no" 
border="0" 
frameborder="no" 
framespacing="0" 
allowfullscreen="true" 
height=600 
width=800> 
</iframe>

Docker也用过，但是例如winapps这样的占用资源好大
#### 好吧一个简短的的笔记就到这里吧，Thanks For Readering！！！