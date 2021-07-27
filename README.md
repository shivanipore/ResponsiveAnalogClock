# ResponsiveAnalogClock
Designed a Responsive Analog Clock using HTML, CSS and Javascript.

To calculate the rotation of the hour hand of the clock:

## For one rotation of the hour hand:

12h = 360 degrees;
so, 1h = 30 degrees;

also, 60min = 30 degrees;
so, 1min = 1/2 degrees;

Combining we get;
**hrotation = 30*hour + min/2;_______(1)**

## For one rotation of the minute hand:

60min = 360 degrees;
so, 1min = 6 degrees

Therefore, we get;
**mrotation = 6*min;_________(2)**

## Similarly, for one rotation of the second hand:

60sec = 360 degrees;
so, 1sec = 6 degrees

Therefore, we get;
**srotation = 6*sec;_________(3)**


