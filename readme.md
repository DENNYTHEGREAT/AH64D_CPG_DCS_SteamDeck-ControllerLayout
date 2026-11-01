# DCS AH-64D CPG Steam Input Layout
Custom Steam Input configuration for AH-64D CPG/Gunner optimized for HOTAS-style controller use.

Supports:
- Steam Deck (Tested with remote play)
- Steam Controller
Role: CPG/Gunner
Version: 1.3

Layout Overview:
<img width="1872" height="1051" alt="InputMapFull" src="https://github.com/user-attachments/assets/9adb05b6-d156-436c-bc1f-cbe584d2e112" />

## Design Philosophy
This layout prioritizes:
- Minimal keyboard usage for TEDAC Controls
- HOTAS-style muscle memory
- Left Bumper (L1), Right Bumper (R1), Back Right Botton (R5) as modifiers
- To be used along side HOTAS/HOSAS/HOCAS or standalone as a primary input CPG Role
- Allows quick role switching between Pilot and CPG without the need for CPG input mapping (There are a ton of buttons for TEDAC Controls using steam input to virtualize some of the buttons and switches allows the entire TEDAC Controlls to be mapped + George AI for those who fly solo as CPG)
- Due to a limitation with DCS layouts, only use one input modifier at a time. Using multiple modifiers will result in unexpected behavior and button pressing.

## Installation (Steam Community Config)
1. Open Steam
2. Go to Library
3. Right-click DCS World → Manage → Controller Layout
4. Browse Community Layouts
5. Search for: "AH64D - CPG Steam Deck/Controller V" Or 
6. Install using community steam input link: steam://controllerconfig/223750/3831655863  
7. Select and Apply
8. Optional but recommended, download the "AHButtons_SteamInput" folder and place the icons into the "C:\Program Files (x86)\Steam\tenfoot\resource\images\library\controller\binding_icons" location then you MUST restart steam to see those icons. Note: I have not been able to test this if images will be properly remapped from the steam input config + having them in the input folder location. (You might need to modify the steam controller layout to add each icon for the virtual menu)

## Required In-Game Settings
- The way things are bound might seem a little wacky... It uses a mix of controller inputs for axis controls and also uses keyboard inputs to map the additional buttons that cannot be bound using the controller.
- Install and import the controller scheme layout from the uploaded github files. This has everything needed to match the steam controller/deck layout.

## Versioning
V1.3 
  - Added ESC to the controller
V1.2
 - Fixed issues with first and second detent
V1.1
  - Initial release of this configuration

