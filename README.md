# esplink-promini-apds9960

This sketch get the uses the following sensor library.

## SparkFun APDS9960 library
Sparkfun library (SparkFun_APDS9960.h) has a validation to check the valid ID is return by the sensor at the init phase. For compatible module bought from China, this value has to change according. 

```C
// Acceptable device IDs 
#define APDS9960_ID_1           0xA8
#define APDS9960_ID_2           0x9C 
```

## ELClient library
This library (https://github.com/jeelabs/el-client) managed the communication between ESP-01 and the Pro Mini.

More details about the setup can be found at (https://iotdiary.blogspot.sg/2017/09/using-esp-link-transparent-bridge.html )
