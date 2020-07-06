## O loop de bateria

Agora que você tem uma introdução, vamos codificar o loop principal da bateria!

+ O loop de bateria será composto de 4 samples, alternando o bumbo (o som mais grave da bateria) e a caixa (o som mais agudo da bateria).
    
    Adicione este código **após sua introdução**:
    
    ![captura de tela](images/drum-main.png)

+ Teste seu loop de bateria. Você deve ouvir 4 batidas após a introdução.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-1.mp3" type="audio/mpeg"> 
    Seu navegador não suporta o elemento de <code>áudio</code>. 
    </audio>
    </div>
+ Você pode repetir o loop da bateria adicionando `4.times do` antes de suas batidas e `end` no fim.
    
    ![captura de tela](images/drum-loop-bug.png)

+ Teste seu loop de bateria novamente e você perceberá que ele não soa muito bem. Isso porque você precisa adicionar um `sleep` após a batida final do loop.
    
    ![captura de tela](images/drum-loop-fix.png)

+ Teste seu código novamente. Desta vez, você deve ouvir suas 4 batidas repetidas 4 vezes.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-2.mp3" type="audio/mpeg"> 
    Seu navegador não suporta o elemento de <code>áudio</code>. 
    </audio>
    </div>
+ Para tornar seu loop de bateria um pouco mais interessante, você pode tocar o segundo bumbo **duas vezes**, por apenas **0,5** batida cada.
    
    ![captura de tela](images/drum-loop-double.png)

+ Teste seu código novamente. Você deve ouvir um ritmo diferente.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-3.mp3" type="audio/mpeg"> 
    Seu navegador não suporta o elemento de <code>áudio</code>. 
    </audio>
    </div>