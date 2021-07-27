# ResponsiveAnalogClock
Designed a Responsive Analog Clock using HTML, CSS and Javascript.

To calculate the rotation of the hour hand of the clock:

## For one rotation of the hour hand:

12h = 360 degrees;
so, 1h = 30 degrees;

also, 60min = 30 degrees;
so, 1min = 1/2 degrees;

Combining we get;
**hrotation = 30 x hour + min/2;______(1)**

## For one rotation of the minute hand:

60min = 360 degrees;
so, 1min = 6 degrees

Therefore, we get;
**mrotation = 6 x min;________(2)**

## Similarly, for one rotation of the second hand:

60sec = 360 degrees;
so, 1sec = 6 degrees

Therefore, we get;
**srotation = 6 x sec;________(3)**

![image](https://user-images.githubusercontent.com/67893793/127120490-aa78ddf5-85fd-493f-b596-c9b5a71dbe4c.png)


