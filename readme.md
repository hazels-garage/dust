![GitHub](https://img.shields.io/github/license/hazels-garage/dust?label=%20&logo=creativecommons&logoColor=%23ffffff&style=flat-square)
<a href="https://shop.hazel.cc/products/dust">
 <img src="https://img.shields.io/badge/-Purchase-%23000?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABGdBTUEAALEQa0zv0AAAACBjSFJNAACHDwAAjA8AAP1SAACBQAAAfXkAAOmLAAA85QAAGcxzPIV3AAABCGlDQ1BJQ0MgUHJvZmlsZQAAKM9jYGBckZOcW8wkwMCQm1dSFOTupBARGaXAfoeBkUGSgZlBk8EyMbm4wDEgwIcBJ/h2DagaCC7rgsxiIA1wpqQWJwPpD0Acn1xQVAJ0E8gunvKSAhA7AsgWKQI6CsjOAbHTIewGEDsJwp4CVhMS5Axk8wDZDulI7CQkNtQuEGBNNkrORHZIcmlRGZQpBcSnGU8yJ7NO4sjm/iZgLxoobaL4UXOCkYT1JDfWwPLYt9kFVaydG2fVrMncX3v58EuD//9LUitKQJqdnQ0YQGGIHjYIsfxFDAwWXxkYmCcgxJJmMjBsb2VgkLiFEFNZwMDA38LAsO08APD9Tdt4gbWmAAAACXBIWXMAABJ0AAASdAHeZh94AAABC0lEQVQ4T2MAgv9kYqyCxGBMQUtFVwwxLBhVwEDG+n934PL/HQFLUMSxYEzBJp85/8td+/97aUf9jzcv+s/HIQgWZ2JkQlaH0MDOwgG2rcJtAhjXek773+G/+D8POz9QEzOyJhBGcMwVnf83es+GawThNr8FYDlGBka4OihGcEzlHcEaS1x6wJoq3Sf9L3PtQ1aMjBEcNTH9/xoShv9jzPL/13lOB2tKta76b6vihawBhhEcER7J/yxMrECF3v8TLEr+V7lP/t/qu+C/grAGsgYYRhUABUiD10ywJpCtDV6z/ksLKKKogWJUgXb/RcAAWQjEi/6HG2dhC00YxhTkZOXGEMOCsQoSwAz/AUZL+dIX/BrCAAAAAElFTkSuQmCC" /></a>
<a href="https://discord.gg/jP6hvgNN8r">
  <img src="https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square" />
</a>


# dust
## ultrathin sweep-alike

![top](images/PXL_20221206_002310840.MP2.jpg)
![side](images/PXL_20221206_002219334.MP.jpg)


| Left | Right |
| :---: | :---: |
| ![left](images/dust-top.png) | ![right](images/dust-bottom.png) |


**dust** is my attempt at making the thinnest sweep-alike.
### Sacrifices were made.  

- XIAO is surface mounted to be reversible without jumpers.  
- There is no reset button because the xiao has one on it.  
- Soldering the battery connection on the XIAO is gonna suck.
- You're probably gonna need to tape the battery to the board.

## MATERIALS
- 34x [Kailh X Switches](https://www.aliexpress.us/item/2251832799288171.html)
- 34x [1N4148 - SOD-123 Diodes](https://www.aliexpress.us/item/3256801606142520.html)
- 2x SeeedStudio XIAO (RP2040 or BLE)
- 2x [TRRS Jack](https://www.aliexpress.us/item/3256801742337046.html) (RP2040)
- 2x [Power Switch](https://mkultra.click/alps-ssss811101/) (BLE)
- 2x [Battery](https://tinycircuits.com/collections/all/products/lithium-ion-polymer-battery-3-7v-40mah) (BLE)
- 2x [Battery Connector](https://www.aliexpress.us/item/3256803789364982.html) (BLE)

## CASE
3D Printable case designed by ant: [Dust Tray](https://github.com/Ant6009/Dust_Tray)

## FIRMWARE

[QMK](https://github.com/jasonhazel/qmk_hazel/tree/master/keyboards/jasonhazel/dust)

[ZMK](https://github.com/jasonhazel/zmk-config/tree/master/config/boards/shields/dust)
