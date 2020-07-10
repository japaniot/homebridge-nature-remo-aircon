# homebridge-nremo-aircon

Homebridge Plug-in for Air Conditioner Managed by Nature Remo.

__This is a personal fork not intended for general use, please use the upstream
https://github.com/kmaehashi/homebridge-nature-remo-aircon instead.__

Example:

```js
...

"accessories": [
  {
    "accessory": "NatureRemoAircon",
    "name": "Air Conditioner",
    "useDryForCool": false,
    "accessToken": "xxxxxxxxx_xxxxxxxxxxxxxxx_x_xxxxxx_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
    "applianceId": ""
  }
]

...
```

* Please get your access token at https://home.nature.global/ and set it to `accessToken`.
* `applianceId` can be left blank if you only have one aircon.
* `useDryForCool` can make map cool mode to dry mode in Home.
