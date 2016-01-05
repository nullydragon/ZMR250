# QAV250  
![Image of Completed ZMR250](https://github.com/nullydragon/ZMR250/blob/master/Titan/Images/20151228_0787.png)

## Parts  
 * [QAV250/ZMR250 Fiberglass frame](http://www.ebay.com.au/itm/ZMR250-3K-Glass-Fiber-4-Axis-250-MM-FPV-Quadcopter-H-Quad-Frame-for-QAV250-/311507474610?hash=item48874ad8b2:g:5e4AAOSwSdZWdRfF)
 * [QAV250 PDB Board](http://www.aliexpress.com/item/ZMR250-PDB-V2-for-CC3D-Naze32-with-Micro-minimOSD-Buzzer-LC-Filter-5-12V-BEC-Regulator/32455211211.html) - Suitable for naze32 rev 5 & micro minimosd
 * [Naze32 Rev5](http://www.aliexpress.com/item/Free-shipping-NAZE32-Rev5-10DOF-Flight-Control-Board-Barometer-Compass-Protective-case/32505612371.html)
 * [Mini MinimOSD](http://www.aliexpress.com/item/MICRO-MINIMOSD-Minim-OSD-Mini-OSD-W-KV-TEAM-MOD-For-Naze32/32428830797.html)
 * [Ublox 7 Neo GPS](http://www.aliexpress.com/item/New-Ublox-7-Series-Mini-GPS-for-OPLink-CC3D-Revolution-Naze32-Flip32-Mini-Naze32-Flight-control/32468038245.html)
 * [1500mAH 35/40C Zippy Lipo 3S](http://www.hobbyking.com/hobbyking/store/__25510__ZIPPY_Compact_1500mAh_3S_35C_Lipo_Pack.html)
 * [Sony 960H 700TVL CCD Camera](http://www.surveilzone.com/sony-960h-ccd-effio-e-dsp-700tvl-board-camera-cc1503)
 * [200mW Video Transmitter (VTX)]()
 * [MultiStar 15A BLHeli ESC](https://www.hobbyking.com/hobbyking/store/uh_viewItem.asp?idProduct=65152)
 * [DYS BE1806-2300kv](https://www.hobbyking.com/hobbyking/store/uh_viewItem.asp?idProduct=61433)
 * [5030 Gemfan Propeller]()
 * [APM Current Sensor](http://www.ebay.com.au/itm/Current-Sensor-Module-90A-APM-Flight-Controller-APM2-5-APM2-52-AttoPilot-Voltage-/181485306857?hash=item2a415e03e9:g:~10AAMXQVT9St7Aq)
 * [Frsky D4R-II Receiver](https://www.hobbyking.com/hobbyking/store/uh_viewItem.asp?idProduct=24788) (or your choice of cppm compatible receiver)

## Notes
To get frsky telemetry working with cleanflight 1.1.0 we need to use the cli and enter the following command  
    **set telemetry_inversion = ON**  
      
Serial Port 1 doesnt line up with the pdb, you will need to manually connect it using a jumper, this is a good thing as we can disconnect the OSD to connect to the naze32 via USB    
      
I would suggest getting different ESC's as the MultiStar ones are not true BLHeli, you cannot flash them, and they twitch when using oneshot.  
      
An alternative to the DYS BE1806's is the [RCX 1804 2400KV](http://www.ebay.com.au/itm/RCX-1804-2400KV-Brushless-Motor-Plus-Thread-for-DJI-F330-ZMR250-H250-Multicopter-/381138996104?hash=item58bda78b88:g:LbEAAOSwkNZUnQL0)  
      
Make sure to get lock nuts for your props, early flights without resulted in crashes where props came off. (Most likely my fault but a few dollars and you can make sure this doesnt happen to you)  
      
The props from surveilzone are great, [5030's](http://www.surveilzone.com/High-Quality-Customized-5040-Multirotor-Propellers-Two-Pair-CW-CCW-g-1352) that have taken a beating and still not broken on me  
      
You can feel free to upgrade the frame to carbon fiber to shave some grams off of the weight, but this is a starter quad for me so the price to replace the frame needed to be as low as possible  
      
  
## Schematic  
  *TODO*
  
## Explanations  
### Connections to Naze32  
  Minim OSD is connected to Serial Port 1 (Disconnect to use USB)  
  GPS is connected to Serial Port 2  
  Frsky Telemetry is connected to Soft Serial Port 1 (pins 5 and 6 [green])  
### Cleanflight Settings
 *TODO*  
### Erata
  

