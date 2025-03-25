|     Font      |     Back      |
| ------------- | ------------- |
|![PCB Top design](https://github.com/<<repo_name>>/releases/download/<<tag>>/<<ID>>_<<project_name>>_<<version>>_PCBdraw_Top.png)|![PCB Back design](https://github.com/<<repo_name>>/releases/download/<<tag>>/<<ID>>_<<project_name>>_<<version>>_PCBdraw_Back.png)|

Fix critical Bugs with the serialUPDI and the power cycle Switch. 
The SerialUPDI resitor was incorrectly placed on the RX line and not on the TX line.
Pins for the power cycle pushbutton were wired incorrectly, this is now corrected.  

New
* Add DTR automatic switching
* Add Testpoints for ch340 pins

Changes
* correct power cycle switch pins
* correct serialUPDI resistor
* switch outputs of TS3USB30RSWR (D1<->D2) because of DTR signal Levels