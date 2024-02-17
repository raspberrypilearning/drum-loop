## Il giro di batteria

Ora che hai un'introduzione, creiamo il codice del giro di batteria principale!

+ Il giro di batteria sarà composto da 4 campioni, alternando i bassi (il suono di batteria più basso) e il rullante (il suono di batteria più alto).
    
    Aggiungi questo codice **dopo la tua intro**:
    
    ![screenshot](images/drum-main.png)

+ Prova il tuo giro di batteria. Dovresti sentire 4 colpi di tamburo dopo la tua intro.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-loop-1.mp3" type="audio/mpeg"> Il tuo browser non supporta l'<code>audio</code>. </audio>
    </div>
+ Puoi ripetere il tuo giro di batteria aggiungendo `4.times do` prima dei tamburi e `end` alla fine.
    
    ![screenshot](images/drum-loop-bug.png)

+ Riproduci di nuovo la batteria, e noterai che non suonano in modo corretto. Questo perché è necessario aggiungere uno `sleep` dopo il tamburo finale all'interno del ciclo.
    
    ![screenshot](images/drum-loop-fix.png)

+ Prova di nuovo il tuo codice. Questa volta dovresti sentire i tuoi 4 tamburi ripetersi 4 volte.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-loop-2.mp3" type="audio/mpeg"> Il tuo browser non supporta l'<code>audio</code>. </audio>
    </div>
+ Per rendere il tuo giro di batteria un po' più interessante, puoi suonare la seconda grancassa **due volte**, per **0.5 ** battute ciascuna.
    
    ![screenshot](images/drum-loop-double.png)

+ Prova di nuovo il tuo codice. Dovresti sentire un ritmo diverso.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-loop-3.mp3" type="audio/mpeg"> Il tuo browser non supporta l'<code>audio</code>. </audio>
    </div>