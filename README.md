---
description: TBD
title: TBD
keywords:
- Grove
image: TBD
slug: Grove - NFC(ST25DV64)
last_update:
  date: 5/14/2023
  author: Stephen Lo
---


<!-- ![](https://files.seeedstudio.com/wiki/Grove-VOC_and_eCO2_Gas_Sensor-SGP30/img/IMG_0012a.jpg) -->
  <p style={{textAlign: 'center'}}><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/c7b51f84ceaca85c9e24df663dbf5c0c2bf3524d/images/2-101021093---Grove---NFC(ST25DV64KC)-font.jpg" alt="pir" width={600} height="auto" /></p>

Grove - NFC (ST25DV64) is an innovative and versatile NFC/RFID tag board based on the advanced ST25DV64K chip from STMicroelectronics. This dynamic chip supports ISO/IEC 15693 and NFC Forum Type 5 tag standards, making it compatible with a wide array of NFC-enabled devices.

Designed for makers, DIY enthusiasts, and anyone interested in experimenting with NFC technology, the Grove - NFC (ST25DV64) offers a simple, cost-effective solution for adding NFC functionality to your projects. With its open-source nature, you can not only use this board as is but also tweak it to better fit your specific needs, whether you're building a smart home system, a secure access control device, a contactless payment solution, or an inventory tracking system.

The Grove - NFC (ST25DV64) is more than just an NFC tag. It's also a powerful tool that you can use to learn about NFC technology and its applications. With its rich features, you can explore various aspects of NFC, from data transfer and energy harvesting to data protection and general-purpose output.

This board is designed with convenience in mind. It features the standard Grove connector (HY2.0 - 4Pin), making it easily compatible with other Grove modules. Additionally, it works with both 3.3V and 5V systems, making it a flexible solution for your NFC needs.

Despite its small size, the Grove - NFC (ST25DV64) packs a punch when it comes to storage. It offers 64 Kbits of EEPROM, organized in 2048 blocks of 32 bits each, providing ample space for your data.

Note: Please remember that the Grove - NFC (ST25DV64) does not come with an NFC antenna. You will need to purchase a separate 13.56MHz NFC antenna to use with this product. You can also purchase this antenna from Seeedstudio.

Whether you're new to NFC or an experienced developer looking for an easy-to-use NFC solution, the Grove - NFC (ST25DV64) is an excellent choice. Its open-source software and hardware, combined with its ease of use and versatility, make it an invaluable tool for any NFC project.

<p style={{textAlign: 'center'}}><a href="https://www.seeedstudio.com/-Grove-VOC-and-eCO2-Gas-Sensor-(SGP30)-p-3071.html" target="_blank"><img src="https://files.seeedstudio.com/wiki/Seeed-WiKi/docs/images/300px-Get_One_Now_Banner-ragular.png" /></a></p>

:::tip
    We've released the [Seeed Gas Sensor Selection Guide](https://wiki.seeedstudio.com/Sensor_gas/), it will help you choose the gas sensor that best suits your needs.
:::

## Features

- Based on the ST25DV64K chip, supporting ISO/IEC 15693 and NFC Forum Type 5 tag standards
- 64 Kbits of EEPROM, organized in 2048 blocks of 32 bits each
- Energy harvesting and GPO (General Purpose Output)
- Fast transfer mode and multiple levels of data protection
- Compatible with both 3.3V and 5V systems
- Uses the standard Grove connector (HY2.0 - 4Pin) for easy integration with other Grove modules
- Open-source software and hardware

## Specification

- Chip: ST25DV64K
- Operating frequency: 13.56 MHz
- Protocol: ISO/IEC 15693
- Communication interface: I2C
- Grove connector: 4-pin HY2.0
- Operating voltage: 3.3/5V

## In the Box

![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/5-101021093---Grove---NFC(ST25DV64KC)-45fontall.jpg)
- 1xGrove - NFC(ST25DV64) Board
- 2xGrove Cable(20cm)

## Applications

- **Access Control:** Use the Grove - NFC (ST25DV64) as a key card for access control systems.
- **Smart Home Automation:** Store configuration data on the tag to control smart home devices or trigger specific actions.
- **Contactless Payments:** Integrate the tag into a payment system for contactless transactions.
- **Device Pairing:** Simplify the pairing process between devices by storing connection information on the NFC tag.
- **Inventory Tracking:** Attach the NFC tag to products to store product information and simplify inventory management.

## Hardware Overview

### Pin Map

<!-- ![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/pinmap.png) -->
  <p style={{textAlign: 'center'}}><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/pinmap.png" alt="pir" width={600} height="auto" /></p>

## Getting Started

:::note
    If this is the first time you work with Arduino, we strongly recommend you to see [Getting Started with Arduino](https://wiki.seeedstudio.com/Getting_Started_with_Arduino/) before the start.
:::

### Play With Arduino

#### Hardware

**Materials required**

| Seeeduino V4.2 | NFC Antenna| Grove - Smart Air Quality Sensor (SGP41) |
|--------------|-------------|-----------------|
|<p><img src="https://files.seeedstudio.com/wiki/Grove_Light_Sensor/images/gs_1.jpg" alt="pir" width={600} height="auto" /></p>|<p><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/NFC_ANTENNA.jpg" alt="pir" width={600} height="auto" /></p>|<p><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/c7b51f84ceaca85c9e24df663dbf5c0c2bf3524d/images/2-101021093---Grove---NFC(ST25DV64KC)-font.jpg" alt="pir" width={500} height="auto" /></p>|
|<a href="https://www.seeedstudio.com/Seeeduino-V4.2-p-2517.html" target="_blank">Get One Now</a>|<a href="https://www.seeedstudio.com/NFC-Antenna-p-1805.html?queryID=32009a01d3dd8bba3d47aacebce9f91d&objectID=1138&indexName=bazaar_retailer_products" target="_blank">Get One Now</a>|<a href="https://www.seeedstudio.com/-Grove-VOC-and-eCO2-Gas-Sensor-(SGP30)-p-3071.html" target="_blank">Get One Now</a>|

:::note
    **1** Please plug the USB cable gently, otherwise you may damage the port. Please use the USB cable with 4 wires inside, the 2 wires cable can't transfer data. If you are not sure about the wire you have, you can click [here](https://www.seeedstudio.com/Micro-USB-Cable-48cm-p-1475.html) to buy
    
    **2** Each Grove module comes with a Grove cable when you buy. In case you lose the Grove cable, you can click [here](https://www.seeedstudio.com/Grove-Universal-4-Pin-Buckled-20cm-Cable-%285-PCs-pack%29-p-936.html) to buy.
:::

- **Step 1.** Connect Grove - Smart Air Quality Sensor (SGP41) to **I2C** port  of Grove-Base Shield.

- **Step 2.** Plug Grove - Base Shield into Seeeduino.

- **Step 3.** Connect Seeeduino to PC via a USB cable.

:::note
    The Grove - NFC (ST25DV64) does not come with an NFC antenna. Therefore, you will need to purchase a separate 13.56MHz NFC antenna to use with this product. You can also purchase this antenna from Seeedstudio.
:::

| Seeeduino     | Grove-VOC and eCO2 Gas Sensor(SGP30) |
|---------------|-------------------------|
| 3.3/5V        | Red                     |
| GND           | Black                   |
| SDA           | White                   |
| SCL           | Yellow                  |

#### Software

- **Step 1.** Download the [ST25DV Arduino Library](https://github.com/stm32duino/ST25DV) from Github.

- **Step 2.** Refer to [How to install library](https://wiki.seeedstudio.com/How_to_install_Arduino_Library) to install library for Arduino.

- **Step 3.** After downloading and installing the library correctly, you can find an example program named ST25DV_HelloWorld.ino in the examples folder. This program is designed for the ST25DV module.

```Arduino
#include "ST25DVSensor.h"

#define SerialPort      Serial

#if defined(ARDUINO_B_L4S5I_IOT01A)
// Pin definitions for board B-L4S5I_IOT01A
  #define GPO_PIN PE4
  #define LPD_PIN PE2
  #define SDA_PIN PB11
  #define SCL_PIN PB10
  #define WireNFC MyWire
  TwoWire MyWire(SDA_PIN, SCL_PIN);
  ST25DV st25dv(12, -1, &MyWire);
#else
  #define DEV_I2C         Wire
  ST25DV st25dv(12, -1, &DEV_I2C);
#endif

void setup() {
  const char uri_write_message[] = "st.com/st25";       // Uri message to write in the tag
  const char uri_write_protocol[] = URI_ID_0x01_STRING; // Uri protocol to write in the tag
  String uri_write = String(uri_write_protocol) + String(uri_write_message);
  String uri_read;

  // Initialize serial for output.
  SerialPort.begin(115200);

  // The wire instance used can be omitted in case you use default Wire instance
  if(st25dv.begin() == 0) {
    SerialPort.println("System Init done!");
  } else {
    SerialPort.println("System Init failed!");
    while(1);
  }

  if(st25dv.writeURI(uri_write_protocol, uri_write_message, "")) {
    SerialPort.println("Write failed!");
    while(1);
  }

  delay(100);
  
  if(st25dv.readURI(&uri_read)) {
    SerialPort.println("Read failed!");
    while(1);
  }

  SerialPort.println(uri_read.c_str());

  if(strcmp(uri_read.c_str(), uri_write.c_str()) == 0) {
    SerialPort.println("Successfully written and read!");
  } else {
    SerialPort.println("Read bad string!");
  }
}

void loop() {  
  //empty loop
} 
```

- **Step 4.** Upload the demo. If you do not know how to upload the code, please check [How to upload code](https://wiki.seeedstudio.com/Upload_Code/).

- **Step 5.** Open the **Serial Monitor** of Arduino IDE by click **Tool-> Serial Monitor**. You will get below result:

![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/result.jpg)

#### Test

After uploading the provided program to your Arduino, your Grove - NFC (ST25DV64) becomes a fully functioning NFC Tag, which can operate independently. You can remove it from your Arduino board; it doesn't require any additional setup to work.

To test its functionality, you'll need an NFC-enabled smartphone, either Android or Apple. For the purpose of this demonstration, an iPhone 14 Pro Max was used. The NFC antenna for this device is located adjacent to the camera. However, if you are unsure about the location of the NFC antenna on your smartphone, it would be beneficial to look it up online.

Place the phone's NFC antenna close to the NFC antenna of the Grove - NFC (ST25DV64). Your smartphone should display a prompt requesting to open a webpage at st.com. This response indicates that your Grove - NFC (ST25DV64) is functioning correctly as an NFC Tag and demonstrates the demo's functionality.
![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/stcom.jpg)

## Schematic Online Viewer

<div className="altium-ecad-viewer" data-project-src="https://github.com/Longan-Labs/NFC_ST25DV_RES/raw/main/Grove%20-%20NFC(ST25DV64).zip" style={{borderRadius: '0px 0px 4px 4px', height: 500, borderStyle: 'solid', borderWidth: 1, borderColor: 'rgb(241, 241, 241)', overflow: 'hidden', maxWidth: 1280, maxHeight: 700, boxSizing: 'border-box'}}>
</div>

## Resources

- **[Zip]** [Grove - NFC(ST25DV64)](https://github.com/Longan-Labs/NFC_ST25DV_RES/raw/main/Grove%20-%20NFC(ST25DV64).zip)
- **[PDF]** [ST25DV64K Datasheet](https://github.com/Longan-Labs/NFC_ST25DV_RES/blob/c7b51f84ceaca85c9e24df663dbf5c0c2bf3524d/st25dv.pdf)
- **[GITHUB]** [ST25DV Arduino Library](https://github.com/stm32duino/ST25DV)

## Tech Support
If you have any technical issue.  submit the issue into our [forum](https://forum.seeedstudio.com/).