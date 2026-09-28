# FilaCab

![FilaCab](https://github.com/Bunny350/FilaCab/blob/main/Media/filacab.png)

FilaCab is a 3-spool dry cabinet intended for storing FFF 3D printer filament spools with some Voron design. It contains parts derived from [V2, specifically my 150mm mod / OitswilliamV2](https://github.com/Bunny350/OitswilliamV2) and Voron Trident.

## Because there are no raw materials seen in the CAD, this lists (almost) all the raw materials.
* Side and back panel mounting brackets: 4X M3x10mm BHCS + 4X M3 T-wing or T-nuts per part, totaling 48X M3x10mm BHCS and 48X M3 T-wing or T-nuts,
* Top panel mounting brackets: 16X M3x8mm BHCS + 16X M3 T-wing or T-nuts,
* Panel shields (top and bottom): 4X M3x8mm SHCS + 4X M3 T-wing or T-nuts per part, totaling 32X M3x8mm SHCS and 32X M3 T-wing or T-nuts,
* Side shields (except back): 14X M3x6mm BHCS + 14X M3 T-wing or T-nuts and 2X M5x10mm BHCS + 2X M5 T-wing or T-nuts per side, totaling 38X M3x6mm, 38X M3 T-wing or T-nuts, 4X M5x10mm BHCS and 4X M5 T-wing or T-nuts,
* Back shield: 16X M3x6mm BHCS + 16X M3 T-wing or T-nuts,
* Front shield + frame-side door seal: 16X M3x8mm BHCS and 16X M3 T-wing or T-nuts,
* Dryer unit mounting: at least 4X M3x20mm BHCS + 4X M3 self-locking hex nuts,
* Filament holder with rollers (in case if it ever has MMU implemented): 12X F695 (ZZ or 2RS) bearings (inserted to the holders), 4X M5x10mm BHCS for mounting the roller to the bearings, 8X M3x12mm SHCS and 8X M3 T-wing or T-nuts
* Door seal magnets: Left 20X 6x3mm neodymium N35 magnets per side, Right 32X 6x3mm neodymium N35 magnets (the higher, the better), per side, totaling 104X of them.
  * Magnet placement guide: <img src="https://github.com/Bunny350/FilaCab/blob/main/Media/filacab_magnet_placement.svg" height="720"></img>
* File guides - CAD component
  * [ref] - reference material used for creating - do not print.
* File guides - printable parts
  * SIdes (after the part name), t - top, b - bottom, l - left, r - right. Some parts may use two-side combination i.e. tl\_br, meaning top-left, bottom-right.

## Development
The development began on 2023 with the first method being just heat, but the efficiency was too low with constant 200W, the second method replaces it with the Peltier, but it is also inefficient due to lacking of airflow. This is then changed to desiccant-based, which can drop to around 30%, or even around 20%.

This project has been released to the public because there are filament manufacturers began building filament dry cabinets, aside non-filament manufacturers have already been building these eons ago.

By using FilaCab, you agree to GNU GPLv3 which is available in the *LICENSE* document. FilaCab uses some parts from Voron 2, including the door hinge, some parts from Voron Trident, such as the feet, and [Snap Latch by richardjm](https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/richardjm/snap-latch-2020).
