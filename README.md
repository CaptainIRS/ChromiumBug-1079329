# Chromium Bug #1079329

#### Unexpected glitches(flickers) in the ends/caps of animated arc strokes

https://bugs.chromium.org/p/chromium/issues/detail?id=1079329

**Category** : Blink > Canvas

(Star the bug if you find it in your browser)

## Details:
#### Steps to reproduce:
* Visit https://jsfiddle.net/djfn2pyk/
#### What is the expected behavior?
The ends of the arc strokes must be consistent. 
This works just fine in non-Chromium based browsers(including IE). The bug is present in Chrome, Opera and the new MS Edge(Tested).

The bug and expected behaviour(captured using Firefox) are attached.

#### What went wrong?
Random unexpected glitches/flickers occur in the ends of animated arc strokes
The glitch is significantly visible when lineCap property of canvas is set to 'butt' or 'square'.

**Did this work before?** N/A 

**Does this work in other browsers?** Yes

**Chrome version:** 81.0.4044.129  **Channel:** stable

**OS Version:** 10.0