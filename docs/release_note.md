|     Font      |     Back      |
| ------------- | ------------- |
|![PCB Top design](https://github.com/<<repo_name>>/releases/download/<<tag>>/<<ID>>_<<project_name>>_<<version>>_PCBdraw_Top.png)|![PCB Back design](https://github.com/<<repo_name>>/releases/download/<<tag>>/<<ID>>_<<project_name>>_<<version>>_PCBdraw_Back.png)|

Version bump due to changed pinout of the J1 connector. 
Otherwise only small updates. 
Stencil of Version v1.0 is still valid but with the downside of USB Type-C Tabs not geting soldered. 

New
-

Changes
* Add missing Pin 1 markers
* Update USB Type-C Footprint to include correct Stencil Data (Tabs had no solder - needed to be soldered by hand)
* exclude the unneeded switch from BOM. Is not needed due to the automatic switch over
* minor refactoring of Schematic and PCB

Breaking Changes
* Pinout of the J1 connector (changed to GLL1 Standard)

