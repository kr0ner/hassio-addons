# hassio-hostapd
Raspberry Pi as hotspot in hass.io

### This Hass.io Addon

This add-on allows you  to use the Raspberry Pi as a hotspot to connect the different devices directly to the `hass.io` network without going through the router.

## Installation

To use this repository with your own Hass.io installation please follow [the official instructions](https://www.home-assistant.io/hassio/installing_third_party_addons/) on the Home Assistant website with the following URL:

```txt
https://github.com/kr0ner/hassio-addons
```

Also install [DHCP server](https://github.com/home-assistant/addons/blob/master/dhcp_server/README.md) and set domain to e.g. "homeassistant" and change the ```interface: wlan0```

### Configuration

The available configuration options are as follows (this is filled in with some example data):

```
{
    "ssid": "WIFI_NAME",
    "wpa_passphrase": "WIFI_PASSWORD",
    "channel": "6",
    "address": "192.168.99.1",
    "netmask": "255.255.255.0",
    "broadcast": "192.168.99.254"
}
```
**Note**: _This is just an example, don't copy and paste it! Create your own!_
