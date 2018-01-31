---
description: Configure the PC Port Speed
search:
    keywords: ['network','pc','port_mode']
---

# Configure the PC Port Speed

#### network/pc/port_mode

Configure the PC Port Speed,
 * Auto negotiation.
 * 10Mbps + full duplex
 * 100Mbps + full duplex
 * 10Mbps + half duplex
 * 100Mbps + half duplex 


| This parameter is currently investigating what this parameter does. Please refer to Audiocodes wesite for details on this parameter | 
| :--- |

## Syntax
| Parameter | Syntax |
| :--- | :--- |
|network/pc/port_mode | Automatic,Full_10,Full_100,Half_10,Half_100|

## Parameters
|Device|Parameter|value|Description|
|:---|:---|:---|:---|
|  | network/pc/port_mode | AUTOMATIC (default) | Configure to Auto Negotiation |
|  | network/pc/port_mode | FULL_10 | Configure to 10mb Full Duplex |
|  | network/pc/port_mode | FULL_100 | Configure to 100mb Full Duplex |
|  | network/pc/port_mode | HALF_10 | Configure to 10mb Half Duplex |
|  | network/pc/port_mode | HALF_100 | Configure to 100mb Half Duplex |
|  | network/pc/port_mode | AUTOMATIC (default) | Configure to Auto Negotiation |
|  | network/pc/port_mode | FULL_10 | Configure to 10mb Full Duplex |
|  | network/pc/port_mode | FULL_100 | Configure to 100mb Full Duplex |
|  | network/pc/port_mode | HALF_10 | Configure to 10mb Half Duplex |
|  | network/pc/port_mode | HALF_100 | Configure to 100mb Half Duplex |

## Examples
#### Configure to 100mb

```
network/pc/port_mode=FULL_100
```
#### Configure to 100mb

```
network/pc/port_mode=FULL_100
```

## Devices
This parameter is available on the following devices

| Device | Latest Firmware | Default Value |
|:---|:---|:---|
| audc405HD | ;UC_3.0.1.322 | network/pc/port_mode=AUTOMATIC 
| audc440HD | ;UC_3.0.1.322 | network/pc/port_mode=AUTOMATIC 
| audc450HD | ;UC_3.0.4.111.77 | network/pc/port_mode=AUTOMATIC 

ADD A DISCLAIMER
