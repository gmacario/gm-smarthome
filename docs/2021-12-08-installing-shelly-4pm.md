# Installing Shelly Pro 4PM

## References

* [Shelly 4 PRO PM | Shelly Italia](https://www.shellyitalia.com/shelly-4-pro-pm/) - SKU: SH4PROPM
* [Shelly Pro 4PM - User and Safety Guide](https://shelly.cloud/documents/user_guide/shelly_pro_4pm_multi_language.pdf) (PDF, 2 pages)
* [#45: First look at the new Shelly Pro 4PM](https://www.superhouse.tv/45-first-look-at-the-new-shelly-pro-4pm/) - SuperHouse.tv, 2021-09-15
* [Recensione Shelly PRO 4PM finalmente qui con l'attesissimo supporto LAN](https://www.youtube.com/watch?v=lmQLyWvBcpk) - Vincenzo Caputo, 2021-08-25
* [SHELLY PRO 4PM - The professional automation solution](https://www.youtube.com/watch?v=Wr63YhMD6zU) - YouTube video by Shelly, 2021-08-19
* [Shelly Pro product family](https://shelly.cloud/shelly-pro-smart-home-automation-solution/)

## Setting up Shelly Pro 4PM for Vernante

...

<!-- (2021-12-08 19:00 CET) -->

Browse <http://192.168.64.198/>

Click "Device" > "Firmware version"

> Firmware version
>
> * Device ID: 84CCA87FB720
> * Firmware version: 0.6.10
> * Firmware build ID: 20210810-140121/0.6.10-g11bf9a3-master
> * Web build ID: 1.3.0-master+g941e9d9
>
> [Check for update](TODO)
>
> * Avaliable version: 0.9.1
>
> [Update](TODO)


### Updating firmware

<!-- (2021-12-08 19:30 CET) -->

Click "Update"

...

Browse <http://192.168.64.198/>

> | Switch   | Power | Voltage
> |----------|-------|---------
> | switch_0 |   0 W | 232.1 V
> | switch_1 |   0 W | 232.1 V
> | switch_2 |   0 W | 232 V
> | switch_3 |   0 W | 232 V
>
> [Device](TODO) | [Networks](TODO) | [Scripts](TODO)

Click "Device"

> Device
>
> * Sntp server
> * Device name
> * Firmware version
> * Location
> * Reboot
> * Factory reset
> * Authentication
> * Debug

Expand "Sntp server"

> Sntp server
>
> * time.google.com
>
> [Apply](TODO)

Expand "Device name"

> Device name
>
> * (empty)

Expand "Firmware version"

> Firmware version
>
> * Device ID: 84CCA87FB720
> * Firmware version: 0.9.1
> * Firmware build ID: 20211203-125315/0.9.1-ga939435
> * Web build ID: 1.5.5-34db4f9
>
> [Check for update](TODO)

Click "Networks"

> Networks
>
> * Wifi
> * Access point
> * Ethernet
> * Cloud
> * Bluetooth
> * Mqtt

Expand "Cloud"

> Cloud
>
> * Connected: shelly-35-eu.shelly.cloud:6022/jrpc
> * Enable: YES
>
> Connecting your Shelly to its cloud allows you to control it remotely, receive notifications and updates about your devices.
>
> WARNING: If you disable the device cloud support, you will lose connection to your device from outside its local network!

<!-- EOF -->
