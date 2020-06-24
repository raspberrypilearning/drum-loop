## حلقة الطبل

الآن بعد أن حصلت على مقدمة ، دعنا نبرمج حلقة الطبل الرئيسية!

+ وستتألف حلقة الطبل من 4 عينات بالتناوب بين (صوت الطبل الأدنى) و(صوت الطبل الأعلى).
    
    أضف هذا التعليمة البرمجية**بعد المقدمة الخاصة بك**:
    
    ![لقطة الشاشة](images/drum-main.png)

+ اختبر حلقة الطبل الخاصة بك. يجب أن تسمع 4 دقات طبل بعد المقدمة الخاصة بك.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-1.mp3" type="audio/mpeg">
    المتصفح الخاص بك لا يدعم هذا الجزء <code>الصوت </code>. 
    </audio>
    </div>
+ يمكنك تكرار حلقة الطبل الخاصة بك عن طريق إضافة `4.times do` قبل الطبول ونهاية `end` في النهاية.
    
    ![لقطة الشاشة](images/drum-loop-bug.png)

+ قم بتشغيل الطبول مرة أخرى ، وستلاحظ أنها لا تبدو صحيحة تمامًا. هذا لأنك تحتاج إلى إضافة `فاصل` بعد الطبل النهائي في التعليمة البرمجية تكرار.
    
    ![لقطة الشاشة](images/drum-loop-fix.png)

+ اختبر التعليمة البرمجية الخاصة بك مرة أخرى. هذه المرة يجب ان تسمع 4 اصوات وتكرار 4 مرات.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-2.mp3" type="audio/mpeg">
    المتصفح الخاص بك لا يدعم عنصر <code>الصوت </code>. 
    </audio>
    </div>

+ لجعل حلقة الطبل أكثر إثارة للاهتمام ، يمكنك تشغيل الطبل الثاني **مرتين** ، يدق كل منهما لمدة**0.5** فقط.
    
    ![لقطة الشاشة](images/drum-loop-double.png)

+ اختبر التعليمة البرمجية الخاصة بك مرة أخرى. يجب أن تسمع إيقاعًا مختلفًا.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-3.mp3" type="audio/mpeg">
    المتصفح الخاص بك لا يدعم هذا الجزء <code>الصوت </code>. 
    </audio>
    </div>