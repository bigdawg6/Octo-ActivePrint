# Octo-ActivePrint
open port   
https://github.com/bigdawg6/OctoPrint-ActiveFilters/blob/dc26bfeb12b433067f673c591ec4d6129213e1e6/.github/workflows/main.yml
[Uploading apache maven-3.8.6-bin.zip.]() for files
[Ender-6 mainboard firmware.zip](https://github.com/bigdawg6/Octo-ActivePrint/files/9332107/Ender-6.mainboard.firmware.zip)
G28 G29
M220 S100
M221 S100
M104 S200
M140 S55
G0 Z25
G0 X0 Y0 wait for temp to rise
M190 R55
M109 S210 
G92 E0
G1 E0
G1 X0 Y20 Z0.28 F5000
G1 X0 Y200.0 Z0.28 F1500.0 E15
G1 X0.3 Y200.0 Z0.28 F5000.0 E30
G92 E0
G1 Z2.0 F3000
