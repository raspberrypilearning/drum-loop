## イントロ

まず、ドラムループの短いイントロから作りましょう。

+ まず、サンプル音源 (おんげん) `:drum_tom_hi_hard`を追加します。 入力し始めると、表示されるリストからサンプル音源 (おんげん) を選べます。
    
    ![スクリーンショット](images/drum-sample-help.png)

+ コードは次のようになります。
    
    ![スクリーンショット](images/drum-intro-1.png)
    
    sample（サンプル）の上にある`#`で始まる行は**コメント**です。 Sonic Pi はコメントを無視しますが、コードが何をするかを思い出したいときに便利です。

+ run をおすと、ドラムのサンプル音源 (おんげん) が聞こえます。
    
    ![スクリーンショット](images/drum-run.png)

+ ハイからローになるように、ドラムのサンプル音源 (おんげん) をさらに2つ追加します。 また、サンプル音源 (おんげん) ごとに1拍 (いっぱく) ずつ `sleep` する (休む) 必要があります。
    
    ![スクリーンショット](images/drum-intro-2.png)

+ もう一度イントロを実行すると、かなりおそいことが分かるでしょう。 1分あたりのビート (**bpm** - スピード) を変更するコードを追加しましょう。
    
    ![スクリーンショット](images/drum-bpm.png)

+ 最後に、イントロのいちばん後ろに `sleep` とサンプル音源 (おんげん) `:drum_splash_hard` を追加します。
    
    ![スクリーンショット](images/drum-intro-splash.png)

+ もう一度テストしてみましょう。 3つのドラムとシンバルの音が聞こえてくるはずです。
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-intro.mp3" type="audio/mpeg"> 
    お使いのブラウザは<code>audio</code>要素をサポートしていません。 
    </audio>
    </div>