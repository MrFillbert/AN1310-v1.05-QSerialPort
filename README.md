# AN1310-v1.05-QSerialPort 
Requirements
QT5, W7 and more
#
Hi All!
Vlad Leschenko and Anton Zhukousky made this bootloader together. The project is based on Microchip's AN1310 bootloader's host application reference code and works on Qt5. The code was really tested with baudrate from 2400 to 115200 in PIC18F46k80 (16 MIPS). Old QextSerialPort has been replaced with Qt5's QSerialPort class. When run, the executable requires 'devices.db' file. Please obtain it from the original Microchip AN1310 source code.

The Original Source Code available here: http://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en546974

Best VL&AJ
