## De drumloop

Nu je een intro hebt, gaan we de drumloop zelf coderen!

+ De drumloop gaan we maken met 4 samples, afwisselend de basdrum (het lagere drumgeluid) en snaardrum (het hogere drumgeluid).
    
    Voeg deze code toe **na je intro**:
    
    ![schermafbeelding](images/drum-main.png)

+ Test je drumloop. Na je intro zou je 4 drumbeats moeten horen.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-loop-1.mp3" type="audio/mpeg"> Je browser ondersteunt het <code>audio</code>-element niet. </audio>
    </div>
+ Je kunt je drumloop herhalen door `4.times do` toe te voegen voor je drums en `end` aan het einde.
    
    ![schermafbeelding](images/drum-loop-bug.png)

+ Speel je drums weer af en je zult horen dat het niet helemaal goed klinkt. Dat is omdat je een `sleep` na de laatste drum in de loop moet toevoegen.
    
    ![schermafbeelding](images/drum-loop-fix.png)

+ Test je code opnieuw. Deze keer zou je je 4 drumbeats 4 keer herhaald moeten horen.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-loop-2.mp3" type="audio/mpeg"> Je browser ondersteunt het <code>audio</code>-element niet. </audio>
    </div>
+ Om je drumloop een beetje interessanter te maken, kun je de tweede basdrum **twee keer** spelen, beide keren maar een **0.5** (halve) beat durend.
    
    ![schermafbeelding](images/drum-loop-double.png)

+ Test je code opnieuw. Je zou een ander ritme moeten horen.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/drums-loop-3.mp3" type="audio/mpeg"> Je browser ondersteunt het <code>audio</code>-element niet. </audio>
    </div>