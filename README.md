# AS7265x

Food recognition experiments with the AS7265x spectral sensor (18 channels 410nm to 940nm).

> The SparkFun Triad Spectroscopy Sensor is a powerful optical inspection sensor also known as a spectrophotometer. Three AS7265x spectral sensors are combined alongside a visible, UV, and IR LEDs to illuminate and test various surfaces for light spectroscopy. The Triad is made up of three sensors; the AS72651, the AS72652, and the AS72653 and can detect the light from 410nm (UV) to 940nm (IR). In addition, 18 individual light frequencies can be measured with precision down to 28.6 nW/cm2 and accuracy of +/-12%.

> The AS7265x should not be confused with highly complex mass spectrometers, but the sensor array does give the user the ability to measure and characterize how different materials absorb and reflect 18 different frequencies of light.

- https://learn.sparkfun.com/tutorials/spectral-triad-as7265x-hookup-guide/all
- https://how2electronics.com/interfacing-triad-spectroscopy-sensor-as7265x-with-arduino/
- Datasheets: https://github.com/sparkfun/Qwiic_Spectral_Sensor_AS7265x/tree/master/Documents

![image](https://user-images.githubusercontent.com/493741/146160091-eb812200-ea12-4d0d-9f05-1a1754b1d930.png)
![image](https://user-images.githubusercontent.com/493741/146161368-8f752513-44b6-4810-a146-d3f8e9be5362.png)
![image](https://user-images.githubusercontent.com/493741/146166124-e7da548a-d1eb-41e8-ab76-0cb94d988637.png)

Connected to a Wemos D1 mini (ESP8266) via I2C (SDA: D2, SCL: D1).
Library: https://github.com/sparkfun/SparkFun_AS7265x_Arduino_Library.
Starting point: [Example2_BasicReadingsWithLEDs.ino](https://github.com/vogler/AS7265x/blob/main/Example2_BasicReadingsWithLEDs/Example2_BasicReadingsWithLEDs.ino).

TODO: 3D printed shroud to remove background illumination and remove read distance variations.
