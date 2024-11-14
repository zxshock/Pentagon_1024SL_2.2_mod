# Pentagon_1024SL_2.2_mod
Pentagon 1024SL 2.2 Modification by shock__

Based upon the gerbers by KOE found here:
https://github.com/koe1234/pentagon_2.2/

Original license here:
http://pentagon.nedopc.com/disclaimer.htm#!!!%20%D0%94%D0%B8%D1%81%D0%BA%D0%BB%D0%B0%D0%B9%D0%BC%D0%B5%D1%80

Changes are minor:
- added top silkscreen layer
- corrected silkscreen VD22 (previously VD27 which existed twice) and C45 (had a drawn footprint but no label)
- added 4pin Molex connector for power
- added optional circuits for Tape-In and 2 additional LEDs (Turbo, 1MB) in the breadboard area - they are connected via wires on the underside of the board.
- changed "DEATH TO NATO" to "DEATH TO NATO AND FASCISTS"
- added small credits on the silkscreen layer

 Otherwise the layout is unchanged, successfully prototyped on 14th of November 2024
 Gerbers were imported in Sprintlayout, soldermask redone (since it can't be imported) and the silkscreen drawn manually.

 Tested: 3.5/7.0MHz modes, 1024/128/48k modes, 16c modes, RGB out, LPT out (covox only), Kempston Joystick, Palcoder/composite out, RAM test for 12 hours, tape-in, LEDs, NemoBus with Z-Controller/ZXM-GS/GS (fixed for Pentagon 1024SL 2.2), TSFM
 Not tested: onboard audio amp, in-circuit programming of CPLDs
