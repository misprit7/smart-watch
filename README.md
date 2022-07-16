# Smart Watch

This is a project to create a custom smart watch from complete scratch. This means designing a custom PCB, creating the mechanical fixture and writing all of the UI elements for embedded linux. This repository is the Altium files for the project. 

## Battery

Planning on using this battery, have ordered 3 of them: https://www.adafruit.com/product/1578 

## Questions

Things to ask Arrsh/Pablo about: 
1. Does my diode based power selection actually work? 
2. Which of the capacitors are actually necessary? Definitely don't have room for them all
3. (To Arrsh): How does usb work? 
4. Are pullups/series resistors on SD lines necessary? I don't think so since rocket didn't need them
5. Is it fine to leave boot config pins floating? (data sheet says they have an internal pulldown on reboot)
6. What's with the inductors being labelled with resistances @ frequency? I assume these are signal integrity or power stability, are they required? 
7. Am I correct about _t being positive and _c being negative? 

Manufacturing Questions: 
1. Will JLCPCB be able to do 0.4mm BGA components? I'm fine paying extra
2. Do BGA components need solder past below

