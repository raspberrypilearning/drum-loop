## La intro (introduzione)

Iniziamo creando una breve introduzione al giro di batteria.

+ Inizia aggiungendo il campione `:drum_tom_hi_hard`. Se inizi a digitare, dovresti essere in grado di scegliere il campione dall'elenco che appare.
    
    ![screenshot](images/drum-sample-help.png)

+ Il tuo codice dovrebbe essere più o meno così:
    
    ![screenshot](images/drum-intro-1.png)
    
    La linea sopra il campione che inizia con `#` è un **commento**. Queste linee sono ignorate da Sonic Pi, ma sono utili per quando vogliamo ricordare a noi stessi cosa fa il nostro codice!

+ Premi run e dovresti ascoltare il tuo campione di batteria.
    
    ![screenshot](images/drum-run.png)

+ Aggiungi altri 2 campioni di batteria, in modo che vadano dall'alto verso il basso. Dovrai anche inserire uno `sleep` della durata di 1 battito tra ciascun campione.
    
    ![screenshot](images/drum-intro-2.png)

+ Se esegui di nuovo la tua intro, sentirai che è piuttosto lenta. È possibile aggiungere un codice per modificare i battiti al minuto (**bpm** - la velocità) della musica.
    
    ![screenshot](images/drum-bpm.png)

+ Infine, aggiungi uno `sleep` e un campione `:drum_splash_hard` alla fine dell'intro.
    
    ![screenshot](images/drum-intro-splash.png)

+ Prova di nuovo il tuo codice. Ora dovresti sentire 3 suoni di tamburo, seguiti da un piatto.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-intro.mp3" type="audio/mpeg"> Il tuo browser non supporta l'<code>audio</code>. </audio>
    </div>