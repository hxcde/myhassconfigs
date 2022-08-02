<img src="https://user-images.githubusercontent.com/30338980/182402058-6cd045f7-cd5b-405c-8444-e505f25407ae.png" width="70" /> <img src="https://user-images.githubusercontent.com/30338980/182389009-98f48692-3752-4e14-9a2a-4f16fbe152f3.png" width="70" />

## How to create a smart doorbell in Home Assistant!
#### This is also working in HomeKit!

1. Create a [script](https://github.com/hxcde/myhassconfigs/blob/190e841e7040152a5c1d2fa8ffe77ec759a85177/makethingssmart/doorbell/doorbell#L1) that play the bell on you media players.
2. Create an [automation](https://github.com/hxcde/myhassconfigs/blob/190e841e7040152a5c1d2fa8ffe77ec759a85177/makethingssmart/doorbell/doorbell#L23) that binds a button to the script.
3. For Homekit you need to create a dummy switch, that switches back after some seconds.
