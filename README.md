# byrandev (V1.0)

# I am happy to announce that the next revision of the byrandev will be coming to an OSHW GitHub repository near you! :)

 a nrf52840 dev board that is highly experimental.
 The components are based off the [mikoto](https://github.com/zhiayang/mikoto) board.
 I will do some finishing touches when I have the time.
 Since the board is two layered, it can be made affordably and be _directly integrated_ into larger boards with no issue.
##### V2 come soon with a ton of new features:
 - SMA Antenna Connector
 - More Pins
 - JST-PH connector for power
 - and a lot more!
 
### There are currently no instructions, I will write them sometime in the future :)
### Notes for anyone that is considering using the design: 
 - Optimize the impdedance matching traces for your particular board stackup (if you are using JLC 2 layer, you should be fine)
 - It is expensive. Under current silicon shortage conditions, 2 assembled boards costed 100, and 5 would've costed 150. Self assembly should be cheaper but difficult due to the aQFN73 footprint of the nRF52840.
 - It's large. Being two layered, I couldn't fit traces very well. I will reconsider my routing decisions on V2 and hopefully achieve a much smaller footprint.

### PCB (28 GPIO pins)
<p align="center">
 <img src="./images/pcb.jpg" width="60%"/>
 
#### PCB 3D File Raytraced Render in KiCAD
<p align="center">
 <img src="./images/raytraced.jpg" width="60%"/>

#### Real Images (working prototype from JLCPCB, HASL(PBF) 2 Layer, Black Solder Mask)
<p align="center">
 <img src="./images/top.jpg" width="60%"/>
 <img src="./images/side.jpg" width="60%"/>

### Unsightly Image with more detail on the PCB
<p align="center">
 <img src="./images/top_with_flash.jpg" width="60%"/>

As with most open source projects, I am not liable for any issues, and no warranty is provided. Please use at your own risk and make this world a better place :)
