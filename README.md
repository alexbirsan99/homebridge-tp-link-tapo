# Homebridge TP-Link Tapo

[![Discord](https://img.shields.io/discord/942035865658613790.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/CAvGGvRGB3)

We recommend to use the platform as a Child Bridge for the best performance.

Most of the time the response time between the app and the device is 80ms.
With the official app i measured around 1s to 2s as a response time.

### Migrate to V3

The platform name was changed to `HomebridgeTPLinkTapo` from HomebridgeTPLinkLights

Package was renamed from `to`

### Current device types

- Light Bulb
- Socket (**COMING SOON**)

### Config

You can add multiple devices bulbs with a single platform.

```json
{
  "platforms": [
    {
      "platform": "HomebridgeTPLinkTapo",
      "name": "TPLink Tapo Platform",
      "email": "tplink-email",
      "password": "tplink-password",
      "addresses": ["192.168.x.x (the ip address of the device)"]
    }
  ]
}
```
