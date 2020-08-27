## 드럼 루프 만들기

이제 인트로가 있으므로 메인 드럼 루프를 코딩해보겠습니다!

+ 드럼 루프는 베이스(낮은 드럼 사운드)와 스네어(높은 드럼 사운드)를 번갈아 가며 4개의 샘플로 구성됩니다.
    
    **인트로 이후**에 이 코드를 추가하세요:
    
    ![스크린샷](images/drum-main.png)

+ 드럼 루프를 테스트하세요. 인트로 후에 4개의 드럼 비트가 들려야합니다.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
       <source src="resources/drums-loop-1.mp3" type="audio/mpeg"> 브라우저가 <code>오디오</code>를 지원하지 않습니다. 
     </audio>
    </div>
+ 드럼 샘플 앞에 `4.times do`를 추가하고 뒤에 `end`를 추가하여 드럼 루프를 반복할 수 있습니다.
    
    ![스크린샷](images/drum-loop-bug.png)

+ 드럼을 다시 재생하면 제대로 들리지 않는 것을 알 수 있습니다. 이는 루프의 마지막 드럼 다음에 `sleep`를 추가하지 않았기 때문입니다.
    
    ![스크린샷](images/drum-loop-fix.png)

+ 코드를 다시 테스트 해 보세요. 이번에는 4개의 드럼 비트가 4번 반복되는 소리가 들려야 합니다.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-2.mp3" type="audio/mpeg"> 브라우저가 <code>오디오</code> 를 지원하지 않습니다. 
    </audio>
    </div>
+ 드럼 루프를 좀 더 재미있게 만들려면 두 번째 베이스 드럼을 각각 **0.5**박자로 **두 번** 연주 할 수 있습니다.
    
    ![스크린샷](images/drum-loop-double.png)

+ 코드를 다시 테스트 해 보세요. 다른 리듬이 들릴 것입니다.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/drums-loop-3.mp3" type="audio/mpeg"> 브라우저가 <code>오디오</code>를 지원하지 않습니다. 
    </audio>
    </div>