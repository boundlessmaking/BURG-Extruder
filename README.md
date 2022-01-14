# BURG Extruder

Motor Driver Manual (in German):   
https://www.labviewforum.de/attachment.php?aid=55209   
The Motor driver is a Sourcetronic ST9000-Frequenzumrichter.  

Extruder 3D-Model:
https://a360.co/2XM20yt

Electronics housing:
Made with
https://en.makercase.com/


____

## Motor Settings 

To start the Motor you need to set Parameter F0.01 (Zielfrequenz). 
See the [Manual](https://github.com/robin-gdwl/BURG-Extruder/blob/master/ST9000BDA_v1.1a.pdf) page 32 for instructions: 

- Press the ```PRG```Button 
- You should see ```F 0``` 
- Press ```ENTER``` 
- Press the UP-arrow until the display says ```F0.01``` 
- Press ```Enter``` 
- You can now set the desired target frequency with the arrow-buttons or the wheel.  
- Press ```Enter``` to confirm the frequency 
- Press the ```PRG```Button until you are back at the starting display. 

Do not start the Motor when the Extruder is still cold and there is material inside of the extrusion screw. 


____
Projects that use this Extruder: 

[Thermoplastic Shapewinding (2019)](https://github.com/robin-gdwl/gh_thermoplastic_shapewinding)
