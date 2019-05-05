# NFCUART

## Micro:bit NFC Sensor expansion board.

## Table of Contents

* [URL](#url)
* [Summary](#summary)
* [Blocks](#blocks)
* [License](#license)

## URL
project URL: ```https://github.com/DFRobot/pxt-NFCUART```

## Summary
NFC Sensor expansion board provides some Micro:bit blocks for reading and interpreting PN532 NFC RFID Module over I2C. These blocks make it easy to operate or acquiring imformation from the card via NFC sensors.Near field communication (NFC) is a set of standards for smart phones and similar devices to establish radio communicationwith each other by touching them together or bringing them into close proximity, usually no more than a few centimeter.

## Blocks
### 1.nfcEvent
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/nfcEvent.png)
When the card is detected, the program in the module is executed.

### 2.writeData
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/writeData.png)
NFC data writing.

### 3.checkUID
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/checkUID.png)
Whether UID data of card is detected.

### 4.getCard
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/getCard.png)
Whether a card is detected by NFC.

### 5.getUID
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/getUID.png)
Read NFC sensor UID data.

### 6.readNFCData
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/readNFCData.png)
Read all data on NFC data block.

### 7.readNFCDataOne
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/writeData.png)
Read NFC data specifying one byte.

### 8.blockList
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/blockList.png)

### 9.nfcDataList
![image](https://github.com/shanluoMu/pxt-NFCUART/blob/master/image/nfcDataList.png)

## License

MIT

## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)
```package
NFC=github:DFRobot/pxt-NFCUART
```
