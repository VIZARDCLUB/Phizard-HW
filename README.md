# Phizard-HW

The Phizard board is licensed under CERN Open Hardware Licence Version 2 - Strongly Reciprocal.  
This means that any changes made to the board should be made public and CHANGES.txt be updated to reflect said changes.  

The Phizard Link-V board is licensed under GPL-3.0 licence.  

Phizard has some added features based on PhobGCC 2.0.5.  
Currently works with [PhoZL](https://github.com/sean44104/PhoZL) firmware.  
![IMG_2520](https://github.com/VIZARDCLUB/Phizard-HW/assets/134335147/54af4208-bb35-46a4-88ca-e7e95654e258)  
![image](https://github.com/VIZARDCLUB/Phizard-HW/assets/134335147/83d506ce-dc8b-435e-b41e-be14c6ea5f8f)  
![image](https://github.com/VIZARDCLUB/Phizard-HW/assets/134335147/3473c820-71ee-499b-a177-d424e563db54)  
![image](https://github.com/VIZARDCLUB/Phizard-HW/assets/134335147/df654ec8-4677-4bfc-84fb-fe51693e88d6)  

# CHANGES.txt
- Original pad footprint for ABXY. Support 2pin DIP switches. Added holes for D2LS switches.  
- Original pad footprint for D-pad. Support SMD tact switches, D2LS switches and 2pin DIP switches.  
- Added thin tactile switch support to the START button.  
- Swap USB connecter to USB-C.  
- Added ZL button connected to GPIO12. Works with PhoZL firmware.  
- Fixed the Z/ZL footprint to fit right angle mouse switches.  
- Added breakout pad for Dup and Dleft for SoreiruFactory's Double LR Trigger.
- Added a 22ohm resister and a pad for 3.3V cell rumble.  
- Added Phizard Link-V based on OlyU-V. This supports Phob vision output. (I will make an adapter for it in the future.)
- PH connector can be used for LR pad without shell trimming

# Parts example
[H5.2mm Square micro switch](https://a.aliexpress.com/_on09e08) for ABXY and D-pad  
[D2LS-11](https://mou.sr/3ILtBsM) and the other switches that uses the same footprint for ABXY and Dpad  
[SKRRAAE010](https://mou.sr/3PtAZNg) and GBASP start button rubber for start (The edited shell will be published after tested)  

# Credit
## Main board
https://github.com/PhobGCC/PhobGCCv2-HW  
https://github.com/sean44104/phozl  

## USB features
https://github.com/Crane1195/Model-U  
https://github.com/sean44104/OlyU  
https://github.com/rana-sylvatica/OlyU-V  
