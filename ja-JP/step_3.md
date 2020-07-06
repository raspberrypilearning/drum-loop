## ドラムループ

イントロができたので、メインのドラムループをコーディングしましょう！

+ ドラムループは4つのサンプル音源 (おんげん) で構成され、ベース (低音) とスネア (高音) をこうごに鳴らします。
    
    **イントロの後ろに**このコードを追加します。
    
    ![スクリーンショット](images/drum-main.png)

+ ドラムループをテストしましょう。 イントロの次に4つのドラムの音が聞こえるはずです。
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-1.mp3" type="audio/mpeg"> 
    お使いのブラウザは<code>audio</code>要素をサポートしていません。 
    </audio>
    </div>
+ ドラムループをくり返すには、ドラムの前に`4.times do` (4回くり返す) を、最後に `end` (終わり) を追加します。
    
    ![スクリーンショット](images/drum-loop-bug.png)

+ もう一度ドラムを鳴らすと、音が少しおかしいことが分かります。 ループの最後のドラムの後に `sleep` を追加する必要があるからです。
    
    ![スクリーンショット](images/drum-loop-fix.png)

+ もう一度テストしてみましょう。 今度は4つのドラムの音が4回くり返されます。
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-2.mp3" type="audio/mpeg"> 
    お使いのブラウザは<code>audio</code>要素をサポートしていません。 
    </audio>
    </div>
+ 2つ目のバスドラムを**2回**、それぞれ**0.5拍**ずつ鳴らしてドラムループをもう少し楽しくしてみましょう。
    
    ![スクリーンショット](images/drum-loop-double.png)

+ もう一度テストしてみましょう。 ちがうリズムが聞こえます。
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-3.mp3" type="audio/mpeg"> 
    お使いのブラウザは<code>audio</code>要素をサポートしていません。 
    </audio>
    </div>