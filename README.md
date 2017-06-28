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
##以上为官网写法，而现实中的使用inangular2/4,因挖掘其代码，是以函数的写法...
```
import * as device from "device.js";

let _device = device();
if (_device.ios()) {
		var video = [data.UrlStreamHls];
} else if (_device.android()) {
		var video = [data.UrlStreamFlv];
} else {
		var video = [data.UrlStreamRtmp];
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
