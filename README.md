# Prototypes

This repository describes the different parts and versions of DAISEE prototype  
  
![schema prototype](https://hackpad-attachments.imgix.net/hackpad.com_d55JBV5B1Vy_p.602889_1472755256932_14215184_10154001154263915_845143439_o.jpg)


## Prototype v0.1

See [HERE](https://github.com/DAISEE/UrbanEntrepreneurs/wiki) the instructions (in FR, EN ASAP) to rebuild the prototype. Tag for sources is **v0.1-beta** (pre-release). 

### Hardware
- Citizen Watt sensors
- Pine64+ boards and Arduino
- Arduino + Relay shield
- Light bulbs

### Software
- CitizenWatt 
    - [Sensor sketch](https://github.com/CitoyensCapteurs/CitizenWatt-sensor)
    - Application
        - [PINE64](https://github.com/DAISEE/CitizenWatt-Base-PINE64)  
        - [Arduino](https://github.com/DAISEE/CitizenWatt-ArduinoBase)

- Ethereum   
    - [geth](https://github.com/ethereum/go-ethereum)
    - [Dapp](https://github.com/DAISEE/DApp)
   
- [Connection](https://github.com/DAISEE/DzScripts) => [release 0.1](https://github.com/DAISEE/Scripts/releases/tag/v0.1-beta)
  
  
## Prototype v0.2

### Documentation
- [DAISEE/Prototypes/wiki](https://github.com/DAISEE/Prototypes/wiki)  

### Changes from version 0.1
#### Hardware
- Single computer boards
    - [x] Back to Raspberry Pi 3 board ([#1](https://github.com/DAISEE/Prototypes/issues/1))  
- Current sensors (work in progress)
#### Software
- Ethereum  
A new repo has been created for this new version : [DAISEE/DApp-v2](https://github.com/DAISEE/DApp-v2)
    - [x] Use of Parity instead of geth ([#2](https://github.com/DAISEE/Prototypes/issues/2)) 
        - [x] Implementation of 'Proof of Authority' ([#6](https://github.com/DAISEE/Prototypes/issues/6))
    - [ ] New algo for energy exchanges ([#3](https://github.com/DAISEE/Prototypes/issues/3))  
    - [ ] Modify the data storage ([#4](https://github.com/DAISEE/Prototypes/issues/4))
    - [ ] Energy data display ([#5](https://github.com/DAISEE/Prototypes/issues/5), partially done)
    - [x] Use of a specific token ([DAISEE/DApp-v2#4](https://github.com/DAISEE/DApp-v2/issues/4))
