# QAV250  
![Image of Completed ZMR250](https://github.com/nullydragon/ZMR250/blob/master/Titan/Images/20151228_0787.png)

## Parts  

## Notes
To get frsky telemetry working with cleanflight 1.1.0 we need to use the cli and enter the following command  
    **set telemetry_inversion = ON**  
    Serial Port 1 doesnt line up with the pdb, you will need to manually connect it.

## Schematic  

## Explanation  
  Connections to Naze32  
  Minim OSD is connected to Serial Port 1 (Disconnect to use USB)  
  GPS is connected to Serial Port 2  
  Frsky Telemetry is connected to Soft Serial Port 1 (pins 5 and 6 [green])  
  

