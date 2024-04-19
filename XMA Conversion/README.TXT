NEEDS: 
-SDK/XDK installed [https://archive.org/details/xbox-360-xenon-recovery-xdk-setup]
-Audacity (another prog might work, but this is what i use, and is FREE)    
-Some MP3's
-Half a brain 

STEPS: 
(i) Copy xma2encode from SDK install directory to "C:/Windows/System32/".
(ii) Open Audacity, File->Open (or Ctrl+O), select MP3.﻿
(iii) File->Export Audio (or Ctrl+Shift+E), save as "song#.wav" for convienece (# = 1-8), and select "WAV (Microsoft) signed 16-bit PCM" as "SAVE AS TYPE:"
(iv) Navigate to where you stored the "song#.wav" and open terminal from that folder
(v) Type "xma2encode song#.wav﻿" in Terminal
                          OR 
    Type "xwmaencode *.wav *.xma﻿". The *'s are for what ever names you chose
(vi) Wait for it to convert, there is no progress bar, but will produce "song#.xma" when finished, as well as bring up another input line


