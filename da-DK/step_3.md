## Trommeloopet
Nu hvor du har en intro, er det tid til at programmere hovedtrommeloopet!

+ Trommeloopet vil bestå af 4 samples og skifte mellem storetrommen (den dybe trommelyd) og lilletrommen (den lyse trommelyd).

    Tilføj denne kode __efter din intro__:

    ![screenshot](images/drum-main.png)

+ Test dit trommeloop. Du burde høre 4 trommeslag efter din intro.

    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload>
      <source src="resources/drums-loop-1.mp3" type="audio/mpeg">
    Din browser understøtter ikke <code>audio</code> elementet.
    </audio>
    </div>

+ Du kan gentage dit trommeloop ved at tilføje `4.times do` før dine trommer og `end` i slutningen.

    ![screenshot](images/drum-loop-bug.png)

+ Spil dine trommer igen og du vil bemærke, at det lyder ikke helt korrekt. Det er fordi at du er nødt til at tilføje en `sleep` efter den sidste tromme i loopet.

    ![screenshot](images/drum-loop-fix.png)

+ Test din kode igen. Denne gang burde du høre dine 4 trommeslag gentage 4 gange.

    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload>
      <source src="resources/drums-loop-2.mp3" type="audio/mpeg">
    Din browser understøtter ikke <code>audio</code> elementet.
    </audio>
    </div>

+ For at gøre dit trommeloop en smule mere interessant, kan du afspille den anden storetromme __to gange__, med kun __0.5__ slag efter hver.

    ![screenshot](images/drum-loop-double.png)

+ Test din kode igen. Du burde høre en anderledes rytme.

    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload>
      <source src="resources/drums-loop-3.mp3" type="audio/mpeg">
    Din browser understøtter ikke <code>audio</code> elementet.
    </audio>
    </div>
