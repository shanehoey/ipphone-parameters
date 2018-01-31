---
description: Configure telnet access for management
search: false
---

# Configure telnet access for management

#### management/telnet/enabled

Configure telnet access for management


| unknown | 
| :--- |

## Syntax
| Parameter | Syntax |
| :--- | :--- |
|management/telnet/enabled | 0,1|

## Parameters
|Device|Parameter|value|Description|
|:---|:---|:---|:---|
|  | management/telnet/enabled | 0 | Disable Telnet access |
|  | management/telnet/enabled | 1 | Enable Telnet access |

## Examples
#### Enable Telnet

```
management/telnet/enabled=1
```

## Devices
This parameter is available on the following devices

| Device | Latest Firmware | Default Value |
|:---|:---|:---|
| audc405HD | ;UC_3.0.1.322 | management/telnet/enabled=1 
| audc440HD | ;UC_3.0.1.322 | management/telnet/enabled=1 
| audc450HD | ;UC_3.0.4.111.77 | management/telnet/enabled=1 

ADD A DISCLAIMER
