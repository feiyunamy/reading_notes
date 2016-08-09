#Android drawable细节问题#

----------

**mimap**文件夹是Android Studio中用来存放icon图片的，将icon放置在mipmap文件夹可以让我们程序的launcher图标自动拥有跨设备密度展示的能力，比如说一台屏幕密度是xxhdpi的设备可以自动加载mipmap-xxxhdpi下的icon来作为应用程序的launcher图标，这样图标看上去就会更加细腻。icon在不密度屏幕下的建议尺寸如下:

>![Aaron Swartz](https://github.com/feiyunamy/readindnotes_pic/blob/master/1.png?raw=true)

不同屏幕dpi所对应的密度范围大致如下:
>![Aaron Swartz](http://img.mukewang.com/572af9ce0001640509550271.png)