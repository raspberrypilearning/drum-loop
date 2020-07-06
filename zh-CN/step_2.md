## 前奏

让我们从创作简单的鼓点前奏开始。

+ 首先添加`:drum_tom_hard`样本。 如果您开始键入，则应该能够从出现的列表中选择样本。
    
    ![截屏](images/drum-sample-help.png)

+ 现在你的代码应如图所示：
    
    ![截屏](images/drum-intro-1.png)
    
    样本上方以`＃`开始的一行是**评论** 。 这些行会被Sonic Pi忽略，但是当我们想提醒自己代码的作用时很有用！

+ 按下运行，您应该会听到一声鼓声。
    
    ![截屏](images/drum-run.png)

+ 再添加2个鼓点，让这三个鼓点的音量从高到低。 还要在每个鼓点之间添加停顿`sleep`。
    
    ![截屏](images/drum-intro-2.png)

+ 如果再次运行您就会发现前奏的速度已经很慢了。 您可以添加代码以更改音乐每分钟的节拍速度（**bpm** - 速度）。
    
    ![截屏](images/drum-bpm.png)

+ 最后，在前奏末尾添加一个`sleep`和一个`:drum_splash_hard`样品。
    
    ![截屏](images/drum-intro-splash.png)

+ 再次测试您的前奏。 您现在应该听到3声鼓声，然后是钹声。
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-intro.mp3" type="audio/mpeg"> 
    您的浏览器不支持 <code>audio</code> 元素。 
    </audio>
    </div>