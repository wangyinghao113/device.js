# device.js



#用法

```
import { device } from 'device.js';
```
```
device.addClasses(document.documentElement);
```
```
if（device.mobile）{
 //做移动的东西
} else if（device.tablet || device.desktop）{
  // do tablet && desktop stuff
}
```


```
import { device } from 'device.js';

device.setUserAgent(ua);
///////
import Device from 'device.js';

const device = new Device(ua1);
const device2 = new Device(ua2);
```
##更多设备
```
import * as device from "device.js";


if (device.ios) {
   
} else if (device.android) {
   
} else {
}
```




#参数、设备
```
deviceorientation
ie9
ie10
touch
ios
iphone
ipod
ipad
android
androidPhone
androidTablet
blackberry
blackberryPhone
blackberryTablet
windows
windowsPhone
windowsTablet
fxos
fxosPhone
fxosTablet
meego
cordova
nodeWebkit
mobile
tablet
desktop
television
portrait
landscape
```
