## WLED 2D-gaps.json Generator


Try it here: <a href="https://intrinsically-sublime.github.io/WLED-2D-gaps.json-Generator/">WLED-2D-gaps.json-Generator<br></a>

### Other versions
WLED ledmap.json https://intrinsically-sublime.github.io/WLED-Ledmap.json-Generator/

FastLED XY remapper https://intrinsically-sublime.github.io/FastLED-XY-Map-Generator/

WLED Arbitrary Path Ledmap.json Generator https://intrinsically-sublime.github.io/WLED-Arbitrary-Path-Ledmap.json-Generator/

### About
* Normal mode allows 1 & 0 or 1 & -1 depending on the discard pixel option.
* Tri-State allows 1, 0, or -1 regardless of the discard pixel option.
  * Recommend using Normal for the majority and then change to tri-state when needed to reduce the clicks.

### How to use

<ol>
  <li>Configure the array by setting the maximum x and y dimensions and click Rebuild.<br>
  <li>Click the LEDs to edit the shape of the array by enabling, disabling or hiding pixels.<br>
  <li>Download the resulting "2d-gaps.json" file and upload it to your device via the webapp Settings/2D Configuration/upload<br>
</ol>


Based on<a href="https://github.com/Intrinsically-Sublime/FastLED-XY-Map-Generator"> XY-Map-Generator</a> by Intrinsically-Sublime
which is based on<a href="https://github.com/macetech/FastLED-XY-Map-Generator"> XY-Map-Generator</a> by Garrett Mace


![Screenshot](https://github.com/Intrinsically-Sublime/WLED-2D-gaps.json-Generator/blob/main/2d-gaps-mapper_screenshot.png)
