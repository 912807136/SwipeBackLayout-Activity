# SwipeBackLayout-Activity
SwipeBackLayout侧滑关闭Activity<br/>
目前大部分的APP都支持侧滑关闭Activity及切换Activity的动画效果，这些效果极大的提高了用户体验。其它实现方式也比较简单，能够很方便的集成到我们的项目里，所以做了一个Demo分享给大家参考。

注意点：
1.右滑的时候，下面出现的背景不是前一个activity，而是黑色背景，解决方式是activity或者application的theme设置背景色透明.
<item name= "android:windowIsTranslucent" >true </item>
2.当activity不需要侧滑关闭时,setEnableGesture(false);<br/><br/>
![image](http://img.blog.csdn.net/20150427232218409?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQveGllY2hlbmdmYQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)
