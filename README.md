<div align="center">
<h1>📡 MTL-2: Portable High-Power LoRa node</h1>
  <img src="03-pic/08.jpg" alt="08" width="30%"> <img src="03-pic/22.jpg" alt="22" width="32%">

<div align="left">
  
  ## MTL-2
MTL-2 - Это портативное энергоэкономичное устройство, основанное на модулях [Ebyete](https://www.ebyte.com/) и ProMicro (NRF52840). Предназначено для работы в [MeshCore](https://github.com/meshcore-dev), [Meshtastic](https://github.com/meshtastic), в качестве клиента и ретранслятора.

 
  
##  Ключевые особенности
* LoRa 30-31dBm
* Oled 1.3'
* Buzzer
* Switch Buzzer/Led (Quiet mode)
* Switch POWER set Low/Hight (20dBm/30dBm)
* Vibro-notification
* 3-position multifuctional switch or 3 button
* Connector for GPS-module like VK2828U7G5LF
* 1A Standalone Linear Li-Ion Battery Charger
* Battery protection lithium-ion/polymer battery
* Li-Ion cell holder 2x18650 TBH-18650-2A-P (FC1-5212)

##  Органы управления
<img src="03-pic/16.jpg" alt="interface1" width="10%"><img src="03-pic/17.jpg" alt="interface2" width="10%"><img src="03-pic/18.jpg" alt="interface3" width="10%">


##  Software MeshCore
The software was developed by [VladelfPv](https://github.com/VladelfPv)  [MTLmicro](https://github.com/VladelfPv/MeshCoreMTL.git) 

##  Software Meshtastic
Use the J9 jumper for compatibility with FakeTec. In this case, DC-DC Up remains constantly on, which will increase battery consumption to 10mA.

As a jumper, you can use the chip ferrite beads like BLM21PG221SN1D, BLM21PG121SH1D etc 
Оther settings are configured in the Meshtastic software.

GPIO: 
- 6-Buzzer.
- 8-Vibro.

<img src="03-pic/14-ProMicro-J9.jpg" alt="FakeTec" width="30%"><img src="03-pic/19.jpg" alt="FakeTec2" width="12%">

##  Update Software 
To update the Software, click the RESET button twice. In the window that opens, copy the firmware file xxxxx.uf2

<img src="03-pic/16.jpg" alt="interface1" width="20%">

### Frequency range
#### 150-170Mhz
- e22-170m30s    SX1268  30dBm

#### 430Mhz
- e22p-433m30s   SX1268          30dBm
- e22-400m30s    SX1262, SX1268  30dBm 
- e22-400m33s    SX1268          33dBm
<img src="03-pic/e22p-433m30s.jpg" alt="mtle22p433" width="20%">


#### 868-915Mhz
- e22p-868m30s   SX1262  31dBm
- e22p-915m30s   SX1262  31dBm 
- e22-900m30s    SX1262  30dBm
- e22-900m33s    SX1262  33dBm

<img src="03-pic/e22p-868m30s.jpg" alt="mtle22p868" width="20%">

##  Files
*[Gerber and Pick Place](/01-PCB/Fabrication)

*Shematic and documentation for [E22](/01-PCB/e22-C)

*Shematic and documentation for [E22p](/01-PCB/e22p-C)

*[IO spreadsheet](/01-PCB/MTL-2_IO.xlsx)

*3d model PCB [step](/04-3dmod)

*3d print model [Case](/05-case)

##  ⚠️Special attention
 Replace the capacitor C6 with a jumper!









##  Additional images

 <img src="03-pic/03.jpg" alt="Main" width="205" height="150"><img src="03-pic/PCB-2.png" alt="PCB" width="198" height="213"><img src="03-pic/04-Case-ver1.jpg" alt="3dCaseF" width="142" height="221"><img src="03-pic/05-Case-ver1.jpg" alt="3dCaseB" width="132" height="219"><img src="03-pic/12.jpg" alt="back" width="187" height="256"><img src="03-pic/20.jpg" alt="case" width="30%"><img src="03-pic/23.jpg" alt="23" width="15%">
 

