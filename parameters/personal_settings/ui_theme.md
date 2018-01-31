---
description: Configure the UI theme on the IP Phone
search:
    keywords: ['personal_settings','ui_theme']
---

# Configure the IP Phone UI theme

#### personal_settings/ui_theme

Configure the UI theme on the IP Phone :
* AUDC_THEME
* MSFT_THEME



## Syntax
| Parameter | Syntax |
| :--- | :--- |
|personal_settings/ui_theme | MSFT_THEME,AUDC_THEME|

## Parameters
|Device|Parameter|value|Description|
|:---|:---|:---|:---|
|  | personal_settings/ui_theme | MSFT_THEME | Configure theme to MSFT (Default) |
|  | personal_settings/ui_theme | AUDC_THEME | Configure theme to AUDC theme |

## Examples
#### Configure the theme

Configure the theme to AUDC_THEME

```
personal_settings/ui_theme=AUDC_THEME
```
#### Configure the theme

Configure the theme to MSFT_THEME

```
personal_settings/ui_theme=MSFT_THEME
```

## Devices
This parameter is available on the following devices

| Device | Latest Firmware | Default Value |
|:---|:---|:---|
| audc450HD | ;UC_3.0.4.111.77 | personal_settings/ui_theme=MSFT_THEME 

ADD A DISCLAIMER
